# 🤖 Agentic AI Examples — Incentro

This repository contains simple and practical code examples used during Agentic AI presentation at **Incentro**.  
The goal is to show how to build and run agent-based applications using the **[Agno](https://github.com/khoj-ai/agno)** framework with models like OpenAI and Groq, tool integrations, multi-agent workflows, and memory using vector databases.

---

## What’s Inside

| File | Description |
|------|-------------|
| `simpleagent.py` | A single agent using OpenAI + DuckDuckGo search |
| `multiagents.py` | A team of agents working together (Groq + OpenAI) for financial analysis |
| `agent_memory.py` | An agent with memory using LanceDB and PDF knowledge |

---

## Getting Started

1. **Clone the repo**

```bash
git clone https://github.com/MostafaBaluchzehi/getting-started-with-agents.git
cd getting-started-with-agents
```

2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Set up environment variables**
Create a file named `.env` in the root of the project:
```bash
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```
## ▶️ Run an Example

To run any of the agent demos:

```bash
python 1_simpleagent.py
# or
python 2_agent_memory.py
# or
python 2_multiagents.py
```
