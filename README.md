# 📊 Startup Expansion Data Analysis

## 📌 Project Overview
This project analyzes a dataset of **150 startup expansion stores across the US**, containing details such as **location, sales region, marketing spend, and revenue**.  
The main goal is to evaluate the **impact of marketing spend on revenue and profitability**, and to compare performance between **new vs. old expansions** and across **sales regions**.

---

## 🛠️ Tools & Libraries
- **Python 3**
- **Pandas** – data cleaning, processing, and aggregation  
- **NumPy** – numerical computations  
- **Matplotlib & Seaborn** – data visualization and trend analysis  

---

## 📂 Dataset
- **File:** `startup-expansion.xlsx`  
- **Rows:** 150 stores  
- **Columns:**
  - Store ID  
  - City & State  
  - Sales Region (Region 1 / Region 2)  
  - Expansion Type (New / Old)  
  - Marketing Spend  
  - Revenue  

---

## 🔑 Analysis Steps
1. **Data Cleaning & Inspection**
   - Checked null values, duplicates, and column distributions.  
   - Verified unique values for states, cities, and regions.  

2. **Feature Engineering**
   - Created `Profit = Revenue – Marketing Spend`.  
   - Calculated **ROMS (Return on Marketing Spend)** as `(Profit / Marketing Spend) * 100`.  
   - Added `ROMS %` for easier comparisons.  

3. **Exploratory Analysis**
   - Compared **new vs old expansions** in terms of revenue and ROMS.  
   - Identified top-performing states and cities by revenue.  
   - Highlighted top 10 stores for **new expansions** and **old expansions** based on ROMS %.  

4. **Visualization**
   - Boxplots comparing ROMS % across **Expansion Type** and **Sales Region**.  
   - Correlation heatmaps (before and after encoding categorical variables).  
   - Revenue distribution and top-performers analysis.  

---

## 📊 Key Results
- **Old expansions** had significantly higher ROMS % compared to new expansions.  
- **Region 2** stores generally outperformed **Region 1** in revenue and profitability.  
- Top-performing store (Old expansion): **Little Rock, Arkansas** with ROMS % of ~27.2%.  
- Best new expansion by ROMS %: **Glendale, California** (~19.9%).  
- Strong positive correlation found between **Marketing Spend** and **Revenue**.  

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
   pip install numpy pandas matplotlib seaborn openpyxl
   jupyter notebook



