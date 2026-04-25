# 📄 Resume Screening & Candidate Ranking System

## 📌 Overview
This project focuses on building an intelligent system to screen and rank resumes based on their relevance to a given job description. Using Natural Language Processing (NLP) techniques, the system evaluates resumes, extracts key skills, and identifies gaps to assist recruiters in shortlisting candidates efficiently.

---

## 🎯 Objectives
- Analyze resume text data
- Match resumes with job description
- Rank candidates based on relevance
- Identify important skills and missing skills
- Automate candidate shortlisting process

---

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- Matplotlib

---

## 📂 Dataset Description
The dataset contains resume-related information such as:
- Resume text / candidate profile
- Skills and experience details
- Additional candidate attributes (if available)

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted text to lowercase
- Removed special characters
- Cleaned resume content

### 2. Feature Extraction
- Used TF-IDF vectorization to convert text into numerical form

### 3. Similarity Calculation
- Applied cosine similarity between resume and job description

### 4. Candidate Ranking
- Generated match score for each candidate
- Ranked candidates based on similarity score

### 5. Skill Analysis
- Extracted key skills from resumes
- Identified missing skills based on job requirements

---

## 📊 Key Features
- Resume matching with job description
- Candidate ranking system
- Skill extraction and gap analysis
- Visualization of match score distribution

---

## 📈 Output
- Ranked list of candidates with match scores
- Skills found in each resume
- Missing skills for improvement
- Graph showing score distribution
