# 🎓 Online Course Recommendation System

An end-to-end interactive **Hybrid Course Recommendation System** built using **Machine Learning + Streamlit** that recommends relevant online courses based on content similarity, ratings, and popularity.

This project demonstrates a complete recommender system workflow including data preprocessing, feature engineering, similarity modeling, hybrid scoring, evaluation, and deployment.

---

## 🔗 Live Deployment

🚀 **Live Application (Streamlit Cloud):**  
👉 https://online-course-recommendation-system.streamlit.app/

The application is publicly accessible and allows users to select a course and receive personalized course recommendations instantly without any local setup.

---

## 🔍 Project Overview

This project implements a structured real-world recommendation pipeline:

📤 Dataset loading & preprocessing  
🧹 Feature engineering  
📊 Course similarity modeling  
⭐ Popularity scoring  
🧠 Hybrid recommendation logic  
🎯 Top course recommendations  

The application is interactive and suitable for:

- Academic projects  
- Interviews & viva  
- Data science portfolios  
- Recommender system demonstrations  
- EdTech product prototypes  

---

## 🔁 Recommendation Pipeline

Load course dataset  
Preprocess and clean features  
Transform categorical information  
Compute feature vectors  
Calculate cosine similarity  
Combine similarity with popularity score  
Generate top recommended courses  

⚠️ Hybrid scoring ensures more realistic recommendations compared to pure similarity models.

---

## 📂 Dataset Requirements

The dataset typically contains:

Column | Description
--- | ---
Course Title | Name of the course
Category | Course domain
Rating | Average rating
Enrollment | Number of students
Duration / Level | Course metadata

Automatic preprocessing:

- Missing value handling  
- Feature normalization  
- Encoding categorical features  
- Popularity score normalization  

---

## 🧠 Recommendation Logic

The system uses a **Hybrid Recommendation Approach**:

### 📌 Content-Based Filtering
- Converts course metadata into feature vectors
- Computes cosine similarity between courses

### 📌 Popularity-Based Ranking
- Uses enrollment and ratings
- Normalizes popularity metrics

### 📌 Hybrid Score
Hybrid Score =
0.7 × Similarity Score - 
0.3 × Popularity Score


This balances relevance and real-world usefulness.

---

## 📈 Recommendation Output

Users can view results as:

- Top recommended courses list  
- Similarity-based ranking  
- Popular course suggestions  

The system provides fast real-time recommendations.

---

## 🛠️ Tech Stack

Programming: Python  
Web Application: Streamlit  
Data Handling: Pandas, NumPy  
Machine Learning: Scikit-learn  
Similarity Modeling: Cosine Similarity  
Model Persistence: Joblib  
Visualization: Streamlit charts  

---

## 🚀 Deployment

Platform: Streamlit Community Cloud  
Deployment Type: Public Web Application  
Entry Point: app.py  
Automatic Rebuilds: Enabled on GitHub updates  

### Deployment Workflow

Push project to GitHub repository  
Define dependencies in requirements.txt  
Connect repository to Streamlit Cloud  
Deploy using app.py  
Automatic redeployment on updates  

---

## 📁 Project Structure

online-course-recommendation-system/
│

├── app.py

├── hybrid_recommendation_model.joblib

├── dataset.xlsx

├── requirements.txt

└── README.md

---

## 🎯 Key Features

- Hybrid recommender system (Similarity + Popularity)
- Real-time course recommendations
- Interactive Streamlit interface
- Explainable recommendation logic
- Production-style ML deployment
- Lightweight and fast inference

---

## 📊 Skills Demonstrated

- Recommender Systems
- Feature Engineering
- Similarity Modeling
- Hybrid ML Design
- ML Deployment (Streamlit)
- Applied Data Science Workflow
- EdTech Analytics

---

## 🔮 Future Improvements

- User-based collaborative filtering  
- NLP embeddings for course descriptions  
- Personalized user profiles  
- Deep learning recommenders  
- Vector database integration  
- LLM-powered course search  

---
