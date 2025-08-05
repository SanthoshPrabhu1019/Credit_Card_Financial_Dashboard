# 💳 Credit Card Financial Dashboard (Power BI)

## 📌 Overview

This project showcases a full-scale **Power BI dashboard** built using credit card transaction and customer demographic data. The goal is to analyze trends in customer behavior, card performance, revenue sources, and key business KPIs using powerful visual storytelling.

---

## 🗃️ Dataset Overview

We used two CSV files:

### 1. `credit_card.csv` (Transaction Data)
Contains weekly-level transaction and card usage information.


### 2. `customer.csv` (Customer Info)
Contains demographic details for each customer.


---

## 📊 Dashboard Pages & Chart Explanations

### 1. **Credit Card Transaction Report**

#### 📉 Quarterly Revenue and Transactions
- **Chart Type**: Clustered Column + Line
- **Insight**: Tracks revenue and transaction volume per quarter.
- **Usage**: Understand seasonal trends and performance.

#### 🛒 Revenue by Expenditure Type
- **Chart Type**: Bar Chart
- **Insight**: Breaks down revenue from various spending types (Bills, Travel, Grocery, etc.).
- **Usage**: Helps optimize reward categories and marketing.

#### 🎓 Revenue by Education Level
- **Chart Type**: Horizontal Bar
- **Insight**: Shows revenue grouped by customer education level.
- **Usage**: Tailor financial products based on educational background.

#### 💳 Revenue by Card Category
- **Chart Type**: Stacked Column
- **Insight**: Revenue comparison between card types (Blue, Silver, Gold, Platinum).
- **Usage**: Identify best-performing card categories.

#### 👷 Revenue by Customer Job
- **Chart Type**: Bar Chart
- **Insight**: Compares how much revenue comes from different job types.
- **Usage**: Target customer segments with high revenue potential.

---

### 2. **Customer Profile Dashboard**

#### 📅 Revenue by Week
- **Chart Type**: Line Chart
- **Insight**: Shows weekly revenue trend over the year.
- **Usage**: Detect dips/spikes in revenue.

#### 👩‍❤️‍👨 Revenue by Marital Status
- **Chart Type**: Pie/Donut
- **Insight**: How revenue is distributed between single and married individuals.
- **Usage**: Understand spending behavior by marital status.

#### 🧓 Revenue by Age Group
- **Chart Type**: Column Chart
- **Insight**: Distribution of revenue across age segments.
- **Usage**: Develop age-specific offers or campaigns.

#### 💰 Revenue by CSS (Customer Satisfaction Score)
- **Chart Type**: Column Chart
- **Insight**: Maps revenue against satisfaction score (1–5).
- **Usage**: Study if happier customers spend more.

#### 💵 Revenue by Income Group
- **Chart Type**: Column Chart
- **Insight**: Categorizes revenue by customer income range (Low, Medium, High).
- **Usage**: Validate pricing strategy and affordability.

---

## 🧮 DAX Calculations

All custom measures and calculated columns used in Power BI are documented in [`DAX_Measures.txt`](./DAX_Measures.txt).

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `credit_card.csv` | Transaction data |
| `customer.csv` | Customer demographic data |
| `sql_query.sql` | SQL schema and data loading script |
| `Credit_Card_Dashboard.pbix` | Power BI dashboard |
| `Credit_Card_Dashboard.pdf` | Export of the dashboard |
| `DAX_Measures.txt` | All DAX calculations |
| `README.md` | Project documentation (this file) |

---

## ✅ Insights & Recommendations

- **Blue cards** generated the highest revenue and interest.
- Customers with **graduate or higher education** spent the most.
- **Middle-aged groups (30–50)** contributed most of the revenue.
- Most revenue came from **Bills, Grocery, and Fuel** categories.
- Retaining **high-income customers** with high CSS could be a key growth strategy.

---

## 🚀 How to Run This Project

1. Set up the database using `sql_query.sql` (optional).
2. Open `Credit_Card_Dashboard.pbix` in Power BI.
3. Refresh the data sources if needed.
4. Explore insights using built-in filters, slicers, and charts.

---

## 🙋 Contact

Made with ❤️ by **Santhosh Prabhu**

📧 santhoshprabhu1019@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/santhosh-prabhu-67833a288/)  
🐙 [GitHub](https://github.com/SanthoshPrabhu1019)