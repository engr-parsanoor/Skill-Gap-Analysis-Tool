# Skill Gap Analysis Tool

## 📌 Overview
This project analyzes the gap between intern skill sets and industry job requirements using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.

## 🎯 Features
- Extracts high-demand skills from job descriptions using **TF-IDF Vectorization**
- Groups industry skills using **K-Means clustering**
- Compares intern skills to industry needs
- Lists missing skills and suggests targeted training
- Generates a WordCloud of industry skills for visualization

## 🛠️ Tech Stack
- **Python**  
- **Pandas** – Data handling  
- **Scikit-learn** – TF-IDF & K-Means  
- **Matplotlib** – Visualization  
- **WordCloud** – Skill cloud generation  

## 📂 Dataset
Two CSV files are used:
1. **intern_skills.csv** – List of interns and their current skills
2. **job_descriptions.csv** – Industry job descriptions

Sample format:
```csv
Intern,Skills
Alice,"Python, Data Analysis, Excel"
Bob,"Java, Spring Boot, SQL"
