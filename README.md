# RAG-Powered Document QA System with Astra DB and Groq LLM

This project is a Streamlit web application that implements a Retrieval-Augmented Generation (RAG) model to provide question answering capabilities over PDF documents. It leverages Astra DB as a vector store for document chunks and Groq LLM for language model inference, enabling users to ingest PDFs and interactively query document contents.

---

## Features

- Upload and parse PDF documents directly in the app.
- Split documents into meaningful chunks for efficient retrieval.
- Embed text chunks using HuggingFace embeddings.
- Store embeddings and documents in Astra DB vector store.
- Query documents using a LangChain RetrievalQA chain backed by Groq LLM.
- Interactive Streamlit UI for seamless user experience.

---

## Installation

### Prerequisites

- Python 3.8 or above
- Astra DB account with application token and database ID
- Groq API key for LLM access

### Setup

1. Clone the repository:


