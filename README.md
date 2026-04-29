# Customer Retention Prediction using Machine Learning

## 📌 Project Overview

This project applies machine learning classification techniques to predict customer retention (churn). The goal is to identify customers at risk of leaving and support data-driven retention strategies.

---

## 📊 Dataset

* Customer-level dataset including:

  * Demographics
  * Account activity
  * Usage behavior

---

## ⚙️ Methodology

### Data Processing

* Missing value handling
* Encoding categorical variables
* Feature scaling
* Train-test split

---

### Models Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* XGBoost

---

## 📈 Model Performance

<p align="center">
  <img src="images/Test_AUC_by_Model.png" width="600"/>
</p>
<p align="center"><i>Model comparison based on AUC score.</i></p>

<p align="center">
  <img src="images/Test_F1_score_by_Model.png" width="600"/>
</p>
<p align="center"><i>F1-score comparison highlighting balance between precision and recall.</i></p>

---

## 🔍 Confusion Matrix (Best Model)

<p align="center">
  <img src="images/Confusion_Matrix_for_XGBoost.png" width="500"/>
</p>
<p align="center"><i>XGBoost confusion matrix showing classification performance.</i></p>

---

## 📈 ROC Curve

<p align="center">
  <img src="images/ROC_Curve_for_XG_Boost_Classifier.png" width="600"/>
</p>
<p align="center"><i>ROC curve showing strong classification ability of XGBoost.</i></p>

---

## 🔑 Feature Importance

<p align="center">
  <img src="images/Feature_Importance_for_XGBoost.png" width="600"/>
</p>
<p align="center"><i>Top features influencing customer retention predictions.</i></p>

---

## 📊 Data Insights

<p align="center">
  <img src="images/Customer_Retention_Distribution.png" width="500"/>
</p>
<p align="center"><i>Distribution of retained vs churned customers.</i></p>

---

## 🔍 Key Insights

* XGBoost achieved the best overall performance based on AUC and F1-score
* Recall is critical for identifying at-risk customers
* Ensemble models outperform simpler models in classification tasks

---

## 💡 Business Insights

* Early identification of churn enables targeted retention strategies
* Retention-focused models can significantly reduce customer loss
* Data-driven decision-making improves marketing effectiveness

---

## 📁 Project Structure

* `data/` → dataset
* `notebooks/` → analysis
* `images/` → visualizations
* `reports/` → report

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib

---

## 🚀 Future Improvements

* Hyperparameter tuning for improved model performance
* Incorporation of behavioral and transactional features
* Deployment of model for real-time churn prediction
