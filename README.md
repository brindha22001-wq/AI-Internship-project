# AI Internship Project – Skillryt

## 🍽 Project Title
Coimbatore Restaurant & Food Discovery AI Assistant using RAG

---

## 📌 Project Overview

This project implements a domain-specific AI chatbot that helps users discover restaurants in Coimbatore.  
The system uses Retrieval-Augmented Generation (RAG) architecture to provide accurate and context-aware responses.

The chatbot:
- Scrapes restaurant data from public sources
- Cleans and structures the dataset
- Generates embeddings
- Stores them in a vector database
- Retrieves relevant data for user queries
- Uses an LLM to generate final responses
- Provides an interactive chatbot UI

---

## 🧠 System Architecture

User Query  
→ Query Embedding  
→ Vector Database (FAISS / ChromaDB)  
→ Retrieve Top-K Relevant Documents  
→ Inject Context into LLM Prompt  
→ Generate Context-Aware Response  
→ Display in Chatbot UI  

---

## 🛠 Technologies Used

- Python
- BeautifulSoup / Requests (Web Scraping)
- Pandas (Data Processing)
- SentenceTransformers (Embeddings)
- FAISS / ChromaDB (Vector Database)
- OpenAI / HuggingFace LLM
- Streamlit (Frontend UI)

---

## 📂 Project Structure

AI-INTERN PROJECT  
│  
├── Backend  
│   ├── scraper.py  
│   ├── preprocess.py  
│   ├── rag_pipeline.py  
│   ├── backend_prompt_template.txt  
│   └── data/  
│  
├── Front end  
│   ├── app.py  
│   ├── system_prompt.txt  
│   └── rag_prompt_template.txt  
│  
└── README.md  

---

## 🎯 Learning Objectives

- Understand LLM-based chatbot systems
- Implement Retrieval-Augmented Generation (RAG)
- Perform web scraping
- Clean and preprocess unstructured data
- Generate embeddings and use vector databases
- Integrate LLMs for domain-specific applications
- Build an interactive chatbot UI
- Evaluate chatbot performance

---

## 📊 Expected Outcomes

The chatbot can answer questions such as:
- Best restaurants in Coimbatore
- Restaurants under ₹500
- South Indian restaurants
- Restaurant ratings
- Menu availability

---

## ✅ Evaluation Alignment

This project satisfies:
- Web Scraping & Data Collection
- Data Cleaning & Preprocessing
- RAG Implementation
- LLM Integration
- Chatbot UI Development
