# 🧠 Customer Personality Analysis

## 📌 Problem Statement

Customer Personality Analysis involves examining the characteristics, behaviors, and preferences of a company’s ideal customers. This analysis enables businesses to gain deeper insights into their customer base and tailor their products, services, and marketing strategies to meet the specific needs of different customer segments.

Instead of targeting the entire customer base uniformly, businesses can identify and focus on segments that are most likely to respond positively to a product or campaign. This targeted approach helps optimize marketing efforts, improve customer satisfaction, and enhance overall business performance.

---

## 📊 Dataset Description

The dataset consists of various attributes related to customer demographics, purchasing behavior, marketing campaign responses, and more.

### **Attributes:**

#### 👥 People
- `ID`: Customer's unique identifier  
- `Year_Birth`: Year of birth  
- `Education`: Education level  
- `Marital_Status`: Marital status  
- `Income`: Yearly household income  
- `Kidhome`: Number of children  
- `Teenhome`: Number of teenagers  
- `Dt_Customer`: Date of enrollment with the company  
- `Recency`: Days since last purchase  
- `Complain`: 1 if the customer complained in the last 2 years, 0 otherwise  

#### 🛍️ Products
- `MntWines`: Amount spent on wine in the last 2 years  
- `MntFruits`: Amount spent on fruits  
- `MntMeatProducts`: Amount spent on meat  
- `MntFishProducts`: Amount spent on fish  
- `MntSweetProducts`: Amount spent on sweets  
- `MntGoldProds`: Amount spent on gold products  

#### 📢 Promotion
- `NumDealsPurchases`: Number of purchases made with a discount  
- `AcceptedCmp1` to `AcceptedCmp5`: 1 if the offer in the respective campaign was accepted  
- `Response`: 1 if the offer in the last campaign was accepted  

#### 🏬 Place
- `NumWebPurchases`: Purchases via the website  
- `NumCatalogPurchases`: Purchases via catalog  
- `NumStorePurchases`: Purchases directly in stores  
- `NumWebVisitsMonth`: Number of website visits in the last month  

---

## 🎯 Project Goal

- **Objective:** Perform clustering to identify and summarize customer segments.
- By clustering similar customers based on behavioral and demographic attributes, the business can:
  - Personalize marketing strategies
  - Optimize product recommendations
  - Improve customer retention

---

## 🧪 Solution Overview

This project uses **Python** for data analysis and machine learning. A clustering model is built to segment customers using features derived from the dataset.

Key questions addressed:
1. **What do people say about the product?**  
   (Reflects opinions and customer attitudes)

2. **What do people do?**  
   (Reflects real behavior, useful for predictions and targeting)

Techniques and tools used:
- Exploratory Data Analysis (EDA)
- Feature engineering
- K-Means Clustering
- Principal Component Analysis (PCA) for visualization
- Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 📈 Insights

Through clustering and visual analysis, the project uncovers actionable customer segments based on:
- Spending habits
- Demographic factors
- Channel preferences (web, store, catalog)
- Response to marketing campaigns

These insights can be used to:
- Personalize future campaigns
- Improve targeting efficiency
- Increase conversion rates and customer satisfaction

---

