# 🏥 Medical Insurance Cost Analysis & Prediction (Python)

## 📝 Project Overview

This project involves performing **exploratory data analysis (EDA)** and building a **predictive model** to estimate medical insurance costs based on various personal and health-related factors. It is aimed at helping an insurance agency better understand what drives premium variations and make data-informed business decisions.

---

## 📁 Dataset

**File**: `insurance.ipynb`  
**Domain**: Healthcare  
**Source**: Simulated insurance dataset  
**Key Features:**

| Feature       | Description                                                  |
|---------------|--------------------------------------------------------------|
| age           | Age of the policyholder                                      |
| sex           | Gender of the policyholder                                   |
| bmi           | Body Mass Index (used to assess body type)                   |
| children      | Number of children covered by health insurance               |
| smoker        | Whether the policyholder is a smoker                         |
| region        | Residential region of the policyholder                       |
| charges       | Final insurance cost (target variable)                       |

---

## 🎯 Objective

To understand and predict how various demographic and lifestyle factors affect the **cost of medical insurance**. This includes:
- Analyzing the **impact of body type (BMI)** and **lifestyle (smoking)**
- Evaluating how **region and family status** influence premiums
- Creating a **regression model** to predict `charges` based on input features

---

## 🛠 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for regression modeling)
- Plotly (optional for interactive visuals)

---

## ✅ Key Tasks Performed

1. **Exploratory Data Analysis (EDA)**
   - Univariate & bivariate analysis of features
   - Visualizations: Histograms, Boxplots, Pairplots, Heatmaps
   - Correlation analysis

2. **Business Insights**
   - **Smokers pay significantly higher premiums**
   - **Higher BMI leads to increased cost**
   - **Certain regions show higher average charges**
   - **Family size affects cost, but to a lesser extent**

3. **Model Building**
   - Built a **Linear Regression** model
   - Preprocessing: Label Encoding, Feature Scaling
   - Evaluated model performance using metrics like RMSE and R²

---

## 📈 Key Insights

- Smokers, on average, incur **much higher medical insurance charges**
- Higher **BMI** correlates with increased cost — especially for smokers
- The **southeast region** shows notably high charges compared to others
- The **age** and **number of children** show moderate effects on premiums

---

## 📌 How to Run the Notebook

1. Open `insurance.ipynb` using **Jupyter Notebook** or **VS Code**  
2. Make sure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

---

## 🧠 Skills Demonstrated

- Data Cleaning & EDA
- Data Visualization
- Feature Engineering
- Predictive Modeling (Linear Regression)
- Business Insight Generation

---

## 📬 Contact

**Created by:** Samia Anis  
📧 samia.anis01@gmail.com  
🌍 Birmingham, UK
