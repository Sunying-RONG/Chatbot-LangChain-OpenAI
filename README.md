# Chatbot-LangChain-OpenAI

This Chatbot project is build with Python, LangChain, LangSmith, OpenAI for practice purpose.

LangChian API KEY, OpenAI API KEY, and LangSmith tracing config are set on local environment variable, otherwise they could be configured in Jupyter Lab with  
```python
import getpass
import os

os.environ["LANGCHAIN_TRACING_V2"] = "true"
os.environ["LANGCHAIN_API_KEY"] = getpass.getpass()

os.environ["OPENAI_API_KEY"] = getpass.getpass()
```
An example of tracing in LangSmith
<img width="967" alt="Screenshot 2024-06-10 at 16 51 56" src="https://github.com/Sunying-RONG/Chatbot-LangChain-OpenAI/assets/44567186/a46efdf7-3e35-4a04-ad33-1b891bd9f454">
