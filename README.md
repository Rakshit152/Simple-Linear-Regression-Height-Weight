# Simple Linear Regression — Height vs Weight

This project is a beginner-friendly implementation of **Simple Linear Regression** using the Height-Weight dataset.

The goal is to predict **Weight (in pounds)** from **Height (in inches)** using a linear regression model.

---

## 📌 Dataset
The dataset contains:
- `Height(Inches)`
- `Weight(Pounds)`

Source: HeightWeight.csv (included in this repository)

---

## 🔍 Steps Performed

### 1. Import necessary libraries  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

### 2. Exploratory Data Analysis (EDA)  
- Displayed first few rows  
- Plotted Scatter Plot (Height vs Weight)  
- Correlation matrix  
- Pairplot for visualization  

### 3. Training the Model  
- Separated features (X) and labels (y)  
- Train-Test Split (25% test)  
- Standard Scaling applied to training data  
- Trained a LinearRegression model  

### 4. Evaluation Metrics  
- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

Model performance:
- **MSE:** approx 102  
- **MAE:** approx 8  
- **RMSE:** approx 10  
- **R² Score:** approx 0.25  

---

## 🧠 What I Learned
- How Linear Regression works  
- How to prepare data  
- How to scale features  
- How to evaluate regression models  
- How to visualize relationships in data  

---

## 📁 Files Included
- `Simple_Linear_Regression.ipynb` — Jupyter notebook  
- `HeightWeight.csv` — dataset  
- `README.md` — project documentation  

---

## 🚀 Future Improvements
- Try without scaling  
- Add polynomial regression  
- Try other datasets  
- Build a small UI to take user height and predict weight  

---

## 🙌 Author  
**Rakshit**  
Beginner in ML, building skills step by step 😊
