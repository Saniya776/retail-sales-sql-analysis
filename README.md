# Retail Sales Analysis – SQL Project  

## 📌 Project Overview  
This project focuses on analyzing a **Retail Sales dataset** using SQL. The objective is to explore sales patterns, customer behavior, and product category performance. The queries range from basic exploration to advanced analysis using grouping, ranking, and CTEs.  

---

## 🗂️ Dataset  
The dataset (`retail_sales`) contains the following columns:  

- `transaction_id` – Unique ID for each transaction  
- `sale_date` – Date of sale  
- `sale_time` – Time of sale  
- `customer_id` – Unique customer ID  
- `gender` – Customer gender  
- `age` – Customer age  
- `category` – Product category (Clothing, Electronics, Beauty, etc.)  
- `quantity` – Number of items sold  
- `price_per_unit` – Price of a single item  
- `cogs` – Cost of goods sold  
- `total_sale` – Total revenue from the transaction  

---

## ⚙️ SQL Tasks Performed  

### 🔹 Data Cleaning  
- Checked for null values in key fields (`transaction_id`, `sale_date`, `sale_time`, `gender`, `category`, `quantity`, `cogs`, `total_sale`)  
- Removed rows with missing values  

### 🔹 Exploratory Analysis  
1. Total number of sales transactions  
2. Number of unique customers  
3. List of unique product categories  

### 🔹 Business Questions Solved  
- Sales on a specific date (`2022-11-05`)  
- Clothing category sales with quantity ≥ 4 in Nov 2022  
- Total sales and order count by category  
- Average customer age for Beauty category  
- Transactions with total_sale > 1000  
- Sales distribution by **gender & category**  
- Best-selling month per year (using window functions)  
- Top 5 customers by sales amount  
- Unique customer count per category  
- Orders by **shift (Morning, Afternoon, Evening)**  

---

## 🛠️ SQL Features Used  
- **Aggregate functions**: SUM, AVG, COUNT, ROUND  
- **Filtering**: WHERE, BETWEEN  
- **Grouping**: GROUP BY, HAVING  
- **Sorting**: ORDER BY  
- **Window Functions**: RANK, PARTITION BY  
- **CTEs (Common Table Expressions)**  
- **CASE statements** for conditional grouping  

---

## 📊 Key Insights  
- Clothing was one of the highest-selling categories in Nov 2022.  
- Beauty category attracted relatively younger customers.  
- Sales peak occurred during specific months.  
- Evening shift had higher transaction volume compared to morning and afternoon.  
- A few customers contributed to a large portion of total revenue.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/retail-sales-sql.git

