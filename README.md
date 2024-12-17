# Chat-with-websites-using-RAG-pipelines
# Web Scraping and Embedding-Based Search

## Description
This project demonstrates how to:
- Scrape content from websites using `requests` and `BeautifulSoup`.
- Convert textual content into embeddings using the `SentenceTransformer` model.
- Store embeddings in a FAISS index for efficient similarity search.
- Handle user queries and retrieve relevant content based on embeddings.

## Features
- **Web Scraping**: Extracts textual content from a list of URLs.
- **Embedding Conversion**: Uses pre-trained models from `transformers` for encoding text.
- **FAISS Indexing**: Implements FAISS for similarity-based content retrieval.
- **Query Handling**: Retrieves top-matching website chunks based on user queries.
