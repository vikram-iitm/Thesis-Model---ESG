# ESG and Stock Performance (S&P 500)

This project analyzes whether ESG scores impact the stock performance of S&P 500 companies from 2018 to 2022. We implement three panel data models using Python to test the relationship between ESG indicators and future stock returns and risk.

## 📌 Models Implemented

1. **Model 1:** ESG score → next-year stock return  
2. **Model 2:** ENV, SOC, GOV components → next-year return  
3. **Model 3:** ESG score → firm-level Beta (systematic risk proxy)

All models include financial controls and fixed effects (year and industry).

## 🔧 Tools & Libraries

- Python, Jupyter Notebook  
- `pandas`, `statsmodels`, `linearmodels`, `matplotlib`, `seaborn`

## 📈 Key Insight

Across all models, ESG indicators showed no statistically significant relationship with future returns or risk—macro-level factors dominated during the study period.

## 🚀 Run the Notebook

```bash
pip install -r requirements.txt
jupyter notebook Thesis_Models.ipynb
