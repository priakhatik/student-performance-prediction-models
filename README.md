# 🎓 Student Performance Prediction Models (KNN vs Linear Regression)

## Overview
This project compares **K-Nearest Neighbors (KNN)** and **Linear Regression** models to predict student academic performance based on key academic and behavioral factors.  
The goal is to evaluate which regression approach provides more accurate grade predictions using real-world student data.

---

## Objectives
- Build predictive models to estimate student performance.  
- Compare **KNN** and **Linear Regression** based on multiple evaluation metrics.  
- Perform hyperparameter tuning and model validation.  
- Visualize actual vs. predicted performance results.  

---

## Data
- **Dataset Name:** Student Performance Dataset  
- **Source:** Open-source dataset for academic performance prediction  
- **Records:** ~500–1000 (depending on cleaning and preprocessing)  
- **Target Variable:** `Final Grade`  

**Key Attributes**
- `StudyHours`, `Attendance`, `PreviousScores`, `ParentalEducation`, `Age`  
- `ExtraActivities`, `Health`, `Absences`, and related demographic features  

---

## 🧰 Tools & Technologies
- Python (3.10+)  
- Pandas, NumPy  
- scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Methodology

### 1. Data Preprocessing
- Handled missing values and standardized numerical features.  
- Encoded categorical variables.  
- Split dataset into **training (80%)** and **testing (20%)** subsets.  

### 2. Model Training
- Implemented and trained both **Linear Regression** and **KNN Regression** models.  
- Used **GridSearchCV** for K-value tuning in KNN.  

### 3. Model Evaluation
- Evaluated using:
  - **Mean Squared Error (MSE)**  
  - **Mean Absolute Error (MAE)**  
  - **R² Score**  
- Visualized **Actual vs Predicted** performance for both models.  

---

## 📊 Results
| Model | MSE | MAE | R² Score |
|--------|-----|-----|----------|
| Linear Regression | 22.45 | 3.89 | 0.74 |
| K-Nearest Neighbors | **18.62** | **3.25** | **0.81** |

**Best Model:** K-Nearest Neighbors (KNN) – achieved higher R² and lower prediction error.  

**Example Visualization:**  
![Actual vs Predicted – Linear Regression](images/linear_regression_actual_vs_pred.png)

---

## 🔍 Key Insights
- **KNN** performed better at capturing nonlinear relationships.  
- **Linear Regression** offered interpretability but less accuracy on complex data.  
- Feature scaling had a significant impact on KNN model performance.  
- Predictive accuracy can be improved with more features and data normalization.  

---

## 🌍 Real-World Applications
- Academic performance tracking and early-warning systems.  
- Data-driven learning interventions and personalized study plans.  
- Predictive modeling for school and university analytics.  

---

## 🚀 Future Work
- Add more advanced algorithms (e.g., Random Forest, XGBoost).  
- Apply cross-validation for more robust results.  
- Extend analysis with socio-economic or behavioral data.  
- Build an interactive visualization dashboard.  

---

## 👩‍💻 Author
**Pria Khatik**  
M.S. in Artificial Intelligence & Business Analytics, University of South Florida  
🔗 [LinkedIn](https://www.linkedin.com/in/priyakhatik/)  
💬 *"Data doesn’t lie—models just need to learn to listen."*  

---
