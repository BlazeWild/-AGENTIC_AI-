# 🤖 Agentic AI

Welcome to **Agentic AI** — a curated monorepo of real-world agents, practical crash courses, and essential tools for building modern AI agents using frameworks like ADK (Agent Development Kit), LangChain, Gemini, Claude, and more.

Whether you're a beginner, practitioner, or researcher, this repository will help you build, understand, and deploy agentic systems end-to-end.

---

## 🛠️ Repository Structure

This is a **monorepo** powered by Git submodules. Each subproject exists both here and as its own standalone GitHub repository.

| Folder | Description |
|--------|-------------|
| [`adk-crash-course`](./adk-crash-course) | A hands-on introduction to Google’s ADK (Agent Development Kit) with working examples. |
| [`travel-agent`](./travel-agent) | A multi-agent travel planner built with ADK and Gemini. |
| [`linkedin-post-agent`](./linkedin-post-agent) | AI agent that writes and reviews posts for LinkedIn using LLMs. |
| [`lead-qualification-agent`](./lead_qualification_agent) | A loop-based sequential agent that qualifies leads and logs interactions. |

> ⚙️ **Note:** Each submodule has its own README, instructions, and license.

---

## 🚀 Getting Started

To clone this repo with all agent submodules:

```bash
git clone --recurse-submodules https://github.com/yourusername/Agentic-AI.git
cd Agentic-AI
