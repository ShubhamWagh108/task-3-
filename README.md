# 🛒 E-commerce SQL Analysis

Analyze an E-commerce dataset using SQL for insights on sales, products, and customers.

## 📁 Dataset
`E-commerce Dataset.csv`  
Columns include: `Order_Date`, `Customer_Id`, `Product`, `Sales`, `Profit`, `Quantity`, `Order_Priority`, etc.

## 🛠 Setup (MySQL)

1. **Create Table**
```sql
CREATE TABLE E_Commerce (
  Order_Date DATE,
  Time TIME,
  Aging INT,
  Customer_Id INT,
  Gender VARCHAR(10),
  Device_Type VARCHAR(20),
  Customer_Login_type VARCHAR(20),
  Product_Category VARCHAR(100),
  Product VARCHAR(100),
  Sales FLOAT,
  Quantity INT,
  Discount FLOAT,
  Profit FLOAT,
  Shipping_Cost FLOAT,
  Order_Priority VARCHAR(20),
  Payment_method VARCHAR(20)
);
