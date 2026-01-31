# Titanic Survival Analysis & Modeling

## Overview
This project explores the Titanic dataset using data visualization, feature engineering, and machine learning modeling.  
The goal is to understand survival patterns and build predictive models to estimate passenger survival.

The project includes exploratory data analysis (EDA), visual insights, preprocessing, and classification modeling using Logistic Regression.

---

## Dataset
- Source: Titanic dataset (Kaggle)
- Contains passenger information such as:
  - Age
  - Sex
  - Passenger Class
  - Fare
  - Family details
  - Survival status

---

## Project Tasks

###  Data Analysis & Visualization
- Missing value handling
- Distribution plots
- Survival analysis by gender and class
- Correlation and trend visualizations

###  Feature Engineering
- Data cleaning
- Encoding categorical variables
- Feature selection & transformation

###  Modeling
- Dummy Classifier (baseline model)
- Logistic Regression model
- Model comparison using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---

##  Model Results (Summary)

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|------------|-------------|-----------|------------|
Dummy Classifier | ~0.62 | 0.00 | 0.00 | 0.00 |
Logistic Regression | ~0.80 | ~0.78 | ~0.68 | ~0.73 |

Logistic Regression significantly outperforms the Dummy Classifier baseline.

---

##  Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / VS Code

---

##  How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Titanic_Project.git


Project Structure
Titanic_Project/
├── visualization.ipynb     # EDA and visualization
├── Modeling.ipynb          # ML modeling and evaluation
├── README.md
└── .gitattributes
Author

Ahmad Ali
GitHub: https://github.com/AhmadAlee10