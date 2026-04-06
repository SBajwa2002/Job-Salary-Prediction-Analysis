Project Title: Job Salary Prediction & Analysis
1. Project Overview

This project aims to predict whether a job falls into a high-salary or low-salary category based on various professional factors. A large dataset of over 250,000 records was used to perform data engineering, exploratory data analysis, and machine learning modeling to achieve high prediction accuracy.

2. Key Technical Tasks

Data Cleaning:
Missing values were handled using median (for numerical data) and mode (for categorical data). Duplicate records were removed to ensure data quality.

Advanced Preprocessing:
Z-score technique was applied to detect and remove outliers. Categorical data was standardized for consistency.

Feature Engineering:
New meaningful features were created, including:

Age: Estimated based on years of experience
Salary per Skill: Measures value per skill
Weekend Flag: Identifies job posting trends

Exploratory Data Analysis (EDA):
Data was analyzed using visualization tools such as correlation heatmaps, violin plots (salary vs. education), and pairplots to understand relationships between variables.

Model Development:
A HistGradientBoostingClassifier was implemented, which outperformed other machine learning models in terms of accuracy and efficiency.

Performance Evaluation:
The model was evaluated using key metrics such as Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC curve.

3. Final Model Performance

The model achieved excellent performance, showing that experience, industry, and education are strong predictors of salary levels:

Accuracy: ~95.45%
ROC-AUC Score: 0.9743
Precision & Recall: ~91%
4. Technology Stack
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, SciPy
Visualization Tools: Seaborn, Matplotlib
5. How to Use (Prediction)

The project includes a prediction module where users can input job-related details such as job title, experience, and industry to get an instant prediction of the salary category along with a confidence score.

✨ Tip:

“This project demonstrates strong skills in data analysis, feature engineering, and machine learning model development.”
