# Employee Attrition Analytics

Business intelligence and predictive analytics project that finds which employees are most likely to leave and what a company can do about it. CIS 3252W (Business Intelligence), Cal Poly Pomona, April 2026.

**Methods:** CRISP-DM, descriptive analytics, logistic regression

## Data

[IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) on Kaggle. 1,470 employees, 35 variables, no missing values. Attrition rate: 16.1%.

## Results

| Metric | Value |
|--------|-------|
| Accuracy | 86.1% |
| AUC | 0.730 |
| Precision | 80.0% |

Key findings:

- Overtime is the strongest predictor. Employees who work overtime are 4.2x more likely to leave (p < .001).
- Higher job satisfaction (OR 0.736), better work-life balance (OR 0.676), and longer tenure (OR 0.942) all lower attrition risk.
- Monthly income was not significant once job role was controlled for.

## Recommendations

1. Reduce overtime and flag employees over standard hours for 3+ weeks.
2. Run short quarterly satisfaction surveys with manager follow-up.
3. Add early-tenure mentorship with 30, 90, and 180-day check-ins.
4. Offer flexible scheduling and clear after-hours norms.

## Files

- `Final_Report.pdf` - full written report
- `Presentation.pptx` - 7-slide summary deck

Author: [Munim Awal](https://munimawal.com)
