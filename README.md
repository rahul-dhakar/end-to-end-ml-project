# End-to-End Machine Learning Project

## 📌 Project Overview

This project is an end-to-end Machine Learning application that predicts a student's **Math Score** based on various demographic and educational factors.

The project covers the complete ML lifecycle, including:

- Data Ingestion
- Data Validation
- Data Transformation
- Model Training
- Model Evaluation
- Prediction Pipeline
- Flask Web Application
- Deployment on Render

---

## 📖 Problem Statement

This project aims to understand how a student's academic performance is influenced by several factors, including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

Using these features, the model predicts the student's **Math Score**.

---

## 📂 Dataset

**Source:**

https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

### Dataset Information

- Total Records: **1000**
- Total Features: **8**

### Features

| Feature | Description |
|----------|-------------|
| Gender | Student's Gender |
| Race/Ethnicity | Student's Ethnic Group |
| Parental Level of Education | Highest education completed by parents |
| Lunch | Standard or Free/Reduced Lunch |
| Test Preparation Course | Completed or Not Completed |
| Reading Score | Reading Marks |
| Writing Score | Writing Marks |
| Math Score | Target Variable |

---

## 🚀 Project Workflow

```
Data Collection
        │
        ▼
Data Ingestion
        │
        ▼
Data Transformation
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Prediction Pipeline
        │
        ▼
Flask Web Application
        │
        ▼
Deployment on Render
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Flask
- Matplotlib
- Seaborn
- Dill
- Git & GitHub
- Render

---

## 📁 Project Structure

```
ML Project/
│
├── artifacts/
├── notebook/
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
├── application.py
├── requirements.txt
├── runtime.txt
├── setup.py
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/end-to-end-ml-project.git
```

Move into the project directory

```bash
cd end-to-end-ml-project
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python application.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

The application is deployed on **Render** using **Gunicorn** as the production WSGI server.

---

## 📷 Application

The web application allows users to enter student information and predicts the student's **Math Score** using the trained machine learning model.

---

## 👨‍💻 Author

**Rahul Dhakar**

GitHub: https://github.com/rahul-dhakar

## 🌍 Live Demo

https://end-to-end-ml-project-uz6x.onrender.com