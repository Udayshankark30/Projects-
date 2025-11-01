# 🛒 Blinkit Sales Analysis Dashboard (Power BI)

## 📘 Overview
This Power BI project provides a comprehensive analysis of **Blinkit's sales performance** across multiple outlets and product categories.  
It helps stakeholders understand key trends, identify top-performing items, and make data-driven decisions to improve business outcomes.

---

## 🎯 Objective
To analyze Blinkit’s sales data and uncover insights about:
- Which product categories contribute most to overall sales  
- The impact of **fat content (Regular vs Low Fat)** on sales  
- Performance of different **outlet types, sizes, and establishment years**  
- Identifying **underperforming items** with high visibility but low sales  

---

## 📊 Key Insights
- **Top Categories:** Certain product categories drive the majority of total revenue.  
- **Fat Content Influence:** Regular fat products tend to sell more than low-fat ones.  
- **Outlet Analysis:** Tier 3 outlets show significant sales growth in recent years.  
- **Product Visibility:** Several items with high visibility have lower sales, indicating possible pricing or placement issues.  

---

## 🧩 Tools & Techniques Used
- **Power BI** – for data visualization and dashboard design  
- **DAX Functions** – for calculated measures and KPIs  
- **Data Cleaning & Transformation** – using Power Query Editor  
- **Excel/CSV Dataset** – as the source of sales data  

---

## 🧠 DAX Measures Implemented
- **Total Sales** = `SUM(Sales[NetAmount])`  
- **Average Sales per Outlet** = `AVERAGE(Sales[NetAmount])`  
- **Category-wise Sales** = `SUMX(FILTER(...), ...)`  
- **Sales Growth by Year** using `CALCULATE` and `YEAR()` functions  

---

## 📈 Dashboard Preview
![Screenshot (110).png](attachment:fec99752-8388-4436-b812-16f81a592d58.png)
---

## ⚙️ How to Use
1. Download the `.pbix` file from this repository.  
2. Open it in **Microsoft Power BI Desktop**.  
3. Explore filters, slicers, and visualizations for interactive insights.  

---

## 📍 Conclusion
The dashboard enables quick and intuitive decision-making for marketing and sales teams.  
It highlights key sales drivers, underperforming areas, and growth opportunities for Blinkit’s retail business.

---

## 💡 Future Improvements
- Add customer segmentation and purchase frequency analysis  
- Include predictive insights using Power BI + Python integration  
- Automate data refresh using Power BI Service  

---

## 🧾 Author
**KAKUMANU UDAY SHANKAR**
📧 kudayshakar30@gmail.com  
💻 *Data Analyst | Power BI Developer | SQL Enthusiast*  
