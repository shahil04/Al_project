# 🚀 AI Resume Analyzer & Job Matcher

An intelligent Resume Analysis and Job Matching application built using **NLP**, **Streamlit**, and **Google Gemini AI**. This application helps job seekers analyze their resumes, identify strengths and weaknesses, receive AI-powered suggestions, and match their profiles with relevant job descriptions.

---

## 📌 Features

### 📄 Resume Analysis
- Upload Resume (PDF format)
- Extract resume text using NLP techniques
- Analyze resume content
- Identify missing skills and keywords
- ATS (Applicant Tracking System) optimization suggestions
- Resume improvement recommendations

### 🤖 AI-Powered Suggestions
- Powered by **Google Gemini**
- Professional resume feedback
- Career guidance and improvement tips
- Skill enhancement recommendations
- Project suggestions based on profile

### 🎯 Job Matching
- Compare resume against Job Description (JD)
- Calculate Resume Match Score
- Identify missing skills from JD
- Recommend improvements for better job alignment
- Generate actionable insights

### 📊 NLP Processing
- Text preprocessing
- Tokenization
- Keyword extraction
- Skill extraction
- Similarity scoring
- Resume-JD comparison

### 🌐 Interactive Dashboard
- Built using Streamlit
- User-friendly interface
- Real-time analysis
- Visual score representation
- Downloadable insights

---

# 🖼️ Application Screenshots

## Home Page

![Home Page](img/img1.png)

---

## Resume Analysis Dashboard

![Resume Analysis](img/img2.png)

---

## Job Matching & Suggestions

![Job Matching](img/img3.png)

---

# 🏗️ Project Architecture

```text
Resume Upload
      │
      ▼
PDF Text Extraction
      │
      ▼
NLP Processing
      │
      ├── Skill Extraction
      ├── Keyword Analysis
      ├── Resume Scoring
      └── Job Matching
      │
      ▼
Google Gemini AI
      │
      ▼
AI Suggestions & Recommendations
      │
      ▼
Streamlit Dashboard
