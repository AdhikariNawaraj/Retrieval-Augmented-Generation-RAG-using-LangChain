# Retrieval-Augmented-Generation-RAG-using-LangChain

This repository demonstrates an end-to-end Retrieval-Augmented Generation (RAG) system designed to efficiently extract information from PDF documents and deliver context-aware answers using Large Language Models (LLMs). The project implements a complete pipeline including PDF ingestion, text preprocessing, embeddings creation, vector storage, retrieval, and LLM-powered response generation using LangChain and Groq.

**Skills Demonstrated**: 

- Retrieval-Augmented Generation (RAG) Architecture Design

- LangChain for LLM-based Application Development

- Vector Databases & Embeddings (FAISS / Chroma)

- Python for NLP & Document Processing

**Project Overview**:

This project implements a RAG pipeline where PDF documents are processed, converted into vector embeddings, stored in a vector database, and retrieved upon user query. Unlike standard LLM responses, RAG enhances accuracy by grounding answers in uploaded documents.
It is suitable for use cases such as:

- Document-based Q&A systems

- Research assistance and knowledge retrieval

- Enterprise knowledge bots

- Automated PDF and policy document analysis

**Tech Stack**:


<img width="456" height="302" alt="image" src="https://github.com/user-attachments/assets/928b0bc0-758d-47fb-8fbc-ce00ec06d3f4" />

**Repository Structure**:


├── document.ipynb                        # Main end-to-end RAG pipeline

├── pdf_loader.ipynb                      # PDF ingestion and text extraction

├── RAG with Langchain.ipynb              # RAG implementation using LangChain

├── requirements.txt                      # Python dependencies

├── assets/

│     └── rag_architecture.png           # System architecture diagram

└── README.md                            # Project documentation


**Reference**:

The concept of attention-based models is inspired by the paper:

Vaswani et al., “Attention Is All You Need” (2017)


**Future Enhancements**:

- Add support for multi-document retrieval

- Integrate OpenAI / Llama 3 for comparison with Groq

- Deploy as a web app (Streamlit or FastAPI)

- Add citation highlighting in model responses

  

