Hybrid QA Assistant: README
Overview
This project implements a hybrid question-answering system that combines:

Dual Retrieval Methods:

Keyword-based (BM25)

Semantic search (MiniLM embeddings + FAISS)

Rank Fusion: Reciprocal Rank Fusion (RRF)

Answer Generation:

GPT-2 (initial implementation)

TinyLlama (optimized version)

The system answers technical questions using StackExchange's Data Science corpus 

Requirements
text
pip install -r requirements.txt
File Structure
text
├── stacklite_dataset/          # QA dataset
│   ├── top_datascience_questions.json
│   ├── queries.json
│   └── qrels.json
├── models/                     # LLM weights (TinyLlama)

└── code.ipynb
Usage
GPT-2 

TinyLlama 

The web interface will launch at http://localhost:7861