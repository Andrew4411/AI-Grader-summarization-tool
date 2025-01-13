# AI-Grader-summarization-tool
This page is a part of the AI Grader project about the summarization tool that is planned to be deployed.<br>
The tool is from <a href="https://github.com/callstack/ai-summarization">ai-summarization</a> repositry, developed by <a href="https://github.com/mdjastrzebski">mdjastrzebski</a>.<br>
# Installation
Install Python3, Desktop development with C++ in Visual Studio Installer.<br>
Install dependencies with <code>pip install -r requirements.txt</code>.<br>
Put the model file under <code>./models</code>.
# Testing
The models used are downloaded from Hugging Face <a href="https://huggingface.co/TheBloke/Mistral-7B-OpenOrca-GGUF/tree/main" rel="nofollow">TheBloke/Mistral-7B-OpenOrca-GGUF</a> repository.
<br>
<table>
  <tr><th>Input</th><th>Model</th><th>Style</th><th>Context</th></tr>
  <tr><td>1-5</td><td>mistral-7b-openorca.Q5_K_M.gguf</td><td>number list</td><td>Grimm's Fairy Tales</td></tr>
</table>
