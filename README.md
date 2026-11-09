# RAG System: Kenyan Employment and Labour Court Decisions

A retrieval-augmented generation (RAG) notebook that answers questions about 37
Employment and Labour Relations Court decisions from 2025, with source citations.

## Stack
- Source: Kenya Law (public court judgments)
- Embeddings: intfloat/e5-base-v2
- Vector DB: Chroma (local, persisted)
- LLM: Qwen2.5-3B-Instruct (local, no API key)

## How to run
1. Open the notebook in Google Colab and set the runtime to a T4 GPU.
2. Upload the zip of case files to `/content`.
3. Run all cells. Type `exit` at the Task 7 prompt to continue.

## Data
Court decisions are from Kenya Law (kenyalaw.org), used for non-commercial academic purposes. All rights remain with their owners.

## Disclaimer
Educational use only. Not legal advice.