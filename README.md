# 🧠 Healthcare Stroke Data Analysis using Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Healthcare Stroke Dataset to identify patterns, trends, and relationships between demographic, lifestyle, and medical factors that influence stroke occurrence.

The project focuses on data cleaning, visualization, statistical analysis, and generating meaningful insights that can support future predictive modeling.

---

## 🎯 Problem Statement

Stroke is one of the leading causes of death and disability worldwide. Early identification of important risk factors can help improve healthcare decisions.

The objective of this project is to:

- Clean and preprocess the healthcare dataset
- Perform Exploratory Data Analysis (EDA)
- Discover important stroke risk factors
- Visualize relationships between variables
- Generate actionable healthcare insights

---

## 📂 Dataset Information

- **Dataset:** Healthcare Stroke Prediction Dataset
- **Source:** Kaggle
- **Records:** 5,110 Patients
- **Features:** 12 Columns
- **Target Variable:** Stroke (0 = No Stroke, 1 = Stroke)

### Dataset Features

- Gender
- Age
- Hypertension
- Heart Disease
- Ever Married
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis Process

### ✔ Data Cleaning

- Removed unnecessary columns
- Checked duplicate records
- Handled missing BMI values using Median Imputation
- Verified data types
- Generated summary statistics

---

### ✔ Missing Value Analysis

- Identified missing values
- Visualized missing data
- Filled BMI missing values with median

---

### ✔ Outlier Analysis

Outliers were analyzed using Boxplots for:

- Age
- BMI
- Average Glucose Level

Instead of removing them, they were retained because they represent genuine medical conditions.

---

### ✔ Univariate Analysis

Performed analysis using:

- Histograms
- KDE Plots
- Count Plots

Variables analyzed:

- Age
- BMI
- Gender
- Smoking Status
- Work Type

---

### ✔ Bivariate Analysis

Compared Stroke occurrence with:

- Gender
- Hypertension
- Age
- BMI
- Average Glucose Level

Visualizations:

- Countplots
- Boxplots

---

### ✔ Multivariate Analysis

Performed:

- Correlation Heatmap
- Pair Plot
- Scatter Plot
- Correlation Analysis

---

## 📈 Visualizations

The project includes multiple visualizations such as:

- Histogram
- KDE Plot
- Count Plot
- Box Plot
- Scatter Plot
- Correlation Heatmap
- Pair Plot

---

## 🔍 Key Insights

- Age is one of the strongest indicators of stroke.
- Higher glucose levels are associated with stroke.
- Patients with hypertension have a higher stroke occurrence.
- Heart disease is an important contributing factor.
- BMI alone is not a strong predictor.
- Stroke cases are highly imbalanced compared to non-stroke cases.
- Stroke risk depends on multiple medical and demographic factors.

---

## 📁 Project Structure

```
Healthcare-Stroke-EDA/
│
├── Healthcare Stroke Data Analysis Using EDA.ipynb
├── healthcare_stroke.csv
├── README.md
├── images/
│   ├── histogram.png
│   ├── boxplot.png
│   ├── heatmap.png
│   ├── pairplot.png
│   └── scatterplot.png
```

---

## 📷 Sample Visualizations

- Distribution of Age
- BMI Distribution
- Gender Count Plot
- Stroke vs Hypertension
- Stroke vs Age
- Correlation Heatmap
- Pair Plot
- Age vs Glucose Scatter Plot

---

## 🚀 Future Improvements

- Feature Engineering
- Machine Learning Models
- Stroke Risk Prediction
- Model Evaluation
- Interactive Dashboard using Power BI or Streamlit

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning Techniques
- Missing Value Handling
- Outlier Detection
- Exploratory Data Analysis
- Data Visualization
- Healthcare Data Interpretation
- Feature Relationship Analysis
- Statistical Insight Generation

---

## 💡 Conclusion

This project demonstrates how Exploratory Data Analysis can uncover meaningful healthcare insights from patient data. Age, glucose level, hypertension, and heart disease emerged as significant factors associated with stroke, while highlighting the importance of considering multiple variables together rather than relying on a single predictor.

---

## 👨‍💻 Author

**Monesh Chaudhari**

Aspiring Data Analyst

- LinkedIn: https://www.linkedin.com/in/monesh-chaudhari-4a9732377/
- GitHub: https://github.com/Monesh242004

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub!
