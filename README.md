# 🌾 AgriBot – Multilingual Agronomic Question-Answering System

AgriBot is a multilingual AI-powered question-answering system designed to assist farmers and agricultural professionals by providing accurate, context-aware responses to queries related to crop diseases, pest management, and fertilizers. The system supports various Indian languages and leverages state-of-the-art NLP models like T5, DistilBERT, and BERT.

## 🚀 Features

- Multilingual support: Hindi, Marathi, Tamil, Punjabi, Bengali
- Language detection and bidirectional translation
- NLP pipeline using TF-IDF, cosine similarity
- QA via T5 (generative) and DistilBERT (extractive)
- Retrieval-Augmented Generation using web scraping + semantic search
- Fine-tuned on AgroQA Dataset
- Real-time interactive chatbot interface

## 📊 Methodology

1. **Language Detection** using `langdetect`
2. **Translation** using `googletrans`
3. **Query Matching** using TF-IDF + Cosine Similarity
4. **Answer Generation**:
   - Generative: T5
   - Extractive: DistilBERT
   - Fine-tuned BERT (SQuAD 2.0 + AgroQA)
5. **Context Enhancement** via RAG:
   - Web scraping & semantic retrieval (SentenceTransformers)

## 🔧 Tech Stack

- Python
- NLP Libraries: `transformers`, `sklearn`, `langdetect`, `googletrans`
- QA Models: T5, DistilBERT, BERT
- Sentence Transformers for semantic search
- AgroQA dataset for fine-tuning
- Web scraping for external context

## ⚙️ Challenges Addressed

- Language diversity and translation accuracy
- Domain-specific knowledge retrieval
- Real-time performance and system scalability

## 📈 Results

- Accurate and context-specific responses across multiple languages
- Enhanced advisory support in agriculture
- Continuous system improvement via expert validation and user feedback

## 📌 Future Work

- Improve translation pipeline for domain-specific terms
- Expand to more Indian languages
- Optimize for large-scale deployment using cloud infrastructure
