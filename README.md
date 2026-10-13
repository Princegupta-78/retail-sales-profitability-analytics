# Retail Sales & Profitability Analytics

## Overview
An exploratory data analytics project that examines retail sales, profitability, regional performance, product categories, and discount patterns to support data-driven business decisions.

## Business Objective
The goal is to understand which product categories and regions contribute to sales and profit, identify loss-making subcategories, and investigate how discount levels relate to profitability.

## Tech Stack
- **Python** — data analysis
- **Pandas & NumPy** — data manipulation and cleaning
- **SQLite & SQL** — business queries and aggregations
- **Matplotlib** — data visualization
- **Google Colab** — notebook development

## Dataset
Sample Superstore retail transaction dataset.

Source: [Kaggle — Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The notebook prompts the user to upload the CSV dataset before running the analysis.

## Analysis Performed
- Inspected data types, missing values, and duplicate records.
- Cleaned date and numeric columns.
- Calculated total sales, total profit, unique orders, and profit margin.
- Compared sales and profit across geographic regions.
- Evaluated product category performance using SQL.
- Investigated average sales and profit across discount bands.
- Visualized category profitability and monthly sales trends.
- Identified loss-making product subcategories using SQL aggregation.

## Key Findings

- **Regional performance:** The West region recorded the highest sales ($725,457.82) and profit ($108,418.45), while Central generated the lowest regional profit ($39,706.36).
- **Category performance:** Technology delivered the highest profit ($145,454.95), followed by Office Supplies ($122,490.80). Furniture generated $741,999.80 in sales but only $18,451.27 in profit.
- **Subcategory losses:** Tables recorded the largest loss ($17,725.48), followed by Bookcases ($3,472.56) and Supplies ($1,189.10).

## Business Recommendations

- Investigate regional differences in product mix, discounting, and profitability.
- Review Furniture margins to understand why substantial sales translate into comparatively low profit.
- Examine Tables' pricing, discount levels, and costs to identify potential causes of losses.
- Validate potential improvements against further product-level and transaction-level analysis before implementing changes.

## Key Business Questions
1. Which regions generate the highest total profit?
2. Which product categories contribute most to sales and profitability?
3. Which subcategories report negative total profit?
4. How does average profit vary across discount bands?
5. How do sales change over time?

## Business Recommendations
Recommendations should be based on the actual analysis results. Potential actions to investigate include reviewing discount policies, examining loss-making subcategories, and comparing regional performance before allocating additional resources.

## How to Run
1. Open `Retail_Sales_Profitability_Analysis.ipynb`.
2. Launch the notebook in Google Colab.
3. Upload the Sample Superstore CSV when prompted.
4. Run the notebook cells in order.
5. Review the SQL query outputs, KPIs, and visualizations.

## Limitations
- The analysis is exploratory and uses a sample retail dataset.
- Observed associations do not establish causation.
- Findings should be validated against business context before making operational decisions.

## Author
Prince Gupta

GitHub: [Princegupta-78](https://github.com/Princegupta-78)
