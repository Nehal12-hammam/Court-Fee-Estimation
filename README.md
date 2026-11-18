# Court Fee Estimation System - AI-Assisted Legal RAG

## 📌 Overview
Built an intelligent system designed to calculate Egyptian court fees under **Law No. 90 of 1944**. The architecture combines a deterministic fee calculation engine with an AI-assisted RAG pipeline for handling uncovered or complex legal cases.

## 🛠️ Key Features & Architecture
- **Deterministic Engine:** Handles precise, rule-based statutory fee calculations.
- **AI-Assisted RAG Pipeline:** Leverages **Qwen2.5-Instruct (4-bit)** for intelligent reasoning and rule extraction.
- **Hybrid Retrieval:** Powered by **Qdrant** supporting semantic and lexical (BM25) search with page-level citations.
- **Safe Evaluation & Human-in-the-Loop:** Structured extraction rules are verified against verbatim source quotes, run through a safe expression interpreter (no `eval`), and require human approval before activation.
- **Interactive UI:** Deployed with **Gradio** on **Google Colab**.

## 💻 Technologies Used
- **Programming & Environment:** Python, Google Colab
- **AI & LLMs:** Qwen2.5-Instruct (4-bit), Hybrid Search
- **Vector Database & Search:** Qdrant (Semantic & BM25)
- **User Interface:** Gradio
