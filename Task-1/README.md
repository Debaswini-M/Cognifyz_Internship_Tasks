
# Task 1: Predict Restaurant Ratings

### Task: Build regression models to predict the aggregate rating of a restaurant.

---

## 📌 Objective

To build and evaluate machine learning regression models to predict `aggregate_rating` based on features like:

- City and Locality
- Cuisines
- Cost for Two
- Votes and Price Range
- Online Delivery and Table Booking Availability

---

## 🛠️ Tools & Technologies Used

- **Python** (v3.10+)
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (for regression models, preprocessing, metrics)


---


## Dataset

The dataset contains restaurant-level metadata including:

- Categorical: City, Locality, Cuisines
- Numerical: Average cost for two, Votes
- Binary: Online delivery, Table booking, etc.

  Key preprocessing steps:
- Replaced `'<unset>'` and 0 values with `NaN`
- Imputed missing values using mode or median
- Encoded categorical variables using `OrdinalEncoder` and `OneHotEncoder`
- Scaled numerical features using `StandardScaler`

---

## Models Used

Four regression models were trained and evaluated:
- Linear Regression
- Decision Tree Regressor
- Ridge Regression
- Lasso Regression

---

## Visualizations

### ✅ RMSE & R² Comparison Across Models


<img width="930" height="490" alt="image" src="https://github.com/user-attachments/assets/5e943c02-ce91-41c4-8911-27129eb3564a" />


---

### 🎯 Actual vs Predicted Ratings


<img width="843" height="468" alt="image" src="https://github.com/user-attachments/assets/c0822d32-092e-4e2a-b336-4e0102079e23" />


---

### ⭐Top 10 Features per Model

#### 📌 Decision Tree
<img width="929" height="590" alt="image" src="https://github.com/user-attachments/assets/fa6c122e-c0e6-42fd-a2aa-b2ea15a7b1f9" />


#### 📌 Linear Regression
<img width="1012" height="590" alt="image" src="https://github.com/user-attachments/assets/3827ad4f-ba42-4633-a690-970bc0ee39f0" />


#### 📌 Ridge Regression
<img width="1014" height="590" alt="image" src="https://github.com/user-attachments/assets/323bd1db-dc3c-4344-8ea2-b8fd08de52ab" />


#### 📌 Lasso Regression
<img width="916" height="590" alt="image" src="https://github.com/user-attachments/assets/0df1a0bf-145e-4cac-b6da-b2a855cae487" />


---

## 📊 Evaluation Results


| Model                | RMSE (√MSE) | R² Score |
|---------------------|-------------|----------|
| Linear Regression   |0.166        |0.464|
| Decision Tree       | 0.197    |  0.363  |
| Ridge Regression    |0.141      |0.545 |
| Lasso Regression    | 0.27       | 0.126     |

---

## Author

**Debaswini**  

---
