# 🧠 Sales & Market Performance Dashboard – Bytes & Insights

A **Power BI dashboard** designed to provide a **360° view of sales performance, customer growth, and market share** for a beverage company.  
Built with a focus on interactivity, usability, and actionable insights — empowering data-driven business decisions.

---

## 🚀 Overview

This dashboard brings together multiple dimensions of sales data to answer key business questions like:

- 📈 How are sales and market share trending over time?  
- 🏢 Which regions and dealers are driving performance?  
- 👥 How many new customers are being added month over month?  
- ⚔️ What’s the company’s standing against competitors?

---

## 🧩 Key Features

- 📊 **Sales vs Market Share %** – Monthly trend analysis comparing company sales to market performance.  
- 👥 **Customer Insights** – Track total and new customers over time.  
- 🏢 **Company Share Breakdown** – Visualize competition with market share donut chart.  
- 🌍 **Regional Performance** – Compare sales across Central, Eastern, Northern, Southern & Western regions.  
- 💼 **Sales Executive Insights** – Scatter plot showing individual performance vs company’s MS%.  
- 🔍 **Dynamic Filters** – Year, Month, Region, State, Dealer, Product Category, Product Name & Bottle Size.  

---

## 🧠 Tech Stack

| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data modeling, dashboard creation |
| **DAX** | Calculated measures & KPIs |
| **Excel / CSV** | Source data |
| **Power Query** | Data transformation & cleaning |

---

## ⚙️ Explore Dashboard


🔗 **Power BI Dashboard** [Open Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmE3YzdkMWYtOGRlNy00N2I4LWExMzEtMWM3Mjc5OGY4YjVhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9) 

---

## 🧾 DAX Measures (Examples)

| **Measure Name** | **Expression** |
|------------------|----------------|
| **Sales** | `SUMX('Sales Files',[QTY_Case]+([Qty_Bottle]/[Case Size]))` |
| **Sales YTD** | `IF([ShowValueForDates],CALCULATE([Sales],DATESYTD(Calendar[Date])))` |
| **Sum of QTY_Case** | `SUM('Sales Files'[QTY_Case])` |
| **Sum of Qty_Bottle** | `SUM('Sales Files'[Qty_Bottle])` |
| **Category** | `Premium Soft Drink` |

---

## 🖼️ Dashboard Preview

![Sales Dashboard Screenshot](Sales Dashboard.jpg)

---

## 🧩 Use Cases

- Sales performance tracking  
- Customer acquisition trend analysis  
- Regional and dealer performance comparison  
- Competitive market share analysis  
- Data storytelling and executive reporting  

---


## 📬 Contact

👤 **Author:** Ankit Yadav   
🔗 **LinkedIn:** [ankityadav-info](https://linkedin.com/in/ankityadav-info)  


