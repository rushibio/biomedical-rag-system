# BioRAG - 3-Way Biomedical RAG Comparison

A complete RAG system for biomedical literature that compares three answering approaches side-by-side.

## Features
- Downloads papers from PubMed Central
- Semantic search with sentence-transformers
- **3-way output comparison**: Raw Retrieval | Standard LLM | Few-shot LLM

## How to Run
1. Open in Colab
2. Add your Groq API key
3. Run all cells

## Sample Output
- Raw Retrieval: Shows similarity scores (0.534, 0.291, 0.289)
- Standard LLM: Direct mutation list
- Few-shot LLM: Structured answer with percentages (EGFR 61.5%, KRAS 8.2%, etc.)
