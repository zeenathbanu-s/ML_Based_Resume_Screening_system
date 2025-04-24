# Resume Screening using Machine Learning

## 📌 What is this project?

This project helps companies automatically read and understand resumes using **Machine Learning (ML)** and **Natural Language Processing (NLP)**. It saves time by quickly sorting resumes into job categories like Data Science, HR, DevOps, etc.

## 💡 Why did I build it?

Big companies get thousands of resumes for each job. Reading all of them manually takes a lot of time and effort. This system helps them:
- Quickly find the right candidates
- Avoid hiring mistakes
- Save money and reduce work

## 🔧 How does it work?

### 🗂️ Dataset
I used a dataset with many resumes. Each resume was already labeled with a job category.

### 🛠️ Tools and Libraries
- Python
- Pandas and NumPy (for data handling)
- Seaborn and Matplotlib (for graphs)
- Scikit-learn (for machine learning)
- TF-IDF (to convert text into numbers)
- KNN and Logistic Regression (ML models)
- Google Colab (to run the code)

### 🔍 Steps I followed
1. **Clean the text** in resumes (removed unwanted symbols)
2. **Convert job categories** into numbers
3. **Change text to numbers** using TF-IDF
4. **Train models** to learn and predict categories
5. **Check accuracy** of the models
6. **Show results** using pie charts and bar graphs
  
🧠 Algorithms Used:
K-Nearest Neighbors (KNN)

A classification algorithm that finds the most similar resumes (neighbors) and uses them to guess the category of a new resume.

🛠️ Techniques Used:
TF-IDF Vectorization

Converts resume text into numbers based on word importance.

Helps the model understand which words are common vs. unique.

Label Encoding

Converts job category names (like ‘Data Science’, ‘HR’) into numbers so the model can process them.

One-vs-Rest (OvR) Strategy

Used with KNN to handle multiple resume categories (multi-class classification).

It creates one classifier per category.



## 📊 What did I visualize?
- A **bar chart** to show how many resumes are in each category
- A **pie chart** to show the percentage of each job role

## ✅ Final Result

The system can now read resume text and predict which job category it belongs to. It is a useful tool for any company that wants to speed up their hiring process.
