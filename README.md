# 🤖 Multi-User ReAct AI Agent Chatbot with LangGraph

This project demonstrates how to build an **interactive multi-user AI chatbot** using [LangGraph](https://docs.langgraph.dev/) and **ReAct-style LLM agents**. It features a conversational agent capable of reasoning about its next steps and using tools like **web search** or **weather lookup**, all orchestrated within a LangGraph state machine.

---

## 📌 Features

- 🧠 **ReAct Agent Framework:** LLM-based agents that reason and act through tool use.
- 🔄 **LangGraph Flow:** Agent decisions loop through action → tool use → feedback → response.
- 🧰 **Prebuilt Tools:** Search engine, weather APIs, and more (pluggable & extendable).
- 👥 **Multi-user Support:** Extendable for user-specific session flows or roles.
- 🧪 **Lightweight & Extensible:** Ideal for prototyping agent apps that require reasoning + tool use.

---

## 🚀 Demo Overview

The notebook walks through building a chatbot that:

1. Accepts user input.
2. Uses an LLM to decide whether a tool is needed.
3. Calls a tool (like web search or weather) if required.
4. Feeds the result back into the LLM.
5. Repeats until the agent decides it can respond directly.

This follows the **ReAct** (Reason + Act) paradigm—enabling more dynamic and explainable AI behaviors.

---

## 🛠️ Setup Instructions

### 1. Install Dependencies

```bash
pip install langgraph openai
