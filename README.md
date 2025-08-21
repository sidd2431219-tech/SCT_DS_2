# SCT_DS_2
🚢 Performed Data Cleaning &amp; Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle. 🧹 Cleaned missing values, engineered new features, and 📊 visualized key survival patterns based on gender, passenger class, age, and embarkation port. The project highlights clear insights and trends that can support predictive modeling.


# Titanic Data Cleaning and Exploratory Data Analysis

This project is part of my internship task as a beginner Data Analyst.  
I worked on the Titanic dataset from Kaggle to perform Data Cleaning and Exploratory Data Analysis (EDA).  
The main goal was to clean the dataset, handle missing values, and explore patterns in survival rates.  

## Dataset
- Source: Kaggle Titanic Dataset  
- Files included:
  - train.csv → used for cleaning and EDA (contains survival information)  
  - test.csv → usually for prediction tasks (not used here)  

## Steps Performed
1. Data Cleaning
   - Filled missing values (Age with median, Embarked with mode)  
   - Dropped Cabin column (too many missing values)  
   - Created new feature: HasCabin (1 if passenger had a cabin, 0 if not)  

2. Exploratory Data Analysis (EDA)
   - Univariate Analysis (Age, Fare, Pclass distributions)  
   - Bivariate Analysis with Survival (Sex, Pclass, Embarked, Age groups)  
   - Visualizations created using Matplotlib  

## Key Insights
- Women had a much higher survival rate than men  
- Passengers in 1st class survived more compared to 3rd class  
- Children (age under 12) survived more than adults  
- Passengers from Port C had better survival chances  

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

## How to Run
1. Clone this repository
2. Upload the train.csv file in Google Colab or Jupyter Notebook  
3. Run the notebook to view the data cleaning process, analysis, and visualizations  

## Conclusion
This project provided practical experience with:  
- Cleaning messy real-world data  
- Handling missing values and irrelevant features  
- Performing exploratory data analysis  
- Discovering clear survival patterns based on gender, class, and age  

## Acknowledgments
Dataset: Kaggle Titanic Challenge

