# RAG Chatbot — Chat with Your Documents (LangChain + FAISS + Gemini)

This project is a Retrieval-Augmented Generation (RAG) based chatbot that allows users to upload documents (PDFs) and ask questions. The chatbot provides accurate answers by retrieving relevant information from the uploaded content instead of relying purely on the LLM, reducing hallucination and improving reliability.

## Features
- Upload PDF and convert it to text
- Split content into meaningful chunks
- Generate embeddings for each chunk
- Store embeddings in FAISS vector database
- Perform semantic similarity search
- Answer queries using Google Gemini LLM
- Returns context and source reference

## 🧠 Architecture Flow
<img width="1556" height="52" alt="image" src="https://github.com/user-attachments/assets/cd6fb1a9-4b50-4d80-87c1-31725ad5b14f" />

