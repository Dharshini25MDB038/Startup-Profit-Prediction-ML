# Startup Profit Prediction using Multiple Linear Regression

## 📌 Project Overview

This project builds a **Multiple Linear Regression Machine Learning model** to predict the profit of startup companies based on their spending patterns.

The model analyzes how different types of investments influence profit:

* R&D Spend
* Administration Spend
* Marketing Spend
* State (categorical variable)

The goal is to help businesses understand which investment contributes most to profit.

---

## 📊 Dataset Information

Dataset: **50_Startups.csv**

Features:

| Feature         | Description                                |
| --------------- | ------------------------------------------ |
| R&D Spend       | Money invested in research and development |
| Administration  | Administrative expenses                    |
| Marketing Spend | Marketing budget                           |
| State           | Location of startup                        |
| Profit          | Company profit (Target Variable)           |

---

## 🧠 Machine Learning Workflow

1. Data Loading using Pandas
2. Handling categorical variable (State) using Encoding
3. Splitting dataset into Training & Testing sets
4. Training Multiple Linear Regression model
5. Predicting profits
6. Evaluating model performance

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## 📈 Model Output

The model predicts startup profit based on investment distribution.

Key Insight:
R&D Spend has the strongest impact on profit compared to marketing and administration expenses.

---

## ▶️ How to Run the Project

1. Clone repository

```
git clone https://github.com/yourusername/Startup-Profit-Prediction-ML.git
```

2. Install required libraries

```
pip install -r requirements.txt
```

3. Run Jupyter Notebook

```
jupyter notebook
```

Open:

```
Multiple_Linear_Regression.ipynb
```

---

## 📂 Project Structure

```
Startup-Profit-Prediction-ML
│── Multiple_Linear_Regression.ipynb
│── 50_Startups.csv
│── README.md
│── requirements.txt
```

---

## 👩‍💻 Author

**Dharshini R**
Aspiring Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you found this useful

Give this repository a star!

