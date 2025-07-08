# 🌍 Income Group Classification – WHO Data Case Study

## 📌 Problem Statement

**DeltaSquare**, an NGO working with the government, was given the task of analyzing WHO-provided demographic data to identify socioeconomic factors influencing individual income groups. The goal is to create a machine learning model to classify individuals into `Low Income` or `High Income` categories and aid in targeted policy-making for underserved communities.

## 🎯 Objective

- Classify individuals into income groups using logistic regression
- Identify key demographic and health-related variables that impact income
- Provide actionable insights to support social policy decisions

## 📊 Dataset

- **File**: `who_data.csv`
- **Target Variable**: `IncomeGroup` (Binary: `'Low'` or `'High'`)
- **Key Features**:
  - `BMI`, `GDP`, `LiteracyRate`, `EmploymentRate`, `UrbanPopulation`
  - `SchoolingYears`, `LifeExpectancy`, `HealthcareExpenditure`, etc.

## 📁 Repository Structure

```
├── IncomeGroupClassification_CaseStudy_DSBA_V2.ipynb   # Main notebook
├── who_data.csv                                        # Dataset file
├── README.md                                           # Project overview
```

## 🧪 Project Workflow

1. **Data Preprocessing**
   - Handled missing values and corrected inconsistent data types
   - Encoded categorical variables and normalized numerical columns

2. **Exploratory Data Analysis (EDA)**
   - Visualized distribution of income groups across demographic metrics
   - Used correlation matrix and box plots to detect strong predictors

3. **Model Development**
   - Applied Logistic Regression as the primary classification algorithm
   - Performed train-test split and evaluated model generalization
   - Validated assumptions like multicollinearity using VIF

4. **Evaluation Metrics**
   - Confusion Matrix
   - Accuracy, Precision, Recall, and F1 Score
   - ROC Curve & AUC

## 🏆 Results

- **Best Model**: Logistic Regression
- **Accuracy**: ~83%
- **Key Predictive Features**:
  - `LiteracyRate`, `GDP`, `SchoolingYears`, `HealthcareExpenditure`
- **Insights**:
  - Higher literacy and education years are strong indicators of high-income classification
  - GDP per capita and access to healthcare are pivotal for income stratification

## 🔍 Takeaways

- Basic logistic regression can yield highly interpretable and effective models for binary classification
- Data-driven policy making can improve targeting and impact of welfare programs
- Feature engineering and understanding domain context are crucial for actionable models

## 🚀 Future Enhancements

- Expand dataset with regional indicators or cultural variables
- Use tree-based ensemble methods (e.g., XGBoost, Random Forest) for improved accuracy
- Build a dashboard for policy makers to simulate changes in predictors

## 👨‍💻 Author

**Suhaib Khalid**  
AI & ML Practitioner
