# 🚀 Startup Profit Prediction using Multiple Linear Regression

👋 Hi, I'm V. Chinna Koteswara Rao, currently pursuing B.Tech in **Artificial Intelligence & Machine Learning** at Chalapathi Institute of Technology.

This project focuses on predicting startup **profits** using various spending features like R&D, Administration, and Marketing, based on the **VC_Startup** dataset.
## 📌 Project Objectives
- Perform Exploratory Data Analysis (EDA)
- Visualize relationships between variables using scatter and box plots
- Identify statistically significant features using **OLS Regression**
- Build and train a **Multiple Linear Regression** model
- Predict profits for test data using `Scikit-learn`
## Key Learnings
- 🧪 R&D Spend had the highest impact on Profit
- 📉 Administration and Marketing showed less statistical significance
- 🧾 Learned the difference between `statsmodels` (for analysis) and `sklearn` (for prediction)
- 📐 Manually added intercept column using NumPy for `statsmodels.OLS`

##  Tools & Libraries
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn
## 📊 Visualizations
- Scatter plots: Profit vs R&D, Admin, Marketing, State
- Box plot: Profit grouped by State
- OLS Regression Summary for p-value analysis
## 🔮 Output
- Final trained model with `.intercept_` and `.coef_`
- Predicted Profit values using `regressor.predict(X_test)`
