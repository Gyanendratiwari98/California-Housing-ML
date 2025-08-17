# California-Housing-ML
Linear and Polynomial Regression on California Housing & Other Datasets

---

## 📊 Dataset Sources

- **California Housing Dataset** → `fetch_california_housing()` from `sklearn.datasets`
  - Target: House price
  - Common feature used: `MedInc` (Median Income)
- **Toy / Synthetic Data** → small generated datasets to demonstrate polynomial fitting
- **Kaggle Datasets** → external `.csv` files for real-world regression practice

---

## 🔧 Models Used

- **Linear Regression** (`sklearn.linear_model.LinearRegression`)
- **Polynomial Regression** (`sklearn.preprocessing.PolynomialFeatures` + Linear Regression)

---

## 📈 Workflow

1. Load dataset (sklearn / toy / Kaggle)
2. Perform EDA (explore, clean, visualize)
3. Train-test split
4. Train **Linear Regression** model
5. Train **Polynomial Regression** model (degree 2, 3…)
6. Evaluate with **R², RMSE**
7. Visualize results (predictions vs actual, curve fitting, residual plots)

---

## 📂 Files

- `House price predition using linear Regression.ipynb` – Linear regression on California Housing  
- `House price predition using Polynomial Regression.ipynb` – Polynomial regression on California Housing  
- `Polynomial Regression.ipynb` – Polynomial regression on toy datasets  
- `regression_model.ipynb` – End-to-end regression pipeline  
- `Other Notebooks` – Regression experiments on Kaggle datasets  

---

## 🧠 Learnings

- How to apply regression models using scikit-learn  
- Difference in performance between **linear vs polynomial models**  
- Understanding **bias–variance tradeoff**  
- Visualizing model fits on **different types of datasets**  

---

## ✅ Output Example

*(Add your plots here for better presentation, e.g. predicted vs actual values)*

---

## 🚀 Author

Made by **Gyanendra Tiwari**  
Final Year AIML Student  

⭐ If you like this project, please star the repo!
