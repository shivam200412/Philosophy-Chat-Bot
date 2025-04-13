# 🧠 Philosophy Chatbot

A context-aware conversational chatbot that answers philosophical questions using a combination of vector similarity search, large language models, and a clean Streamlit interface.

![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-orange)
![LangChain](https://img.shields.io/badge/Powered%20By-LangChain-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Philosophy Chatbot is a smart assistant capable of answering questions about philosophy based on embedded knowledge from philosophical texts. It uses:

- **LangChain** for building the RetrievalQA pipeline  
- **FAISS** for fast semantic search over embedded documents  
- **HuggingFace** for embedding and LLM access  
- **Streamlit** for an interactive web interface  

The chatbot sticks to facts and avoids hallucinating answers outside of the provided content. If it doesn't know the answer, it simply says so.

---

## ⚙️ Features

- Real-time conversational interface  
- Mistral-7B Instruct model via HuggingFace  
- Vector-based semantic search using FAISS  
- No hallucination — answers are grounded in provided documents  
- Custom prompt template for precise and concise replies  

---


