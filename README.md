# 📊 Expectation Decider Model - Student Performance Analysis

## 📌 Overview
This project analyzes student data to build an **Expectation Decider Model** that predicts whether a student will pass a competitive mathematics exam.  

The analysis is based on **probability theory, statistical techniques, and data visualization** to identify key factors influencing student success.

---

## 🎯 Objectives
- Understand and apply probability concepts
- Analyze student performance data
- Identify factors affecting exam success
- Build a probability-based prediction approach

---

## 📂 Dataset Description
The dataset contains **200 student records** with the following features:

| Feature | Description |
|--------|------------|
| study_hours | Weekly study hours |
| attendance | Lecture attendance (%) |
| group_discussion | Participation (Yes/No) |
| previous_test_score | Internal test marks (out of 100) |
| final_exam_pass | Pass/Fail result |

---

## 📊 Key Concepts Used
- Probability Basics
- Empirical & Theoretical Probability
- Random Variables
- Binomial Distribution
- Conditional Probability
- Independence of Events
- Bayes Theorem

---

## 📈 Analysis Performed

### 🔹 1. Probability Analysis
- Calculated probability of passing using dataset
- Compared empirical vs theoretical probability

---

### 🔹 2. Random Variable Modeling
- Defined random variable: number of students passing out of 3
- Constructed probability distribution
- Calculated:
  - Mean = 1.65
  - Variance = 0.7425

---

### 🔹 3. Relationship Analysis
- Found:
  - P(Pass) = 0.55
  - P(Pass | Group Discussion) = 0.66
- Conclusion:
  - Group discussion improves chances of passing
  - Events are **dependent but not mutually exclusive**

---

### 🔹 4. Bayes Theorem Application
- Calculated:
  - P(Pass | High Attendance) ≈ **64.2%**
- Insight:
  - High attendance significantly increases success probability

---

## 📊 Visualizations
- Venn Diagram (Study Hours vs Attendance)
- Contingency Table (Group Discussion vs Pass/Fail)
- Charts:
  - Pass vs Fail
  - Study Hours vs Performance
  - Attendance vs Performance

---

## 🔍 Key Insights
- Students with **higher study hours (>10)** perform better
- **Attendance >80%** strongly increases passing probability
- **Group discussion participation** improves success rate
- Previous test scores are strong performance indicators

---

## 🛠 Tools Used
- Microsoft Excel (Data Analysis & Visualization)
- Basic Statistics & Probability Concepts

---

## 🚀 How to Use
1. Open the dataset in Excel
2. Apply filters and formulas
3. Use pivot tables for contingency analysis
4. Create charts for visualization
5. Interpret results using probability concepts

---

## 📌 Conclusion
This project demonstrates how probability and statistics can be applied to real-world educational data to predict outcomes and derive meaningful insights.  

The **Expectation Decider Model** highlights the importance of:
- Consistent study habits  
- High attendance  
- Active participation  

---

## ⭐ Future Improvements
- Apply Machine Learning models (Logistic Regression)
- Automate predictions using Python
- Build an interactive dashboard (Power BI / Tableau)

---

## 👨‍💻 Author
**Yakshraj Gohil**

---
