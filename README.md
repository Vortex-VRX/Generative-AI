# Generative-AI
Technologies: Python, GPT-2, TinyLLaMA, FAISS, BM25, MiniLM, Gradio, Sentence-Transformers

Built an advanced question answering system over a Stack Overflow-style dataset using a hybrid retrieval and generation approach. Integrated traditional IR techniques (BM25) with dense embeddings (MiniLM) and fused them via Reciprocal Rank Fusion (RRF) to extract relevant context. Answers were generated using local language models (GPT-2 and TinyLLaMA) without relying on external APIs.

1-Implemented dual-retrieval system using BM25 and MiniLM (sentence-transformers) with FAISS indexing.

2-Created a hybrid RRF-based fusion algorithm to merge traditional and dense results.

3-Integrated both GPT-2 and TinyLLaMA to generate high-quality natural language answers based on retrieved context.

4-Built a Gradio web interface for real-time QA interactions and answer citation.

5-Evaluated search quality using MAP@10, MRR@10, and nDCG@10 metrics (via pytrec_eval).

6-Demonstrated TinyLLaMA outperforming GPT-2 in both answer relevance and fluency.
