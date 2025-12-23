# 🧑‍💼 Employee Burnout Analysis Project

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.5.3-blue?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.25.0-orange?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-red?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-blueviolet?logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

---

## 👋 Introduction
This project analyzes **employee burnout data** to identify patterns related to **mental fatigue, resource allocation, and work environment factors**.  
Completed during my **internship at Edunate Foundation (Skills Build)**.

## 👨‍💻 About Me
**Ashish Kumar** – a passionate learner in **Data Science, AI, and Web Development**.  
I focus on building **data-driven projects** that generate insights and visualization for decision-making.

## 📊 Project Objective
- Identify factors affecting **employee burnout**  
- Analyze correlations between **Designation, Resource Allocation, Gender, Company Type, and Burn Rate**  
- Visualize trends for actionable insights  

## 🛠️ Technologies Used
- **Python** – Data processing and analysis  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Excel** – Dataset handling  

## 📂 Dataset Overview
- **Rows:** 22,750  
- **Columns:** 9  
- **Key Features:**  
  - `Date of Joining` – Employee joining date  
  - `Gender` – Male / Female  
  - `Company Type` – Service / Product  
  - `WFH Setup Available` – Yes / No  
  - `Designation` – Employee level (0–5)  
  - `Resource Allocation` – 1–10 scale  
  - `Mental Fatigue Score` – 0–10 scale  
  - `Burn Rate` – 0–1 scale  

### Dataset Cleaning
- Removed missing values (`NaN`)  
- Dropped duplicates (6 duplicate rows)  
- Removed `Employee ID` for analysis  

## 🔍 Data Analysis & Insights
- `Designation` is highly correlated with `Resource Allocation` (0.87)  
- **Company Type Distribution:** Service: 12,174 | Product: 6,416  
- **Gender Distribution:** Female: 9,747 | Male: 8,843  

## 📈 Visualizations
### Sample Charts
![Heatmap](./Portfolio_Screenshot.png)  
- Heatmaps for missing values and correlations  
- Bar charts for `Company Type` & `Gender` vs `Designation`  
- Pie chart for gender distribution  
- Histograms for key variables  

*(Add more screenshots in `images/` folder and reference here for better visualization)*

## 🧩 How to Run Locally
1. Clone the repository:
```bash
git clone https://github.com/Ashish943164/Portfolio.git
Navigate to the project folder

Run employee_burnout_analysis.py or open in Jupyter Notebook

🔮 Future Improvements
Predictive modeling for burnout risk using Machine Learning

Interactive dashboards for HR decision-making

Incorporate more datasets for broader analysis

📬 Contact
Ashish Kumar
📧 Email: ashishkumarmjl011@gmail.com
💻 GitHub: Ashish943164
🌐 Portfolio: https://ashish943164.github.io/Portfolio/

⭐ If you find this project useful, please consider giving it a star!
