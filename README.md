# RAG PDF Chatbot

AI-powered RAG (Retrieval-Augmented Generation) chatbot for answering questions from PDF documents using LangChain, FAISS, and OpenAI API.

---

## Features

- Upload PDF documents
- Ask questions from uploaded PDFs
- Context-aware intelligent responses
- Semantic search using vector embeddings
- Fast document retrieval with FAISS
- Interactive chatbot interface
- REST API integration

---

## Tech Stack

### Programming Language
- Python

### Generative AI & LLM
- LangChain
- OpenAI API
- RAG Architecture
- Embeddings

### Vector Database
- FAISS

### Backend
- FastAPI
- Flask

### Frontend
- HTML
- CSS
- JavaScript

### Tools & Libraries
- PyPDF
- NumPy
- Pandas

---

## Project Workflow

1. Upload PDF document
2. Extract text from PDF
3. Split text into chunks
4. Generate embeddings
5. Store embeddings in FAISS vector database
6. Retrieve relevant context
7. Generate intelligent answers using LLM

---

## Folder Structure

```bash
rag-pdf-chatbot/
│
├── app.py
├── main.py
├── chunking.py
├── data_ingestion.py
├── embedding.py
├── requirements.txt
├── Dockerfile
├── README.md
├── index.html
│
├── static/
│   ├── style.css
│   └── javascript.js
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/RAMESH18041999/rag-pdf-chatbot.git
```

### Move to Project Folder

```bash
cd rag-pdf-chatbot
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run Project

```bash
python app.py
```

or

```bash
uvicorn main:app --reload
```

---

## Future Improvements

- Multi-PDF support
- Chat history
- Voice-based interaction
- Deployment on cloud
- Advanced document search
- Authentication system

---

## Author

### Ramesh Chandra Mahakud

- GitHub: https://github.com/RAMESH18041999
- LinkedIn: https://www.linkedin.com/in/rameshchandramahakud/

---

## License

This project is developed for educational and learning purposes.
