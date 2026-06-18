

 🏈 NFL Draft Prediction using Machine Learning

 📌 Project Overview

This project aims to predict whether an NFL prospect will be **Drafted or Not Drafted** using historical player data and Machine Learning techniques.

The goal is to leverage player attributes and performance-related features to build robust classification models capable of estimating a player's likelihood of being selected in the NFL Draft.

---

 🎯 Objectives

* Perform exploratory data analysis (EDA) on NFL prospect data.
* Clean and preprocess the dataset.
* Engineer features suitable for classification models.
* Train and compare multiple boosting algorithms.
* Evaluate model performance using the Area Under the ROC Curve (AUC).

---

📊 Dataset

**Source:** Kaggle

The dataset contains historical information about NFL prospects, including physical attributes, collegiate statistics, and other relevant variables used to determine draft outcomes.

**Target Variable:**

* `Drafted`

  * 1 = Drafted
  * 0 = Not Drafted

---

 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* CatBoost
* XGBoost
* Google Colab

---

🤖 Models Used

CatBoost Classifier

* **AUC Score:** `0.8405700105526975`

 XGBoost Classifier

* **AUC Score:** `0.8356`

🏆 Best Performing Model

**CatBoost** achieved the highest performance with an **AUC of 0.84057**, slightly outperforming XGBoost, because CatBoost natively handles categorical features

---

📈 Evaluation Metric

The primary evaluation metric for this project was:

* **ROC-AUC (Receiver Operating Characteristic - Area Under Curve)**

ROC-AUC was selected because it effectively measures a model's ability to distinguish between drafted and undrafted prospects, especially in potentially imbalanced datasets.

---

🔍 Key Insights

* Boosting-based models performed strongly on this classification problem.
* CatBoost demonstrated superior predictive performance compared to XGBoost on this dataset.
* Proper preprocessing and feature engineering contributed significantly to model performance.

---

🚀 Future Improvements

* Hyperparameter optimization
* Feature selection techniques
* Ensemble modeling
* Incorporating additional prospect and combine data
* Model explainability using SHAP values

---



---

## 👨‍💻 Author

**GitHub:** @wonkavite

Feel free to explore the notebook, suggest improvements, or connect to discuss Machine Learning and Sports Analytics!

