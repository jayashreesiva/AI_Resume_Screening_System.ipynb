# AI-Based Resume Screening System

## 📌 Project Overview

The **AI-Based Resume Screening System** is an Artificial Intelligence and Natural Language Processing (NLP) project that automatically compares candidate resumes with a given job description.

The system uses **TF-IDF** to convert resume and job-description text into numerical features and **Cosine Similarity** to calculate how closely each resume matches the job requirements.

Candidates are then ranked based on their matching scores, and suitable candidates can be shortlisted using a predefined score threshold.

The project is developed using **Python** and can be executed in **Google Colab**.

---

## 🎯 Objective

The main objective of this project is to automate the initial stage of resume screening.

Instead of manually comparing every resume with a job description, the system calculates a similarity score and ranks candidates according to their textual relevance.

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Natural Language Processing (NLP)**
* **TF-IDF**
* **Cosine Similarity**

---

## 📊 Dataset

The project uses a small sample dataset containing **5 candidate resumes** created for educational and demonstration purposes.

The resumes represent candidates with different technical skills, such as:

* Python
* Machine Learning
* SQL
* Data Analysis
* Java
* React
* AWS
* Docker
* Kubernetes

---

## 🤖 Techniques Used

### 1. TF-IDF

TF-IDF stands for **Term Frequency-Inverse Document Frequency**.

It converts resume and job-description text into numerical vectors based on the importance of words.

The project uses:

```python
TfidfVectorizer(
    stop_words="english",
    ngram_range=(1, 2)
)
```

Both individual words and two-word combinations are considered.

---

### 2. Cosine Similarity

Cosine Similarity measures the similarity between the resume vector and job-description vector.

A higher similarity score indicates that the resume contains more textually relevant terms compared with the job description.

---

## 🔄 Project Workflow

```text
Candidate Resumes
       ↓
Job Description
       ↓
Text Processing
       ↓
TF-IDF Vectorization
       ↓
Cosine Similarity
       ↓
Calculate Match Score
       ↓
Rank Candidates
       ↓
Shortlist Candidates
```

---

## ✨ Features

### 1. Resume Dataset

Creates a sample dataset containing candidate resumes.

### 2. Job Description Input

Allows a job description to be provided for screening.

### 3. TF-IDF Processing

Converts resume and job-descr
