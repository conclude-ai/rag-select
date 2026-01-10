# RAG Optimizer Package

A framework for experimenting with and optimizing Retrieval-Augmented Generation (RAG) pipeline architectures.

## Overview

This package provides a framework for testing different RAG pipeline configurations and measuring their performance. It supports pluggable components for document ingestion, chunking strategies, and retrieval methods.

## Features

- **Modular Architecture**: Easily swap out ingestion, chunking, and retrieval implementations
- **Experiment Tracking**: RAGArtifact stores experiment parameters and metrics
- **Multiple Ingestion Methods**: Support for Unstructured and Docling document parsers
- **Flexible Chunking**: Sliding window chunking with customizable size and overlap
- **Type-Safe Vector DB Interface**: Protocol-based type hints for vector database integration
- **LangChain Integration**: Ready to integrate with LangChain Q&A pipelines
- **Evaluation Metrics**: Built-in support for Precision@K, Recall@K, and MRR

## Installation

### Development Installation

```bash
# Clone the repository
git clone <repository-url>
cd rag_package

# Install in development mode
pip install -r requirements.txt
pip install -e src/rag_search
```

## License

MIT
