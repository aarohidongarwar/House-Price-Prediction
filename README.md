# 🏡 House Price Prediction using Regression & Random Forest

This project focuses on predicting the selling price of a house based on various property features.  
Two machine learning approaches were used — **Linear Regression (basic model)** and **Random Forest (advanced model)**.  
We also experimented with regularized regression techniques like **Ridge** and **Lasso** to improve performance.

---

## 📂 Dataset
The dataset used in this project is the **House Prices Dataset** available on Kaggle:  
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

It contains property attributes such as:
- Lot Area  
- Overall Material and Construction Quality (OverallQual)  
- Above Ground Living Area (GrLivArea)  
- Total Basement Area (TotalBsmtSF)  
- Number of Bedrooms and Bathrooms  
- Year Built, and many more.

---

## 🛠️ Project Workflow
1. Load the dataset and explore feature relationships.
2. Preprocess the data:
   - Handle missing values
   - Encode categorical variables
   - Log-transform the target variable due to skewness
3. Train baseline **Linear Regression**.
4. Train and tune:
   - **Ridge Regression**
   - **Lasso Regression**
5. Train **Random Forest Regressor** and tune hyperparameters.
6. Compare model performance and select the best model.
7. Evaluate using R-squared, MAE, MSE, and RMSE metrics.

---

## 📊 Result
- **Random Forest** performed better than Linear Regression and regularized models.
- Achieved **~85% accuracy (R² Score)** on the test data.
- **Most Important Predictors:**
  - OverallQual (House Quality)
  - GrLivArea (Above Ground Living Area)
  - TotalBsmtSF (Basement Area)

These features strongly influence house prices in real-world scenarios.

---

## ✅ Conclusion
- Random Forest is more effective for this dataset because it captures complex patterns better than linear models.
- This project provides a strong base model that can be extended into a real-world pricing application.

---

## 🚀 Future Scope
- Deploy the model as a web app using **Streamlit** or **Flask**.
- Add location-based price trend data.
- Use advanced ensemble models like Gradient Boosting or XGBoost.

---

## 👩‍💻 Author
*Aarohi Dongarwar*  
Data Science Intern  
