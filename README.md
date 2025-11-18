# 🩺 Medical Cost Prediction
This project aims to predict medical insurance costs based on personal factors. It uses regression models to identify the factors that most influence an individual's insurance costs. The models used are Linear Regression, Random Forest, and K-Neighbors Regressor.

---
## 📁 Dataset
Source: Kaggle - Medical Cost Personal Dataset
- This dataset contains 1,338 individual data points with seven input features, including age, sex, BMI, children, smoker, region, and charges. 

---
## ⚙ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
---
## 🔎 EDA & Feature Engineering
- Checking missing values
- Encoding
- Scaling
 --- 
## 🤖 Models
- Linear Regression
- Random Forest
- KNN
  
---
## 📊 Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---
## 🧠Insight
- Smokers incur much higher insurance costs than non-smokers.
- Older age → higher insurance costs.
- High BMI → higher insurance costs.
- Region & number of children → less impact.
- Combined effects (BMI_smoker & age_smoker) → amplify costs.
- Among all the models tested, Random Forest performed best in predicting insurance charges, demonstrating its ability to identify non-linear relationships in the data. Linear regression showed the highest R² score (0.8869), indicating better overall suitability and consistency in the data. Therefore, linear regression was selected as the final model for this project due to its strong balance between readability and prediction accuracy.

---
## 🚀 How to Run

- Ensure all required packages are installed:
```
  pip install pandas numpy scikit-learn seaborn matplotlib
```

- Run the notebook in Jupyter or VS Code:
```
  jupyter notebook Project_MedicalCost.ipynb
```
