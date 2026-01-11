# Semantic Quote Retrieval using RAG

## Project Description
This project implements a **semantic quote retrieval system** using **Retrieval Augmented Generation (RAG)** concepts.  
It allows users to search for quotes using **natural language queries** and retrieves the most relevant quotes based on **semantic similarity**, along with author and tags.

---

## Objective
To build an intelligent quote search system using the **Abirate/english_quotes** dataset where:
- Quotes are embedded using a sentence embedding model
- FAISS is used for fast similarity search
- Results are returned in a structured format

---

## Dataset
- **Name:** Abirate/english_quotes  
- **Source:** HuggingFace  
- **Fields Used:**
  - quote
  - author
  - tags

---

## Technologies Used
- Python
- Sentence Transformers
- FAISS
- Pandas
- Google Colab

---

## Workflow
1. Load and clean the quotes dataset
2. Generate sentence embeddings for each quote
3. Index embeddings using FAISS
4. Convert user query into embedding
5. Retrieve top-k similar quotes
6. Display results in structured JSON format

---

## Core Function

```python
retrieve_quotes("quotes about hope by oscar wilde")
## How to Run
1. Open the Google Colab notebook:
   https://colab.research.google.com/drive/1AwwX2NL2GwORIGWBTpM4eUR-mCwyQQ7N?usp=sharing

