# LiteLLM-Production-Gateway
Production-ready LiteLLM project with clean structure, examples, and notebook for experimentation
This repository contains a Jupyter Notebook demonstrating how to use LiteLLM with multiple providers such as Groq and Cohere.

## 📌 Overview

This notebook demonstrates how to use **LiteLLM** to interact with multiple large language model providers in a unified way.

## 🧠 What’s inside the notebook

The notebook walks through practical, hands-on examples including:

* **Basic LiteLLM usage**
  How to send prompts and receive responses using a simple, unified API.

* **Working with multiple providers**
  Examples of calling different LLM providers such as Groq and Cohere using the same interface.

* **Routing and model selection**
  How to switch between models or providers depending on the use case.

* **Fallback strategies**
  Handling failures by automatically switching to alternative models.

* **Logging and monitoring (Langfuse)**
  Tracking requests and responses for debugging and observability.

## 🎯 Purpose

This notebook is intended as a **learning and experimentation resource** for:

* Understanding how LiteLLM simplifies multi-provider LLM usage
* Testing different models
* Building a foundation before moving to production-level code

## 📂 Structure

```
.
├── README.md
├── requirements.txt
└── notebook/
    └── LiteLLM.ipynb
```

## 🛠️ Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔐 Environment Variables

Create a `.env` file and add your API keys:

```
GROQ_API_KEY=your_key_here
COHERE_API_KEY=your_key_here
LANGFUSE_SECRET_KEY=your_key_here
LANGFUSE_PUBLIC_KEY=your_key_here
```

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook notebook/LiteLLM.ipynb
```

## ⚠️ Notes

* API keys are loaded using environment variables
* Do not expose your keys publicly

## 📄 License

MIT
