# Medical Chatbot using RAG (Retrieval-Augmented Generation)

A **Medical Question-Answering Chatbot** built using **LangChain**, **Pinecone**, and **OpenAI GPT-4o**.  
This project allows users to ask medical questions, and the bot retrieves relevant context from PDF documents to generate concise, accurate answers.

---

## Features

- Load and process PDF documents.
- Split large documents into smaller chunks for better embedding.
- Generate embeddings using **HuggingFace sentence-transformers**.
- Store and search embeddings using **Pinecone Vector Database**.
- RAG pipeline for answering questions with context.
- Add new documents dynamically to the knowledge base.
- Concise answers limited to three sentences.
- Uses **GPT-4o** for generating natural language answers.

---

## Installation

1. **Clone the repository**
```bash
git clone <repository-url>
cd <repository-folder>
```
2. **Setup**
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```
3.**Install dependencies**
```bash
pip install -r requirements.txt
```
4.Dependencies used in the project
```bash
langchain
langchain-community
pypdf
sentence-transformers
pinecone
langchain-pinecone
python-dotenv
```
