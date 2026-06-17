# E-Commerce-Customer-Insights-and-Churn-Dataset-Analysis

## Executive Summary
This project presents a forensic diagnostic audit of a 2,000-customer e-commerce dataset. By moving beyond high-level churn metrics, this analysis identifies deep-seated profitability risks, debunks ineffective "vanity" metrics, and maps a high-precision retention strategy using a Value-Engagement Matrix. 

**Key Business Impact:** Identified a significant "Quality Erosion" trend where high-value customers are exiting, and mapped out a $450,000+ latent revenue opportunity within the "At-Risk" customer segment.

---

## 🔍 Key Findings

* **Profitability Divergence:** Discovered "Quality Erosion"—our churned cohort has a higher Average Order Value ($1,030) than our active cohort ($1,022). We are systematically losing our most profitable customers.
* **Debunking Vanity Metrics:** Statistical audit ($R^2 < 0.2$) proved that `cancellations_count` and `purchase_frequency` are non-predictive indicators of churn. 
* **Database Integrity:** Confirmed a clean user base with <0.1% "Terminal" (dead) accounts, validating that our churn data represents actual active customer attrition.
* **Risk-Based Segmentation:** Identified 445 "At-Risk" customers (22% of the user base) who have cleared the initial purchase hurdle but have yet to reach sustainable profitability.

---

## 🛠 Methodology

The audit utilized a multi-stage diagnostic framework:
1.  **Divergence Analysis:** Comparing AOV and revenue contribution across active and churned groups.
2.  **Metric Validation:** Correlation testing to identify actionable leading indicators.
3.  **Value-Engagement Matrix:** A proprietary segmentation logic used to categorize users into **Healthy**, **At-Risk**, and **Terminal** cohorts.

---

## 📂 Project Structure
* `/sql_queries`: Contains the forensic audit scripts used for data extraction and behavioral analysis.


---

## 📈 Strategic Recommendations
Based on the audit, the business is advised to:
1.  **Pivot to Signal-Based Retention:** Discontinue reliance on frequency-based metrics and adopt engagement-duration tracking.
2.  **Targeted Re-Engagement:** Deploy personalized value-add incentives for the 445 "At-Risk" users to capture the identified $450k+ revenue potential.
3.  **High-Touch Intervention:** Implement priority retention programs for Tier 1 and Tier 2 customers to halt "Whale" attrition.

---

## ⚙️ Technical Stack
* **Analysis:** SQL (Diagnostic logic & cohort segmentation)
* **Strategy:** Forensic Data Analysis & Business Intelligence

*Note: This project is currently transitioning from manual SQL-based diagnostic workflows to Python (Pandas) for automated reporting.*
