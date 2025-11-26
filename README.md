# 📊 E-Commerce Sales Analysis & Customer Segmentation (India)

A complete end-to-end **Data Analysis & Machine Learning Segmentation Project** built using a realistic **Indian E-commerce Dataset (5,000+ orders)**.

This project covers:
- Exploratory Data Analysis (EDA)
- Sales Trends (Monthly, Category, Region)
- Product Performance Insights
- Customer Behaviour Analysis
- Customer Segmentation using **K-Means Clustering**
- Visualizations & Insights for business decisions

---

## 📁 **Dataset Overview**

**Rows:** 5,000  
**Customers:** 300  
**Categories:** Smartphones, Laptops, Headphones, Footwear, Books, Watches & Accessories  
**Regions:** North, South, East, West, Central  
**Timeline:** Jan 2023 – Dec 2023  

### **Columns Included**
- `Order_ID`
- `Order_Date`
- `Customer_ID`
- `Gender`
- `Region`
- `Product`
- `Category`
- `Unit_Price`
- `Quantity`
- `Revenue`
- `Payment_Method`
- `Delivery_Time_Days`
- `Rating`

---

## 📈 **Key Business Insights**

### 🔹 **Total Revenue:** ₹23.08 Crore  
### 🔹 **Average Order Value (AOV):** ₹46,177  
### 🔹 **Total Items Sold:** 10,246  
### 🔹 **Unique Customers:** 300  
---

## 🗓 **Monthly Sales Trend**
- **Highest Revenue Month:** **October 2023** — ₹2.13 Crore  
- **Lowest Revenue Month:** **August 2023**  
- Sales show a **fluctuating trend** with a major spike during the festive season.

  <img width="580" height="487" alt="graph_2" src="https://github.com/user-attachments/assets/020a4cdb-67a9-4cf0-ba6c-17e5d2f371a7" />


---

## 🛒 **Category Performance**
- **Top Category:** 🏆 **Laptops**  
- High-ticket items like Acer Aspire 7, Asus VivoBook 15 & HP Victus 16 dominate sales.

---

## 🛍 **Top Performing Products**
1. **Acer Aspire 7**  
2. **Asus VivoBook 15**  
3. **HP Victus 16**

### ❗ Least Performing Products
- *Deep Work*  
- *Rich Dad Poor Dad*  
- *Ikigai*  

Books category under-performs vs premium electronics.

---

## 👥 **Customer Segmentation (K-Means Clustering)**

Based on:
- **Total Spend**
- **Total Orders**
- **Average Order Value**

### 🎯 Resulting Segments:

#### ⭐ **Segment 2 – High Value Customers**
- Highest total spend (₹11+ lakh avg)
- Highest Avg Order Value (₹73,000)
- Premium electronics buyers

#### ⭐ **Segment 0 – Medium Value Customers**
- Highest order frequency (21+ orders)
- Good total spend
- Loyal repeat shoppers

#### ⭐ **Segment 1 – Low Value Customers**
- Lowest total spend (₹4.7 lakh)
- Lowest AOV  
- Budget/occasional buyers

---

## 📊 **Segmentation Visualization**
Scatter plot showing clear 3 customer clusters based on:
- Total Orders  
- Total Spend  
- AOV  

<img width="857" height="547" alt="graph" src="https://github.com/user-attachments/assets/c2cb25c9-ef62-4096-9172-9c323c32b412" />


---

## 🛠 **Tech Stack**
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-Learn**
- **Seaborn**
- **Jupyter Notebook / Colab**

---

## 🚀 **How to Run**
```bash
pip install -r requirements.txt
jupyter notebook
