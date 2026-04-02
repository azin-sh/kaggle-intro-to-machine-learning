# kaggle-intro-to-machine-learning (Iowa Housing) 🏠
A comprehensive progression through the Scikit-Learn workflow, covering EDA, model validation, and optimization (Random Forests) for house price prediction.

## 📋 Project Overview

This repository documents my comprehensive progression through the Kaggle "Introduction to Machine Learning" track. Using the **Iowa House Prices dataset**, I built an end-to-end regression pipeline—starting from basic data exploration to deploying a high-performance Random Forest model.

## 📂 Project Roadmap

The analysis is structured into six progressive stages to demonstrate a mastery of the Scikit-Learn workflow:

1. **[Data Exploration](./01_Data_Exploration.ipynb):** Initial inspection using `pandas.describe()` to understand house price distributions.

2. **[First ML Model](./02_First_Model.ipynb):** Implementing a basic `DecisionTreeRegressor` to establish a baseline.

3. **[Model Validation](./03_Model_Validation.ipynb):** Utilizing Mean Absolute Error (MAE) to measure prediction accuracy.

4. **[Underfitting & Overfitting](./04_Underfitting_Overfitting.ipynb):** Analyzing the trade-off between model complexity and leaf node count.

5. **[Random Forests](./05_Random_Forests.ipynb):** Scaling from single trees to ensemble methods to reduce error.

6. **[Competition Entry](./06_Competition_Entry.ipynb):** Final model optimization for the "Housing Prices Competition for Kaggle Learn Users."



## 🛠️ Key Technical Skills

* **Preprocessing:** Managing target variables (y) and features (X) using Pandas.
* **Ensemble Methods:** Implementing `RandomForestRegressor` to improve stability over single Decision Trees.
* **Model Optimization:** Fine-tuning `max_leaf_nodes` to prevent overfitting.
* **Validation:** Calculating MAE to ensure the model generalizes to new data.

## 📈 Results & Insights

By transitioning from a simple Decision Tree to a **Random Forest**, I was able to significantly lower the Mean Absolute Error (MAE). This project highlights the importance of ensemble learning: by averaging predictions from many trees, the model becomes less sensitive to "noise" in the training data, leading to more reliable price estimates.

---

## 📜 Data Source
The data used in these exercises is provided by [Kaggle](https://www.kaggle.com/learn/intro-to-machine-learning) and includes various features of residential homes in Ames, Iowa.
