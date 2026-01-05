

# MS Agent Framework

Welcome to the MS Agent Framework, a professional, extensible platform for building, experimenting with, and comparing modern agentic AI frameworks and patterns. This repository is designed for both beginners and advanced users, providing hands-on resources to accelerate your journey in agent-based AI development.

<img src="img/ai-agent-decision-tree.svg" alt="AI Agent Decision Tree" width="40%">

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/divakarkumarp/agent-lightning-playground.git
cd MS_Agent_Framework
```

### 2. Set Up Your Environment
```bash
python -m venv .venv
.venv\Scripts\activate  # On Windows
pip install -r requirements.txt
```

### 3. Explore and Run
- Open any notebook in Jupyter Lab or VS Code and run cells top-to-bottom.
- Review the example scripts and modules for inspiration.

---

## 📂 Repository Overview

### Main Notebooks (Root)
- **agent-framework-aifoundry-file-search.ipynb**: File search agent demo (shows how agents can search and retrieve files)
- **agent-framework-basicagent.ipynb**: Minimal working agent example (start here for basics)
- **HITL-Agent-Framework-aifoundry.ipynb**: Human-In-The-Loop (HITL) agent pattern demonstration
- **RAG-Agent-Framework-aifoundry.ipynb**: Retrieval-Augmented Generation (RAG) agent example

### Advanced Patterns (`AutoGen Vs Microsoft Agent Framework`)
- **Agent-as-Tool-Pattern.ipynb**: Agents using other agents as tools
- **Agent-Function-Tools.ipynb**: Function-calling tools for agents
- **Group-chat-dynamic-speaker.ipynb**: Multi-agent group chat with dynamic speaker selection
- **multi-agent-magnetic-pattern.ipynb**: Magnetic pattern for agent collaboration
- **Single-Multi-Agent-Vs-AutoGen-MAF.ipynb**: Compare single agent, multi-agent, and AutoGen MAF
- **Swarm-Handoff Pattern.ipynb**: Swarm agent handoff pattern
- **Thread-Management-Streaming-Responses.ipynb**: Thread management and streaming responses in agent systems

---

## 🌟 Features

- **Modular Agent Design:** Easily create, extend, and compose agents for diverse tasks.
- **Human-in-the-Loop Support:** Integrate human feedback and oversight into agent workflows.
- **Tool & API Integration:** Connect agents with external tools, APIs, and data sources.
- **Rich Example Library:** Includes ready-to-use agents for research, document writing, weather information, and more.
- **Interactive Notebooks:** Explore, test, and demonstrate agent capabilities in Jupyter notebooks.

---

## 💡 Best Practices

- Organize new experiments as separate notebooks.
- Move reusable code into `.py` modules for clarity.
- Use feature branches for new ideas; keep `main` stable.
- Don’t commit `.venv/` or large DB files.
- Use `.env` files (not in git) for secrets and API keys.
- Add lightweight unit tests for helper modules (use `pytest`).
- Clear notebook output cells before committing.

---

## 🏁 Where to Start

We recommend starting with:
- [agent-framework-basicagent.ipynb](agent-framework-basicagent.ipynb)
- [RAG-Agent-Framework-aifoundry.ipynb](RAG-Agent-Framework-aifoundry.ipynb)

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features. For major changes, open an issue to discuss your proposal first.

---



---

