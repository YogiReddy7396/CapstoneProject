# 🔍 Capstone Project: Machine Failure Data Analysis

This project is a data analysis and machine learning capstone completed during my internship.  
The goal is to analyze machine sensor data and predict whether a machine will fail or not.

---

## 🚀 Project Overview

This project focuses on:

- Understanding machine behavior using data analysis
- Identifying patterns that lead to machine failure
- Building a predictive model to classify failure

The dataset contains multiple features such as temperature, air quality, usage metrics, and operational parameters.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Data Analysis Steps

- Data loading and inspection
- Checking dataset shape and structure
- Handling missing values (no missing values found)
- Statistical summary using `.describe()`
- Feature correlation analysis

---

## 📈 Exploratory Data Analysis (EDA)

- 📌 **Failure Distribution**
  - Visualized using count plot
  - Balanced dataset observed (failure vs non-failure)

- 📌 **Correlation Heatmap**
  - Identified relationships between features
  - Strong correlations observed with VOC and AQ

- 📌 **Pairplot Analysis**
  - Visualized feature interactions
  - Helped understand feature separation for classification

---

## 🤖 Machine Learning Model

- Model Used: **Random Forest Classifier**
- Data Split:
  - 80% Training
  - 20% Testing
- Feature Scaling applied using StandardScaler

---

## 📊 Model Performance

- ✅ Accuracy: **~92.5%**
- Precision, Recall, F1-score evaluated
- Confusion Matrix generated for performance validation

---

## 🔑 Key Insights

- VOC (Volatile Organic Compounds) is the most important feature
- AQ (Air Quality) also significantly impacts failure prediction
- Temperature shows moderate influence
- Model performs well in distinguishing failure vs non-failure

---

## 📂 Project Structure

```

CapstoneProject/
│── Capstone_Project_Data_Analysis.ipynb
│── README.md

```

---

## ⚙️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the dataset (`Machine_failure_data.csv`)
3. Run all cells step-by-step
4. View analysis and model output

---

## 📌 Notes

- This project is part of internship learning
- Focus is on data analysis + basic ML implementation
- No deployment is included

---

## 👨‍💻 Author

**Yogeswar Reddy**

---

## ⭐ Future Improvements

- Try advanced models (XGBoost, Gradient Boosting)
- Hyperparameter tuning
- Deploy model using Flask or Streamlit
- Real-time prediction system
```
