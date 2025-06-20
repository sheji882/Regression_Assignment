# Regression Assignment – California Housing Dataset

## Objective
The objective of this assignment is to apply and evaluate multiple regression algorithms on the **California Housing dataset** using Python and scikit-learn. This project demonstrates model training, evaluation, and comparison across various metrics such as MSE, MAE, and R² Score.

---

## Dataset Used
- **Source**: California Housing dataset from `sklearn.datasets`
- **Description**: Contains information about various California districts including median income, house age, population, and more, with the target variable being the median house value.

---

##  Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn (optional for visualizations)

---

##  Models Implemented

1. **Linear Regression**  
2. **Decision Tree Regressor**  
3. **Random Forest Regressor**  
4. **Gradient Boosting Regressor**  
5. **Support Vector Regressor (SVR)**  

Each model was trained on the preprocessed dataset and evaluated using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

**Conclusion**:  
Random Forest and Gradient Boosting Regressors performed best, with Random Forest slightly ahead. SVR had the weakest performance, likely due to sensitivity to scaling and dataset size.
