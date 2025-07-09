# 🧠 Brain Stroke Prediction using Machine Learning

This project focuses on building and comparing machine learning models to **predict the risk of stroke** in individuals using medical history and demographic data. Early prediction can significantly reduce mortality and improve healthcare outcomes.

---

## 📌 Objective

To develop an ML-based predictive system that identifies patients at risk of having a stroke, allowing for timely medical intervention and preventive care.

---

## 📂 Dataset

- **Features**:
  - Gender
  - Age
  - Hypertension
  - Heart Disease
  - Ever Married
  - Work Type
  - Residence Type
  - Avg Glucose Level
  - BMI
  - Smoking Status
- **Target**: `stroke` (1 for stroke, 0 for no stroke)

> ⚠️ Due to sensitive healthcare data, the dataset has **not been balanced** to preserve its real-world class distribution.

---

## 🔧 Machine Learning Models & Performance

| ML Model                | Accuracy  | F1 Score | Recall   | Precision |
|-------------------------|-----------|----------|----------|-----------|
| Logistic Regression     | 0.9403    | 0.0317   | 1.0000   | 0.0161    |
| Gradient Boosting       | 0.9403    | 0.0317   | 1.0000   | 0.0161    |
| XGBoost Classifier      | 0.9393    | 0.1621   | 0.5000   | 0.0968    |
| Support Vector Machine  | 0.9393    | 0.0000   | 0.0000   | 0.0000    |
| Random Forest           | 0.9393    | 0.0000   | 0.0000   | 0.0000    |
| Decision Tree           | 0.9168    | 0.1905   | 0.2326   | 0.1613    |

> ✅ **Logistic Regressionr** delivered the most balanced F1 Score among all models.

---

## 📊 Evaluation Metrics

- **Accuracy**: Overall correctness of predictions
- **F1 Score**: Balance between precision and recall
- **Recall**: Ability to identify actual stroke cases
- **Precision**: Trustworthiness of stroke predictions

---

## 🚀 How to Run the Project

 **Clone the repository**
   ```bash
   git clone https://github.com/BrijeshRakhasiya/Brain-Stroke-Prediction.git
  ```
**Navigate into the directory**
```
cd Brain-Stroke-Prediction
```
   
# 📈 Results & Insights
Logistic Regression and Gradient Boosting achieved 100% recall but had low precision, flagging almost every case as stroke.

XGBoost Classifier provided a more practical balance between recall and precision.

Class imbalance posed a significant challenge, common in medical datasets.

## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**

