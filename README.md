# **Models and frameworks exploration**
This repository contains experiments on how to invoke and work with Google models along with the exploration of Langgraph; a multi-agent framework, by understanding it's concepts and exploring it's capabilities.

## **Index**
* [Setup](#Setup)
* [Files](#Files)

## **Setup**
Clone the repository
```python
git clone https://github.com/Thejpal/Langchain.git
```
Install the requirements to run the files
```python
pip install -r requirements.txt
```
Set the following environmental variables in .env file (Requirement to run the first three files)
```python
GOOGLE_GEMINI_API_KEY="<your-api-key>"
```

## **Files**
|**File**|**Description**|
|--- |--- |
|[basics.ipynb](/basics.ipynb)|*LLM basics*|
|[google_models.ipynb](/google_models.ipynb)|*Invoking Google models with a variety of libraries and exploring their response objects*|
|[google_thinking_model.ipynb](/google_thinking_model.ipynb)|*Exploring Google thingking models*|
|[langgraph_practice.ipynb](langgraph_practice.ipynb)|*Exploring Langgraph nodes, edges and state management*|
|[langgraph_memory.ipynb](langgraph_memory.ipynb)|*Exploring memory management for the graphs in Langgraph*|
|[interrupt_test.ipynb](/interrupt_test.ipynb)|*Exploring human in the loop workflow for Langgraph*|
|[requirements.txt](/requirements.txt)|*Packages to be installed to run the files*|
