# 🤖 Smart ATS Resume Copilot

An AI-powered ATS (Applicant Tracking System) and Resume Copilot built with **FastAPI**, **Scikit-Learn**, **NLTK**, and **Groq (Llama 3.3)**. It calculates match scores, extracts contact info, identifies missing keywords, and uses lightning-fast LLMs to generate realistic resume edits.

---

## 🚀 Features
* **ATS Match Score**: Computes cosine similarity between the candidate's resume and the job description using TF-IDF.
* **Entity Extraction**: Automatically parses candidate email and phone numbers.
* **Skill Gap Analysis**: Compares required keywords against resume text to flag missing skills.
* **AI Resume Enhancer**: Uses Groq's high-speed `llama-3.3-70b-versatile` model to suggest realistic bullet point rewrites naturally incorporating missing skills.

---

## 🛠️ Project Setup & GitHub Instructions

### 1. Local Project Structure
Ensure your project files are organized like this in your local directory:
```text
your-repo-name/
│
├── app.py
├── requirements.txt
└── README.md
