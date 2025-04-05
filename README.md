# Basic-Multi-Agent-Application-using-CrewAI


# Goal
 CrewAI basic Multi-Agent LLM App: multi-agent app to replace the  content marketing team



# How to run?
### STEPS:

```bash
Project repo: https://github.com/
```
### STEP 01- Create a Poetry environment after opening the repository 

# In terminal:

```bash
cd project_name
pyenv local 3.11.4
poetry install
poetry shell
```


### Create a `.env` file in the root directory and here is where you will add your confidential api keys. Remember to include:

```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
```


```bash
# Finally run the following command
python basic-multiagent-crewai.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:
  - Python
  - LangChain
  - CrewAI
  - Tavily




Track operations
we can track the operations and the cost of this project from LangSmith:

smith.langchain.com

The results of the app will improve by fine-tuning the backstories of the agents and the task descriptions.