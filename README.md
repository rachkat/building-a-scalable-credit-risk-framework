# Building a Scalable Credit Risk Framework  

![Made with R](https://img.shields.io/badge/Made%20with-R-blue?logo=r) 
![Made with SQL](https://img.shields.io/badge/Made%20with-SQL-lightgrey?logo=databricks) 
![Made with PowerBI](https://img.shields.io/badge/Made%20with-PowerBI-yellow?logo=powerbi) 
![License: MIT](https://img.shields.io/badge/License-MIT-green) 
![Status: Finished](https://img.shields.io/badge/Status-Finished-brightgreen)

---

## Executive Summary  

In this project, I develop a **scalable credit risk framework** for GE’s credit team, following the **CRISP-DM methodology**. It consolidates three milestones into a cohesive solution:

1. **Business Case & Ethics Review** – Assessed Excel-based credit evaluation, identified risks of bias in sensitive fields (gender, race, marital status), and proposed an ethical strategy aligned with fair lending laws.  
2. **Pilot Predictive Model (k-NN)** – Built in R to classify loan applicants using historical data; tested with Age and Na/K ratio features to validate feasibility.  
3. **Final Deployment Plan** – Outlined integration with SQL + Power BI for scalability, real-time dashboards, and automation to reduce manual workload.  

**Business Impact:**  
- Potential to reduce loan default losses by **15%+ annually**.  
- Automates applicant vetting, cutting turnaround time by **30–40%**.  
- Strengthens compliance by excluding sensitive variables and embedding continuous monitoring.  

This project demonstrates strengths in **predictive modeling (k-NN, logistic regression, decision trees)**, **data preparation in R**, and **business translation**, while highlighting the ethical considerations of deploying AI in financial services.  


📄 **Full report PDF** → [Building-A-Scalable-Credit-Risk-Framework.pdf](./building-scalable-credit-risk-framework.pdf)  

---

## Business Context  

- **Problem**: GE’s Excel-based credit evaluation lacked scalability and predictive power.  
- **Data**: 1,000 applicants × 31 features (salary, credit history, loan amount, etc.).  
- **Goal**: Build a **scalable, predictive solution** to reduce loan default losses and improve decision-making.  
- **Business Value**:  
  - Prevented loan default losses → up to **15% annual reduction**.  
  - Improved turnaround → **30–40% faster evaluations**.  
  - Automated workflows → reduced manual workload, enabling staff to focus on strategy.  

---

## CRISP-DM Workflow  

1. **Business Understanding**  
   - Need for scalable, fair, and transparent risk modeling post-2008 crisis.  
2. **Data Understanding**  
   - 31 applicant variables including demographics, credit history, and loan amount.  
3. **Data Preparation**  
   - Cleaning, imputation, feature scaling (Z-score standardization).  
   - Ethical filtering → excluded gender, race, and marital status.  
4. **Modeling**  
   - k-NN pilot with Age + Na/K ratio.  
   - Compared to logistic regression & decision trees.  
5. **Evaluation**  
   - Confusion matrix, ROC-AUC, and interpretability checks.  
   - k-NN chosen for transparency in compliance-heavy environments.  
6. **Deployment**  
   - Proposed SQL integration + Power BI dashboards for **real-time loan risk scoring**.  

---

## Methods  

- **Algorithm**: k-NN (Euclidean distance, tested multiple k values).  
- **Tools**:  
  - **R** → Data prep, modeling, evaluation.  
  - **SQL** → Integration with GE’s Oracle warehouse.  
  - **Power BI** → Dashboards for stakeholder reporting.  
- **Ethics**: Removed sensitive fields, monitored compliance with **Equal Credit Opportunity Act**.  

---

## Results & Insights  

- **Pilot k-NN** successfully classified new applicants → transparent and explainable.  
- **Validation** with distance matrices confirmed interpretability.  
- **Scaling potential**: Automating evaluation across 10,000+ annual applications.  
- **Expected ROI**: Hundreds of thousands saved annually from reduced defaults + operational efficiency.  

---

## Key Skills Demonstrated  

- Applied **CRISP-DM methodology** end-to-end.  
- **Predictive modeling** with k-NN, logistic regression, decision trees.  
- **Ethics in analytics**: Fair lending compliance, bias detection, and variable selection.  
- **Business translation**: Linking technical outputs to ROI, compliance, and efficiency gains.  
- **Data prep best practices**: Cleaning, feature scaling, reproducibility in R.  
- **Visualization & reporting**: Proposed BI dashboards for executives.  

---

## Limitations & Next Steps  

- Small pilot dataset → expand with income, credit history, debt-to-income ratio.  
- Class imbalance → explore **SMOTE** or cost-sensitive learning.  
- Add **hyperparameter tuning** (grid search, Bayesian optimization).  
- Deploy models with **PMML** for integration into CRM systems.  
- Pilot test with full GE customer dataset before large-scale rollout.  

---

## Repository Structure  

credit-risk-framework/
├─ Building-A-Scalable-Credit-Risk-Framework.pdf # Full written report
├─ README.md
└─ LICENSE


---

## License  

Released under the **MIT License**. See [LICENSE](./LICENSE).  

---

## Tags  

`credit-risk` `predictive-modeling` `crisp-dm` `k-nn` `logistic-regression`  
`decision-trees` `loan-default` `machine-learning` `r` `sql` `powerbi`  
`ethics` `fair-lending` `data-science` `portfolio`  

---


