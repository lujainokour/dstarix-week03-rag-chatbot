# DStarix Internship Guide Chatbot (RAG)

This repository contains a Retrieval-Augmented Generation (RAG) Chatbot designed to answer questions regarding the DStarix Internship Guide.

## Features
- Uses **LangChain** for RAG orchestration.
- Document Embeddings powered by **HuggingFace (all-MiniLM-L6-v2)**.
- Vector Storage utilizing **FAISS**.
- Generation handled by **Google Gemini API**.

## Setup Instructions
1. Clone the repository.
2. Install requirements using: `pip install -r requirements.txt`
3. Set your `GOOGLE_API_KEY` in the `.env` file.
4. Run the chatbot pipeline.
