# Customer RFM Segmentation & K-Means Clustering

## Overview
End-to-end customer segmentation analysis on 55,000 retail 
transactions across 8,000 customers using RFM scoring and 
K-Means clustering.

Built to demonstrate the full data analyst workflow:
data generation → cleaning → analysis → modelling → 
validation → business recommendations.

---

## Business Problem
A retail business needs to understand its customer base to:
- Identify high-value customers worth protecting
- Detect churned customers who need re-engagement
- Prioritise marketing spend more effectively
- Quantify revenue concentration risk

---

## Key Findings

### Revenue Concentration
| Segment | Customers | Revenue |
|---|---|---|
| High Value | 750 (9.9%) | £4,346,016 (56.8%) |
| Mid Value | 1,814 (24.0%) | £2,303,999 (30.1%) |
| Low Value | 3,332 (44.2%) | £889,600 (11.6%) |
| Churned | 1,650 (21.9%) | £107,419 (1.4%) |

**Top 10% of customers drive 57% of revenue.**

### Model Performance
| Metric | Score |
|---|---|
| Adjusted Rand Index | 0.72 (Strong) |
| Overall Accuracy | 89.3% |
| Churned Detection | 100% |
| High Value Detection | 89.4% |

### Business Recommendations
1. **Protect High Value customers** — loyalty programme, 
   priority service for 750 customers driving 57% revenue
2. **Re-engage Churned customers** — £2,002,548 recovery 
   potential from 1,650 inactive customers
3. **Monitor Low Value customers** — £889,600 at risk, 
   trigger alerts at 90 days inactivity
4. **Upsell Mid Value customers** — closest behavioural 
   profile to High Value, highest conversion potential
