# 🛒 Walmart Sales Data Analysis

This project focuses on analyzing sales data from Walmart stores. The dataset was sourced from Kaggle and includes detailed transactional information such as sales, products, customer ratings, payment methods, and timestamps.

---

## 📊 Project Overview

The main objective of this project is to extract meaningful business insights from Walmart's transactional data using Python for preprocessing and PostgreSQL for querying.

---

## 🛠 Tools & Technologies Used

- **Python**: Data cleaning, preprocessing, and database connection
- **Pandas & NumPy**: Data manipulation
- **SQLAlchemy**: Connecting Python to PostgreSQL
- **PostgreSQL**: Storing and querying the cleaned dataset
- **SQL**: Performing advanced queries for insights
- **Kaggle**: Data source
- **Jupyter Notebook**: Data exploration and transformation


---

## 🧹 Data Cleaning & Preprocessing

Performed using Python:
- Removed duplicates and null values
- Standardized column names and formats
- Converted data types appropriately (e.g., date and time columns)
- Handled inconsistent or incorrect entries
- Added derived columns like year, month, day, and hour for better analysis

---

## 🗄 Database Integration

- Created a PostgreSQL database named `walmart_db`
- Loaded the cleaned dataset into a table using **SQLAlchemy** and **Pandas**


---

## 📌 SQL Analysis & Insights

Here are the major insights generated using SQL:

1. **Payment Method Analysis**  
   Find the number of transactions and total quantity sold per payment method.

2. **Highest Rated Category per Branch**  
   Identify which category had the highest average rating in each store.

3. **Busiest Day per Branch**  
   Analyze which day of the week each branch had the most transactions.

4. **Product Rating Summary by City**  
   Evaluate average, minimum, and maximum product ratings city-wise.

5. **Category-Wise Profit Calculation**  
   Estimate total profit by category using formula: `unit_price * quantity * profit_margin`.

6. **Most Preferred Payment Method per Branch**  
   Determine which payment method was most frequently used per branch.

7. **Sales Time Slot Categorization**  
   Categorize invoices into Morning, Afternoon, and Evening slots.

8. **Revenue Drop Analysis**  
   Compare 2022 vs 2023 revenues to identify top 5 branches with the highest revenue drop ratio.



