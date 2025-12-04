# Algorithmic Classification Analysis: IoT & Environmental Data

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and **Supervised Learning** applied to complex time-series datasets:
1.  **IoT Sensor Data** (PIR sensors, temperature, timestamps).
2.  **Environmental Data** (Air pollution metrics, atmospheric conditions).

The goal was to build robust classification models capable of handling **class imbalance**, **outliers**, and **high-dimensional feature spaces**.

## 🚀 Key Features
* **Advanced Preprocessing:** Implemented **IQR-based outlier detection** to clean sensor noise and performed dimensionality reduction using correlation thresholds (>0.95).
* **Model Development:** Trained and optimized three distinct models using **Scikit-Learn**:
    * Random Forest Classifier
    * Multi-Layer Perceptron (MLP / Neural Network)
    * Logistic Regression
* **Optimization:** Addressed class imbalance using **weighted optimization** (`class_weight='balanced'`) and standardized features for distance-based algorithms.

## 📊 Results
The models were evaluated using Accuracy, Precision, Recall, and Confusion Matrices.

| Dataset | Best Model | Accuracy | Key Insight |
| :--- | :--- | :--- | :--- |
| **IoT Sensor Data** | **Random Forest** | **99.35%** | Highly effective at modeling non-linear decision boundaries. |
| **Environmental Data** | **MLP (Neural Net)** | **96.97%** | Strong performance in capturing complex atmospheric correlations. |

> *For a detailed breakdown of confusion matrices, learning curves, and theoretical analysis, please refer to the **[Technical Report](docs/Project_Report.pdf)**.*

## 🛠️ Technologies Used
* **Language:** Python 3.x
* **Libraries:**
    * `scikit-learn` (Modeling & Preprocessing)
    * `pandas` & `numpy` (Data Manipulation)
    * `matplotlib` & `seaborn` (Visualization)
