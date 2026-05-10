# PDF AI Assistant — RAG-based Question Answering

A Google Colab-based AI assistant that answers questions from PDF documents using Retrieval-Augmented Generation.

The project extracts text from a PDF file, splits the content into chunks, creates embeddings, stores them in a vector database, retrieves relevant context, and generates answers using an LLM. It also supports text, image, and audio-style outputs.

## Notebook

[Open in Google Colab](https://colab.research.google.com/drive/1cnDF9h9InMKB7IlpydNnti5adjn1Mnfi?usp=sharing)

## Features

- PDF text extraction
- Text chunking for retrieval
- OpenAI embeddings
- Vector storage with ChromaDB
- Similarity search
- RAG-based question answering
- Text output
- Image output generation
- Audio output using text-to-speech
- Google Colab workflow

## Tech Stack

- Python
- Google Colab
- OpenAI API
- text-embedding-3-small
- ChromaDB
- pypdf
- gTTS
- Pillow
- Pydantic

## How It Works

1. Upload a PDF document in Google Colab.
2. Extract the text from the PDF.
3. Split the text into overlapping chunks.
4. Generate embeddings for the chunks.
5. Store the embeddings in ChromaDB.
6. Retrieve the most relevant chunks for a user question.
7. Generate an answer using an LLM.
8. Return the answer as text, image, or audio.

## Project Purpose

This project was built as part of my SoftUni AI Integrations work.  
It demonstrates practical use of LLM APIs, embeddings, vector databases, retrieval-augmented generation, and multimodal output workflows.

## Requirements

This notebook requires:

- A valid OpenAI API key
- Google Colab
- API billing/credits enabled for OpenAI usage

Do not commit API keys or private credentials to this repository.

## Status

Portfolio / educational project.
