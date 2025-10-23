# 💳 Credit Card Transaction Analysis Dashboard — Power BI

---

## 🖼️ Dashboard Preview

<img src="Screenshot 2025-10-23 164706.png" alt="Credit Card Transaction Analysis Dashboard" width="100%">

---

This interactive **Credit Card Transaction Analysis Dashboard** provides detailed insights into customer spending behavior using Power BI. The aim of this project is to analyze **total spend, transaction count, and category-wise expenditure patterns** to better understand credit card usage trends.

---

## 📊 About the Dataset
- **Source:** Kaggle  
- **Columns Included:** `trans_date_trans_time`, `cc_num`, `category`, `amt`, `gender`, `trans_num`, `Full_Name`  
- **Data Preparation:**
  - Formatted the data types of all columns  
  - Merged *first name* and *last name* into **Full_Name** using a space delimiter  
  - Created a separate **_measures** table for all KPI calculations using DAX  

---

## 🧮 DAX Measures Used
1. **Total Spend**
   ```DAX
   Total_Spend = SUM(Credit_Card_dataset[amt])
2. **Total Transaction**
   ```DAX 
   Total_Transaction = COUNT(Credit_Card_dataset[trans_num])
3. **Average Transaction Value**
   ```DAX
   Average_Transaction_Value = AVERAGE(Credit_Card_dataset[amt])

---

## 🧠 Dashboard Features

- 📊 **4 KPI Cards** showing Total Spend by category  
- 🍩 **Donut Chart:** Spend by Category (percentage share)  
- 📅 **Clustered Column Chart:** Spend by Month  
- 🔽 **Dropdown Slicer:** Filter by `Full_Name`  
- ✅ **Vertical Slicer:** Filter by multiple `Category` values  

---

## 🧰 Tools & Technologies

- **Power BI** — Dashboard creation & visualization  
- **DAX** — Calculated measures  
- **Kaggle** — Dataset source  
- **Data Cleaning & Modeling**
  
---

## 👨‍💻 Author

**Ramesh Sonta**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sonta-ramesh/)
