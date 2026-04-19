# 🌧️ Rainfall Prediction using Machine Learning

## 📌 Problem Statement
India receives highly irregular rainfall across different regions and seasons. Some years there is too much rainfall causing floods. Some years there is too little causing droughts.
The real problem is — can we use past rainfall data to predict how much rain a region will receive annually?
Currently, traditional weather forecasting is expensive and complex. But with Machine Learning, we can use simple historical data to make accurate predictions — without needing complex weather equipment.
Rainfall is a critical natural resource. This project uses historical rainfall data to build a Machine Learning model that predicts **Annual Rainfall** based on monthly and seasonal rainfall patterns.
This is the problem my project solves."

---

## 📂 Dataset Description
- **File:** `Area_Weighted_Monthly_Seasonal_And_Annual_Rainfall_0.xls`
- **Contents:** Monthly, Seasonal, and Annual rainfall data for various meteorological stations across multiple years.
- **Key Columns:** Station Name, Year, Monthly rainfall (Jan–Dec), Seasonal values, Annual total.

---

## 🔄 Workflow Steps

| Step | Description |
|------|-------------|
| 1 | Import Libraries & Load Dataset |
| 2 | Exploratory Data Analysis (EDA) |
| 3 | Data Visualization |
| 4 | Data Cleaning |
| 5 | Data Preparation & Feature Scaling |
| 6 | Train-Test Split |
| 7 | Build Linear Regression Model |
| 8 | Model Evaluation |

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning

---

## 📊 Results & Insights
- Linear Regression was used to predict Annual Rainfall.
- Evaluation metrics: MAE, MSE, RMSE, and R² Score.
- Monthly rainfall features showed strong correlation with Annual totals.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rainfall-ml-project.git
   cd rainfall-ml-project
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl xlrd jupyter
   ```

3. Place the dataset file in the project root folder.

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

5. Run all cells from top to bottom.

---

## 📁 Folder Structure
```
rainfall-ml-project/
├── main.ipynb               # Main Jupyter Notebook
├── README.md                # Project documentation
├── .gitignore               # Git ignore rules
├── Area_Weighted_Monthly_Seasonal_And_Annual_Rainfall_0.xls
└── visualizations/          # All saved plots
    ├── histogram.png
    ├── boxplot.png
    ├── correlation_heatmap.png
    ├── pairplot.png
    └── yearly_trend.png
```

---

## 👨‍🎓 Academic Project
This project was created as a class assignment to demonstrate a complete Machine Learning workflow using real-world meteorological data.
