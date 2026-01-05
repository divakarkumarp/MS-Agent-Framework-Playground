
# Auto Gen Vs Microsoft Agent Framework

AutoGen developers move to the Microsoft Agent Framework (AF) with minimal guesswork. Each script pairs AutoGen code with its AF equivalent so you can compare primitives, tooling, and orchestration patterns side by side while you migrate production workloads.

This folder contains advanced agent framework patterns and experiments. Each notebook demonstrates a unique multi-agent or orchestration use case, with code and explanations.

## 📚 Notebooks & Use Cases

Each notebook below demonstrates a specific agent pattern or migration scenario, with paired AutoGen and Microsoft Agent Framework (AF) code for direct comparison:

### Agent as Tool Pattern
- [Agent-as-Tool-Pattern.ipynb](Agent-as-Tool-Pattern.ipynb)
  - **Use Case:** Agents use other agents as tools (modular, composable workflows)
  - **Code Focus:** Tool agent registration, delegation, inter-agent communication

### Agent Function Tools
- [Agent-Function-Tools.ipynb](Agent-Function-Tools.ipynb)
  - **Use Case:** Agents call external functions/tools (APIs, Python functions)
  - **Code Focus:** Function tool integration, agent-to-function invocation, result handling

### Group Chat Dynamic Speaker
- [Group-chat-dynamic-speaker.ipynb](Group-chat-dynamic-speaker.ipynb)
  - **Use Case:** Multi-agent group chat with dynamic speaker selection
  - **Code Focus:** Speaker selection logic, group message routing, conversational state

### Multi-Agent Magnetic Pattern
- [multi-agent-magnetic-pattern.ipynb](multi-agent-magnetic-pattern.ipynb)
  - **Use Case:** Agents are drawn to tasks/topics based on affinity (magnetic pattern)
  - **Code Focus:** Affinity scoring, agent-task matching, collaborative workflows

### Single vs Multi-Agent vs AutoGen MAF
- [Single-Multi-Agent-Vs-AutoGen-MAF.ipynb](Single-Multi-Agent-Vs-AutoGen-MAF.ipynb)
  - **Use Case:** Compare single-agent, multi-agent, and AutoGen MAF for the same problem
  - **Code Focus:** Comparative analysis, performance/behavioral differences, framework strengths/weaknesses

### Swarm Handoff Pattern
- [Swarm-Handoff Pattern.ipynb](Swarm-Handoff%20Pattern.ipynb)
  - **Use Case:** Swarm agent handoff for efficiency or specialization
  - **Code Focus:** Handoff protocols, swarm coordination, agent state transitions

### Thread Management & Streaming Responses
- [Thread-Management-Streaming-Responses.ipynb](Thread-Management-Streaming-Responses.ipynb)
  - **Use Case:** Thread management and streaming responses for concurrent tasks and real-time feedback
  - **Code Focus:** Threading, streaming output, managing multiple agent conversations

## 🧩 How to Use

1. Open any notebook above in Jupyter or VS Code.
2. Read the intro cell for context, then run cells top-to-bottom.
3. Modify agent logic or parameters to experiment with new behaviors.

---
Created on December 20, 2025
