# Sales Dashboard — Power BI

An interactive business intelligence dashboard built with Power BI to analyze
and monitor sales performance across regions, product categories, and order statuses.

## 📊 Dashboard Overview

The dashboard contains **2 pages**:
- **Sales** — Main KPIs and visual breakdowns
- **Tooltip** — Supporting hover details

## 🔢 Key Metrics (KPIs)

| Metric          | Value     |
|-----------------|-----------|
| Orders          | 24K       |
| Order Details   | 24K       |
| Total Freight   | 915.97K   |
| Total Amount    | $30.1M    |
| Total Tax       | 2.93M     |
| Total Due       | 33.93M    |

## 📈 Visuals Included

- **Orders by Order Date** — Line chart tracking order volume over time (2011–2013)
- **Orders by Status** — Pie chart breaking down: Approved, In Process,
  Shipped, Cancelled, Rejected, Backordered
- **Order Details by Product Category** — Treemap showing Bikes, Components,
  Clothing, and Accessories
- **Orders and Total Amount by Territory** — Combo chart across Canada,
  Northwest, France, United Kingdom, Germany, Australia, Southwest, Central

## 🗂️ Data Model — Fields Used

### DAX Measures
- Order Details, Orders, Total Amount, Total Due, Total Freight, Total Tax

### Sales Table Fields
- CustomerID, DueDate, Freight, OnlineOrderFlag, OrderDate,
  OrderDetailID, OrderID, OrderQty, Product, ProductHierarchy,
  ProductCategory, ProductID, ProductSubCategory, SalesPersonID, ShipDate

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Data modeling with relationships across Sales tables

## 📌 How to Open

1. Clone or download this repository
2. Open the `.pbix` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop)
3. Refresh data source credentials if needed

## 📷 Preview

![Dashboard Preview](preview.png)

## 📃 License

MIT License — feel free to use and adapt.
