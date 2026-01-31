# An Loc's LangChain journey

Welcome to my workspace for the **LangChain Academy: Introduction to LangChain** course. This repo tracks my progress as I build AI agents and explore the LLM ecosystem.

---

## Current progress
- [x] **Module 1: Create Agent** (Foundational models, Tools, Memory, Multimodal)
- [x] **Module 2: Advanced Agent** (MCP, Context, State, Multi-Agent Systems)
- [ ] **Module 3: Production-Ready Agent** (Middleware, HITL, Dynamic Agents)

---

## Projects

### 1. Personal Chef (Module 1)
An AI agent equipped with **Short-Term Memory** and a **Web Search Tool (Tavily)**. It can suggest recipes based on leftover ingredients and remember user preferences.

### 2. Wedding Planner (Module 2)
A complex **Multi-Agent System** that uses **Runtime Context** and **State Management** to coordinate different specialists (Venue, Catering, Decor) for event planning.

---

## Tech Stack
- **Framework**: [LangChain](https://www.langchain.com/) & [LangGraph](https://langchain-ai.github.io/langgraph/)
- **Models**: GPT-5 (Nano), GPT-4o
- **Database**: [ChromaDB](https://www.trychroma.com/) (Vector Store)
- **Protocol**: [Model Context Protocol (MCP)](https://modelcontextprotocol.io/)
- **Package Manager**: [uv](https://docs.astral.sh/uv/)

---

## Repository dtructure

- `notebooks/module-1/`: **Agent Fundamentals**
  - Foundational models (GPT-5, Claude, Gemini)
  - Custom Tool definition & Binding
  - Short-term Memory (Checkpointers)
  - Multimodal Messaging (Images & Audio)
  - **Project**: *Personal Chef* - A memory-aware recipe agent with web search skills.
- `notebooks/module-2/`: **Advanced Agent Architectures**
  - Model Context Protocol (MCP) for universal integrations
  - Runtime Context (Passing background data)
  - Persistent State Management
  - Multi-Agent Orchestration (Managers & Specialists)
  - **Project**: *Wedding Planner* - Coordinating multiple AI specialist agents.
- `notebooks/module-3/`: **Production & Deployment**
  - Middleware & Custom Logic
  - Managing Message History (Trimming & Filtering)
  - Human-in-the-loop (HITL) Workflows
  - Dynamic Model & Prompt Selection
  - **Project**: *Email Assistant* - A robust, production-ready automation agent.

---


## Related Resources
- [LangChain Documentation](https://python.langchain.com/)
- [LangSmith Dashboard](https://smith.langchain.com/)
- [Tavily Search API](https://tavily.com/)
