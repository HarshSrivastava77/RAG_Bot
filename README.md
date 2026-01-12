##RAG System for Mathematics for Machine Learning

Python | OpenAI API | Qdrant | Docker | RAG | Vector Databases

Built a Retrieval-Augmented Generation (RAG) pipeline to answer mathematical queries from the Mathematics for Machine Learning textbook with high factual accuracy.

Implemented PDF ingestion and intelligent text chunking to preserve mathematical and contextual continuity.

Generated semantic embeddings using OpenAI embedding models and stored them in Qdrant vector database for efficient similarity search.

Deployed Qdrant using Docker & Docker Compose, enabling reproducible and scalable vector database setup.

Designed a context-aware QA system that retrieves relevant textbook sections via cosine similarity before LLM response generation.

Reduced hallucinations by grounding responses in retrieved source context, improving reliability for technical learning.

Tools & Technologies:
Python, RAG, OpenAI API, Qdrant, Vector Databases, Docker, PDF Parsing, Cosine Similarity

🚀 Key Features

PDF ingestion & overlapping text chunking

Semantic embeddings using OpenAI models

Vector similarity search with Qdrant

Fully Dockerized vector database setup

Context-aware mathematical Q&A

🏗️ Architecture

PDF Loader → Extracts raw textbook text

Chunking → Preserves mathematical context

Embeddings → Dense vector generation

Vector Store → Qdrant (Dockerized)

Retriever → Cosine similarity search

LLM → Context-grounded answer generation

🧠 Why RAG for Mathematics?

Ensures high factual accuracy

Reduces hallucinations in symbol-heavy explanations

Grounds responses in original textbook context

🔹 Skills Mapping 

Databases: Vector Databases (Qdrant)
AI/ML: RAG, LLMs, Embeddings, Semantic Search
Tools: Docker, OpenAI API
Languages: Python