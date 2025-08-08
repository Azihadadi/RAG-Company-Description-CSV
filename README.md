# RAG, RAG-Fusion, and RAG-Multi-Query

## Overview
This repository implements Retrieval-Augmented Generation (RAG) techniques to analyze company descriptions. It includes three main components: RAG, RAG-Fusion, and RAG-Multi-Query, each designed to enhance the performance of querying a dataset of public companies.

## Components

### 1. RAG
- The RAG component processes company descriptions to answer basic questions using a language model.
- **Key Features**:
  - Loads and preprocesses company data.
  - Utilizes a language model (LLAMA 3.1) to generate answers based on company descriptions.
  - Evaluates performance using ROUGE scores and cosine similarity.

### 2. RAG-Fusion
- This component enhances the RAG approach by fusing results from multiple retrieval queries.
- **Key Features**:
  - Generates multiple queries from a single question using a language model.
  - Implements reciprocal rank fusion to combine results from different queries.
  - Evaluates the quality of answers against ground truth data.

### 3. RAG-Multi-Query
- This implementation focuses on generating multiple perspectives on a single user question to improve retrieval accuracy.
- **Key Features**:
  - Produces alternative queries to retrieve relevant documents.
  - Combines results from multiple queries while removing duplicates.
  - Evaluates performance using ROUGE scores and cosine similarity.

## Requirements
To run this project, you will need:
- Python 3.x
- Required libraries (listed in `requirements.txt`):
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
   git clone https://github.com/Azihadadi/RAG_Company_Description_CSV/
   cd RAG_Company_Description_CSV
   
