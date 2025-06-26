# 🎬 IMDB Movie Rating Prediction

This repository contains a machine learning project focused on predicting movie IMDB ratings using various features like **genre, director, runtime, votes, and revenue**. The objective is to explore the dataset, build regression models, and evaluate their performance in estimating movie ratings.

---

## 📁 Dataset Source

**IMDB Movie Dataset**

The dataset includes the following columns:
- Title  
- Genre  
- Description  
- Director  
- Actors  
- Year  
- Runtime (Minutes)  
- Rating (Target variable)  
- Votes  
- Revenue (Millions)  
- Metascore  

---

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Workflow

### 🔹 Data Preprocessing
- Handling missing values  
- Encoding categorical features  
- Feature selection  

### 🔹 Exploratory Data Analysis (EDA)
- Rating distribution  
- Correlation between features  
- Genre-wise average ratings  

### 🔹 Model Building
- Linear Regression  
- Random Forest Regressor  

### 🔹 Model Evaluation
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## ✅ Results

- **Random Forest** performed better than **Linear Regression**
- Feature importance revealed that **votes** and **revenue** are key indicators of ratings

| Model              | MAE  | RMSE | R² Score |
|-------------------|------|------|----------|
| Linear Regression | 0.55 | 0.73 | 0.68     |
| Random Forest     | 0.41 | 0.58 | 0.82     |


