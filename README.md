# RAG-LLM-PROJECT

# PresentPal Bot

Welcome to PresentPal Bot, an intelligent chatbot designed to help students and professionals navigate the rules and regulations for preparing and presenting papers.

<img width="1010" alt="Image" src="https://github.com/user-attachments/assets/34e5f4b8-6989-411e-94b3-a52eeba524e2">

## Overview

PresentPal Bot is an AI-powered FAQ system that provides quick and accurate answers to questions about paper preparation, presentation guidelines, and related regulations. Leveraging the power of Google Palm LLM, HuggingFace embeddings, and FAISS vector stores, PresentPal Bot ensures that users have access to reliable information at their fingertips.




## Features

- **Intelligent Query Handling:** Uses advanced language models to understand and respond to user queries.
- **Comprehensive Knowledge Base:** Covers a wide range of topics related to campus rules and regulations.
- **Interactive Interface:** Built with Streamlit for an engaging user experience.
- **Scalable and Extendable:** Designed to be easily extendable with additional documents and data sources.

## Project Structure

- `Helper.py`: Contains functions for creating the vector database and setting up the QA chain.
- `Main.py`: The main entry point for the Streamlit application.
- `rules.txt`: Contains the rules and regulations document used for creating the vector database.

## Getting Started

### Prerequisites

- Python 3.7+
- Streamlit
- HuggingFace Transformers
- FAISS
- Google API Key

Note: Use .env file for providing API Key.
