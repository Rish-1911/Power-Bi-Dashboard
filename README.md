# 📊 Online Retail Analysis Dashboard using Power BI

This Power BI project analyzes an online retail dataset to uncover key business insights and support strategic decision-making. The dashboard answers targeted questions raised by the CEO and CMO, such as customer segmentation, sales trends, and geographic performance.

---

# 🛠️ Tools Used
- **Microsoft Power BI**
- **Microsoft Excel** (for preprocessing)

---

# 📁 Dataset
The dataset contains transaction-level details from an online retail store, including:
- Invoice Number
- Invoice Date
- Customer ID
- Country
- Product Description
- Quantity
- Unit Price

---

# 🔍 Business Questions Answered

# 1. 📅 Monthly Revenue Trend for 2011  
**Stakeholder**: CEO  
> Time-series line chart displays how revenue varied month-by-month in 2011.

# 2. 🌍 Top 10 Countries by Revenue & Quantity (Excluding UK)  
**Stakeholder**: CMO  
> Horizontal bar chart compares the top countries by sales and product volume, excluding the dominant UK market.

# 3. 👥 Top 10 Customers by Revenue  
**Stakeholder**: CMO  
> Identifies top revenue-contributing customers to support targeted marketing.

# 4. 🗺️ Country-wise Product Demand  
**Stakeholder**: CEO  
> World map visualization shows demand patterns across countries, excluding UK, to identify expansion potential.

---

# 🧼 Data Cleaning Steps
- Filtered only 2011 transactions
- Removed rows with:
  - Missing `CustomerID`
  - Negative or zero `Quantity`
- Added `Revenue = Quantity × UnitPrice`
- Extracted Month-Year from `InvoiceDate`

---

# ✅ Key Insights
- Revenue peaks in November 2011 – possibly due to seasonal sales.
- Netherlands, Germany, and France emerged as promising markets (excluding UK).
- A few customers contribute disproportionately to revenue.
- Certain countries show high quantity sales with lower revenue, hinting at volume-based strategies.
