## Student Performance Analysis & Prediction

##  Project Overview
This project analyzes student data and predicts final exam scores using a complete data science pipeline. It includes data cleaning, visualization, feature engineering, and machine learning using Linear Regression.


##  Dataset
The dataset contains 205 student records with features like:
- Age, Gender, City
- Department, Education Level
- Attendance, Study Hours
- Assignments, Quizzes, Midterm
- Final_Score (Target)

##  Steps Performed

### 1. Data Cleaning
- Fixed inconsistent casing (Gender, Name, Department)
- Converted Age to numeric
- Removed invalid values in Attendance and Final Score
- Filled missing values using median
- Removed duplicate rows

### 2. Exploratory Data Analysis
- Used histograms, scatter plots, and heatmaps
- Found strong relationships between attendance, midterm, and final score

### 3. Feature Engineering
- Created **Total_Academic**
- Created **Attendance_Category**
- Applied encoding (One-Hot + Ordinal)
- Scaled numerical data

### 4. Model Building
- Used Linear Regression
- Built pipeline using sklearn
- Train-test split (80/20)

##  Model Performance

- **R² Score:** 0.59  
- The model explains **59% of variation** in final scores  


##  Key Insights
- Higher attendance improves performance  
- Midterm score is strongest predictor  
- Study hours positively affect results  

##  Conclusion
The model achieved moderate performance and successfully captured key patterns in student data. Further improvements can be made by using advanced models and adding more features.


##  Future Work
- Try Random Forest / Decision Tree  
- Add more features  
- Improve data quality  


##  Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  


##  Author
Alishba Arooj  
Software Engineering Student
