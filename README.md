<h1 align="center">🔍 GenAI Job Recommendation System Using LLM</h1>

<p align="center">
  <em>An AI-powered system that recommends jobs based on user skills, profile, and experience using LLMs + Embeddings.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-GenAI-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Backend-FastAPI-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/LLM-OpenAI%2FGemini-orange?style=for-the-badge">
</p>

---

## 📌 Overview

This project builds a **personalized AI job recommendation system** using:

- **LLMs** to extract skills, roles, and experience from resumes/user text  
- **Embeddings** to convert job descriptions + profiles into meaningful vectors  
- **Vector Search** to match relevant job postings  
- **LLM Re-ranking** for final recommendation reasoning  

The system is suitable for:

- Job portals  
- Career recommendation apps  
- HR automation  
- College placement cells  
- Resume-based job filtering  

---

## 🌟 Features

- 🔎 **Automatic skill extraction**
- 🧠 **Embedding-based matching**
- 🎯 **LLM-powered re-ranking**
- 📈 **Similarity scoring**
- 🛠 **Modular architecture**
- 🧩 **API-ready design**
- 🔮 **Future-proof with scraping & resume parsing**

---

## 🏗️ System Architecture

        ┌────────────────────────┐
        │      User Input        │
        │ (Resume, Skills, Text) │
        └────────────┬───────────┘
                     ▼
            ┌──────────────────┐
            │   LLM Extractor  │
            │ (skills, roles)  │
            └──────────┬───────┘
                       ▼
            ┌──────────────────┐
            │ Embedding Engine │
            │ (OpenAI, Gemini) │
            └──────────┬───────┘
                       ▼
        ┌────────────────────────────┐
        │     Vector DB (FAISS)      │
        │ job vectors vs user vector │
        └────────────┬──────────────┘
                     ▼
          ┌─────────────────────┐
          │    LLM Re-Ranker    │
          │ final recommendations│
          └────────────┬────────┘
                       ▼
        ┌────────────────────────┐
        │  Recommended Job List  │
        └────────────────────────┘
 
  
  📁 Folder Structure

genai-job-recommendation-system/
│
├── api/
├── data/
├── embeddings/
├── models/
├── services/
├── utils/
├── notebooks/
├── config/
└── README.md





