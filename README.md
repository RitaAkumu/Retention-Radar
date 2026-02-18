# Retention Radar — Customer Churn Risk Scoring & Retention Strategy

This project analyzes customer churn patterns and builds a predictive churn risk model to help prioritize retention interventions. Using demographic, service, contract, and billing variables, I trained a **logistic regression** model to estimate churn probabilities and translate the results into clear, operational recommendations.

**Report:** [📄 Download Full Report (PDF)](https://raw.githubusercontent.com/RitaAkumu/Retention-Radar/main/Retention_Radar_Styled%20(1).pdf)



---

## Highlights

- **Dataset:** 7,044 customers, 21 variables (telecom subscription context)
- **Model:** Logistic Regression (risk scoring / probability ranking)
- **Performance:** **ROC–AUC = 0.84**
- **Targeting efficiency (risk percentiles):**
  - Top **10%** risk: **~75% precision**, **~28% recall**
  - Top **30%** risk: **~57% precision**, **~65% recall**
- **Highest-risk segment:** Month-to-month + electronic check (**~53.7% churn**) :contentReference[oaicite:2]{index=2}

---

## Key Drivers of Churn (from segmentation)

- **Contract:** Month-to-month churn is materially higher than 1–2 year contracts  
- **Tenure:** Churn is concentrated early (0–3 months highest)
- **Payment:** Electronic check users churn significantly more than autopay users
- **Product:** Fiber customers show elevated churn, especially without value-add bundles :contentReference[oaicite:3]{index=3}

---

## Risk-Based Targeting Approach

Instead of using a single fixed threshold, customers are ranked by predicted churn probability and segmented into risk percentiles (top 10%, 20%, 30%) to support flexible outreach depending on budget and capacity. :contentReference[oaicite:4]{index=4}

---

## Recommendations (Actionable Plays)

1. **Contract migration**: move month-to-month customers into 12/24-month plans  
2. **Auto-pay adoption**: incentives for switching from electronic/manual payments  
3. **Fiber bundle strategy**: bundle security/support add-ons to increase stickiness  
4. **Early-life onboarding**: structured onboarding for first 0–3 months  
5. **Risk-based outreach**: focus on top risk deciles to maximize retention ROI :contentReference[oaicite:5]{index=5}

---

## Contents

- `Retention_Radar_Styled (1).pdf` — Full report with charts, segmentation insights, and action plan
- *(Optional)* `notebooks/` — EDA + modeling (if you upload notebooks)
- *(Optional)* `data/` — dataset (if licensing allows)

---

## Tech Stack (suggested)

- Python (pandas, numpy, scikit-learn)
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Author

**Rita Akumu**  
LinkedIn: *(add your LinkedIn link here)*

