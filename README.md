# 📚 RAG Book Assistant

A simple Retrieval-Augmented Generation (RAG) application built with **Streamlit**, **LangChain**, **ChromaDB**, **Hugging Face Embeddings**, and **Mistral AI**. Upload a PDF, create a vector database, and ask questions based on the document.

## Features

* Upload PDF documents
* Create embeddings using Hugging Face
* Store embeddings in ChromaDB
* Retrieve relevant document chunks
* Ask questions using Mistral AI
* Answers are generated only from the uploaded document

## Installation

```bash
git clone <repository-url>
cd <project-folder>

# Install dependencies
uv sync
```

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key_here
```

## Run the App

```bash
uv run streamlit run app.py
```

## Tech Stack

* Streamlit
* LangChain
* ChromaDB
* Hugging Face Embeddings
* Mistral AI

## License

This project is for educational purposes.
