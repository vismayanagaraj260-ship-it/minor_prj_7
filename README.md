# QuickCart Market Basket Analysis

## Project Overview
This project uses Market Basket Analysis to identify products that are frequently purchased together. It applies the Apriori and FP-Growth algorithms to discover frequent itemsets and association rules from retail transaction data.

## Dataset
- **Product line items:** 26,878
- **Orders:** 5,000
- **Stores:** 12
- **Unique products:** 60
- **Date range:** November 1–30, 2026

## Objectives
- Identify frequently purchased product combinations.
- Generate association rules using support, confidence, and lift.
- Compare Apriori and FP-Growth.
- Identify actionable patterns for retail business decisions.
- Visualize important findings.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Mlxtend
- Jupyter Notebook

## Methodology
1. Loaded and explored the transaction dataset.
2. Created a basket matrix for product-level analysis.
3. Applied Apriori and FP-Growth with a minimum support threshold of 0.02.
4. Generated 980 association rules using a minimum lift threshold of 1.0.
5. Filtered 42 actionable rules using support greater than 0.05 and lift greater than 2.
6. Created visualizations and exported the results to CSV files.

## Key Findings
- Toned milk and white bread showed a strong purchasing association.
- Potato chips and cola showed a strong snack-and-drink association.
- Ghee and poha had a lift of approximately 5.07.
- The results suggest opportunities to explore product bundling, cross-selling, and product placement.

## Repository Contents
- Jupyter Notebook containing the analysis
- Frequent itemsets CSV files
- Association rules CSV files
- Actionable rules CSV file
- Visualizations generated during the analysis

## Conclusion
This project demonstrates how association rule mining can uncover purchasing patterns and support data-driven retail decisions.

**Note:** Association rules identify relationships in transaction data; they do not establish causation.
