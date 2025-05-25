# 🌐 AI Web Scraper + 🤖 RAG Chatbot

An intelligent web application built using **Streamlit** that combines **web scraping**, **PDF parsing**, and **Retrieval-Augmented Generation (RAG)** to answer user queries using both online content and uploaded documents.

---

## 🚀 Features

- **Web Scraping**: Enter any website URL to extract and clean the body content.
- **PDF Parsing**: Automatically loads and processes local PDF documents.
- **Embeddings with Hugging Face**: Uses `all-MiniLM-L6-v2` for semantic search.
- **Vector Store**: Stores chunks in a local Chroma DB for retrieval.
- **Chat with Context**: Uses LangChain's `RunnableWithMessageHistory` and Groq's `llama3` model for contextual chat.
- **RAG Pipeline**: Retrieval + Answer generation using LangChain's retriever and document chain.
- **Streamlit UI**: Clean, interactive interface with styled widgets.

---

## 📦 Dependencies

Install all Python dependencies using:

```bash
pip install -r requirements.txt
