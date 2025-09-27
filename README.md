🏥 Medical Insurance Cost Analysis (Python)
📝 Project Overview

This project performs an exploratory data analysis (EDA) of a health insurance dataset to identify the demographic and lifestyle factors most strongly associated with higher medical charges. The goal is to surface clear, decision-ready insights for stakeholders (e.g., insurers, care managers, policy teams).

📁 Dataset

File: insurance.csv (analyzed in insurance.ipynb)
Domain: Healthcare
Source: Simulated insurance dataset

Key Features

Feature	Description
age	Age of the policyholder
sex	Gender of the policyholder
bmi	Body Mass Index (body composition proxy)
children	Number of dependents covered
smoker	Smoker status
region	Residential region
charges	Final insurance cost (analysis target)
🎯 Objective

To analyze factors influencing medical insurance charges, focusing on demographic (age, sex, children), lifestyle (smoking, BMI), and regional patterns—without building predictive models.

🛠 Tools & Technologies

Python (Jupyter Notebook)

Pandas, NumPy

Matplotlib, Seaborn

(Optional) SciPy/StatsModels for simple statistical tests

✅ What’s Included

Data Quality & Preparation

Shape, dtypes, duplicate removal, and null checks

Basic formatting (e.g., float display) and sanity checks

Univariate Analysis

Distributions for age, bmi, charges, children

Identification of skew/outliers (right-skew in charges)

Bivariate Analysis (Charges vs. …)

Smoking: substantially higher charges among smokers

Age & BMI: positive relationships with charges

Sex, Region, Children: minimal or small effects overall

Correlation heatmap for numeric features (age, bmi, charges)

Insights & Takeaways

Smoking status emerges as the dominant cost driver

Charges increase with age and BMI

Gender, region, and number of children show limited impact compared to smoking/age/BMI

Heavy-tailed (right-skewed) charges distribution highlights a small group of very high-cost cases

📈 Key Insights (Highlights)

Smoking is the most influential factor associated with higher medical charges.

Age and BMI show clear positive associations with costs.

Gender, region, and children have comparatively minor effects.

Charges are right-skewed, indicating outliers/high-cost cases that merit special attention in strategy and risk management.

▶️ How to Run

Clone the repo and open insurance.ipynb in Jupyter or VS Code.

Install dependencies:

pip install pandas numpy matplotlib seaborn


Run the notebook cells in order.

🧠 Skills Demonstrated

Python (Pandas, NumPy)

Data Cleaning & Wrangling

Exploratory Data Analysis (EDA)

Data Visualization (histograms, bar charts, scatter plots, heatmaps)

Insight Communication for non-technical stakeholders

📬 Contact

Created by: Samia Anis
📧 samia.anis01@gmail.com
