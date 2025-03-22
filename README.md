
### **Boston Housing Price Prediction **  

#### **Step 1: Understanding the Problem**  
The objective of this project was to build a regression model from scratch to predict house prices using the **Boston Housing Dataset**. This dataset contains multiple features related to housing characteristics, such as crime rate, number of rooms, and property tax.  

---

#### **Step 2: Data Preprocessing**  
Before building the models, I performed the following preprocessing steps:  
- **Handled missing values** by filling them with the median.  
- **Normalized numerical features** to scale them between 0 and 1.  
- **Separated the dataset** into features (**X**) and the target variable (**y**), where **y** represents the house prices.  
- **Split the dataset** into training (80%) and testing (20%) sets to evaluate model performance.  

---

#### **Step 3: Implementing Regression Models from Scratch**  
Since the goal was to avoid built-in regression models like `sklearn.linear_model`, I implemented three different models from scratch:  

1. **Linear Regression**  
   - Used **Gradient Descent** to optimize weights and bias.  
   - Predicted house prices using a linear equation.  
   - Evaluated performance using **Root Mean Square Error (RMSE)** and **R² score**.  

2. **Random Forest**  
   - Built multiple **Decision Trees** using bootstrapped datasets.  
   - Averaged the predictions from multiple trees to improve accuracy.  
   - Compared performance with Linear Regression.  

3. **XGBoost (Extreme Gradient Boosting)**  
   - Implemented a **boosting algorithm** where weak learners are trained sequentially.  
   - Improved accuracy by reducing errors at each step.  
   - Used **gradient-based optimization** to fine-tune predictions.  

---

#### **Step 4: Performance Evaluation**  
To compare the models, I used two evaluation metrics:  

- **RMSE (Root Mean Square Error):** Measures how far the predicted values are from actual values. Lower RMSE means better accuracy.  
- **R² Score:** Indicates how well the model explains the variability in house prices. Higher R² means better performance.  

After evaluating all three models, I compared their results and identified which model performed best on the test data.  

---

#### **Step 5: Feature Importance Visualization**  
For **tree-based models** like Random Forest and XGBoost, I visualized **feature importance** to understand which housing attributes had the most impact on price predictions. Features like **average number of rooms (RM)** and **lower status of the population (LSTAT)** were among the most influential.  

---

### **Conclusion**  
- Successfully built **three machine learning models from scratch** to predict Boston house prices.  
- **Compared performance** using RMSE and R² scores, showing the strengths and weaknesses of each model.  
- **Visualized feature importance**, highlighting the most critical factors affecting house prices.  

This project demonstrates how regression models work at a fundamental level without relying on pre-built machine learning libraries. 🚀  

Now, I am ready to **publish my work on GitHub** and share it with others! 🎉
