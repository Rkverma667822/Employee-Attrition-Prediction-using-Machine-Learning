# Employee-Attrition-Prediction-using-Machine-Learning
## 📌 Project Overview

Employee attrition is a major challenge for organizations as it impacts productivity, recruitment costs, and employee morale. This project uses Machine Learning techniques to predict whether an employee is likely to leave the company based on various personal and professional attributes.

The project includes data preprocessing, exploratory data analysis (EDA), model training, model evaluation, feature importance analysis, and HR recommendations.

---

## 📂 Dataset

- **Dataset:** IBM HR Analytics Employee Attrition & Performance
- **Records:** 1,470 employees
- **Features:** 35 original features
- **Target Variable:** Attrition (Yes/No)

---

## 🎯 Project Objectives

- Explore and understand employee attrition patterns.
- Clean and preprocess the dataset.
- Build multiple Machine Learning models.
- Compare model performance.
- Identify the key factors influencing employee attrition.
- Provide actionable HR recommendations.

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Attrition Rate Analysis
- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition

### Key Business Insights

- Sales department has the highest attrition rate (**20.63%**).
- Human Resources department also shows relatively high attrition (**19.05%**).
- Employees with lower monthly income are more likely to leave.
- Overtime and work environment significantly influence attrition.
- Employee attrition is an imbalanced classification problem.

---

## ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed unnecessary columns
- Converted Attrition (Yes/No) into 1/0
- Applied One-Hot Encoding to categorical variables
- Scaled numerical features using StandardScaler
- Split data into Training (80%) and Testing (20%)

---

## 🤖 Machine Learning Models

Three classification models were trained:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### Performance Summary

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Logistic Regression | 75.17% | 0.803 |
| Random Forest | 84.69% | 0.787 |
| Gradient Boosting | **86.05%** | **0.805** |

Gradient Boosting achieved the best overall performance based on Accuracy and ROC-AUC Score.

---

## ⭐ Top 10 Important Features

The Gradient Boosting model identified the following important features:

1. Monthly Income
2. Age
3. Total Working Years
4. OverTime_Yes
5. NumCompaniesWorked
6. StockOptionLevel
7. YearsWithCurrManager
8. EnvironmentSatisfaction
9. DailyRate
10. OverTime_No

---

## 📊 Visualizations

The project includes:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income Box Plot
- Confusion Matrix Heatmap
- Top 10 Feature Importance Chart
- ROC Curve Comparison (Bonus)

---

## 💼 HR Recommendations

- Focus retention strategies on employees in the Sales and Human Resources departments.
- Monitor employees working overtime frequently.
- Improve work-life balance initiatives.
- Offer competitive compensation and career growth opportunities.
- Conduct regular retention discussions with high-risk employees.

---

## ⚠ Project Limitation

This model was trained using a single historical dataset. Employee behavior may change over time, so the model may require retraining with updated data for better generalization.

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Employee-Attrition-Prediction.git
```

2. Install required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook or Google Colab notebook.

4. Run all cells.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/
│
├── Employee_Attrition_Prediction.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
```

---

## 👨‍💻 Author

**Rajeev Mukhiya**

- B.Tech (Artificial Intelligence & Machine Learning)
- Python | Machine Learning | Data Science Enthusiast

---

