#Clinical-AI-Assistant-using-Multi-Agent-AI-and-RAG

## Overview
This project is an AI-powered Clinical Assistant that uses a Multi-Agent architecture to analyze patient symptoms and provide intelligent medical support. The system leverages Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and vector search to process patient information and generate context-aware responses.

## Features
- Extract symptoms from patient input
- Multi-Agent workflow for medical reasoning
- Retrieval-Augmented Generation (RAG)
- Vector database using FAISS
- Medical knowledge retrieval
- AI-generated diagnosis suggestions
- Interactive clinical assistant

## Technologies Used
- Python
- LangChain
- Groq LLM
- FAISS
- Hugging Face Embeddings
- Google Colab
- JSON

## Project Workflow
1. Receive patient symptoms.
2. Extract structured medical information.
3. Search relevant medical knowledge using FAISS.
4. Generate context-aware responses with the LLM.
5. Return diagnosis suggestions and recommendations.

## Installation
```bash
pip install langchain
pip install langchain-groq
pip install langchain-community
pip install langchain-huggingface
pip install faiss-cpu
