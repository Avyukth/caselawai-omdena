
# Hybrid RAG

The Hybrid RAG approach combines both Vector RAG and Graph RAG methods to leverage their respective strengths.

In this approach:

1. A query is processed by both the vector and graph components.
2. The vector component retrieves semantically similar passages from Qdrant.
3. The graph component retrieves relevant structured information from Neo4j.
4. Results from both are combined and sent to the Language Model (LLM) for final answer generation.

This hybrid approach allows for comprehensive analysis of legal documents, capturing both semantic nuances and structured relationships. It enables flexible querying for both unstructured aspects of legal information and structured entity relationships.
