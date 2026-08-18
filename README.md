# 🦜 LangGraph Tutorial

A hands-on learning repository for **LangChain, LangGraph, AI Agents, memory, routing, orchestration, evaluation, and Human-in-the-Loop workflows**.

This repository contains Jupyter notebooks covering LangGraph concepts step by step.

## 📚 Notebooks

| Notebook | Topic |
|---|---|
| `1_First_Graph.ipynb` | First LangGraph workflow |
| `2_Pydantic.ipynb` | Pydantic and structured data |
| `3_Messages.ipynb` | Messages and message handling |
| `4_prompts.ipynb` | Prompt design |
| `5_Tools&Binding.ipynb` | Tools and model binding |
| `6_ReAct-Agent.ipynb` | ReAct agent workflow |
| `7_Parallelization.ipynb` | Parallel execution |
| `8_Router.ipynb` | Routing and conditional workflows |
| `9_orchestrator-worker.ipynb` | Orchestrator-worker pattern |
| `10_Generator_Evaluator.ipynb` | Generator-evaluator workflow |
| `11_Memory.ipynb` | Memory and state management |
| `12_human-in-loop.ipynb` | Human-in-the-Loop workflow |

## 🧠 Concepts Covered

- StateGraph, nodes and edges
- Conditional routing
- Parallel execution
- ReAct agents
- Tool calling
- Pydantic structured output
- Orchestrator-worker architecture
- Generator-evaluator pattern
- Memory and state
- Human-in-the-Loop using `interrupt()` and `Command`

## 🛠️ Tech Stack

**Python · LangChain · LangGraph · Pydantic · Jupyter Notebook · Groq/ChatGroq · uv/pip**

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/rohitlonkar2006/langgraph_tutorial.git
cd langgraph_tutorial
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

Using `uv`:

```bash
uv sync
```

Or using pip:

```bash
pip install -r requirements.txt
```

### 4. Add your API key

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key_here
```

If LangSmith is used in a notebook, you can also add:

```env
LANGSMITH_TRACING=true
LANGSMITH_API_KEY=your_langsmith_api_key_here
LANGSMITH_PROJECT=langgraph_tutorial
```

**Do not upload real API keys to GitHub.**

### 5. Start Jupyter

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

Open the `Notebooks` folder and run the notebooks.

## ▶️ Recommended Order

```text
1_First_Graph
      ↓
2_Pydantic
      ↓
3_Messages
      ↓
4_prompts
      ↓
5_Tools&Binding
      ↓
6_ReAct-Agent
      ↓
7_Parallelization
      ↓
8_Router
      ↓
9_orchestrator-worker
      ↓
10_Generator_Evaluator
      ↓
11_Memory
      ↓
12_human-in-loop
```

## 📖 Official Documentation

- [LangChain Documentation](https://docs.langchain.com/oss/python/langchain)
- [LangChain Python API Reference](https://reference.langchain.com/python/langchain/)
- [LangGraph Documentation](https://docs.langchain.com/oss/python/langgraph)
- [LangGraph Python API Reference](https://reference.langchain.com/python/langgraph/)
- [LangGraph Academy](https://academy.langchain.com/courses/intro-to-langgraph)

## 👨‍💻 About Me

**Rohit Lonkar**  
B.Tech CSE (AIA) — MIT ADT University, Pune

**Interests:** AI/ML · Generative AI · AI Agents · Agentic AI · LangChain · LangGraph · RAG · NLP

### Connect

- [LinkedIn](https://www.linkedin.com/in/rohit-lonkar-746948274/)
- [GitHub](https://github.com/rohitlonkar2006)

---

⭐ If this repository helps you learn LangGraph, consider starring it.
