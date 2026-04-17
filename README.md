# 🎓 Student Analysis Dashboard (Power BI)

## 📌 Overview

The **Student Analysis Dashboard** provides a comprehensive view of student performance, attendance, and academic insights. It helps educators and decision-makers track key metrics and identify trends effectively.

---

## 🚀 Key Features

* 📊 **Total Students KPI**
* 📈 **Average Subject Score Analysis**
* 📉 **Performance Category (High / Medium / Low)**
* 📅 **Attendance Tracking**
* 📚 **Subject-wise Performance**
* 🧑‍🎓 **Student-level Detailed Table**
* 📊 **Term-wise Score Trends**
* 🏫 **Class-wise Performance Comparison**

---

## 📷 Dashboard Preview

<img width="1441" height="816" alt="Screenshot 2026-04-17 162509" src="https://github.com/user-attachments/assets/075bbbb3-6c03-47e5-a42b-6166b4e1bad6" />

<img width="1444" height="800" alt="Screenshot 2026-04-17 162541" src="https://github.com/user-attachments/assets/e1c5fd86-5ed7-4239-b2a6-a75406894280" />

---
## 🗂️ Data Model

* **Student Table** → StudentID, Name, Class
* **Score Table** → StudentID, Subject, Score
* **Attendance Table** → StudentID, Status
* **Behaviour Table** → StudentID, Type
### 🔗 Relationships

* Student ↔ Score (1:M)
* Student ↔ Attendance (1:M)
* Student ↔ Behaviour (1:M)
---

## 📊 Visualizations Used

* Bar Chart → Subject-wise Average Score
* Line Chart → Term-wise Trends
* Table → Student Details
* KPI Cards → Key Metrics

---

## 🎯 Insights

* Majority of students fall under **Medium Performance**
* Attendance rate directly impacts performance
* Subject-wise variation helps identify weak areas

---

## 🛠 Tools & Technologies

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Data Modeling**

---

## 📌 How to Use

1. Open `.pbix` file in Power BI Desktop
2. Refresh data
3. Use slicers (Class, Performance Category)
4. Explore insights interactively

---

## 📎 Author

**Man Trivedi**
📍 Data Analyst | Power BI Developer

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
