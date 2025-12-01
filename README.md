Project Summary: Salary Prediction Using Random Forest Regression

This project uses Random Forest Regression to predict an employee’s salary based on their position level. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To build a robust regression model using an ensemble of decision trees to capture complex, non-linear salary trends.

📊 Dataset

The dataset (Position_Salaries.csv) includes:

Position

Level (1–10)

Salary

The dataset shows a non-linear salary pattern that benefits from ensemble methods.

🛠️ Steps Performed

Loaded and analyzed the dataset

Trained a Random Forest Regression model (with n_estimators = X)

Visualized the forest’s predictions against actual salary values

Compared the smoothness of predictions with Decision Tree Regression

Predicted salary for a specific level (e.g., 6.5)

📈 Key Insight

Random Forest averages predictions from many decision trees, reducing variance.

Produces a smoother and more stable prediction curve compared to a single decision tree.

Handles non-linear data very effectively.

Less prone to overfitting due to ensemble averaging.

🧪 Outputs

Random Forest regression curve

Scatter plot of actual salary data

Predicted salary value for the selected level

🚀 Conclusion

Random Forest Regression is a powerful ensemble method that provides accurate, stable predictions for non-linear datasets. It combines multiple trees to reduce overfitting and generally performs better than standalone decision trees.
