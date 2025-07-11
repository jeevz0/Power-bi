# 📁 Dataset Documentation – SuperStore Sales Dashboard

This dataset powers the Power BI report `PROJECT1.pbix`, focused on analyzing sales performance, customer behavior, and product trends. The data is structured, cleaned, and modeled in Power BI using Power Query and DAX.

---

## 📦 Dataset: SuperStore_Sales_Dataset.csv

**Description:**  
This dataset contains transactional-level sales data from a global superstore, capturing details related to customers, orders, geography, and product sales.

---

### 🔑 Key Fields

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `Order ID`          | Unique identifier for each order                                            |
| `Order Date`        | Date when the order was placed                                              |
| `Ship Date`         | Date when the order was shipped                                             |
| `Ship Mode`         | Shipping method chosen by the customer                                     |
| `Customer ID`       | Unique identifier for each customer                                         |
| `Customer Name`     | Full name of the customer                                                   |
| `Segment`           | Customer segment (e.g., Consumer, Corporate, Home Office)                  |
| `Country`           | Country where the order was shipped                                         |
| `City`              | City of the customer                                                        |
| `State`             | State or province                                                           |
| `Postal Code`       | ZIP or postal code                                                          |
| `Region`            | Geographical region (e.g., East, West, Central, South)                      |
| `Product ID`        | Unique product identifier                                                   |
| `Category`          | Product category (e.g., Furniture, Office Supplies, Technology)             |
| `Sub-Category`      | More detailed product classification (e.g., Chairs, Phones, Binders)        |
| `Product Name`      | Name of the product                                                         |
| `Sales`             | Total sales amount (in USD)                                                 |
| `Quantity`          | Number of units sold                                                        |
| `Discount`          | Discount applied to the product                                             |
| `Profit`            | Net profit from the sale                                                    |

---

### 🛠️ Preprocessing Performed in Power BI

- Handled missing values in `Postal Code` and `Profit`
- Converted `Order Date` and `Ship Date` to date format
- Created new columns using DAX (e.g., `Year`, `Month`, `Profit Margin`)
- Added calculated measures such as:
  - Total Sales
  - Total Profit
  - Profit Ratio
  - Sales by Region/Product Segment

---

### 📌 Use in Power BI Dashboard

This dataset is used to:
- Visualize KPIs (Sales, Profit, Quantity, Discount)
- Analyze sales trends over time
- Explore customer segments and regional performance
- Identify top-selling and least-performing products
- Monitor discount impact on profitability

---

## 📬 Contact

For dataset-related queries or collaborations, reach out at **jeevz0211@gmail.com**.

