# Board Gender Diversity & Corporate ESG Performance

## Overview
OLS regression analysis examining whether **board gender composition drives ESG (Environmental, Social, Governance) scores** across **534 S&P 500 companies**. Built two regression models including an interaction term to test whether the effect of board gender diversity on ESG scores differs when the company has a female CEO.

## Tools & Libraries
- **R** (primary language)
- lmtest, sandwich, car, ggplot2, dplyr

## Methods
- **OLS Regression** — Two models with and without interaction terms
- **Interaction Term** — Gender Diversity × Female CEO
- **Diagnostic Testing:**
  - Breusch-Pagan test (heteroscedasticity)
  - VIF (multicollinearity)
  - Robust standard errors (HC1)

## Key Findings
- Board gender diversity showed a statistically significant positive relationship with ESG scores
- The interaction term (Gender Diversity × Female CEO) revealed nuanced effects on ESG outcomes
- Model diagnostics confirmed robust results after correcting for heteroscedasticity

## Files
- `ESG_Board_Diversity_Analysis.Rmd` — Full R Markdown analysis
- `ESG_Board_Diversity_Analysis.html` — Rendered report
- `data/` — Source dataset

## Author
**Kye Jones** — BS Economics (Business Forecasting), Central Washington University
Completed as part of ECON 424: Introduction to Econometrics

