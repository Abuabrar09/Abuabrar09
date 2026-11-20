# Hi, I'm Abrar Ahmed Syed 👋

### Business & Financial Data Analyst | AI

I turn business and financial data into clear decisions using **Python, SQL, Excel, Power BI, Tableau and AI**.
With hands-on experience running a retail and grocery business, I understand the numbers behind real-world operations: margins, inventory, cash flow and growth.

📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/abrar313/)

---

## 📂 Featured Projects

### 👥 [Advanced Customer Analytics & Predictive Intelligence](https://github.com/Abuabrar09/Customer-Analytics-Predictive-Intelligence)

RFM segmentation, customer lifetime value, churn prediction and a value-based retention plan on **2.6M real grocery transactions from 2,500 US households** (dunnhumby, Kaggle). SQL cohorts and RFM, a CLV model validated on held-out households, and a churn model tested out-of-time on a later period. **Key finding:** Champions are 29% of households but 61% of revenue; contacting the riskiest 20% reaches 66% of churners (vs 26% for a simple rule); and **targeting by value nets +$2,062 while a blanket offer to every high-risk household loses $409**. `SQL` `Python` `scikit-learn` `Tableau` 📊 [Live Tableau dashboard](https://public.tableau.com/app/profile/abrar.ahmed.syed4247/viz/CustomerIntelligenceDashboard_17948621753550/ChurnRiskActionPlan) · 📓 [Code & write-up](https://github.com/Abuabrar09/Customer-Analytics-Predictive-Intelligence)

### 💳 [Accounts Receivable & Collection Performance Intelligence](https://github.com/Abuabrar09/AR-Collection-Performance-Intelligence)

Receivables aging, overdue analysis, collection KPIs and late-payment prediction on **48,839 real B2B invoices** from 1,425 corporate customers (Kaggle HighRadius data). Point-in-time AR aging, DSO vs best possible DSO, CEI, bad-debt allowance, and a leakage-safe ML model scored on a time split. **Key finding:** 42% of paid invoices were paid late and the top 10 customers held 63% of past-due dollars; the gradient boosting model (ROC-AUC 0.84 vs 0.77 baseline) captures 47% of late dollars in the riskiest 20% of invoices and flags 2,559 high-risk unpaid invoices worth $95.1M. `SQL` `Python` `scikit-learn` `Tableau` 📊 [Live Tableau dashboard](https://public.tableau.com/app/profile/abrar.ahmed.syed4247/viz/ARCollectionPerformanceIntelligence/ARDashboard) · 📓 [Code & write-up](https://github.com/Abuabrar09/AR-Collection-Performance-Intelligence)

### 🛡️ [Insurance Regulatory Reporting Control Tower](https://github.com/Abuabrar09/Insurance-Regulatory-Reporting-Control-Tower)

Audit-ready quarterly regulatory reporting cycle for an auto insurer on **1,000 real policies and claims** (Kaggle): reporting inventory, filing calendar, 22 data quality rules, remediation with an audit trail, 6 SQL reports, reconciliation to the general ledger, a 10-control matrix and a SHA-256 checksummed submission package, all run with one command. **Key finding:** the raw extract was blocked on 5 of 22 rules; 16 issues were fixed with before/after logging and 1 genuine record (a loss 20 days before the policy was bound) became an approved exception. Reconciliation caught a **$2,500 claim payment posted to the wrong state**, and a 0.1% tolerance rule that would have hidden it was tightened. `Python` `SQL` `pandas` `Internal Controls` 📊 [Live dashboard](https://abuabrar09.github.io/Insurance-Regulatory-Reporting-Control-Tower/) · 📓 [Code & write-up](https://github.com/Abuabrar09/Insurance-Regulatory-Reporting-Control-Tower)

### 🤖 [Generative AI Financial Reporting & BI Assistant](https://github.com/Abuabrar09/GenAI-Financial-Reporting-Assistant)

Natural-language finance assistant on **3M real supermarket sales rows** (Kaggle Corporación Favorita, 54 stores): ask *"Why did operating profit decline?"* and get a grounded answer, chart, the SQL used, and an automated CFO summary. LLM text-to-SQL with read-only guardrails, a deterministic operating-profit bridge (volume, mix, markdowns, labor, logistics), pytest + GitHub Actions CI. **Key finding:** Q2 2017 revenue grew 2.9% vs Q1, yet operating profit fell 10.8% as promo markdowns and labor outpaced volume gains. `Python` `SQL` `LLM API` `Streamlit` `Plotly` 🚀 [Live demo](https://genai-finbi-abrar.streamlit.app) · 📓 [Code & write-up](https://github.com/Abuabrar09/GenAI-Financial-Reporting-Assistant)

### 📊 [Executive Business Performance & KPI Intelligence](https://github.com/Abuabrar09/Executive-KPI-Intelligence)
**SQL · Python · Power BI · DAX** | 1.5M+ rows of real Olist e-commerce data
- Combined sales, finance and operations from 8 tables into one star schema and a 3-page Power BI report with drill-down filters
- Found that late deliveries make bad reviews **6.6× more likely**, only **3%** of customers return, and the top 10% of sellers drive **67%** of revenue
- 19 DAX measures (YoY growth, repeat rate, on-time %, contribution) validated against SQL

### 📦 [Inventory Optimization & Demand Forecasting](https://github.com/Abuabrar09/Inventory-Optimization-Forecasting)
Demand forecasting and inventory policy for 10 stores × 50 items using 913K Kaggle sales records: backtested forecasts, ABC analysis, supplier lead-time risk, safety stock and reorder points. **Key finding:** a seasonal model forecast with 2.2% error (vs 13–17% for simple methods); $6.0M of stock (49%) sat in 8 overstocked items while 10 high-value items were about to run out. `SQL` `Python` `pandas` `DuckDB` `Tableau` 📊 [Live interactive dashboard](https://public.tableau.com/app/profile/abrar.ahmed.syed4247/viz/InventoryOptimizationDemandForecasting/InventoryDashboard) · 📓 [Code & write-up](https://github.com/Abuabrar09/Inventory-Optimization-Forecasting)

### 🏪 [Retail Sales & Profitability Intelligence](https://github.com/Abuabrar09/retail-sales-profitability-analysis)
End-to-end profitability analysis of an 18-store retail chain (133K transactions, 2024–2025): data cleaning, store and product P&L, loss-making products and discount effectiveness. **Key finding:** all 5 Express stores lose money, and fixing them would more than double operating profit; discounts equal 47% of gross profit with no increase in units sold. `SQL` `Python` `Excel` `Tableau` 📊 [Live interactive dashboard](https://public.tableau.com/views/RetailSalesProfitabilityDashboard_17942567393830/ExecutiveDashboard) · 📓 [Code & write-up](https://github.com/Abuabrar09/retail-sales-profitability-analysis)

### 🧺 [Market Basket & Product Association Analysis](https://github.com/Abuabrar09/Market-Basket-Analysis)
Association rules (support, confidence, lift) on 49.5K grocery orders in the Instacart schema: pair rules in SQL, Apriori written from scratch in Python, and cross-sell ideas ranked by shoppers who bought A but not B.
**Key finding:** the highest-lift pairs are mission purchases (baby care, pet food, household restocks, about 8–11× lift), but the biggest cross-sell audience is fresh produce; 3-item bundles reach 72% confidence.
`SQL` `Python` `Apriori` `Tableau`
📊 [Live Tableau dashboard](https://public.tableau.com/app/profile/abrar.ahmed.syed4247/viz/InstacartMarketBasketAnalysis_17951940099710/MarketBasketDashboard) · 📓 [Code & write-up](https://github.com/Abuabrar09/Market-Basket-Analysis)

### 🛒 [Texas Supermarket Retail Analytics](https://github.com/Abuabrar09/supermarket-retail-analytics)
End-to-end analysis of 1.1M point-of-sale line items for a 5-store grocery chain: KPIs, RFM segmentation, cohort retention, market basket analysis, promotion ROI and SQL window functions.
**Key finding:** ~80% of promotion weeks lost gross profit; at-risk loyalty members held 20% of member revenue.
`Python` `pandas` `SQL` `Matplotlib` `Seaborn`
📊 [Live interactive dashboard](https://abuabrar09.github.io/supermarket-retail-analytics/dashboard/) · 📓 [Analysis notebook](https://github.com/Abuabrar09/supermarket-retail-analytics)

### 🏦 [Credit Risk Prediction — Machine Learning](https://github.com/Abuabrar09/Credit-Risk-Prediction)
Built a model to predict loan defaults for **1,000 real applicants** using Random Forest with Bayesian Optimization (Optuna), and chose an approval threshold based on real business costs.
**Finding:** Test ROC-AUC 0.814. The cost-optimal threshold catches **95% of defaulters** and **cuts lending losses by 48%**. [View on Kaggle](https://www.kaggle.com/code/abrarahmedsyed313/credit-risk-prediction)
`Python` `scikit-learn` `Random Forest` `Optuna` `Responsible AI`

### 🛒 [US Retail Financial Statement Analysis](https://github.com/Abuabrar09/us-retail-financial-analysis)
Compared **Walmart, Target and Costco** across 10 financial ratios from their income statements, balance sheets and cash flows.
**Finding:** Costco ranks #1 on 7 of 10 ratios despite the lowest margins. It sells its inventory in 27 days vs 59 for Target.
`Python` `pandas` `Financial Ratios` `yfinance`

### 📈 [Indian Stock Market Analysis](https://github.com/Abuabrar09/Indian-stock-market-analysis)
Analysed 5 years of returns, risk and correlation for **Reliance, TCS, HDFC Bank, Infosys and ICICI Bank** against the Nifty 50.
**Finding:** ICICI Bank was the only stock to beat the index (16.2% per year) with the best risk-adjusted return.
`Python` `pandas` `Risk Metrics` `Data Visualization`

### 🏪 [Superstore Sales & Profitability Analysis](https://github.com/Abuabrar09/superstore-sales-profitability-analysis)
Retail sales and profitability analysis using the Kaggle Sample Superstore dataset.
`Python` `pandas` `Sales Analysis` `Kaggle`


---

## 🛠️ Skills
**Analysis:** Python (pandas, NumPy) · SQL · Excel
**Visualization:** Power BI · matplotlib · seaborn
**Machine Learning:** scikit-learn · Random Forest · Bayesian Optimization
**Finance:** Financial statement analysis · Ratio analysis · Risk & return metrics
**Tools:** Google Colab · Jupyter · GitHub

---

## 🚀 Currently Working On
- AI-powered expense categorization

