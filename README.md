# RAG Implementation with Pinecone and LangChain

This repository demonstrates how to create a Question-Answering (QA) system using Retrieval-Augmented Generation (RAG) with Pinecone vector store and Google's Generative AI.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Required Packages](#required-packages)
- [Environment Setup](#environment-setup)
- [Components](#components)
- [Implementation Steps](#implementation-steps)
- [Usage](#usage)
- [Architecture](#architecture)
- [Rate Limiting](#rate-limiting)

## Prerequisites

Before setting up the system, ensure that you have the following:

- **Python 3.x**: Install the latest version of Python.
- **Pinecone API Key**: Sign up at [Pinecone](https://www.pinecone.io/) and obtain your API key.
- **Google API Key**: Get your Google API key from the [Google Cloud Console](https://console.cloud.google.com/) for embeddings and the language model.

## Required Packages

The following Python packages are required for this implementation:

```bash
pip install langchain
pip install langchain_pinecone
pip install langchain_community
pip install pinecone-client
pip install langchain-google-genai
pip install openai
pip install tqdm
pip install pypdf
pip install PyPDF2
pip install python-dotenv