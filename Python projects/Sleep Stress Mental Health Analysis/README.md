## **Sleep, Stress, and Mental Health: Statistical Analysis Using Python**

---

📌 Project Overview

This project explores the relationship between sleep patterns, lifestyle habits, physical activity, and stress levels using statistical analysis and predictive modeling.

The analysis combines exploratory data analysis (EDA) with Ordinal Logistic Regression to identify the factors most strongly associated with stress levels and mental well-being.

---

## 🎯 Research Questions

- Is there a relationship between sleep patterns and stress levels?
- How do lifestyle habits influence stress after controlling for demographic and health factors?
- How does physical activity affect stress levels?
- Which predictors have the strongest association with mental well-being?

--- 

## 📂 Dataset

**Dataset:** Stress Level Prediction

**Source:** https://www.kaggle.com/datasets/shijo96john/stress-level-prediction

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

---

## 📂 Project Structure

```text
Sleep-Stress-Mental-Health/
│
├── data/
├── notebooks/
├── visuals/
└── README.md
```

---

## 📊 Methodology

### Data Preparation

- Cleaned and prepared survey data
- Handled missing values
- Encoded categorical variables

### Exploratory Data Analysis

- Examined relationships between sleep, lifestyle habits, and stress
- Visualized trends and distributions

### Statistical Modeling

An Ordinal Logistic Regression model was used because the target variable (stress level) is ordinal, allowing the analysis to estimate how demographic, lifestyle, and health-related factors influence the likelihood of experiencing higher stress levels.

- Applied Ordinal Logistic Regression
- Conducted hypothesis testing
- Calculated odds ratios for interpretation

---

## 📈 Key Findings

### Sleep Patterns

- Longer sleep duration was associated with lower stress levels.
- Higher sleep quality significantly reduced the likelihood of severe stress.

### Lifestyle Habits

- Screen time was the most consistent predictor of increased stress.
- Smoking showed a weaker relationship with stress.
- Alcohol intake showed no strong independent relationship with stress.

### Physical Activity

- Exercise type influenced stress outcomes.
- Yoga and Pilates were associated with lower stress levels.

### Demographics

- Males showed higher stress likelihood than females.
- Older individuals tended to experience higher stress levels.

---


## 📈 Sample Visualizations

### Relationship Between Predictors and Stress Levels

![Relationship Between Predictors and Stress Levels](visuals/Relationships%20Between%20Predictors%20and%20Stress%20Detection.jpg)

---

## 🚀 Skills Demonstrated

- Python
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Hypothesis Testing
- Ordinal Logistic Regression
- Model Interpretation
-  Statsmodels

---

## 📌 Conclusion

This analysis identified **sleep quality** and **screen time** as the strongest predictors of stress levels. Participants with better sleep quality were significantly less likely to report high stress, while increased screen time was associated with greater stress. These findings suggest that improving sleep habits and managing screen exposure may contribute to better mental well-being. The project also demonstrates the application of statistical modeling to investigate relationships within health-related data.
