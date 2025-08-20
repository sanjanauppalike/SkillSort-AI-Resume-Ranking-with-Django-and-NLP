# SkillSort-AI-Resume-Ranking-with-Django-and-NLP
AI-powered resume ranking system built with Django, NLP, and ML to analyze, match, and prioritize resumes against job descriptions.

## **📌 Overview**  
SkillSort is a Django-based web application that leverages Natural Language Processing (NLP) and Machine Learning (ML) to analyze and rank resumes against job descriptions. It helps recruiters efficiently filter, compare, and prioritize candidates based on skills, experience, and qualifications.

## **🚀 Features**  
✅ **AI-Powered Resume Screening** – Automatically ranks resumes based on relevance to the job description.  
✅ **Skill Matching** – Extracts and compares candidate skills with job requirements.  
✅ **Experience & Qualification Analysis** – Evaluates work experience and education.  
✅ **Customizable Ranking Criteria** – Adjust weights for different parameters.  
✅ **PDF & DOCX Parsing** – Supports multiple resume formats.  
✅ **Admin Dashboard** – Manage resumes, job descriptions, and ranking criteria.  
✅ **REST API Support** – Integrate with external HR systems.  

## **🛠️ Tech Stack**  
- **Backend:** Django, Django REST Framework  
- **Frontend:** HTML, CSS, JavaScript
- **AI/NLP:** SpaCy, NLTK, Scikit-learn  
- **Database:** PostgreSQL 
- **File Handling:** PyPDF2, python-docx  

## **🔧 Installation & Setup**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/SkillSort-AI-Resume-Ranking-with-Django-and-NLP.git
cd Resume_Ranking_AI_by_Django
```
### **2️⃣ Create & Activate Virtual Environment**  
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```
### **4️⃣ Run Database Migrations**  
```bash
python manage.py migrate
```
### **5️⃣ Start the Development Server**  
```bash
python manage.py runserver
```
Access the app at **http://127.0.0.1:8000/**  
