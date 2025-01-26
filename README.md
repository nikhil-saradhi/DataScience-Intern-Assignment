# eCommerce Transactions Dataset Analysis

## Overview
This project analyzes an eCommerce Transactions dataset to perform the following tasks:
1. **Exploratory Data Analysis (EDA)**: Extract trends and actionable insights.
2. **Lookalike Model**: Recommend similar customers based on profiles and transaction history.
3. **Customer Segmentation**: Cluster customers into meaningful groups using clustering techniques.

The dataset includes three files:
- **Customers.csv**: Contains customer information.
- **Products.csv**: Contains product details.
- **Transactions.csv**: Contains transaction records.

---

## Dataset Description

### 1. Customers.csv
- `CustomerID`: Unique identifier for each customer.
- `CustomerName`: Name of the customer.
- `Region`: Continent of residence.
- `SignupDate`: Customer's signup date.

### 2. Products.csv
- `ProductID`: Unique identifier for each product.
- `ProductName`: Name of the product.
- `Category`: Product category.
- `Price`: Product price in USD.

### 3. Transactions.csv
- `TransactionID`: Unique identifier for each transaction.
- `CustomerID`: ID of the customer involved in the transaction.
- `ProductID`: ID of the purchased product.
- `TransactionDate`: Date of the transaction.
- `Quantity`: Quantity purchased.
- `TotalValue`: Total transaction value.
- `Price`: Price of the product during the transaction.

---

## Project Tasks

### **Task 1: Exploratory Data Analysis (EDA)**
- Analyze the dataset for trends, patterns, and anomalies.
- Derive five actionable business insights.

**Deliverables**:
- `FirstName_LastName_EDA.ipynb`
- `FirstName_LastName_EDA.pdf`

---

### **Task 2: Lookalike Model**
- Build a recommendation system to identify and rank the top 3 similar customers for a given user based on their profiles and transaction data.

**Deliverables**:
- `FirstName_LastName_Lookalike.ipynb`
- `FirstName_LastName_Lookalike.csv` (contains CustomerIDs and their top 3 lookalikes with similarity scores).

---

### **Task 3: Customer Segmentation**
- Perform clustering using customer profiles and transaction data.
- Calculate clustering metrics (DB Index) and visualize clusters.

**Deliverables**:
- `FirstName_LastName_Clustering.ipynb`
- `FirstName_LastName_Clustering.pdf`

---


