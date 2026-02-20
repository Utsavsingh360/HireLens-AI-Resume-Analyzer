# 📄 HireLens – Resume Job Match Scorer

An AI-powered Resume–Job Description Matching Web App built using **Streamlit, NLP, and Machine Learning**.

This tool analyzes how well a resume matches a job description using **TF-IDF Vectorization + Cosine Similarity**, and provides a match score with visual insights.

---

## 🚀 Live Features

- 📤 Upload Resume (PDF format)
- 📋 Paste Job Description
- 📊 TF-IDF based text vectorization
- 📈 Cosine Similarity score calculation
- 📉 Visual Match Score Gauge Chart
- ⚠️ Smart feedback (Low / Good / Excellent Match)
- 🧹 Text preprocessing (Stopwords removal + Cleaning)

---

## 🧠 How It Works

1. Extracts text from uploaded PDF using **PyPDF2**
2. Cleans text (lowercase, remove special characters, normalize spaces)
3. Removes stopwords using **NLTK**
4. Converts text into TF-IDF vectors
5. Computes Cosine Similarity between resume & job description
6. Displays:
   - Match Percentage
   - Visual horizontal gauge chart
   - Tailored feedback message

---

## 🛠 Tech Stack

- **Frontend & App Framework:** Streamlit  
- **NLP:** NLTK  
- **ML Technique:** TF-IDF Vectorizer  
- **Similarity Metric:** Cosine Similarity  
- **PDF Processing:** PyPDF2  
- **Visualization:** Matplotlib  
- **Language:** Python  

---

## 📦 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Utsavsingh360/HireLens-AI-Resume-Analyzer.git
cd HireLens-AI-Resume-Analyzer
