# AI-Grader-summarization-tool
This page is a part of the AI Grader project about the summarization tool that is planned to be deployed.<br>
The tool is from <a href="https://github.com/callstack/ai-summarization">ai-summarization</a> repositry, developed by <a href="https://github.com/mdjastrzebski">mdjastrzebski</a>.

# Installation
Install Python3, Desktop development with C++ in Visual Studio Installer.<br>
Install dependencies with <code>pip install -r requirements.txt</code>.<br>
Put the model file under <code>./models</code>.<br>
Use alternative model by changing <code>MODEL_FILE</code> in summarizel.ipynb.<br>
Modify path to course directory in <code>courses_directory</code> of <code>teacher.ipynb</code> and <code>student.ipynb</code>
Or enter the path and use the update button in the Web UI

# Use Guide
<h3>Jupyter Notebook</h3>
Execute all the cells in <code>menu.ipynb</code> in Jupyter Lab or Notebook.<br>
<h3>Web UI</h3>
Execute <code>start.bat</code> or <code>start.sh</code>.

# Testing
The models used are downloaded from Hugging Face repository.
<br>
<table>
  <tr><th></th><th>Model</th></tr>
  <tr><td>1</td><td><a href="https://huggingface.co/TheBloke/Mistral-7B-OpenOrca-GGUF/tree/main" rel="nofollow">TheBloke/Mistral-7B-OpenOrca-GGUF</a> mistral-7b-openorca.Q5_K_M.gguf</td></tr>
  <tr><td>2</td><td><a href="https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-GGUF/tree/main" rel="nofollow">TheBloke/OpenHermes-2.5-Mistral-7B-GGUF</a> openhermes-2.5-mistral-7b.Q5_K_M.gguf</td></tr>
  <tr><td>2</td><td><a href="https://huggingface.co/TheBloke/CapybaraHermes-2.5-Mistral-7B-GGUF/tree/main" rel="nofollow">TheBloke/CapybaraHermes-2.5-Mistral-7B-GGUF</a> capybarahermes-2.5-mistral-7b.Q5_K_M.gguf</td></tr>
</table>
