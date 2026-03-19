# 📄 Resume / Candidate Screening System — FUTURE_ML_03

## 🔍 Objective

The objective of this project is to build a Machine Learning-based system that can automatically:

- Screen resumes  
- Extract relevant skills  
- Match candidates with job requirements  
- Rank candidates based on suitability  
- Identify missing skills  

This system helps recruiters make faster and more accurate hiring decisions.

---

## 📦 Dataset

Dataset Used:  
Resume Dataset (Kaggle)

🔗 Dataset Link:  
https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset  

The dataset contains:

- Resume text (`Resume_str`)  
- Job category (`Category`)  

Due to file size limitations, the dataset is not included in this repository.

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TF-IDF Vectorization  
- Cosine Similarity  
- Google Colab  

---

## 🚀 Project Workflow

### 1️⃣ Data Loading & Preprocessing
- Loaded resume dataset  
- Selected relevant columns (`Resume_str`, `Category`)  
- Cleaned text (lowercasing, removing special characters)  

---

### 2️⃣ Skill Extraction
- Defined a list of important technical skills  
- Extracted skills from resumes using keyword matching  

---

### 3️⃣ Job Description Processing
- Parsed job description text  
- Extracted required skills for the role  

---

### 4️⃣ Similarity Calculation
- Used TF-IDF vectorization  
- Calculated cosine similarity between resumes and job description  

---

### 5️⃣ Scoring System
Final score is calculated using:

Final Score = (0.7 × Similarity Score) + (0.3 × Skill Match Score)

This ensures both:
- Text relevance  
- Skill matching  

---

### 6️⃣ Candidate Ranking
- Candidates are ranked based on final score  
- Top candidates are shortlisted  

---

### 7️⃣ Skill Gap Analysis
- Identified missing skills in each resume  
- Helps recruiters understand candidate weaknesses  

---

## 📊 Sample Output

- Ranked candidates based on job fit  
- Skill gaps for each candidate  
- Resume evaluation using custom input  

---

## ⚡ Key Features

✔ Resume text cleaning & preprocessing  
✔ Skill extraction using NLP techniques  
✔ Job description parsing  
✔ Resume-to-job similarity scoring  
✔ Candidate ranking system  
✔ Skill gap identification  
✔ Real-time resume screening function  

---

## 🧠 Business Impact

This system helps organizations:

- Reduce manual resume screening effort  
- Identify best-fit candidates quickly  
- Improve hiring efficiency  
- Make data-driven recruitment decisions  
- Highlight missing skills for candidate evaluation  

This type of system is widely used in:

- HR-tech startups  
- Recruitment platforms  
- Enterprise hiring systems  

---

## 📁 Repository Structure

FUTURE_ML_03  
│  
├── FUTURE_ML_03_Resume_Screening.ipynb  
└── README.md  

---

## ▶ How to Run

1. Download dataset from Kaggle  
2. Upload dataset into Google Colab  
3. Run all cells sequentially  
4. Modify job description to test different roles  
5. Use `screen_resume()` to test custom resumes  

---

## ✅ Conclusion

This project demonstrates a complete NLP-based resume screening system that automates candidate evaluation.

By combining skill extraction, text similarity, and scoring logic, the system provides a practical solution for modern recruitment challenges.

Future improvements may include:
- Advanced NLP models (BERT, spaCy pipelines)  
- Automated skill extraction using entity recognition  
- Integration with real hiring platforms  
