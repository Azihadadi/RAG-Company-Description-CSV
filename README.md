# Gen AI Company Description RAG

## Overview
This repository utilizes a dataset of public companies, featuring their names and descriptions. The goal is to deploy a language model that processes these descriptions and answers basic questions related to the data.

## Objectives
- Develop a management tool for analyzing company descriptions.
- Implement a retrieval-augmented generation (RAG) approach to answer questions based on company data.
- Evaluate the performance of the model using ROUGE scores and cosine similarity metrics.

## Features
- **Data Processing**: Load and preprocess company data from a CSV file.
- **Embedding Model**: Use Hugging Face embeddings for semantic understanding.
- **Retrieval Mechanism**: Implement a vector database using Qdrant for efficient retrieval.
- **Language Model**: Utilize the LLAMA 3.1 model for generating responses based on retrieved data.
- **Evaluation Metrics**: Assess performance using ROUGE scores and cosine similarity.

## Requirements
To run this project, you will need:
- Python 3.x
- Required libraries (listed in requirements.txt):
  - pandas
  - numpy
  - qdrant-client
  - langchain-community
  - rouge-score
  - transformers
  - etc.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Azihadadi/Gen_AI_Company_Description_RAG/
   
