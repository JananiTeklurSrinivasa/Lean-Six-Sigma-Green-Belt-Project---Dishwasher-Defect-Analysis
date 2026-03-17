# Lean-Six-Sigma-Green-Belt-Project---Dishwasher-Defect-Analysis

This project applies Lean Six Sigma DMAIC methodology to reduce the percentage of dishes coming out dirty from a dishwasher process.

---

## Problem Statement

- Current defect rate: **10.48% of dishes require re-washing**
- Goal: Reduce defects to **5%**
- Impact: Reduce rework, save detergent cost, and improve time efficiency

---

## Methodology (DMAIC)

### Define
- Identified high defect rate in dishwashing process
- Defined Y metric: % of dishes coming out dirty

### Measure
- Collected data across multiple dishwasher loads
- Key variables:
  - Number of dishes (top/bottom rack)
  - Pod type (Cascade vs Finish)
  - Wash cycle (Light, Normal, Heavy)
  - Greasy dishes, pre-scrubbing behavior

### Analyze
- Conducted:
  - Fishbone (Ishikawa) Diagram for root causes
  - Pareto Analysis to identify major contributors
  - Correlation Analysis
  - Regression Analysis
  - ANOVA testing

#### Key Insights:
- Cascade pods contributed to ~80% of defects
- Heavy and Normal cycles showed higher defect rates
- Load distribution (top vs bottom rack) impacted outcomes
- Weak correlation overall, but statistically significant drivers identified

---

## Results & Findings

- Baseline defect rate: **10.48%**
- Sigma Level: ~2.74
- Identified key drivers:
  - Pod Brand (statistically significant)
  - Wash cycle selection
  - Load distribution

---

## Recommendations

1. **Switch to Finish Pods**
   - Reduced defects to ~5.16%
   - Lower cost per pod

2. **Avoid Light Cycle with Cascade**
   - Causes up to ~21% defects

3. **Improve Load Distribution**
   - Increase usage of top rack
   - Avoid overloading bottom rack

---

## Impact

- Reduced defect rate toward target of 5%
- Lower detergent costs
- Reduced manual rework
- Improved process efficiency

---

## Tools & Techniques

- R (statistical analysis, regression, correlation)
- Excel (data collection, analysis)
- Lean Six Sigma (DMAIC framework)
- Fishbone Diagram, Pareto Charts, ANOVA, Regression

---

## Dataset

- 56 dishwasher load samples collected over ~6 weeks
- Variables include load size, wash cycle, pod type, grease levels, and defect rates

---

## Author

Janani Teklur Srinivasa
