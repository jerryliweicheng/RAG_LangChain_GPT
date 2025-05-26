##Retrieval-Augmented Generation (RAG) Demo Project

This project demonstrates a simple Retrieval-Augmented Generation (RAG) system using LangChain, ChromaDB, OpenAI API, and Streamlit.

## What is RAG?

RAG combines retrieval of relevant documents from your own data source with generation by a large language model (LLM) like GPT. This allows the system to provide answers based on both the model's knowledge and your custom, up-to-date information.

## Features

- Load your own text documents as knowledge base
- Split long texts into manageable chunks for embedding
- Use vector embeddings and ChromaDB to index and retrieve relevant documents
- Use OpenAI GPT models to generate answers grounded in retrieved context
- Simple web interface built with Streamlit for interactive Q&A

## Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://your-repo-url.git
   cd rag_project
