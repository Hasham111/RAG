 Simple RAG System from PDF Using FAISS
Overview

This project implements a minimal Retrieval-Augmented Generation (RAG) pipeline that converts a PDF into searchable text chunks and answers questions using vector search. It extracts text from a PDF, generates embeddings, stores them in a FAISS index, and retrieves the most relevant chunk to produce an answer with an LLM.

 Features

 PDF text extraction using PyPDF

 Automatic text chunking for better retrieval

 Embeddings generation using an LLM API

 Fast vector search with FAISS

 Simple RAG pipeline to answer natural language questions

 Example queries included

 Tech Stack

Python

PyPDF

FAISS

LLM API (for embeddings + answer generation)

Google Colab runtime

 Workflow

Upload PDF using Colab

Extract text

Chunk text

Generate embeddings

Build FAISS index

Query the index

Use LLM to generate answer

 Example
query = "What is mammals?"
answer = answer_query(query)
print(answer)

 Project Goal

To demonstrate the simplest possible RAG pipeline that works from a PDF without requiring a large backend or heavy frameworks.
