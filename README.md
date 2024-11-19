# Laptop Price Determination Analysis
This project investigates the key factors influencing laptop prices to assist companies like Cityville Electronics in developing effective pricing strategies. By analyzing a dataset containing over 1,000 laptop entries, this study explores how variables such as processor tier, brand, number of cores, and RAM memory impact pricing.

## Project Overview
The primary research question addressed in this study is:
- **What are the most significant factors affecting laptop sales prices, and how do these factors interact?**
This project aims to provide actionable insights into the laptop market's pricing dynamics by examining technical specifications and brand value.

## Key Findings
1. **Processor Tiers**:
   - Higher-tier processors (i7, i9) significantly increase laptop prices.
   - Statistical significance confirmed with p-values < 0.001.

2. **Brand Reputation**:
   - Brands like Asus, Dell, HP, and Lenovo command premium prices.
   - Positive coefficients indicate the strong influence of brand recognition.

3. **Core Count and RAM**:
   - Higher core counts and larger RAM capacities correlate with higher prices, highlighting the market's valuation of performance.

4. **Model Fit**:
   - The final multiple linear regression model explains approximately **82% of the price variance** (R² = 0.8216).
   - The F-statistic is highly significant (p < 2.2e-16), indicating strong model reliability.

---

## Methods
### Data Collection:
- Dataset includes over 1,000 laptop entries from Cityville Electronics.
- Variables include brand, processor tier, number of cores, RAM memory, and price.

### Analysis Techniques:
- Multiple linear regression with backward elimination.
- Log transformation applied to ensure linearity and homoscedasticity.
- ANOVA performed to validate variable significance.

### Diagnostics:
- Assumptions of independence, linearity, homoscedasticity, and normality were checked using residual plots, QQ plots, and boxplots.

---

## Files in This Repository
- `Laptop_Price_Analysis_Presentation.pdf`: Presentation slides summarizing the project findings.
- `Laptop_Price_Analysis_Report.pdf`: A comprehensive report detailing the methodology, analysis, and results.

---

## Contributions
- **JooHyeok Seo**: Introduction and Results. Defined study objectives, analyzed results, and interpreted key factors affecting pricing.
- **Vincent Putra**: Diagnostics. Evaluated regression model assumptions, conducted data transformations, and prepared diagnostic plots.
- **Bhavana**: Model Validation. Applied backward elimination, performed ANOVA, and assessed model fit.
- **Patrick**: Conclusion and Discussion. Summarized findings, discussed limitations, and suggested future research directions.

---

## Future Work
- Expand sample scope to improve generalizability.
- Include additional variables like product design and marketing strategies.
- Optimize modeling techniques for better interpretability.

---

## Tools Used
- **R**: Data analysis, regression modeling, and statistical tests.
- **Excel**: Data preprocessing and visualization.

---

This project demonstrates how technical specifications and brand value drive laptop prices, providing strategic insights for businesses in the competitive electronics market.
