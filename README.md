# Keyword-Augmented Retrieval for RAG (KAR-RAG) & Fine-Tuning LLM

This repository contains two core components:
1. **Fine-Tuning LLM** – Fine-tunes a pre-trained language model to adapt it to specific domain queries.
2. **Keyword-Augmented Retrieval for RAG (KAR-RAG)** – Enhances Retrieval-Augmented Generation (RAG) pipelines with keyword extraction to improve context retrieval.

---

## 📌 Features
- Fine-tune large language models using domain-specific data.
- Extract keywords from queries to improve retrieval accuracy.
- Build a RAG system that integrates keyword search with semantic search.
- **KAR-RAG outperforms base RAG** in retrieval accuracy and answer relevance.
- Fine-tuned LLM achieved **ROUGE score of 0.6** in keyword extraction tasks.
- End-to-end pipeline: Dataset preprocessing → Model training → Retrieval → Generation.

---

## 🛠️ Installation
Clone the repository and install dependencies:

```bash
# Clone the repository
git clone https://github.com/Harsha-211/Keyword-Augmented-Retrieval-for-RAG-KAR-RAG-.git
cd Keyword-Augmented-Retrieval-for-RAG-KAR-RAG-

# Install the required dependencies
pip install -r requirements.txt
