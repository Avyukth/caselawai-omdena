
# Vector RAG (Retrieval-Augmented Generation)

Vector RAG uses dense vector embeddings to capture semantic meanings in legal text. This approach is particularly effective for understanding nuances in legal language, including complaints, arguments, and opinions.

## Key Components:

- Embedding Model: BAAI/bge-small-en-v1.5
- Vector Database: Qdrant
- Retrieval Method: Semantic similarity search

In Vector RAG, documents and queries are converted into vector representations. When a query is processed, the system retrieves semantically similar documents or passages from the Qdrant database. This allows for nuanced understanding of legal concepts beyond simple keyword matching.

## Strengths:

- Excellent at capturing semantic similarities and nuances in legal text
- Efficient for retrieving relevant information based on meaning rather than exact keyword matches

## Limitations:

- May not explicitly capture structured relationships between legal entities
