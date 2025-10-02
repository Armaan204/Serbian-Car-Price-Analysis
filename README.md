# Regression Analysis on Used Car Prices in Serbia (2024) 🚗📊

**STAC67** — Armaan Rehman Shah, Darren Guerina, Rachel Takacs

---

## Short description
Reproducible R pipeline to predict used-car prices in Serbia (2024). The project includes data cleaning & filtering, feature engineering (transformations, centering, polynomials, interactions), model selection (AIC / backward elimination), regression diagnostics, and validation — resulting in an interpretable power-regression model with strong explanatory power.

---

## Key results (high-level)
- **Final model:** Interpretable power-model with polynomial and interaction terms.  
- **Performance:** `R² ≈ 0.84` for the power model — strong explained variance while keeping interpretability.  
- **Diagnostics:** Heteroscedasticity observed (residual trumpet pattern). Recommended next step: Weighted Least Squares or variance-stabilizing methods.  
- Full coefficient table, diagnostic plots, and the dataset filtering function are in `STAC67_finalproject.pdf`.

---

## Skills & tools demonstrated
- **Languages:** R (RMarkdown for reproducibility)  
- **Packages / methods:** `tidyverse`, `MASS` (Box–Cox), `car` (diagnostics), `broom`, `caret` (validation)  
- **Techniques:** data cleaning, feature engineering (centering, transforms, polynomials, interactions), AIC/backward model selection, train/validation checks, regression diagnostics

