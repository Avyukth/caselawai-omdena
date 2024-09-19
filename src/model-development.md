
# Model Development

## Approaches Explored

- [Vector RAG](./vector_rag.md)
- [Graph RAG](./graph_rag.md)
- [Hybrid RAG](./hybrid_rag.md)

# Methodology

#### Our methodology involved implementing and comparing three distinct approaches: Vector RAG, Graph RAG, and Hybrid RAG. We used a combination of open-source libraries and custom implementations to build each system.

- For Vector RAG, we utilized the LlamaIndex library, which provides efficient tools for document indexing and retrieval. We used the BAAI/bge-small-en-v1.5 model for generating embeddings and Qdrant as our vector database.

- For Graph RAG, we employed Neo4j as our graph database and used a combination of LangChain and NetworkX for graph creation and querying.

- The Hybrid RAG approach combined elements from both Vector and Graph RAG, using custom implementations to integrate the two methods seamlessly.

