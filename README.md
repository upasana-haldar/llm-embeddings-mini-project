# 🔍 LLM & Embeddings Mini Project

Hands-on exploration of **Large Language Models (LLMs)** and **word embeddings** using **Hugging Face Transformers** and **Gensim**, covering text generation, tokenisation, prompt engineering, and semantic similarity.

---

## 📌 Project Overview

This repository contains a graded mini project focused on understanding how modern NLP systems represent and process language.  
The project combines **LLM-based text generation** with **embedding-based similarity analysis** to bridge theory and practice.

The work demonstrates:
- How LLMs generate and structure text
- How tokenisation converts text into numerical representations
- How prompt engineering influences model output
- How word and sentence embeddings capture semantic meaning
- How cosine similarity enables vector-based retrieval

---

## 🧩 Project Objectives

- Demonstrate applications of embedding models  
- Implement vector-based similarity search  
- Explain semantic similarity concepts  
- Evaluate and interpret vector search results  

---

## 🛠️ Technologies Used

- **Python**
- **Hugging Face Transformers**
- **Gensim (GloVe embeddings)**
- **NumPy**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📂 Repository Structure

llm-embeddings-mini-project/
│
├── notebooks/ # Jupyter notebooks (main project + experiments)
├── src/ # Reusable Python scripts
├── data/ # Raw, processed, and result data
├── outputs/ # Generated text, embeddings, similarity results
├── screenshots/ # Output screenshots for report/article
├── report/ # Final PDF summary
├── requirements.txt # Project dependencies
└── README.md # Project documentation



---

## 📘 Sections Covered

### **Section A: LLM Foundations & Hugging Face**
- Load a lightweight LLM (`distilgpt2`)
- Generate multiple text continuations
- Demonstrate tokenisation (tokens, token IDs, sequence length)

### **Section B: Prompt Engineering**
- Design prompts for:
  - Summarisation
  - Question & Answer
  - Creative text generation
- Compare outputs across prompt styles
- Reflect on how prompt phrasing impacts results

### **Section C: Embeddings with Gensim**
- Load GloVe embeddings (`glove-wiki-gigaword-50`)
- Analyse word vectors and similarity scores
- Build sentence embeddings using averaged word vectors
- Compute cosine similarity matrix for sentence comparison

### **Section D: Transformer Application**
- Apply a Hugging Face pipeline (e.g., sentiment analysis)
- Reflect on real-world business and professional use cases

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/llm-embeddings-mini-project.git
cd llm-embeddings-mini-project
