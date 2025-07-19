# Resume_Cheker
# 🚀 Resume Analyzer Based on Job Description

This is an AI-powered Resume Analyzer that evaluates a candidate's resume against a job description (JD) to determine how well it matches. It uses OCR, NLP, and role-specific skill mapping to generate an **ATS (Applicant Tracking System)** match score and career suggestions.

---

## 🧠 Features

- 📄 **Resume Parsing** – Extracts text from uploaded PDF resumes using OCR.
- 🔍 **Keyword Extraction** – Extracts relevant keywords from the job description.
- 🧰 **Skill Matching** – Matches resume content with predefined skills for various job roles.
- 📊 **ATS Score Visualization** – Displays a pie chart showing match percentage.
- 💡 **Career Suggestions** – Recommends suitable roles based on detected skills.
- 🌐 **Gradio Web UI** – Easy-to-use web interface for input and results.

---

## 🛠️ Technologies Used

- Python
- Gradio
- PyMuPDF (`fitz`)
- Tesseract OCR
- pdf2image
- NLTK
- Matplotlib
- PIL

---

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
