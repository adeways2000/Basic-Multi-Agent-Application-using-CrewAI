# Basic-Multi-Agent-Application-using-CrewAI
CrewAI basic Multi-Agent LLM App: multi-agent app to replace the content marketing team

Setup
After you download the code from the github repository in your computer
In terminal:

cd project_name
pyenv local 3.11.4
poetry install
poetry shell

Create your .env file
In the github repo we have included a file named .env.example
Rename that file to .env file and here is where you will add your confidential api keys. Remember to include:
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
We will call our LangSmith project 001-basic-multiagent-crewai.

Track operations
From now on, we can track the operations and the cost of this project from LangSmith:

smith.langchain.com
