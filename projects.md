---
layout: default
title: Projects
---

# 📂 Selected Projects

Here are a few key projects showcasing my work across fintech strategy, product analytics, and digital optimization:


---
### 🛵 Predicting Delivery Time Using DoorDash Historical Data

Built a machine learning model to predict **actual delivery time** for DoorDash orders using a dataset of historical deliveries across multiple U.S. cities.

- Processed and engineered features from **80K+ delivery records**, including time, location, store, and order details
- Created custom time-based features and handled noisy/missing timestamps using Python and pandas
- Trained and tuned a **Random Forest Regressor** using `RandomizedSearchCV` to optimize delivery time predictions
- Achieved **RMSE under 5 minutes** on validation data and identified top features: `market_id`, `created_at`, and `order_protocol`
- Visualized feature importances and delivery time distributions to support operational improvements

🔍 [Interactive Notebook (nbviewer)](https://nbviewer.org/github/RaisyXu/jupyter-notebooks/blob/main/doordash_delivery_time.ipynb)  
📂 [View on GitHub](https://github.com/raisyxu/jupyter-notebooks/blob/main/doordash_delivery_time.ipynb)


---

## 🧠 BNPL Behavioral Analytics & A/B Testing Optimization  
**Company:** JPMorgan Chase  
**Role:** Senior Data Analyst  
**Tools:** SQL, Tableau, Adobe Analytics, AWS Athena, Snowflake, Alteryx  

Supported data-driven feature testing and user journey optimization for Chase’s Buy Now Pay Later (BNPL) product with a strong focus on conversion rate (CVR), click-through rate (CTR), and funnel drop-off metrics.

**Key Achievements:**
- Created dashboards in **Adobe Analytics** and **Tableau** to visualize user engagement patterns and real-time performance indicators such as **DAU, MAU, CTR, CVR**, and **feature adoption**.
- Used **Snowflake SQL** to extract and transform behavioral data across large customer cohorts, applying **window functions, CTEs**, and **CASE logic** to enable precise segmentation and trend tracking.
- Built cohort-based funnel analysis using Adobe workspace breakdowns to trace **step-by-step user drop-offs** and identify high-friction paths.
- Designed and evaluated A/B tests via custom SQL pipelines in Snowflake, calculating **lift metrics, significance levels**, and **confidence intervals** to validate UX enhancements.
- Partnered cross-functionally with product managers and UX designers to translate behavioral findings into actionable roadmap priorities.
- Automated and standardized 7+ compliance dashboards by building repeatable data workflows in **Alteryx**, reducing error rates by 90%.

---

## ⚙️ Digital Collections Strategy for Overdraft Risk  
**Company:** JPMorgan Chase  
**Role:** Associate – Strategic Analytics  
**Tools:** SQL, SAS, Oracle, Teradata, Snowflake  

Led the strategy design for digital outreach and risk reduction across overdraft recovery operations, contributing to improved net recovery and lower charge-offs.

**Key Achievements:**
- Built a **customer-level SQL rules engine** to assign outreach treatments dynamically based on behavioral, transactional, and scorecard inputs.
- Developed pipelines in **Snowflake** and **Teradata** to support strategy logic replication and daily campaign deployment across digital channels.
- Used **complex joins**, nested CTEs, and union queries to consolidate risk scores from ML models and historical payment behavior into decision flags.
- Collaborated with model governance and risk teams to validate logic used in strategies influencing a **$60M+ portfolio**.
- Converted legacy **SAS logic** into structured modular SQL, enhancing efficiency and shortening deployment cycles by 40%.

---

## 📉 Chase Pay-in-Four: Product Experimentation & API Analytics  
**Company:** JPMorgan Chase  
**Role:** Product Analyst  
**Tools:** SQL, Looker, Snowflake  

Monitored real-time performance of Chase’s Pay-in-Four product infrastructure, supporting both backend integration and user experience tracking.

**Key Achievements:**
- Used **Snowflake SQL** and Looker visualizations to track **API success rates, latency, transaction errors**, and performance degradation signals.
- Defined KPIs such as **API adoption, checkout bounce rate, session duration**, and **conversion lag** to benchmark developer experience.
- Led controlled experimentation analysis using toggles and feature flags, comparing latency and completion metrics pre/post deployment.
- Delivered insight presentations to engineering and product leadership to support feature stabilization and roadmap trade-offs.

---

## 📊 BNPL Competitive Intelligence — Klarna & Affirm Analysis  
**Company:** JPMorgan Chase  
**Role:** Strategic Analyst  
**Tools:** Market research, internal dashboards  

Delivered high-impact competitor research to support Chase's entry and scaling in the BNPL space.

**Key Achievements:**
- Used internal BI dashboards and Tableau to conduct **side-by-side product metric benchmarking** on Klarna and Affirm.
- Mapped out core performance KPIs including **merchant acceptance rate, default probability, APR policies**, and **activation speed**.
- Presented findings and competitive gaps to the BNPL product leadership team, which directly shaped Chase’s differentiated go-to-market approach.

---


Looking for more? [Let’s connect.](mailto:raisy_xu@outlook.com)
