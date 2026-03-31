Name : Ayesha Nawaz
University of Narowal
Semester : 6
Email : 12ayeshanawaz08@gmail.com

_____FINAL PROJECT_____

# 🚢 Titanic Survival Prediction | Machine Learning Project
<p align="center">
  <b>End-to-End ML Pipeline using Python & Scikit-learn</b><br>
  Data Cleaning • EDA • Preprocessing • Model Building • Evaluation
</p>

## 📌 Project Overview
This project is based on the historical dataset of the Titanic ship **RMS Titanic (1912)**.
The goal is to build a Machine Learning model that predicts whether a passenger survived or not based on various features.

## 🎯 Objectives
✔ Perform Exploratory Data Analysis (EDA)
✔ Clean and preprocess messy data
✔ Handle missing values and inconsistencies
✔ Apply feature engineering
✔ Build a complete ML pipeline
✔ Train and evaluate a classification model
✔ Save outputs for reproducibility

## 📂 Dataset Features

| Feature       | Description              |
| ------------- | ------------------------ |
| Survived      | Target (0 = No, 1 = Yes) |
| Pclass        | Passenger class          |
| Sex           | Gender                   |
| Age           | Age                      |
| Fare          | Ticket price             |
| Embarked      | Boarding port            |
| SibSp / Parch | Family info              |

## 📊 Exploratory Data Analysis

✔ Survival distribution
✔ Gender vs Survival
✔ Age distribution
✔ Correlation heatmap

# 🔍 Key Insights

* 👩 Females had higher survival rate
* 💰 Higher class passengers survived more
* 👶 Younger passengers had better chances

## 🧹 Data Cleaning

✔ Missing values handled
✔ Duplicates removed
✔ Cabin column dropped
✔ Data standardized

## ⚙️ Feature Engineering

Created new feature:
👉 **FamilySize = SibSp + Parch + 1**

Removed unnecessary columns:

* Name
* Ticket
* PassengerId

## 🔄 Data Preprocessing

Implemented using **Pipeline & ColumnTransformer**

* 🔤 Categorical → OneHot Encoding
* 🔢 Numerical → Standard Scaling

✔ No data leakage
✔ Clean workflow
✔ Reproducible pipeline

## 🤖 Model Used

👉 **Random Forest Classifier**

Why?
✔ High accuracy
✔ Handles non-linear data
✔ Robust performance

## 📈 Model Evaluation

✔ Accuracy Score
✔ Classification Report
✔ Confusion Matrix

🎯 **Achieved Accuracy:** ~80% – 90%

## 📁 Project Outputs

📂 outputs/

* clean_titanic.csv
* titanic_pipeline.pkl
* graphs (PNG files)
* confusion_matrix.png

## 🧪 Example Prediction

Input: Passenger details
Output: Survival prediction (0 or 1)

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries
3. Run the notebook or script
4. Check `outputs/` folder

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 👩‍💻 Author

**Ayesha Nawaz**
BS Computer Science Student
Passionate about Data Science & AI 🚀

---

