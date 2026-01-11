# RAG-Based Semantic Quote Retrieval

## Project Overview
This project implements a Retrieval-Augmented Generation (RAG) system for semantic quote retrieval using the Abirate/english_quotes dataset. The system retrieves relevant quotes based on natural language queries using sentence embeddings and vector similarity search.

## Dataset
- **Source:** Abirate/english_quotes (HuggingFace)
- **Fields:** quote, author, tags

## Approach
1. Loaded and cleaned the dataset using HuggingFace Datasets.
2. Generated sentence embeddings using a SentenceTransformer (MiniLM).
3. Indexed embeddings using FAISS for efficient similarity search.
4. Retrieved top relevant quotes for a given query.
5. Returned structured JSON output containing quotes, authors, and tags.

## Tools & Libraries
- Python
- Google Colab
- sentence-transformers
- FAISS
- HuggingFace Datasets
- Pandas, NumPy

## How to Run
1. Open the Google Colab notebook:
   - https://colab.research.google.com/drive/1AwwX2NL2GwORIGWBTpM4eUR-mCwyQQ7N?usp=sharing
2. Run all cells from top to bottom.
3. Enter a query using the retrieval function.

## Example Queries
- "Quotes about hope by Oscar Wilde"
- "Motivational quotes about accomplishment"
- "Humorous quotes by Oscar Wilde"

## Limitations
- No explicit generative LLM response due to resource constraints.
- Model fine-tuning limited to embedding-level adaptation.

## Future Improvements
- Integrate a full generative LLM for answer synthesis.
- Deploy as a web application.
- Add RAG evaluation metrics.

## Demo Video
- (Paste your Google Drive demo video link here)
