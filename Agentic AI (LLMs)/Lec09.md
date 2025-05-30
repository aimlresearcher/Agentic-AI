# Lecture 09: Autonomy Frameworks Overview

---

## 🎯 Learning Objectives

By the end of this lecture, you should be able to:

- Identify key frameworks for building autonomous LLM agents.
- Compare features of AutoGPT, BabyAGI, and OpenAgents.
- Understand the architectural patterns and trade-offs.
- Run a basic example from an open-source autonomy framework.

---

## 🧩 Key Concepts

### What Are Autonomy Frameworks?

- Toolkits and architectures designed to turn LLMs into **goal-driven agents**.
- Provide built-in support for:
  - Goal decomposition
  - Memory management
  - Task planning
  - Tool invocation
  - Persistent loops

---

### Popular Frameworks

#### 1. **AutoGPT**
- CLI-based, open-source Python tool.
- Uses OpenAI models to take high-level goals and execute plans.
- Requires API keys, tool setup, and configuration files.

#### 2. **BabyAGI**
- Lightweight task management loop.
- Maintains a task queue and context memory.
- Continuously re-prioritizes and expands tasks from a seed objective.

#### 3. **OpenAgents (OpenAI / LangChain / community forks)**
- Modular, prompt-based agent systems.
- Supports multi-agent collaboration, tool orchestration, and agent roles.

---

### Feature Comparison Table

    | Feature              | AutoGPT | BabyAGI | OpenAgents |
    |----------------------|---------|---------|------------|
    | Goal Planning        | ✅      | ✅      | ✅          |
    | Tool Use             | ✅      | ⚠️ (basic) | ✅        |
    | Task Prioritization  | ❌      | ✅      | ✅          |
    | Memory Persistence   | ✅      | ✅      | ✅          |
    | Setup Complexity     | 🔺 High | ✅ Low  | 🔺 Medium   |

---

## 🛠 Required Tools/Libraries

- Git + Python (for AutoGPT/BabyAGI)
- OpenAI API key
- (Optional) LangChain + LangGraph (for OpenAgents)

---

## 🔬 Hands-on Exercise: Run a Local AutoGPT Clone

**Goal**: Clone and run an open-source AutoGPT-style agent.

### Step 1: Clone a minimal AutoGPT repo

    git clone https://github.com/Torantulino/Auto-GPT.git
    cd Auto-GPT
    pip install -r requirements.txt

### Step 2: Set your API keys

    - Edit `.env` file or use environment variables:
        OPENAI_API_KEY=your_key_here

### Step 3: Define a goal and run

    python scripts/main.py
    Goal: Research and summarize top 3 AI frameworks for developers.

### Step 4: Observe Agent Behavior

    - How does it break the goal into tasks?
    - Does it use tools?
    - Where does it store results or memory?

---

### Bonus:

- Try BabyAGI (https://github.com/yoheinakajima/babyagi)
- Customize a tool in AutoGPT or create your own task loop
- Explore agent logs and reasoning traces to improve transparency

---
