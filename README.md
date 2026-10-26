# SAP ERPSim | Business Analytics & Team G Performance

## Project Overview

This project presents an interactive business intelligence analysis of the SAP ERP Simulation (ERPSim) manufacturing game using Tableau.

Two complementary dashboards provide insights into **market demand, product profitability, pricing trends, sales performance, and production efficiency**.

The objective is to transform simulation data into actionable insights that support data-driven decisions across sales, production, and pricing.

## Technologies Used

- **Tableau:** Interactive dashboards, data visualization, filters, and calculated fields
- **SAP ERPSim:** Enterprise resource planning simulation data
- **Data Analysis:** Sales performance, profitability, production volume, and market demand
- **Calculated Fields:** Gross profit, price conversion, and percentage price changes

---

## Dashboard 1: Market Insights

![SAP ERPSim Market Insights](Market-Insights/Market%20Insights%20.png)

[**View Interactive Market Insights Dashboard on Tableau Public**](https://public.tableau.com/app/profile/akshata.pai/viz/SAPERMSIM-MarketInsights/MarketInsights)

### Dashboard Features

- **Market Demand by Product:** Identifies products with the highest market demand.
- **Team G Gross Profit by Product:** Highlights the most profitable products for Team G.
- **Average Market Price Trends:** Tracks product pricing across simulation rounds.
- **Regional Demand Heatmap:** Compares product demand across North, South, and West regions.
- **Interactive Filters:** Supports exploration by market region, simulation round, and product selection.

### Key Insights

- **500g Blueberry Muesli** recorded the highest overall market demand, at approximately 486K units.
- **1kg Nut Muesli** was Team G's leading product by gross profit.
- Regional demand patterns varied across product categories, highlighting opportunities for targeted inventory and sales strategies.

---

## Dashboard 2: Team G Performance

![SAP ERPSim Team G Performance](Team-G-Performance/Team%20G%20Performance.png)

[**View Interactive Team G Performance Dashboard on Tableau Public**](https://public.tableau.com/app/profile/akshata.pai/viz/ERPSIM-Dashboard1TeamG/TeamGPerformance)

### Dashboard Features

- **Sales Revenue and Gross Profit KPIs:** Summarize Team G's financial performance.
- **Most Popular Products:** Ranks products by sales quantity.
- **Most Profitable Products:** Compares product-level gross profit.
- **Production Volume by Product and Phase:** Examines production across Early, Mid, and Late phases.
- **Average Market Price Trends:** Tracks product prices over the simulation timeline.
- **Interactive Filters:** Enables exploration by product and geographic area.

### Key Insights

- **Total Sales Revenue:** Approximately $4.16M.
- **Total Gross Profit:** Approximately $3.22M.
- **500g Blueberry Muesli** was the highest-selling product, at approximately 110K units.
- **1kg Nut Muesli** generated the highest product-level gross profit, at approximately $414K.
- Production analysis highlights opportunities to align output with demand and optimize resource allocation.

---

## Business Recommendations

1. **Demand-Driven Production:** Align production planning with market demand and sales trends.
2. **Product Prioritization:** Focus on high-demand, high-margin products while reviewing underperforming products.
3. **Pricing Optimization:** Monitor market price movements to support competitive pricing decisions.
4. **Cross-Functional Coordination:** Improve alignment between sales, production, and pricing activities.

---

## Methodology and Assumptions

- Data was obtained from the SAP ERPSim manufacturing simulation.
- Gross profit was calculated as sales net value minus cost.
- Original euro-denominated financial values were converted to USD using a fixed, illustrative exchange rate of **€1 = $1.10** for dashboard presentation and comparison.
- Market Insights includes market-wide metrics alongside Team G-specific profitability.
- Production data does not contain a geographic Area dimension; therefore, production volume represents all regions and does not respond to the Area filter.
- Price change is calculated relative to the previous simulation timeline point for each product.

**Note:** Financial figures represent simulation outcomes, not actual company performance. The currency conversion is illustrative rather than a historical exchange rate.

---

## Project Structure

```text
SAP-ERPSim-Business-Analytics/
├── Market-Insights/
│   ├── Market Insight Enhanced.twbx
│   └── Market Insights .png
├── Team-G-Performance/
│   ├── Team G Performance.twbx
│   └── Team G Performance.png
└── README.md
```

## Author

**Akshata Pai**

[LinkedIn](https://www.linkedin.com/in/akshata-p-pai) | [Tableau Public](https://public.tableau.com/app/profile/akshata.pai/vizzes) | [GitHub](https://github.com/akspai2904)

*Turning data into actionable business decisions.*
