# 🧠 AI Powered Resume Analyzer

This project is an **AI-powered tool** that analyzes PDF resumes using OpenAI’s language models and semantic search.  
It helps you extract, chunk, embed, and query resume content intelligently.

---

## 🚀 Project Overview

The notebook performs the following tasks:

- **PDF Parsing**: Reads any uploaded PDF resume.
- **Text Chunking**: Splits the extracted text into overlapping chunks for better semantic understanding.
- **Embeddings Generation**: Uses OpenAI Embeddings to vectorize the chunks.
- **Vector Store**: Stores vectors in a FAISS index for fast similarity search.
- **Question Answering**: Uses OpenAI’s Chat Model with a QA chain to answer any query about the resume.

---

## ✅ Features

- Upload any PDF resume and analyze its contents.
- Split large texts into context-preserving chunks.
- Store semantic vectors locally with FAISS.
- Ask any question about the resume and get answers instantly.
- Easy to customize for different documents or question sets.

---

## 🛠️ Requirements

- Python 3.x
- `PyPDF2`
- `langchain`
- `faiss-cpu`
- `openai`

---

## 📦 Install Dependencies

Install all required libraries:

```bash
pip install PyPDF2 langchain faiss-cpu openai
