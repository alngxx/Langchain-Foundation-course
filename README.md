# 🔗 An Loc's LangChain Journey

Welcome to my personal workspace for the **LangChain Academy: Introduction to LangChain** course. This repository tracks my progress as I build intelligent agents and explore the LLM ecosystem.

---

## 🏆 Current Progress
- [x] **Module 1: Create Agent** (Foundational models, Tools, Memory, Multimodal)
- [x] **Module 2: Advanced Agent** (MCP, Context, State, Multi-Agent Systems)
- [ ] **Module 3: Production-Ready Agent** (Middleware, HITL, Dynamic Agents)

---

## 🚀 Projects Completed

### 👨‍🍳 1. Personal Chef (Module 1)
An AI agent equipped with **Short-Term Memory** and a **Web Search Tool (Tavily)**. It can suggest recipes based on leftover ingredients and remember user preferences.

### 💍 2. Wedding Planner (Module 2)
A complex **Multi-Agent System** that uses **Runtime Context** and **State Management** to coordinate different specialists (Venue, Catering, Decor) for event planning.

---

## 🛠️ Technical Stack
- **Framework**: [LangChain](https://www.langchain.com/) & [LangGraph](https://langchain-ai.github.io/langgraph/)
- **Models**: GPT-5 (Nano), GPT-4o
- **Database**: [ChromaDB](https://www.trychroma.com/) (Vector Store)
- **Protocol**: [Model Context Protocol (MCP)](https://modelcontextprotocol.io/)
- **Package Manager**: [uv](https://docs.astral.sh/uv/)

---

## 📂 Repository Structure
- `notebooks/module-1/`: Basics of agents, tools, and memory.
- `notebooks/module-2/`: Advanced state management and multi-agent coordination.
- `notebooks/module-3/`: Production concerns and human-in-the-loop patterns.

---

## ⚙️ Setup & Installation

### Prerequisites
- Python >=3.12, <3.14
- [uv](https://docs.astral.sh/uv/) (Recommended)

### Quick Start
1. **Clone & Enter**
   ```bash
   git clone https://github.com/alngxx/Langchain-Foundation-course.git
   cd Langchain-Foundation-course
   ```

2. **Environment Configuration**
   ```bash
   cp example.env .env
   # Edit .env with your API keys:
   # OPENAI_API_KEY, TAVILY_API_KEY
   ```

3. **Install & Verify**
   ```bash
   uv sync
   uv run python env_utils.py
   ```

4. **Run Notebooks**
   ```bash
   uv run jupyter lab
   ```

---

## 📖 Related Resources
- [LangChain Documentation](https://python.langchain.com/)
- [LangSmith Dashboard](https://smith.langchain.com/)
- [Tavily Search API](https://tavily.com/)

---
*Created and maintained with the help of **Antigravity**.*
