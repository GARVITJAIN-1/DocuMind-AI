# DocuMind-AI

![GitHub stars](https://img.shields.io/github/stars/GARVITJAIN-1/DocuMind-AI?style=for-the-badge&logo=github) ![GitHub forks](https://img.shields.io/github/forks/GARVITJAIN-1/DocuMind-AI?style=for-the-badge&logo=github) ![GitHub issues](https://img.shields.io/github/issues/GARVITJAIN-1/DocuMind-AI?style=for-the-badge&logo=github) ![Last commit](https://img.shields.io/github/last-commit/GARVITJAIN-1/DocuMind-AI?style=for-the-badge&logo=github) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 📑 Table of Contents

- [Description](#description)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Key Dependencies](#key-dependencies)
- [Project Structure](#project-structure)
- [Development Setup](#development-setup)
- [Contributing](#contributing)

## 📝 Description

DocuMind AI is a Conversational Retrieval-Augmented Generation (RAG) application that enables users to upload one or more PDF documents and interact with them using natural language queries. The system combines semantic search, vector embeddings, and Large Language Models (LLMs) to deliver accurate, context-aware answers directly from document content.

Built using LangChain, ChromaDB, HuggingFace Embeddings, and Groq's Llama 3.3 model, DocuMind AI supports history-aware conversations, allowing users to ask follow-up questions while maintaining context across interactions. The application processes PDFs, generates vector embeddings, retrieves relevant information through similarity search, and produces grounded responses through a Retrieval-Augmented Generation pipeline.

This project demonstrates practical implementation of document intelligence systems, vector databases, conversational memory, and modern Generative AI workflows in a user-friendly Streamlit interface.


## 🛠️ Tech Stack

- 🐍 **Python**

**Notable libraries:** LangChain

## ⚡ Quick Start

```bash

# 1. Clone the repository
git clone https://github.com/GARVITJAIN-1/DocuMind-AI.git

# 2. Create & activate a virtualenv
python -m venv venv && source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt
```

## 📦 Key Dependencies

```
langchain: latest
langchain-core: latest
langchain-community: latest
langchain-openai: latest
langchain-ollama: latest
langchain-groq: latest
langchain-text-splitters: latest
python-dotenv: latest
streamlit: latest
faiss-cpu: latest
pypdf: latest
chromadb: latest
langchain_huggingface: latest
langchain_chroma: latest
sentence-transformers: latest
```

## 📁 Project Structure

```
.
├── app3.py
└── requirements.txt
```

## 🛠️ Development Setup

### Python
1. Install Python (v3.10+ recommended)
2. `python -m venv venv && source venv/bin/activate`  (Windows: `venv\Scripts\activate`)
3. `pip install -r requirements.txt`

## 👥 Contributing

Contributions are welcome! Here's the standard flow:

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/GARVITJAIN-1/DocuMind-AI.git`
3. **Branch**: `git checkout -b feature/your-feature`
4. **Commit**: `git commit -m 'feat: add some feature'`
5. **Push**: `git push origin feature/your-feature`
6. **Open** a pull request

Please follow the existing code style and include tests for new behavior where applicable.

---
*This README was generated with ❤️ by [ReadmeBuddy](https://readmebuddy.com)*
