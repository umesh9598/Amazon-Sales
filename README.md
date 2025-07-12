
# 📊 Amazon Sales Analysis – Power BI Project

## 🔍 Overview
This project analyzes sales data from the Amazon Marketplace using **Power BI**, **DAX**, and **data modeling** techniques. The objective is to identify business patterns, optimize operations, and deliver actionable insights to improve customer experience, inventory control, and profitability.

## 🎯 Problem Statement
> **Optimizing Sales Performance & Customer Fulfillment for Amazon Marketplace**  
> This dashboard helps stakeholders monitor sales performance, fulfillment efficiency, return behavior, and customer segmentation. The goal is to enhance operational decisions, marketing efforts, and logistics planning.

## ✅ Objectives
- Track and visualize sales performance by category, region, and time.
- Compare order fulfillment types (Amazon vs Merchant).
- Monitor return and cancellation trends.
- Segment customer behavior (B2B vs B2C).
- Identify inventory optimization opportunities.

## 🛠️ Tools Used
| Tool          | Purpose                           |
|---------------|-----------------------------------|
| Power BI      | Dashboard creation & data modeling |
| DAX           | Business logic and KPIs           |
| MySQL         | (Optional) Backend data extraction |
| Python        | (Optional) Data cleaning/EDA       |

## 📌 Key Metrics & DAX Measures

| KPI / Insight                     | Description                                               |
|----------------------------------|-----------------------------------------------------------|
| `Top Categories by Sales`        | Ranks highest revenue-generating product categories       |
| `Return Rate`                    | Tracks % of returned orders per total orders              |
| `On Time Delivery %`             | Measures fulfillment performance                          |
| `B2B vs B2C Sales`               | Compares revenue between business and consumer segments   |
| `Average Monthly Sales`          | Tracks average sales volume for inventory decisions       |

<details>
<summary>Click to see sample DAX</summary>

```DAX
Return Rate = 
DIVIDE(
    CALCULATE(COUNTROWS('Sales'), 'Sales'[Status] = "Returned"),
    COUNTROWS('Sales')
)
```
</details>

## 📈 Sample Visualizations
- Sales by Category (Bar Chart)
- Monthly Sales Trends (Line Chart)
- B2B vs B2C Comparison (Stacked Column)
- Fulfillment Breakdown (Donut Chart)
- Return & Cancellation Heatmap (Matrix/Table)

## 📂 Files in This Repo
| File Name                                      | Description                          |
|-----------------------------------------------|--------------------------------------|
| `Amazon_Sales.pbix`                           | Power BI project file                |
| `Amazon_Sales_Project_Problem_Statement.pdf`  | Clear business problem definition    |
| `Amazon_Sales_Detailed_Project_Report.pdf`    | Full report with objectives, DAX, and outcomes |

## 🚀 How to Use
1. Clone or download this repository.
2. Open `Amazon_Sales.pbix` in Power BI Desktop.
3. Explore the dashboards, interact with filters, and review DAX formulas.

## 📚 Learning Outcomes
- Real-world BI reporting with interactive visuals
- Business-centric KPIs and storytelling
- Hands-on DAX experience
- Communication of insights to non-technical stakeholders

## 🙋‍♂️ About Me
I’m an aspiring data analyst with skills in **Power BI**, **Python**, and **SQL**, building end-to-end projects to develop job-ready expertise.  
📫 Connect with me on [LinkedIn](https://www.linkedin.com/) | 📁 [More Projects](#)
