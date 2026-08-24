# LLM RAG Assistant

A Retrieval-Augmented Generation assistant that answers questions using documents, embeddings, vector search, and large language models.

---

## Overview

This project builds an AI assistant that can answer questions based on a given set of documents.

Instead of relying only on the language model's memory, the system retrieves relevant document chunks and uses them as context for the final answer.

---

## Problem

Large language models can hallucinate or give incorrect answers when asked domain-specific questions.

This project improves answer reliability by grounding responses in retrieved documents.

---

## Solution

The system uses:

- Document loading
- Text chunking
- Embedding generation
- Vector search
- Context retrieval
- Prompt construction
- LLM answer generation

---

## Architecture

```text
User Question
    ↓
Query Processing
    ↓
Embedding Generation
    ↓
Vector Search
    ↓
Retrieved Document Chunks
    ↓
Prompt Construction
    ↓
LLM Answer Generation
    ↓
Final Answer + Sources
```

---

## Tech Stack

| Category | Tool |
|---|---|
| Language | Python |
| LLM Framework | LangChain |
| Embeddings | OpenAI / Hugging Face |
| Vector Store | FAISS / Chroma |
| API | FastAPI |
| Evaluation | Custom metrics |

---

## Features

- Document ingestion
- Semantic search
- Context-aware answers
- Source citations
- API endpoint
- Evaluation pipeline

---

## Status

In progress.

---

## Next Steps

- [ ] Add document loader
- [ ] Add chunking pipeline
- [ ] Add embedding generation
- [ ] Add vector store
- [ ] Add retrieval evaluation
- [ ] Add FastAPI endpoint
- [ ] Add citation support
