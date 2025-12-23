📊 Employee Burnout Analysis Project
📋 Project Overview

This project focuses on analyzing employee burnout patterns using organizational, work environment, and mental health–related factors.
The analysis helps identify how designation level, resource allocation, and mental fatigue influence employee burnout.

The project is developed as part of an Artificial Intelligence internship and uses Python-based data analysis techniques.

👤 Author Information

Name: Ashish Kumar

Father’s Name: Shambhu Pandit

University: Jagannath University, Jaipur

Internship: Edunate Foundation (Skills Build)

Internship Domain: Artificial Intelligence (AI)

Project Title: Employee Burnout Analysis Project

📧 Email: ashishkumarmjl011@gmail.com

📱 Mobile: +91 9431649783

📊 Dataset Information

The dataset contains employee-level burnout information with the following attributes:

Column	Description
Employee ID	Unique employee identifier
Date of Joining	Employee joining date
Gender	Male / Female
Company Type	Product / Service
WFH Setup Available	Yes / No
Designation	Job level (0–5)
Resource Allocation	Assigned resources (1–10)
Mental Fatigue Score	Fatigue level (0–10)
Burn Rate	Burnout level (0–1)

Initial Dataset Size: 22,750 rows × 9 columns

🔧 Data Preprocessing
🔹 Missing Value Analysis

Total missing values found: 4,622

Column	Missing Values
Resource Allocation	1,381
Mental Fatigue Score	2,117
Burn Rate	1,124
🔹 Data Cleaning Steps

Removed rows containing missing values

Dropped Employee ID column (not useful for analysis)

Removed 6 duplicate records

✅ Final Dataset Size: 18,590 rows × 8 columns

📈 Exploratory Data Analysis
🔹 Descriptive Statistics

Average Burn Rate: 0.45

Average Mental Fatigue Score: 5.73

Average Resource Allocation: 4.48

Designation Levels: 0 to 5

🔹 Correlation Analysis

Strong positive correlation between:

Designation & Resource Allocation: 0.878

Mental fatigue shows moderate positive correlation with burnout

🔹 Gender & Company Distribution

Gender:

Female: 9,747

Male: 8,843

Company Type:

Service: 12,174

Product: 6,416

📊 Visualizations

The following visualizations were created in the notebook:

Missing values heatmap

Correlation matrix heatmap

Bar chart: Company Type vs Designation

Histogram: Gender distribution

Bar and pie charts: Gender vs Designation

🎯 Key Findings

Burnout increases with:

Higher Designation Level

Higher Mental Fatigue Score

Higher Resource Allocation

Senior employees experience higher burnout levels

Product and Service companies show similar burnout trends

Burnout patterns are similar across genders

🛠️ Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📁 Project Structure
Employee_Burnout_Analysis/
│
├── employee_burnout_analysis-AI 2.xlsx
├── Employee_Burnout_Analysis.ipynb
└── README.md

🚀 How to Run the Project
Prerequisites
pip install pandas numpy matplotlib seaborn openpyxl

Steps

Open the Jupyter Notebook

Load the dataset

Run all cells sequentially

📈 Future Scope

Build machine learning models to predict burnout

Create dashboards for real-time monitoring

Extend analysis to different industries

📞 Contact

For queries or collaboration:

Ashish Kumar
📧 ashishkumarmjl011@gmail.com

📱 +91 9431649783

✅ FINAL CONFIRMATION

✔ Matches your code & outputs
✔ No false claims
✔ Internship + University ready
✔ Viva-safe
