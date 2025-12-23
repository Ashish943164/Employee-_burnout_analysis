📋 Project Overview
This project analyzes employee burnout patterns using various factors such as work environment, mental fatigue, resource allocation, and demographic information. The goal is to identify key contributors to burnout and provide insights for organizations to improve employee well-being.

👤 Author Information
Name: Ashish Kumar
Father's Name: Shambhu Pandit
Contact: +91 9431649783
Email: ashishkumarmjl011@gmail.com
University: Jagannath University, Jaipur
Internship: Edunate Foundation (Skills Build)
Domain: Artificial Intelligence (AI)
Project: Employee Burnout Analysis Project

📊 Dataset Information
The dataset contains employee burnout records with the following features:
Employee ID: Unique identifier for each employee
Date of Joining: Employee's joining date
Gender: Male/Female
Company Type: Product/Service
WFH Setup Available: Yes/No
Designation: Job level (0-5)
Resource Allocation: Resources assigned (1-10)
Mental Fatigue Score: Mental fatigue measurement (0-10)
Burn Rate: Burnout rate percentage (0-1)
Dataset Size: 22,750 records × 9 columns

🔧 Data Preprocessing Steps
1. Data Cleaning
Removed null values from the dataset
Dropped the 'Employee ID' column (irrelevant for analysis)
Identified and removed duplicate entries (6 duplicates found)
Final clean dataset: 18,590 rows × 8 columns

2. Missing Value Analysis
Initial missing values:
Resource Allocation: 1,381 missing
Mental Fatigue Score: 2,117 missing
Burn Rate: 1,124 missing

3. Data Transformation
Converted 'Date of Joining' to datetime format
Handled categorical variables (Gender, Company Type, WFH Setup Available)

📈 Key Analysis Performed
1. Descriptive Statistics
Average Burn Rate: 0.45 (45%)
Average Mental Fatigue Score: 5.73
Average Resource Allocation: 4.48
Designation levels range from 0 to 5

2. Correlation Analysis
Strong positive correlation between Designation and Resource Allocation (0.878)
Mental fatigue shows moderate correlation with burnout

3. Demographic Insights
Gender Distribution: Female (9,747), Male (8,843)
Company Type: Service (12,174), Product (6,416)
Higher burnout observed in higher designations

4. Visualizations Created
Heatmap of missing values
Correlation matrix heatmap
Bar charts for company type vs designation
Histogram for gender distribution
Pie chart for gender-wise designation distribution

🎯 Key Findings
1. Burnout Patterns
Higher designations have significantly higher burnout rates
Burn Rate increases with:
Higher Mental Fatigue Score
Higher Resource Allocation
Higher Designation level

2. Company Type Insights
Both Product and Service companies show similar burnout patterns
Service sector has slightly more employees experiencing burnout

3. Gender Analysis
Female employees are slightly more represented in the dataset
Burnout patterns are similar across genders

4. WFH Impact
Analysis available for WFH setup availability impact on burnout

🛠️ Technologies Used
Python (Primary programming language)
Pandas (Data manipulation and analysis)
NumPy (Numerical computations)
Matplotlib & Seaborn (Data visualization)
Jupyter Notebook (Development environment)

📁 Project Structure
text
employee_burnout_analysis/
│
├── employee_burnout_analysis-AI 2.xlsx  # Original dataset
├── Employee_Burnout_Analysis.ipynb      # Jupyter notebook with code
├── README.md                            # This file
└── visualizations/                      # Generated plots and charts
🚀 How to Run
Prerequisites
bash
pip install pandas numpy matplotlib seaborn openpyxl
Execution Steps
Clone the repository
Install required libraries
Ensure the Excel file is in the correct path
Run the Jupyter notebook cells sequentially

💡 Business Implications
Resource Management: Higher resource allocation correlates with higher burnout
Mental Health Support: High mental fatigue scores indicate need for wellness programs
Career Progression Planning: Designation levels significantly impact burnout
WFH Policies: Analysis can inform remote work policies

📈 Future Scope
Predictive Modeling: Build ML models to predict burnout risk
Real-time Monitoring: Develop dashboard for continuous monitoring
Intervention Strategies: Suggest personalized intervention strategies
Comparative Analysis: Compare across industries and company sizes

📚 References
Dataset: Employee burnout analysis dataset
Tools: Python, Jupyter Notebook
Libraries: Pandas, NumPy, Matplotlib, Seaborn

📞 Contact
For any queries or collaboration opportunities, please contact:
Ashish Kumar
Email: ashishkumarmjl011@gmail.com
Phone: +91 9431649783
