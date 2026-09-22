# Tata-Data-Visualization-Forage-Tableau 


![image alt](https://github.com/AnkitaSarkar-98/Tata-Data-Visualization-Forage-Tableau/blob/main/Certificate.png?raw=true)


## Project Overview

This project was completed as part of the **TATA Data Visualisation: Empowering Business with Effective Insights** virtual experience program on Forage.

The objective of this project was to analyse an online retail dataset and create business-focused visualisations to answer key questions from the CEO and CMO.

The analysis focused on revenue trends, international markets, high-value customers, and product demand across countries.

---

## Business Objective

The analysis was designed to provide actionable insights for business decision-making in the following areas:

- Monthly revenue trends and seasonality
- International revenue performance
- High-value customer identification
- Product demand across international markets

The analysis was presented from the perspective of a Data Analyst communicating insights to senior business stakeholders.

---

## Dataset

The project uses an online retail transaction dataset provided as part of the TATA Forage virtual experience.

The dataset contains transaction-level information including:

- Invoice / Transaction information
- Invoice Date
- Customer ID
- Country
- Quantity
- Unit Price

The original dataset contained return transactions represented by negative quantities and some invalid unit-price values.

---

## Data Cleaning

Before creating the visualisations, the dataset was checked and cleaned according to the project requirements.

### Cleaning Rules

The following validation rules were applied:

- Quantity should not be below 1.
- Unit Price should not be below 0.

Records that did not satisfy these conditions were excluded from the analysis.

This cleaning step was important because negative quantities and invalid prices could distort revenue, quantity, customer, and geographic analysis.

---

## Analysis Performed

Four business questions were analysed and visualised.

### Q1 – Monthly Revenue Trend

The first analysis examined monthly revenue for **2011**.

The objective was to identify:

- Monthly revenue trends
- Seasonal patterns
- High and low revenue periods
- Potential implications for future forecasting and planning

The analysis showed a strong increase in revenue during the later part of the year, with **November being the highest-revenue month** in the analysed period.

---

### Q2 – Top 10 Countries by Revenue

The second analysis identified the **top 10 countries generating the highest revenue**, excluding the United Kingdom.

Both revenue and quantity sold were analysed.

Key observations included strong revenue contribution from international markets such as:

- Netherlands
- Ireland
- Germany
- France
- Australia

Revenue and quantity were compared together to provide a broader understanding of international market performance.

---

### Q3 – Top 10 Customers by Revenue

The third analysis identified the **top 10 customers by revenue**.

Customers were arranged from the highest revenue contribution to the lowest.

The purpose was to identify high-value customers who could be considered for targeted retention and engagement activities.

Customer 14646 was the highest revenue-generating customer in the visualisation, followed by customers such as 18102 and 17450.

---

### Q4 – International Product Demand

The fourth analysis examined product demand across countries while excluding the United Kingdom.

The objective was to identify international markets with higher product demand and potential opportunities for further business expansion.

Countries such as Australia, Sweden and Japan showed notable demand in the analysis.

The visualisation provides a geographic view of demand across international markets.

---

## Key Business Insights

The analysis highlighted four main insights:

1. **Revenue Seasonality**
   
   Revenue increased significantly toward the later months of 2011, with November representing the highest-revenue month.

2. **International Markets**
   
   Several international countries generated substantial revenue after excluding the United Kingdom, with the Netherlands, Ireland, Germany and France among the stronger markets in the analysis.

3. **High-Value Customers**
   
   A relatively small group of customers contributed significant revenue, highlighting the importance of monitoring and retaining high-value customers.

4. **International Demand**
   
   Product demand was not evenly distributed across countries. Several international markets showed higher demand and can be considered for further market analysis.

---

## Business Recommendations

Based on the analysis:

- Prepare inventory and operational capacity ahead of high-demand seasonal periods.
- Monitor international markets with strong revenue and quantity performance.
- Develop targeted retention and engagement strategies for high-value customers.
- Investigate international markets with strong product demand before making expansion decisions.
- Combine revenue and demand analysis with additional business metrics such as profitability, logistics cost, customer acquisition cost and marketing performance before making major investment decisions.

---

## Tools & Technologies

- **Microsoft Excel**
- **Tableau**
- **Data Cleaning**
- **Data Visualisation**
- **Business Analysis**

---

## Project Deliverables

This repository contains the project work and supporting documentation.

Suggested repository contents:

```text
Tata-Data-Visualisation-Forage/
│
├── README.md
│
├── Project/
│   ├── Tata_Data_Visualisation.pdf
│   ├── Dashboard/
│   │   ├── Q1_Monthly_Revenue.png
│   │   ├── Q2_Top_10_Countries.png
│   │   ├── Q3_Top_10_Customers.png
│   │   └── Q4_International_Demand.png
│   │
│   └── Presentation/
│       └── Presentation_Script.pdf
│
└── Screenshots/
    ├── Q1.png
    ├── Q2.png
    ├── Q3.png
    └── Q4.png
```

## Conclusion

To conclude, the analysis highlights four key findings.

First, 2011 revenue shows a strong increase toward the final quarter, with November being the peak month.

Second, outside the UK, the Netherlands, Ireland, Germany and France are among the strongest revenue-generating markets in the visual.

Third, a relatively small group of high-value customers contributes substantial revenue, making customer retention an important consideration.

And finally, the global demand analysis highlights markets such as Australia, Sweden and Japan where product demand is visible outside the UK.

These insights can support decisions around seasonal planning, international marketing, customer retention and potential market expansion.
