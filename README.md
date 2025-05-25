# AI-TASK
# 🔁 AI Task Planner with LangGraph, LangChain, and Fireworks LLM

This project demonstrates an **agentic workflow** using [LangChain](https://www.langchain.com/), [LangGraph](https://docs.langchain.com/langgraph/), and the [Fireworks AI](https://fireworks.ai/) LLM. It breaks down a user's complex query into subtasks, executes them using tools like DuckDuckGo search, reflects on the results, and refines the plan if needed.

---

## 🧠 Key Features

- 🔧 **Zero-shot tool-using agent** powered by LangChain
- 🔍 **Live web search** using DuckDuckGo
- 🧩 **Workflow automation** using LangGraph (Plan → Act → Reflect)
- ✅ Modular and extensible agent nodes (Planning, Execution, Reflection)
- 🌐 Uses Fireworks AI for reasoning and planning

---

## 🛠️ Installation

This notebook is designed to be run on **Google Colab**.

Run this in the first cell:
```python
!pip install -q langchain langgraph fireworks-ai duckduckgo-search langchain-community
