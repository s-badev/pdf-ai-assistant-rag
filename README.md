# 📄 PDF AI Assistant — RAG-based Question Answering

<p align="left">
  <a href="https://colab.research.google.com/drive/1cnDF9h9InMKB7IlpydNnti5adjn1Mnfi?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-black?logo=openai" />
  <img src="https://img.shields.io/badge/ChromaDB-Vector%20Store-purple" />
  <img src="https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-green" />
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab" />
  <img src="https://img.shields.io/badge/Status-Portfolio%20Project-success" />
</p>

A Google Colab-based AI assistant that answers questions from PDF documents using **Retrieval-Augmented Generation (RAG)**.

The project extracts text from a PDF, splits it into chunks, generates embeddings, stores them in a vector database, retrieves relevant context, and produces answers with an LLM. It also supports **text**, **image**, and **audio** style outputs.

---

## ✨ Highlights

- 📥 PDF text extraction
- ✂️ Text chunking for retrieval
- 🧠 OpenAI embeddings
- 🗂️ Vector storage with ChromaDB
- 🔎 Similarity search
- 💬 RAG-based question answering
- 🖼️ Image output generation
- 🔊 Audio output using text-to-speech
- ☁️ End-to-end workflow in Google Colab

---

## 🧭 Project Workflow

```mermaid
flowchart TD
    A[Upload PDF] --> B[Extract Text]
    B --> C[Split into Chunks]
    C --> D[Generate Embeddings]
    D --> E[Store in ChromaDB]
    E --> F[User Question]
    F --> G[Similarity Search]
    G --> H[Retrieve Relevant Chunks]
    H --> I[LLM Generates Answer]
    I --> J[Text Output]
    I --> K[Image Output]
    I --> L[Audio Output]

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Environment | Google Colab |
| LLM / API | OpenAI API |
| Embeddings | `text-embedding-3-small` |
| Vector Database | ChromaDB |
| PDF Processing | pypdf |
| Audio | gTTS |
| Image Handling | Pillow |
| Validation / Models | Pydantic |

---

## 📚 How It Works

1. Upload a PDF document in Google Colab
2. Extract the text from the PDF
3. Split the content into overlapping chunks
4. Generate embeddings for each chunk
5. Store embeddings in ChromaDB
6. Ask a question about the PDF
7. Retrieve the most relevant chunks
8. Generate an answer using an LLM
9. Return the result as **text**, **image**, or **audio**

---

## 🚀 Open the Notebook

👉 **[Open in Google Colab](https://colab.research.google.com/drive/1cnDF9h9InMKB7IlpydNnti5adjn1Mnfi?usp=sharing)**

---

## 📌 Example Use Cases

This assistant can be used to:

- summarize large PDF documents
- answer questions from reports, guides, or e-books
- retrieve targeted information from long documents
- experiment with RAG workflows in a practical environment

---

## 🎯 Project Purpose

This project was built as part of my **SoftUni AI Integrations** work.

It demonstrates practical use of:

- LLM APIs
- embeddings
- vector databases
- retrieval-augmented generation
- multimodal output workflows

---

## ⚙️ Requirements

To run the notebook successfully, you need:

- a valid **OpenAI API key**
- **Google Colab**
- available **API billing / credits**

> **Important:** Do not commit API keys or private credentials to this repository.

---

## 📁 Repository Contents

```text
pdf-ai-assistant-rag/
├── PDF_AI_Assistant_RAG.ipynb
└── README.md
