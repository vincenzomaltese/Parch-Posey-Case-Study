# Parch & Posey Case Study: Sales and Customer Trends Analysis

## 📌 Project Overview
This project explores the **Parch & Posey** database, a fictional paper company. The goal is to analyze business problems using **SQL queries**, exploring different analytical techniques such as **aggregations, joins, subqueries, and window functions**.

## 📂 Dataset Description
The database consists of five tables:

- **accounts**: Contains customer information, including account name and assigned sales representative.  
- **orders**: Stores details about customer orders, including order quantity, amount spent, and order date.  
- **sales_reps**: Holds data on sales representatives, including their assigned region.  
- **region**: Lists the different regions in which the company operates.  
- **web_events**: Logs online interactions with customers, such as ad clicks and website visits.  

Below is the **Entity-Relationship Diagram (ERD)** to better understand the data structure:

![ERD](https://github.com/vincenzomaltese/Parch-Posey-Case-Study/blob/main/images/ERD_parch_posey.png)

## 🛠️ Technologies Used
- **PostgreSQL** – To execute queries and analyze data.  
- **Visual Studio Code** – Development environment for writing and running SQL.  

## 🎯 Business Problems & Solutions

### 1️⃣ Sales Performance by Representative (Yearly Analysis)  
**Objective:** Identify the top-performing sales representatives based on total sales in **2016**.  
![Sales Performance](https://github.com/vincenzomaltese/Parch-Posey-Case-Study/blob/main/images/1_Sales%20Performance%20by%20Sales%20Representative.jpg)

### 2️⃣ Customer Order Trends Over Time  
**Objective:** Analyze order volume trends over the last year to identify **seasonal patterns**.  
![Customer](https://github.com/vincenzomaltese/Parch-Posey-Case-Study/blob/main/images/2_Customer%20Order%20Trends%20Over%20Time.jpg)
### 3️⃣ Web Engagement by Region  
**Objective:** Compare web engagement levels across different regions to understand **user activity distribution**.  

### 4️⃣ Web Engagement & Sales Correlation  
**Objective:** Investigate whether **web interactions impact sales performance**.  

## 📌 Key Takeaways
✔️ Identified **high-performing sales representatives**  
✔️ Detected **seasonal sales trends** for better planning  
✔️ Found regions with **high web engagement** for targeted marketing  
✔️ Validated the **impact of web engagement on actual sales**  
