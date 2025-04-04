# Retrieval-Augmented Generation (RAG) Pipeline Using OpenAI & Pinecone

This project demonstrates a simple Retrieval-Augmented Generation (RAG) system using OpenAI's embedding model and Pinecone's vector database for semantic search. It loads Wikipedia articles, generates embeddings, stores them in Pinecone, and performs semantic similarity search to enhance question-answering capabilities.

## 🧠 What It Does

- Loads a dataset of Wikipedia articles
- Extracts and embeds text using OpenAI's `text-embedding-ada-002`
- Stores vector embeddings in Pinecone
- Queries Pinecone for relevant documents based on a user query
- Retrieves top-k most relevant passages for contextual use

## 📦 Technologies Used

- [OpenAI API](https://platform.openai.com/)
- [Pinecone](https://www.pinecone.io/)
- [Hugging Face Datasets](https://huggingface.co/docs/datasets/)
- Python + Pandas + tqdm

## 🚀 Getting Started

### 1. Install Dependencies

```bash
pip install openai pinecone-client datasets pandas tqdm
