# 📱 Screentime Analysis & Prediction of Indian Kids (2025)

A detailed exploratory data analysis (EDA) and machine learning (ML) project examining the screen usage patterns of Indian children. This dual-phase project aims to understand screentime behavior and develop predictive models for future trends.

![Screentime Banner](https://github.com/sahil007707/Screen-Time-ML-And-EDA-Analysis-Of-Indian-Kids-2025-/blob/main/Images(PNG)/ChatGPT%20Image%20Jul%209%2C%202025%2C%2002_47_32%20PM.png)  

---

## 📂 Project Structure

- `Screentime EDA Analysis Of Indian Kids (2025).ipynb`  
  Uncovers key behavioral insights through in-depth exploratory data analysis and visualization.

- `Screentime ML Predictive Analysis Of Indian Kids (2025).ipynb`  
  Builds machine learning models to predict screentime categories and behavioral impact based on various demographic and digital usage features.

---

## 📊 Key Objectives

- Understand **how screentime is distributed** across different age groups, genders, and academic performance.
- Investigate correlations between **screen usage and sleep, study, and physical activity hours**.
- Predict whether a child's screentime is **Healthy or Unhealthy** using machine learning models.

---

## 🔬 EDA Highlights

- Gender and Age-based distribution of screentime.
- Time spent across categories: 📚 Study, 💤 Sleep, 🏃 Physical, 📱 Screentime.
- Correlation heatmaps and trendline regressions.
- Violin plots, boxplots, and bar charts for interactive storytelling.

📈 **Tools Used:**
`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`

---

## 🤖 ML Models & Techniques

- **Preprocessing**:
  - Label encoding of categorical data.
  - Feature scaling using `StandardScaler`.

- **Models Implemented**:
  - Logistic Regression
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
  - XGBoost Classifier

- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1 Score
  - Confusion Matrix
  - ROC-AUC Curve

🧠 **Best Performing Model:**  
`Random Forest Classifier` with tuned hyperparameters gave the highest predictive accuracy.

---

## 🗃️ Dataset Overview

| Feature               | Description                             |
|-----------------------|-----------------------------------------|
| Age                  | Age of the child                        |
| Gender               | Male/Female                             |
| Sleep_Hours          | Avg. hours spent sleeping daily         |
| Study_Hours          | Avg. hours spent on study               |
| Physical_Activity_Hours | Time spent in physical activities     |
| Screentime_Hours     | Daily screen exposure                   |
| Screentime_Category  | Healthy / Unhealthy label (Target)      |

🧪 *Synthetic dataset created for educational analysis. Not real-world data.*

---

## 📌 Key Takeaways

- Sleep and physical activity show a **negative correlation with screentime**.
- Older children tend to have **higher screentime**.
- Boys on average have slightly more screen exposure than girls.
- Machine Learning models can **reliably predict unhealthy screentime** with high accuracy.

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/sahil007707/indian-kids-screentime-analysis.git
   cd indian-kids-screentime-analysis
