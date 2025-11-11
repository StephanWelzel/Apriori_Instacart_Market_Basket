# 🛒 Instacart Market Basket Analysis

## 📄 Project Overview
This project explores customer purchasing behavior using the **Simplified Instacart Dataset** from Kaggle.  
The goal is to identify associations between frequently purchased products and uncover actionable insights for marketing, product placement, and customer retention strategies.

---

## 📊 Dataset
**Source:** [Simplified Instacart Data (Kaggle)](https://www.kaggle.com/datasets/brendanartley/simplifiedinstacartdata)

The dataset includes millions of grocery orders from Instacart users, containing information about:
- Product names and categories  
- Orders and reorder patterns  
- Departments and aisles  

---

## 🎯 Objectives
1. Perform **Exploratory Data Analysis (EDA)** to understand general shopping patterns.  
2. Apply **Association Rule Mining (Apriori Algorithm)** to discover frequently co-purchased products.  
3. Identify cross-selling opportunities and potential for personalized recommendations.

---

## ⚙️ Methodology
### 🧹 Data Cleaning
- Removed duplicates  
- Handled missing values  
- Standardized product names  

### 🔍 Exploratory Data Analysis (EDA)
- Analyzed top-selling products, aisles, and departments  
- Investigated order frequency and user activity trends  

### 🧩 Market Basket Analysis
- Generated association rules using the **Apriori algorithm**  
- Evaluated metrics such as **support**, **confidence**, **lift**, and **leverage**  
- Focused on interpretable and high-lift product combinations  

---

## 💡 Key Insights
- The consistent decline in order volume suggests that the dataset reflects a controlled test group rather than a live, continuously growing retail environment — meaning user attrition, not seasonal or market effects, explains the downward trend.
- Organic produce items are frequently purchased together (e.g., *Organic Garlic* and *Organic Ginger Root*).  
- Strong associations appear within “Produce” and “Organic” categories, indicating health-conscious shopping habits.  
- High-lift rules reveal cross-selling opportunities and potential product bundling strategies for e-commerce.

---

## 🧠 Tools & Libraries
- **Python 3**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **mlxtend** (Apriori algorithm and association rule mining)  
- **Jupyter Notebook** for documentation and visualization  

---

## 📁 Repository Structure
    
    📦 Instacart_Market_Basket_Analysis
    ┣ 📜 Instacart_Market_Basket_Analysis.ipynb
    ┣ 📜 README.md
    
   
---

## 👤 Author

Stephan Welzel

Data Analyst/Scientist 

Python, SQL & n8n Enthusiast
