# Laptop Price Determination Analysis

This project investigates the key factors influencing laptop prices to assist companies like Cityville Electronics in developing effective pricing strategies. Using a dataset of over 1,000 laptop entries, the study evaluates how variables such as processor tier, brand, core count, and RAM impact pricing dynamics.

---

## Project Overview
The study explores the following key question:
- What are the most significant factors affecting laptop prices, and how do these factors interact?

This analysis aims to deliver actionable insights into the pricing strategies of laptops by focusing on both technical specifications and brand value.

---

## Key Findings
1. **Processor Tiers**:
   - Higher-tier processors (e.g., i7, i9) significantly increase laptop prices.
   - Statistical significance confirmed with p-values < 0.001.

2. **Brand Reputation**:
   - Brands like Asus, Dell, HP, and Lenovo command premium prices, with positive coefficients indicating strong brand influence.

3. **Core Count and RAM**:
   - Higher core counts and larger RAM capacities correlate with increased pricing, reflecting performance valuation in the market.

4. **Model Fit**:
   - The final multiple linear regression model explains approximately 82% of the price variance (R² = 0.8216).
   - The F-statistic is highly significant (p < 2.2e-16), demonstrating strong model reliability.
     
---

## Methods
### Data Collection:
- Dataset: Over 1,000 laptop entries, including variables such as brand, processor tier, core count, RAM memory, and price.

### Analysis Techniques:
- Multiple linear regression with backward elimination to refine the model.
- Log transformation to improve linearity and homoscedasticity.
- ANOVA performed to validate variable significance.

### Diagnostics:
- Assumptions of independence, linearity, homoscedasticity, and normality checked using residual plots, Q-Q plots, and boxplots.
  
---

## Contributions
- **JooHyeok Seo**: Defined study objectives, analyzed results, and interpreted key factors affecting pricing.
- **Vincent Putra**: Conducted diagnostic checks and data transformations, ensuring model reliability.
- **Bhavana**: Performed ANOVA, backward elimination, and model validation.
- **Patrick**: Summarized findings, discussed limitations, and provided future research directions.
  
---

## Future Work
- Expand dataset to include more entries for improved generalizability.
- Introduce additional variables, such as product design and marketing strategies.
- Optimize modeling techniques for better interpretability and precision.
  
---

## Tools Used
- **R**: Statistical analysis, regression modeling, and diagnostics.
- **Excel**: Data preprocessing and basic visualizations.

---

## Files in This Repository
- Laptop_Price_Analysis_Presentation.pdf: Summarized findings in presentation format.
- Laptop_Price_Analysis_Report.pdf: Comprehensive report detailing methodology, analysis, and conclusions.

