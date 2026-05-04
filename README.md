# 🚀 NeuraDB — Semantic Search & RAG Engine

## Overview

NeuraDB is a custom-built semantic search and retrieval system that combines vector search algorithms with a Retrieval-Augmented Generation (RAG) pipeline using local LLMs.

The system enables efficient high-dimensional similarity search and context-aware question answering over embedded data.

---

## Key Features

- 🔍 **Vector Search Engine**  
  Implements HNSW, KD-Tree, and brute-force search for similarity retrieval

- 📏 **Multiple Distance Metrics**  
  Cosine similarity, Euclidean distance, Manhattan distance

- 🧠 **RAG Pipeline (LLM Integration)**  
  Uses local LLMs via Ollama for context-aware question answering

- ⚡ **Efficient Search**  
  Optimized from **O(N)** to **O(log N)** using HNSW

- 🌐 **REST API Backend**  
  Supports document ingestion, indexing, and querying

---

## System Architecture

Text Input  
↓  
Embedding Model (Ollama)  
↓  
Vector Index (HNSW / KD-Tree)  
↓  
Semantic Search  
↓  
LLM (Context + Generation)  
↓  
Answer

---

## Tech Stack

- **Languages:** C++, Python (planned rebuild)
- **Algorithms:** HNSW, KD-Tree, Brute Force
- **ML Concepts:** Embeddings, Semantic Search, RAG
- **Backend:** REST APIs
- **LLM Integration:** Ollama

---

## Project Structure

NeuraDB/  
├── main.cpp  
├── index.html  
├── httplib.h  
├── README.md

---

## Key Highlights

- Built a custom vector database from scratch
- Implemented multiple search algorithms for comparison
- Designed a retrieval pipeline integrating embeddings and LLMs
- Developed a full end-to-end system from indexing to inference

---

## Future Improvements

- Python-based modular rebuild
- Integration with vector databases (FAISS)
- Improved scalability and benchmarking
- Deployment with Docker

---
