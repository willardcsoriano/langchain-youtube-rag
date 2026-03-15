# YouTube Video Question Answering using RAG

This project builds a Retrieval-Augmented Generation (RAG) system capable of answering questions about YouTube videos.

## Features
- Extracts transcripts from YouTube videos
- Splits transcripts into chunks
- Generates embeddings
- Stores embeddings in FAISS vector database
- Uses a local LLM (Llama3 via Ollama) to answer questions

## Technologies
- Python
- LangChain
- FAISS
- Ollama
- Jupyter Notebook

## Example Workflow
1. Load YouTube transcripts
2. Split transcript into chunks
3. Generate embeddings
4. Store vectors in FAISS
5. Ask questions about the video content

## Setup

Install dependencies:

\\\
pip install -r requirements.txt
\\\

Run Ollama models:

\\\
ollama pull llama3
ollama pull nomic-embed-text
\\\

Then run the Jupyter notebook.

## Project Structure

\\\
project/
│
├── notebook.ipynb
├── notebook.html
├── requirements.txt
├── README.md
└── .gitignore
\\\

## Author
Your Name
