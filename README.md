# Chatbot with ChromaDB and OpenAI

This project is a command-line-based chatbot application using **LangChain**, **OpenAI's GPT API**, and **ChromaDB**. It allows you to chat with a language model that's aware of your local documents through vector-based retrieval.

---

## Features

- Embeds documents into a local vector database (ChromaDB)
- Retrieves semantically similar content using LangChain retrievers
- Uses OpenAI GPT API to generate responses based on query and context
- Secure environment configuration using `.env`
- Modular and extensible Python code

---

## Project Files and Their Purpose

| File / Folder          | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `chatbot.py`           | Main script to start a chatbot session using LangChain and OpenAI       |
| `ingest_database.py`   | Script to embed documents from `data/` into ChromaDB vector store       |
| `data/`                | Folder containing your text or PDF files for knowledge ingestion        |
| `chroma_db/`           | Auto-generated local vector store (excluded from Git)                   |
| `.env`                 | Contains your OpenAI API key (never committed)                          |
| `.env.example`         | Template for setting up `.env`                                          |
| `.gitignore`           | Ensures `.env` and `chroma_db/` are ignored by Git                      |
| `README.md`            | This documentation                                                      |

---
