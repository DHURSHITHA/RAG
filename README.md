# Retrieval-Augmented Generation (RAG) using LangChain & Google Gemini

This project demonstrates a complete **Retrieval-Augmented Generation (RAG)** pipeline that combines **semantic search** with **LLM-based text generation**. It retrieves relevant information from Wikipedia, stores it as vector embeddings, and generates accurate, context-aware responses using Google Gemini.

---

## 🧠 What is RAG?
Retrieval-Augmented Generation (RAG) is an AI architecture that enhances Large Language Models (LLMs) by retrieving relevant information from external data sources before generating a response. This approach improves factual accuracy, reduces hallucinations, and allows models to use up-to-date or domain-specific knowledge.

---

## 🏗️ High-Level Architecture

1. **Data Ingestion Pipeline**
   - Loads documents from Wikipedia
   - Converts text into embeddings
   - Stores embeddings in a vector database

2. **Retrieval Pipeline**
   - Embeds the user query
   - Performs semantic similarity search
