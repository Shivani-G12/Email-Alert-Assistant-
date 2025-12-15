# Email Alert Assistant

## Overview
Email Alert Assistant is an intelligent system that automatically identifies
important emails such as offer letters, interview calls, and meeting invitations.
It uses a Retrieval-Augmented Generation (RAG) approach to improve accuracy and reliability.

## Technologies Used
- Python
- Hugging Face Transformers (FLAN-T5)
- SentenceTransformers
- ChromaDB (Vector Database)
- Gmail API
- Streamlit

## Features
- Automatically detects critical emails from inbox
- Uses RAG-based semantic retrieval with keyword fallback
- Stores and retrieves email embeddings using ChromaDB
- Displays alerts through an interactive Streamlit dashboard

## Architecture Overview
1. Emails are fetched using the Gmail API  
2. Text embeddings are generated using SentenceTransformers  
3. Relevant context is retrieved from ChromaDB  
4. FLAN-T5 generates a classification/decision  
5. Alerts are shown in the Streamlit dashboard  

## Project Type
Group Project

## My Role
Backend Developer  
- Designed and implemented the RAG pipeline  
- Handled embedding generation and retrieval logic  
- Integrated model inference and backend workflows  

> Note: API keys and credentials are not included for security reasons.
