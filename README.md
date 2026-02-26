# Data Science & Machine Learning Portfolio

This repository contains data analysis and predictive modeling projects focused on real-world datasets. Each project covers the full pipeline: EDA, preprocessing, model training, and technical evaluation.

## Projects

### 1. Water Potability Classification
The goal was to predict if water is safe for consumption based on its chemical properties.

* **Challenge:** Dealing with highly imbalanced classes where accuracy is a misleading metric.
* **Models Tested:** Logistic Regression vs. Decision Tree.
* **Results:** Logistic Regression achieved **84% accuracy** but a very low **F1-score (~10%)**, failing to identify potable water samples effectively.
* **Conclusion:** The **Decision Tree** was selected as the superior model with an **F1-score of 30%**, providing much better practical utility despite slightly lower accuracy (83%).

### 2. Real Estate Price Prediction
A regression project aimed at estimating property values based on structural features.

* **Model:** Linear Regression.
* **Performance:** Achieved an **R² score of 0.65** (explaining 65% of price variance) with an **RMSE of 132,450.70$**.
* **Key Driver:** Analysis identified **surface area** as the primary factor influencing market price.
* **Insight:** While effective for basic estimation, the linear model is limited by its inability to capture non-linear factors like **location prestige**.

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
