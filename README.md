# Automated OMR Evaluation & Scoring System

## 📌 Problem Statement

At **Innomatics Research Labs**, placement readiness assessments are conducted regularly across roles like Data Analytics and AI/ML for Data Science with Generative AI.  
Each exam uses standardized OMR sheets with **100 questions**, distributed as:

\[
100 \; \text{Questions} \quad \rightarrow \quad 20 \; \text{per subject} \times 5 \; \text{Subjects}
\]

Currently, the evaluation is manual, which is **time-consuming** and **error-prone**.  
This project automates the process using **Python + OpenCV + Flask**.

---

## 🎯 Objectives

- Automate OMR sheet scanning and bubble recognition.
- Compare with predefined answer keys.
- Display score and subject-wise performance.
- Provide a web interface for uploading OMR sheets.

---

## ⚙️ Tech Stack

- **Python** (Core logic & backend)
- **OpenCV** (Image processing)
- **NumPy** (Numerical computation)
- **Flask** (Web application)
- **Bootstrap 5** (Frontend styling)

---

## 📂 Project Structure

```plaintext
OMR-System/
│── app.py                # Flask application
│── omr_processing.py     # Core OMR evaluation logic
│── static/               # CSS, JS, images
│── templates/            # HTML (Bootstrap frontend)
│── omr_samples/          # Sample OMR sheets
│── answer_key.json       # Predefined correct answers
│── README.md             # Project documentation
