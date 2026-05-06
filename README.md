# LiteLLM-Production-Gateway
Production-ready LiteLLM project with clean structure, examples, and notebook for experimentation

# LiteLLM Project

This repository contains a Jupyter Notebook demonstrating how to use LiteLLM with multiple providers such as Groq and Cohere.

## 📌 Overview

The notebook includes:

* Basic LiteLLM usage
* Calling different LLM providers (Groq, Cohere)
* Load balancing & routing examples
* Fallback strategies
* Integration with Langfuse

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
