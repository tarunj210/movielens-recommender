#  Hybrid Movie Recommendation System  
*A Scalable, Preference-Aware Recommender using Collaborative Filtering, Content-Based Filtering, and LLM-driven Personalization*

---

##  Overview

This project implements a **hybrid recommendation system** that combines:

- **Collaborative Filtering (NeuMF)**
- **Content-Based Filtering (metadata similarity)**
- **Preference-Aware Reranking (LLM / rule-based parsing)**

The system generates **personalized movie recommendations** and dynamically adapts to **user-specified preferences in natural language**.

---

##  Key Features

-  Hybrid recommender (CF + Content)
-  Precomputed top-K recommendations (optimized for latency)
-  Natural language preference parsing (LLM + fallback)
-  Preference-based filtering & reranking
-  Interactive frontend with posters & explanations
-  Scalable backend using FastAPI
-  Docker-ready architecture

---

## 🏗️ System Architecture

### Pipeline

User history
  |
Collaborative Filtering
  |
  |
Content Based 
  |
  | 
Hybrid Scoring
  |
  |
Preferene Parsing
  |
  |
Filtering /Reranking
  |
  |
Final Recommendations



---

## 📦 Tech Stack

### Backend
- Python
- FastAPI
- PostgreSQL

### ML / Data
- PyTorch (NeuMF model)
- Pandas / NumPy
- scikit-learn

### Frontend
- React
- Axios

### Deployment
- Docker
- Kubernetes (optional)

---

## 🧠 Model Components

### 🔹 1. Collaborative Filtering (NeuMF)

- Learns user-item interactions
- Uses embeddings for users and movies
- Captures implicit preferences


---

### 🔹 2. Content-Based Filtering

Uses movie metadata:

- genres
- keywords
- cast
- director






  


