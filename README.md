# FUTURE_DS_01
Developed an interactive Power BI dashboard to visualize and analyze key E-commerce sales metrics for better business insights.


# 📊 E-Commerce Sales Dashboard (Power BI)

This Power BI dashboard provides a detailed analysis of e-commerce sales data across various countries, months, and product categories. The visualizations help identify trends, performance by region, top products, and revenue insights.


---

## 📌 Features Included

✅ KPI Cards:
- Total Revenue
- Total Orders
- Average Order Value

📈 Charts & Graphs:
- Line chart showing Monthly Revenue Trends
- Donut chart: Total Revenue by Product Description
- Bar chart: Quantity Sold by Product Description
- Table: Revenue by Country

🎨 Design:
- Dark theme for visual comfort
- Branded header: "E-Commerce Sales Dashboard"
- Clean layout with consistent formatting and spacing

---

## 📂 Folder Structure

```
📁 E-Commerce-Sales-Dashboard
├── README.md
├── E Commerce Sales Dashboard.pbix
├── E Commerce Sales Dataset

```

---

## 🛠 Built With

- Power BI Desktop
- DAX Measures
- E Commerce Sales Dataset
- Custom Themes and Visualizations

---

## 📈 Measures Used

- `Total Revenue = SUMX(SalesData_AllYears, SalesData_AllYears[Quantity] * SalesData_AllYears[Price])`
- `Total Orders = DISTINCTCOUNT(SalesData_AllYears[Invoice])`
- `Average Order Value = [Total Revenue] / [Total Orders]`

---

## 🧭 Insights You Can Gain

- Identify top-performing countries by revenue
- Discover popular product categories
- Track monthly sales growth/decline

---


## 📬 Contact

For feedback, collaboration, or questions, feel free to connect!

