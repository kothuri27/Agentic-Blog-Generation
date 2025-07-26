# 🧠 Blog Generator using FastAPI + LLMs

This project is an AI-powered blog generation API that takes a topic and returns a structured blog-like response using a graph-based orchestration of Large Language Models (LLMs). It's built using **FastAPI**, integrated with **LangChain**, and uses **Groq API** as the LLM backend.

---

## 🚀 Features

- 🔗 LangChain-based graph execution to handle complex workflows.
- ⚡ FastAPI backend for lightweight REST API.
- 🤖 LLM integration via `GroqLLM`.
- 🧩 Modular structure for easy extension and maintenance.

---



## 🔐 Environment Variables

Create a `.env` file in the root directory with the following:

```env
LANGCHAIN_API_KEY=your_langsmith_api_key
GROQ_API_KEY=your_groq_api_key
