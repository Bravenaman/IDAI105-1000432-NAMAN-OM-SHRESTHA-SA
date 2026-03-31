# 🛍️ Beyond Discounts: Data-Driven Black Friday Sales Insights

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-streamlit-link-here.streamlit.app)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Data Mining](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange.svg)]()

An interactive Business Intelligence web application built with **Streamlit**. This project applies advanced data mining techniques to analyze Black Friday sales data, segment customers, discover product associations, and detect anomalous spending behavior.

---

## 🎓 Academic Details
- **Developer:** Zene-Sophie-Anand  
- **WACP No:** 1000442  
- **CRS Subject:** Artificial Intelligence  
- **Course Name:** Data Mining / IBCP (AI)  
- **Institution:** Aspen Nutan Academy  

---

## 📌 Brief Project Title and Scope

**Project Title:** Beyond Discounts: Data-Driven Black Friday Sales Insights  

**Project Scope:**  
As a Data Analyst at InsightMart Analytics, this project analyzes historical Black Friday sales data to uncover hidden consumer trends. It includes data cleaning, exploratory analysis, customer segmentation using machine learning, and identifying profitable product combinations. The goal is to provide actionable business insights for better inventory planning and targeted marketing.

---

## 🚀 Live Dashboard

👉 **[Click here to view the live app](https://idai105-1000442-zene-sophie-anand-sa.streamlit.app/)**  

---

## 📋 Project Scope & Objectives (Stage 1)

- **Goal:** Understand shopping behavior during Black Friday sales  
- **Objectives:**
  - Identify consumer trends  
  - Segment customers based on purchasing behavior  
  - Discover high-value product combinations  
- **Outcome:** Enable data-driven decisions for marketing and inventory optimization  

---

## 🧹 Key Preprocessing Steps, Visualizations, and Findings

### 🔧 Key Preprocessing Steps
1. Removed duplicate and irrelevant records  
2. Handled missing values in `Product_Category_2` and `Product_Category_3`  
3. Encoded `Gender` (Male = 0, Female = 1)  
4. Converted `Age` groups into ordinal values  
5. Normalized `Purchase` values using **StandardScaler**  

### 📊 Visualizations & Findings
- **Box Plots:** Ages 26–45 show highest spending  
- **Bar Charts:** Electronics & Apparel dominate sales  
- **Scatter Plots:** High spenders cluster in specific occupations  
- **Correlation Heatmap:** Positive correlation between age and spending  

---

## 🧠 Methodology & Advanced Analytics

### 🧹 Stage 2: Data Cleaning & Preprocessing
- Removed duplicates and handled missing values  
- Encoded categorical variables  
- Scaled numerical features  

---

### 📊 Stage 3: Exploratory Data Analysis (EDA)
- Box plots (Age vs Purchase)  
- Bar charts (Category popularity)  
- Scatter plots (Occupation vs Purchase)  
- Correlation heatmap  

---

### 🎯 Stage 4: Clustering Analysis
- **Algorithm:** K-Means  
- **Method:** Elbow Method (k = 3)  
- **Segments:** Discount Lovers, Average Shoppers, Premium Buyers  

---

### 🔗 Stage 5: Association Rule Mining
- **Algorithm:** Apriori  
- Discovered product combinations  
- Evaluated using Support, Confidence, Lift  

---

### ⚠️ Stage 6: Anomaly Detection
- **Method:** IQR  
- Identified high-spending outliers  

---

### 📈 Stage 7: Insights & Reporting

**Key Findings:**
1. Ages **26–45 spend the most**  
2. **Males:** Electronics & Sports  
   **Females:** Apparel, Beauty, Home  
3. High spenders = premium segment  

---

## 🖥️ UI Dashboard

![Dashboard 1](./SCREEN%20SHOT/1.png)  
![Dashboard 2](./SCREEN%20SHOT/2.png)  
![Dashboard 3](./SCREEN%20SHOT/3.png)  

![Dashboard 4](./SCREEN%20SHOT/4.png)  
![Dashboard 5](./SCREEN%20SHOT/5.png)  
![Dashboard 6](./SCREEN%20SHOT/6.png)  

![Dashboard 7](./SCREEN%20SHOT/7.png)  
![Dashboard 8](./SCREEN%20SHOT/8.png)  
![Dashboard 9](./SCREEN%20SHOT/9.png)  

![Dashboard 10](./SCREEN%20SHOT/10.png)  
![Dashboard 11](./SCREEN%20SHOT/11.png)  
![Dashboard 12](./SCREEN%20SHOT/12.png)  

![Dashboard 13](./SCREEN%20SHOT/13.png)  
![Dashboard 14](./SCREEN%20SHOT/14.png)  

---

## 📂 Repository Structure

```text
IDAI105-1000442-ZENE-SOPHIE-ANAND/
│
├── app.py
├── requirements.txt
├── SCREEN SHOT/
│   ├── 1.png
│   ├── 2.png
│   └── ...
└── README.md
```

---

## 🛠️ Installation & Local Setup

1. Clone the repository
```bash
git clone https://github.com/zeneanand/IDAI105-1000442-ZENE-SOPHIE-ANAND.git
cd IDAI105-1000442-ZENE-SOPHIE-ANAND
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the app
```bash
streamlit run app.py
```

---

## 📚 References

- https://scikit-learn.org/  
- http://rasbt.github.io/mlxtend/  
- https://plotly.com/python/  
- https://streamlit.io/  
