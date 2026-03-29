# 📊 Medicine Demand Prediction

⭐ Internship Task Submission – Data Analysis & Machine Learning

This project focuses on predicting medicine demand using historical pharmaceutical sales data. It involves data cleaning, analysis, visualization, and building a basic machine learning model to understand and forecast sales patterns.

---

## 📌 Project Overview

The main objective of this project is to analyze how different factors (especially time-related features) influence medicine sales and to build a model that can predict demand.

The workflow includes:

- Data preprocessing  
- Exploratory data analysis  
- Visualization  
- Machine learning model training and evaluation  

---

## 📂 Dataset

The dataset used in this project is a pharmaceutical sales dataset (sourced from Kaggle).

It contains:

- Date of sales  
- Sales data for different medicine categories  
- Time-based information extracted from the dataset  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Data Processing

- Converted date column into proper datetime format  
- Removed invalid/missing date values  
- Filled missing numeric values using median  
- Created new features such as:
  - Month  
  - Day  
  - Year  
  - Day of week  
  - Weekend indicator  

---

## 📈 Exploratory Data Analysis

- Monthly sales trends were visualized  
- Correlation heatmap used to identify relationships  
- Feature importance graph used to understand key influencing factors  

---

## 🤖 Machine Learning Model

A Random Forest Regressor was used for prediction.

Steps:

- Selected time-based features as input variables  
- Split data into training and testing sets  
- Trained the model on historical data  
- Generated predictions on test data  

---

## 📊 Model Evaluation

The model was evaluated using:

- R² Score → measures how well the model explains variance  
- Mean Absolute Error (MAE) → measures prediction error  

---

## 💡 Key Insights

- Sales vary across different months, indicating seasonal patterns  
- Certain medicine categories contribute more to total demand  
- Weekend impact on sales is relatively low  
- Time-based features play a significant role in prediction  

---

## 📁 Project Structure
medicine-demand-prediction/
│
├── pharma_sales.csv
├── medicine_prediction.ipynb
└── README.md

---

## 🔗 Outputs

- [View Monthly Sales Graph](data/monthly_sales.png)  
- [View Correlation Heatmap](data/heatmap.png)  
- [View Feature Importance](data/feature_importance.png)  
---

## 🔗 Project Files

- [View Jupyter Notebook](medicine_prediction.ipynb)  
- [Dataset File](pharma_sales.csv)

---

## 🧾 Conclusion

This project provides a simple approach to understanding and predicting medicine demand. The model performs reasonably well and can be improved further by including more real-world factors such as seasonal diseases or external demand drivers.

---

## 👩‍💻 Author

Monisha E MSc Data Science Student
