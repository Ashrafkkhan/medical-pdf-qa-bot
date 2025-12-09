🏥 Medical Assistant Bot — README

A Retrieval-Augmented Generation (RAG) chatbot built using:

LangChain

FAISS Vector Store

HuggingFace Embeddings

LLaMA (via CTransformers)

Chainlit UI

This bot retrieves information from your FAISS knowledge base and uses a custom prompt to provide accurate, source-grounded answers.


📌 Features

✅ Uses FAISS for fast vector search
✅ Uses sentence-transformers/all-MiniLM-L6-v2 for embeddings
✅ Loads LLaMA-2 7B (GGML) locally using CTransformers
✅ Provides retrieved source documents
✅ Fully interactive UI with Chainlit
✅ Custom RAG prompt for safe & accurate medical responses
