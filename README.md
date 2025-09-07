# 📱 Flipkart Mobiles Data Analysis & Visualization

## 📌 Project Overview  
This project analyzes **Flipkart Mobiles Dataset** to extract useful insights about mobile phones, their pricing, ratings, discounts, and customer reviews. The analysis and visualization are done using **Python** to understand market trends and customer preferences.  

## 🎯 Objectives  
- Analyze **mobile ratings and reviews**  
- Compare **MRP vs. MSP (discounted price)**  
- Study **brand-wise popularity** (Realme, Redmi, Poco, Apple, Vivo, etc.)  
- Identify **best deals** based on discounts  
- Visualize **customer preferences** using charts  

## 🛠️ Tools & Libraries  
- `pandas` → Data cleaning & manipulation  
- `numpy` → Numerical computations  
- `matplotlib` → Data visualization  
- `seaborn` → Advanced visualizations  

## 📂 Dataset Description  
The dataset used is: **`flipkart_mobiles.csv`**  

| Column Name    | Description |
|----------------|-------------|
| Name           | Mobile phone model name |
| Brand          | Mobile phone brand (Realme, Redmi, Poco, Apple, Vivo, etc.) |
| Ratings        | Average customer rating (out of 5) |
| No_of_rat      | Number of ratings |
| No_of_rev      | Number of reviews |
| Product_f      | Product features |
| MSP            | Market Selling Price (discounted price) |
| MRP            | Maximum Retail Price |
| Discount       | Discount percentage offered |

## 📊 Key Visualizations & Insights  
- **Brand-wise Sales Analysis** → Popular mobile brands  
- **Ratings Distribution** → Most phones have ratings above 4.0  
- **MRP vs. MSP Comparison** → Highlights biggest discounts  
- **Discount Trends** → Budget phones have higher discounts  
- **Top Rated Phones** → Apple & premium segment show high ratings  

## 🚀 Steps Performed  
1. **Data Cleaning & Preprocessing**  
   - Removed missing/duplicate values  
   - Converted price columns to numeric  
   - Extracted brand and features  

2. **Exploratory Data Analysis (EDA)**  
   - Rating distributions  
   - Brand-wise comparisons  
   - Price vs. Discount analysis  

3. **Visualization**  
   - Bar plots for brand popularity  
   - Scatter plots for MRP vs. MSP  
   - Heatmaps for correlations  
   - Histograms for ratings  

## 📌 Results & Insights  
- **Realme & Redmi** dominate with maximum models & ratings  
- **Apple** has high ratings but low discounts  
- **Discount %** is highest for budget phones (₹7k–₹15k)  
- Customers prefer mobiles with **ratings > 4.2** and heavy discounts  

---

✨ This project provides **valuable insights into customer behavior, pricing strategies, and brand competition** in the Flipkart smartphone market.
