# Insurance Auto Data Analysis Report

## Summary

This Analysis presents the findings of an auto insurance claims analysis conducted in April 2025. Based on a comprehensive assessment of performance metrics across four branch cities (Pune, Kolkata, Ranchi, and Guwahati), **KOLKATA** has been identified as the recommended branch for closure due to its consistently poor financial performance.

## Key Findings for Kolkata

Kolkata demonstrates the worst financial performance among all branches, characterized by:

- **Highest Loss Ratio of 4.54**: This means for every ₹1 collected in premiums, the branch is paying out ₹4.54 in claims, making it significantly more unprofitable than other branches
- **Substantial Financial Loss of ₹496,112.79**: Despite handling the fewest claims (16)
- **Low Premium Generation of ₹140,279.78**: The lowest among all branches
- **0% Rejection Rate**: Unlike other branches that have rejection rates between 8-12%, suggesting potential underwriting or claims assessment issues
- **High Average Claim Payout**: Highest average paid amount per claim

## Comparative Analysis of All Branches

| Metric | PUNE | KOLKATA | RANCHI | GUWAHATI |
|--------|------|---------|--------|----------|
| Total Claims | 37 | 16 | 17 | 24 |
| Total Claim Amount (₹) | 1,543,919.00 | 847,893.00 | 570,328.00 | 1,148,030.00 |
| Total Premium (₹) | 369,254.79 | 140,279.78 | 148,858.60 | 261,314.84 |
| Total Paid Amount (₹) | 1,093,273.28 | 636,392.57 | 401,142.67 | 753,189.43 |
| Rejected Claims | 3 | 0 | 2 | 3 |
| Rejection Rate | 8.11% | 0.00% | 11.76% | 12.50% |
| Profit/Loss (₹) | -724,018.49 | -496,112.79 | -252,284.07 | -491,874.59 |
| Loss Ratio | 2.96 | 4.54 | 2.69 | 2.88 |

## Rationale for Kolkata Branch Closure

1. **Highest Loss Ratio (4.54)**: Kolkata's loss ratio is significantly higher than the other branches, which range from 2.69 to 2.96. This indicates a fundamental imbalance between premiums collected and claims paid.

2. **Zero Claim Rejections**: While other branches reject 8-12% of claims, Kolkata approved 100% of claims. This anomaly suggests potential issues with claim assessment procedures or underwriting policies unique to this branch.

3. **Highest Average Claim Payout**: Kolkata pays an average of ₹39,774.54 per claim, which is higher than other branches:
   - Pune: ₹29,547.93
   - Ranchi: ₹23,596.63
   - Guwahati: ₹31,382.89

4. **Lowest Business Volume**: With only 16 claims, Kolkata has the lowest business volume, making it the least impactful branch to close in terms of customer reach.

5. **Inefficient Premium Collection**: Despite high claim payouts, Kolkata collects the lowest premium amounts, suggesting potential pricing or market positioning issues.

## Scoring Methodology

The recommendation was determined based on a multi-factor scoring system that evaluated:
- Profitability (with lower profit resulting in lower scores)
- Loss ratio (with higher ratios resulting in lower scores)
- Total claims (with lower claims resulting in lower scores as an indicator of business volume)

Kolkata consistently scored lowest across these metrics, making it the clear candidate for closure.

## Technical Implementation

This analysis was performed using Python with data processing and statistical analysis functions. The implementation includes:
- Data cleaning and preprocessing
- Rejection classification
- City-wise statistical analysis
- Visualization generation
- Decision recommendation based on objective metrics

