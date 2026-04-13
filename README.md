# Banking Customer Credit & Segment Analysis 🏦💳

## Project Overview
This project focuses on analyzing customer financial data within a banking or large-scale wholesale context. By examining credit limits and purchasing groups across different U.S. states, the analysis provides insights into regional financial strength, credit risk distribution, and the market share of major buying groups like "Tailspin Toys" and "Wingtip Toys."

## Project Workflow
The repository follows a structured data engineering and analysis path:

1.  **Raw Data (`Data Before Cleaning`):** Contains raw customer records with complex formatting, including unformatted credit limits (e.g., "? 100,000.00"), technical lineage keys, and redundant timestamp information.
2.  **Processed Data (`Data After Cleaning`):** A refined version of the dataset where:
    * **Credit Limits** were converted to clean numerical values.
    * **State Extraction:** Locations were parsed to identify specific states (e.g., TX, PA, NY, CA).
    * **Standardization:** Customer names and primary contacts were sanitized for accurate reporting.
3.  **Core Metrics (`Measures`):** Financial aggregations and statistical analysis, including:
    * **Credit Distribution:** Total credit limit analyzed (~$39.9M) across all customer segments.
    * **Group Benchmarking:** Comparing "Wingtip Toys" (Average Credit: ~$100.5K) versus "Tailspin Toys" (Average Credit: ~$98.5K).
    * **Regional Rankings:** Identifying top states by total credit, with Texas (TX) and Pennsylvania (PA) leading the portfolio.
    * **State-Level Averages:** Calculating the average credit limit per customer in specific regions to identify high-value hubs.

## Key Insights Analyzed
- **Market Segmentation:** Analyzing the count and financial weight of different buying groups to understand corporate client dominance.
- **Regional Financial Health:** Mapping total credit limits by state to visualize where the largest financial exposures or opportunities lie.
- **Credit Limit Profiling:** Investigating the frequency of credit tiers (e.g., $100k vs $5k limits) across the customer base.
- **Data Quality Improvement:** Transforming raw, technical "Lineage Keys" and "WWI IDs" into a business-ready analytical format.

## Tools Used
- **Microsoft Excel:** For advanced data cleaning (Power Query), formula-based data extraction, and pivot table modeling.
- **Financial Modeling:** Used to determine average credit exposure and regional contribution percentages.

## How to Explore
- Open `Data After Cleaning.csv` to view the structured financial profiles of the 401 analyzed customers.
- Consult `Measures.csv` for the final summary of credit limits by state and buying group.

---
*Developed as part of a Financial Data Analytics portfolio.*
