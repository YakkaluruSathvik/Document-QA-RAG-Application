# Document QA RAG Application

## Overview

This project implements a Document QA Retrieval-Augmented Generation (RAG) application to analyze and answer questions based on US Census Bureau data. The application leverages advanced language models and embedding techniques to provide accurate and efficient responses.

## Features

- **Data Analysis**: Uses LangChain and HuggingFace models to process and analyze US Census Bureau data.
- **Document Embeddings**: Creates and stores document embeddings with Sentence Transformers (`all-MiniLM-l6-v2`) from HuggingFace.
- **Language Modeling**: Employs GPT-2 for generating responses and understanding queries.
- **Similarity Search**: Utilizes FAISS vector store for efficient similarity search between queries and document embeddings.
