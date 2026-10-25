# RAG

Chunking, embeddings, vector stores, and reranking.

Section page: [Retrieval-Augmented Generation (RAG) Tutorial: Architecture, Implementation, and Production Guide](https://www.glukhov.org/rag/)

[Index of all sections](README.md)

## Architecture

- [Advanced RAG: LongRAG, Self-RAG and GraphRAG Explained](https://www.glukhov.org/rag/architecture/advanced-rag-variants-longrag-self-rag-graphrag/) — Deep dive into advanced RAG variants: LongRAG for long contexts, Self-RAG with self-reflection, and GraphRAG using knowledge graphs.
- [Search vs Deepsearch vs Deep Research](https://www.glukhov.org/rag/architecture/search-vs-deepsearch-vs-deep-research/) — Concepts and comparison

## Embeddings

- [Text embeddings for RAG and search - Python, Ollama, OpenAI-compatible APIs](https://www.glukhov.org/rag/embeddings/) — Learn what text embeddings are, how they power RAG and semantic search, and how to call embedding APIs from Python using Ollama or an OpenAI-compatible server (for example llama.cpp).
- [Cross-Modal Embeddings: Bridging AI Modalities](https://www.glukhov.org/rag/embeddings/using-cross-modal-embeddings/) — Master cross-modal embeddings for multimodal AI applications. Learn implementation strategies, explore CLIP, ImageBind, and contrastive learning techniques for unified representation spaces.
- [Qwen3 Embedding & Reranker Models on Ollama: State-of-the-Art Performance](https://www.glukhov.org/rag/embeddings/qwen3-embedding-qwen3-reranker-on-ollama/) — Qwen3 embedding and reranker models are revolutionizing multilingual NLP with state-of-the-art performance, and explore their integration with Ollama or local deployment via Hugging Face and GitHub.

## Retrieval

- [Chunking Strategies in RAG Comparison: Alternatives, Trade‑offs, and Examples](https://www.glukhov.org/rag/retrieval/chunking-strategies-in-rag/) — A rigorous, engineering‑first guide to chunking for RAG: fixed vs semantic vs hierarchical chunking, evaluation dimensions, decision matrix, and runnable Python implementations with FAISS/Chroma/Weaviate and OpenAI

## Vector stores

- [Vector Stores for RAG Comparison](https://www.glukhov.org/rag/vector-stores/vector-stores-for-rag-comparison/) — Comprehensive comparison of vector databases for Retrieval Augmented Generation: Pinecone, Chroma, Weaviate, Milvus, Qdrant, FAISS, and pgvector. Performance, features, and use cases.

## Reranking

- [Reranking text documents with Ollama and Qwen3 Embedding model - in Go](https://www.glukhov.org/rag/reranking/reranking-with-ollama-qwen3-embedding-golang/) — lang
- [Reranking text documents with Ollama and Qwen3 Reranker model - in Go](https://www.glukhov.org/rag/reranking/reranking-with-ollama-qwen3-reranker-golang/) — lang
- [Reranking with embedding models](https://www.glukhov.org/rag/reranking/reranking-with-embedding-models/) — as a RAG step
