# Pricing Promotion Strategy Dashboard

This project analyses e-commerce pricing and promotion performance to identify where discounting is supporting sales and where it is destroying profitability.

The analysis focuses on discount strategy, category profitability, product-level losses, and pricing recommendations designed to improve margin while protecting revenue.

---

## Featured Dashboard

<img src="Images/Executive Summary.png" width="800">

<img src="Images/Product & Category Risk.png" width="800">

<img src="Images/Pricing Strategy Recommendations.png" width="800">

---

## Project Overview

In this project, I built a realistic e-commerce pricing dataset and developed a Power BI dashboard to assess:

- How discounting affects profit per unit
- Which discount ranges remain commercially viable
- Which product categories are structurally unprofitable
- Which high-discount products are driving losses
- What pricing actions should be taken to improve profitability

The goal was to move beyond descriptive reporting and produce a more prescriptive, decision-focused analysis.

---

## Dataset

The dataset was synthetically generated to reflect realistic e-commerce pricing behaviour and includes:

- 12,000 orders
- 50 products across 5 categories
- Multiple acquisition channels
- Variable discounting behaviour
- Revenue, cost, profit, and profit margin metrics
- Demand sensitivity influenced by discount level

The dataset was intentionally designed to create realistic commercial tension between:

- Revenue growth
- Discounting
- Margin protection
- Category-level pricing strategy

---

## Tools Used

- Python (Pandas, NumPy) – dataset generation and validation
- Power BI – dashboard design and visualisation
- DAX – KPI and calculated metric development

---

## Key Insights

### Pricing & Discounting

- Profitability declines sharply once discounts exceed approximately 25%
- Discounts above roughly 45% frequently result in negative unit economics
- Lower discount bands generate significantly stronger profit per order than deep promotions

### Category Performance

- Electronics generates strong revenue but is structurally unprofitable
- Beauty and Accessories maintain the strongest margins at lower discount levels
- Home and Supplements remain profitable, but require more selective discounting

### Product-Level Risk

- A small number of heavily discounted products account for a disproportionate share of total losses
- Several SKUs become unprofitable when discounting exceeds 40%
- Product-level pricing discipline is required to stop unnecessary margin leakage

### Strategic Recommendations

- Reduce electronics discounting immediately, especially on products currently discounted above 40%
- Maintain lower discount ranges for Beauty and Accessories, where profitability remains strongest
- Use promotions more selectively in Home and Supplements rather than broad discounting
- Avoid deep discounting above 45% except for clearance or inventory liquidation
- Test narrower promotional ranges of 10–25% to protect margin while maintaining demand

---

## Dashboard Pages

### 1. Executive Summary
High-level overview of revenue, profit, margin, discounting, and the relationship between discount % and unit economics.

### 2. Product & Category Risk
Analysis of structurally unprofitable categories, loss-making high-discount products, and the financial impact of discount-driven losses.

### 3. Pricing Strategy Recommendations
Prescriptive pricing guidance by category, including recommended discount ranges, pricing actions, recoverable profit opportunity, and strategy recommendations.

---

## Skills Demonstrated

- Pricing and promotion analysis
- Profitability decomposition
- Category and product-level risk identification
- Prescriptive analytics and business recommendation writing
- Power BI dashboard design
- DAX-based KPI creation
- Commercial storytelling with data

---

## Conclusion

This project demonstrates how pricing and promotion analysis can move beyond performance reporting to support better commercial decision-making.

The findings highlight clear opportunities to:

- Reduce margin leakage from over-discounting
- Improve category-level pricing discipline
- Recover profit from loss-making promotional activity
- Build a more sustainable discount strategy

---

## Files

- `pricing_analysis_dashboard.pbix` – Power BI dashboard
- `pricing_orders.csv` – order-level pricing dataset
- `Notebooks/pricing_promotion_strategy_dashboard.ipynb` – Python notebook used to generate and inspect the dataset
- `Images/` – dashboard screenshots
