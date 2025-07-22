# 🔗 LangChain AI Application

This project demonstrates how to build a **LangChain-based RAG (Retrieval-Augmented Generation)** application using Python and powerful LLM (Large Language Model) tools. It utilizes LangChain, VectorStores, Embedding Models, and Retrieval techniques to answer queries based on uploaded document content.

---

## 🚀 Features

- ✅ Use of **LangChain** to orchestrate LLM and retrieval components.
- ✅ **Document loading and splitting** using `PyPDFLoader` and `CharacterTextSplitter`.
- ✅ **Embeddings generation** using OpenAI Embeddings.
- ✅ **FAISS** for efficient vector similarity search.
- ✅ **ConversationalRetrievalChain** for interactive question-answering over documents.
- ✅ Supports multi-turn conversations.

---

## 🧰 Tech Stack

- Python
- LangChain
- OpenAI (Embeddings & LLMs)
- FAISS
- PyPDFLoader
- Streamlit (if UI is added)
- dotenv (for handling API keys)

---

## 📂 How It Works

1. **Load a PDF** using PyPDFLoader.
2. **Split text** into manageable chunks.
3. **Generate vector embeddings** for each chunk.
4. **Store and retrieve** vectors using FAISS.
5. **Query** the content using ConversationalRetrievalChain.

---

## 🔐 Environment Setup

1. Install required packages:

```bash
pip install langchain openai faiss-cpu python-dotenv
