📊 Employee Burnout Analysis Project (AI)
📋 Project Overview

Employee burnout is a growing concern in modern organizations, directly impacting productivity, job satisfaction, and overall employee well-being.
This project focuses on analyzing employee burnout patterns using multiple factors such as mental fatigue, resource allocation, work-from-home setup, designation level, company type, and demographic information.

The objective is to identify key contributors to burnout and provide actionable insights that organizations can use to improve employee health, engagement, and performance.

👤 Author Information

Name: Ashish Kumar

Father’s Name: Shambhu Pandit

University: Jagannath University, Jaipur

Domain: Artificial Intelligence (AI)

Internship: Edunate Foundation (Skills Build)

Project Title: Employee Burnout Analysis Project

📞 Contact: +91 9431649783
📧 Email: ashishkumarmjl011@gmail.com

📊 Dataset Information

The dataset contains employee burnout records with the following features:

Feature	Description
Employee ID	Unique identifier for each employee
Date of Joining	Employee joining date
Gender	Male / Female
Company Type	Product / Service
WFH Setup Available	Yes / No
Designation	Job level (0–5)
Resource Allocation	Resources assigned (1–10)
Mental Fatigue Score	Mental fatigue level (0–10)
Burn Rate	Burnout rate (0–1)

Dataset Size: 22,750 rows × 9 columns

🔧 Data Preprocessing
1️⃣ Data Cleaning

Removed null values

Dropped Employee ID (not required for analysis)

Identified and removed 6 duplicate records

✅ Final Clean Dataset: 18,590 rows × 8 columns

2️⃣ Missing Value Analysis

Initial missing values found in:

Resource Allocation: 1,381

Mental Fatigue Score: 2,117

Burn Rate: 1,124

Appropriate handling techniques were applied before analysis.

3️⃣ Data Transformation

Converted Date of Joining to datetime format

Encoded categorical variables:

Gender

Company Type

WFH Setup Available

📈 Key Analysis Performed
📌 Descriptive Statistics

Average Burn Rate: 0.45 (45%)

Average Mental Fatigue Score: 5.73

Average Resource Allocation: 4.48

Designation Levels: 0 to 5

📌 Correlation Analysis

Strong positive correlation between:

Designation & Resource Allocation: 0.878

Mental fatigue shows moderate correlation with burnout rate

📌 Demographic Insights

Gender Distribution:

Female: 9,747

Male: 8,843

Company Type:

Service: 12,174

Product: 6,416

Higher burnout observed at higher designation levels

📊 Visualizations

The following visualizations were created:

Heatmap of missing values

Correlation matrix heatmap

Bar charts: Company Type vs Designation

Histogram: Gender distribution

Pie chart: Gender-wise designation distribution

🎯 Key Findings
🔹 Burnout Patterns

Burnout increases with:

Higher Mental Fatigue Score

Higher Resource Allocation

Higher Designation Level

🔹 Company Type Insights

Product and Service companies show similar burnout trends

Service sector has slightly higher burnout prevalence

🔹 Gender Analysis

Female employees are slightly more represented

Burnout patterns are similar across genders

🔹 Work From Home (WFH)

Impact of WFH setup availability on burnout was analyzed

Results can help design better remote work policies

🛠️ Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical computation

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Development environment

📁 Project Structure
employee_burnout_analysis/
│
├── employee_burnout_analysis-AI 2.xlsx   # Original dataset
├── Employee_Burnout_Analysis.ipynb       # Jupyter notebook
├── README.md                             # Project documentation
└── visualizations/                      # Generated plots

🚀 How to Run the Project
🔹 Prerequisites
pip install pandas numpy matplotlib seaborn openpyxl

🔹 Execution Steps

Clone the repository

Install required libraries

Ensure the Excel dataset is in the correct directory

Open and run the Jupyter Notebook sequentially

💡 Business Implications

Resource Management: Higher resource allocation increases burnout risk

Mental Health Support: High fatigue scores indicate need for wellness programs

Career Planning: Senior designations face higher burnout

WFH Policy Design: Data-driven remote work decisions

📈 Future Scope

🔮 Predictive modeling using Machine Learning

📊 Real-time burnout monitoring dashboards

🧠 Personalized employee intervention strategies

🏢 Industry-wise and company-size comparative analysis

📚 References

Dataset: Employee Burnout Analysis Dataset

Tools: Python, Jupyter Notebook

Libraries: Pandas, NumPy, Matplotlib, Seaborn

📞 Contact

For queries or collaboration opportunities:

Ashish Kumar
📧 Email: ashishkumarmjl011@gmail.com

📱 Phone: +91 9431649783

If you want, I can also:

Add badges (Python, AI, Internship)

Optimize it for GitHub stars & recruiters

Convert it into a project report PDF

Just tell me 👍
