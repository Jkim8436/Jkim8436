# Joshua Kim

**Data Analyst — Product, Risk & Customer Analytics**
UIUC Econometrics & Statistics · ADsP · SQLD · Chicago, United States

I find where the data breaks, fix it, and connect the fix to a decision. Below are four projects — each includes the full methodology, validation, and an honest account of what the data doesn't support.

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge) ![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## Portfolio Projects

### [IVE Korea — Ad Fraud Detection & Media Risk Analytics](https://github.com/Jkim8436/IVE-Korea-Ad-Fraud-Detection)
**Goal:** Detect and quantify ad-fraud risk across 189 media partners without a labeled ground truth, and test whether the flags would hold up as a real-time detector, not just a retrospective one.
**Result:** 6.39M high-confidence anomalous clicks (38.0%) identified across 16.8M events; ₩260.7M in exposure quantified; clean-traffic CVR recovers from 8.74% → 30.50%. An out-of-time backtest honestly reports which alert design would and wouldn't have caught the event in real time.
**Tech:** Python, Pandas, Gemini 2.0 Flash API (hybrid domain classification)

### [Starbucks — Reward Offer Waste Analysis](https://github.com/Jkim8436/Starbucks-Marketing-Offer-Optimization)
**Goal:** Find where reward spend leaks without driving real behavior, and measure each offer type's true causal effect rather than its completion rate.
**Result:** Discount's marketing effect (+32.8pp) confirmed at +32.1pp after Propensity Score Matching — 3x BOGO's. Only 5 of 20 customer segments benefit from tightening rewards (+$4,134); the other 15 would lose $22,888. A channel-based fix is estimated to save $21,465.
**Tech:** Python, scikit-learn (PSM), XGBoost, statsmodels

### [Die Casting — Real-Time Defect Prediction](https://github.com/Jkim8436/Die-Casting-Defect-Prediction)
**Goal:** Replace reactive manual visual inspection with a real-time model that predicts defects and traces their root cause.
**Result:** LightGBM selected via PR-AUC — F1 0.79–0.80 across three defect groups; SHAP identifies the process variables driving each one; ₩3.5M estimated savings per 10 days based on stated FN/FP unit costs.
**Tech:** Python, scikit-learn, XGBoost, LightGBM, SHAP · *Team project — individually owned preprocessing, modeling, decision logic, and business-impact modeling*

### [Seoul Real Estate — Investment Strategy & Screening Dashboard](https://github.com/Jkim8436/Seoul-Real-Estate-Investment-Strategy)
**Goal:** Recommend district × building-type investment targets for three investor profiles, and test whether the scoring framework actually predicts forward.
**Result:** Jungnang-gu tops every profile's shortlist; OLS regression (R²=0.543) shows a "cheap" district's discount is often a housing-stock-age effect, not a location discount; a temporal holdout shows the framework would have **underperformed** the market in 2022–2024 — reported as a finding, not adjusted away. Includes an interactive React dashboard for live profile-switching.
**Tech:** Python, statsmodels, SciPy · React/SVG dashboard

---

## Certifications
- ADsP — Advanced Data Analytics Semi-Professional, Korea Data Agency (Mar 2026)
- SQLD — SQL Developer, Korea Data Agency (Jun 2026)

## Contact
📧 jkim43844@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/joshua-kim-87b478263/)
