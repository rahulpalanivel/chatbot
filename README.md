# 🧾 Insurance Chatbot - README

This project is a simple, intelligent chatbot that helps users interactively query insurance policy details extracted from PDF documents. Built using **Python**, **LangChain**, **OpenAI**, **FAISS**, and **Streamlit**, this chatbot utilizes LLMs to understand user questions and provide accurate, context-aware answers.

---

## 📌 Features
- Upload insurance policy PDFs.
- Ask natural language questions about the policy.
- Retrieves relevant policy info using a vector database (FAISS).
- Uses OpenAI LLMs for response generation.
- Web-based UI using Streamlit.
- Fallback detection for human escalation.

---

## 🛠️ Step-by-Step Setup & Development Guide

### 1. **Environment Setup**
- Install Python (>=3.10): [https://www.python.org/](https://www.python.org/)
- Install the requirements from requirements.txt

### 2. **Prepare the PDF Knowledge Base**
- Extract text using `PyMuPDF`.
- Split the text into manageable chunks.
- Create embeddings using OpenAI's API.
- Store these embeddings in FAISS for retrieval.

---

## 🚀 Deployment Options (Free)
- **Streamlit Cloud**: [https://streamlit.io/cloud](https://streamlit.io/cloud)
- **Hugging Face Spaces**: For showcasing via Streamlit


---

## 📚 Free Tools Used
- **Python + LangChain** for backend logic
- **Streamlit** for frontend
- **OpenAI** (Free API tier for GPT-3.5)
- **FAISS** for semantic search
- **PyMuPDF** for PDF reading
- **OBS Studio** / **Loom** for demo

---

