# cafe
Analyze coffee shop sales to uncover insights into customer behavior, best-selling items, and revenue patterns.

# ☕ Coffee Sales Analysis

**Author:** Jennifer Tran  
**Dataset:** [Coffee Sales Dataset – Saad Ali Yaseen (Kaggle)](https://www.kaggle.com/datasets/saadaliyaseen/coffee-sales-dataset)  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## Project Overview

This project explores transactional sales data from a coffee shop to uncover key insights about customer behavior, product performance, and business trends. The analysis focuses on identifying sales patterns, top-performing branches and products, and time-based demand trends.  

The project demonstrates practical data analytics skills, including:
- Data cleaning and transformation  
- Exploratory data analysis (EDA)  
- Visualization and trend detection  
- Business insight communication  

---

## Dataset Description

The dataset contains detailed transaction records with the following key features:

| Column | Description |
|--------|--------------|
| `Date` | Date of the transaction |
| `Time` | Time of sale |
| `Transaction ID` | Unique transaction identifier |
| `Branch` | Coffee shop location |
| `Product Category` | Broad product type (e.g., Coffee, Tea, Food) |
| `Product Type` | Specific product sub-category |
| `Product Detail` | Item name/description |
| `Size` | Size option for the item |
| `Quantity` | Units sold per transaction |
| `Unit Price` | Price per item |
| `Total Bill` | Transaction total (Quantity × Unit Price) |

---

## Objectives

1. **Understand sales performance**
   - Which branch generates the most revenue?
   - What are the top-selling products and categories?

2. **Discover time-based patterns**
   - How do sales vary by time of day or day of the week?
   - Are there specific periods of peak demand?

3. **Identify pricing and quantity trends**
   - What is the relationship between product size, price, and sales volume?

4. **Support data-driven decision-making**
   - Provide actionable insights to optimize product mix, staffing, and marketing.

---

## Analysis & Insights

### 🧹 1. Data Cleaning
- Converted date and time columns to proper datetime formats.  
- Checked for missing or inconsistent entries.  
- Created new features: `DayOfWeek`, `Hour`, and `Month`.

### 🔍 2. Exploratory Data Analysis (EDA)
- Total revenue and average transaction size by branch.  
- Product-level performance using sales volume and total revenue.  
- Hourly and daily sales

### 📈 3. Key Findings (Example Highlights)
- **Branch A** generated the highest total sales revenue.  
- **Cappuccino** and **Latte** are consistently top performers.  
- Peak sales occur between **8–10 AM** and around **3 PM**, aligning with morning and afternoon coffee breaks.  
- Weekends show slightly higher average bills per transaction.  

---

## 🧠 Potential Extensions

- **Forecasting:** Build a time series model (e.g., Prophet or ARIMA) to predict future daily sales.  
- **Customer segmentation:** Cluster transactions by purchase behavior.  
- **Dashboard:** Develop an interactive Streamlit or Power BI dashboard to visualize real-time trends.  

---

