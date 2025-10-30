# 🧠 RAG Document Q&A with Groq and Llama3

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that allows users to upload research papers (PDFs), embed them into a vector database, and query them conversationally using **Groq’s Llama3-8B model** via **LangChain**.  
It runs as an interactive **Streamlit** app for simplicity and fast testing.

---

## 🚀 Overview

This app combines **document retrieval** and **generative AI** to answer user questions **based strictly on uploaded research papers**.  
The workflow:
1. Load PDF research papers from a local folder.  
2. Split and embed documents into a **FAISS vector store** using **OpenAI embeddings**.  
3. Retrieve relevant document chunks using **semantic similarity search**.  
4. Feed the retrieved context and user query to **Groq Llama3-8B** for final answer generation.

---

## 🧩 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| UI Framework | Streamlit |
| LLM | Groq Llama3-8B |
| Framework | LangChain |
| Embeddings | OpenAIEmbeddings |
| Vector Store | FAISS |
| Data Loader | PyPDFDirectoryLoader |

---


