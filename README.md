# 🚀 VIZ-ly: Advanced Customer Retention & Predictive Churn Analytics

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analytics-005571?style=for-the-badge&logo=google-analytics&logoColor=white)

> **"Transforming behavioral data into strategic retention intelligence."**

<div align="center">
  <img src="https://raw.githubusercontent.com/Sauravx4/Churn_Project/main/dashboard.png" alt="VIZ-ly Executive Dashboard" width="100%">
</div>

---

## 📌 Executive Summary
**VIZ-ly** is an end-to-end business intelligence project engineered to diagnose, predict, and mitigate customer churn for a SaaS/Subscription platform. 

The business was facing a critical **57.3% churn rate**, putting **$697,000 in Monthly Recurring Revenue (MRR)** at risk. By combining Exploratory Data Analysis (EDA), Machine Learning feature extraction, and an interactive Power BI dashboard, this project moves beyond historical reporting to provide actionable, predictive insights for the Customer Success and Product teams.

---

## 🎯 The Business Problem & Objective
* **The Challenge:** The company lacked visibility into *why* users were canceling their subscriptions and *who* was most at risk in the current billing cycle.
* **The Goal:** Develop a continuous monitoring command center that identifies behavioral "danger zones" and billing friction points, allowing proactive intervention before the revenue is lost.

---

## 🛠️ Tech Stack & Architecture

| Category | Tools & Technologies Used |
| :--- | :--- |
| **Data Visualization & BI** | Power BI Desktop, DAX (Data Analysis Expressions), Power Query |
| **Predictive Modeling** | Python (`scikit-learn`, `RandomForestClassifier`) |
| **Data Manipulation** | Python (`pandas`, `numpy`) |
| **Statistical Visualizations** | Python (`seaborn`, `matplotlib` - *Kernel Density Estimation*) |

---

## 🧠 Methodology & Workflow

1. **Data Ingestion & Cleaning (Python/Pandas):** * Processed a dataset of 2,800+ unique user records.
   * Handled missing values, encoded categorical variables (Plan Tiers), and engineered new behavioral features.
2. **Predictive Feature Extraction (Machine Learning):**
   * Trained a Random Forest Classifier not for deployment, but for **Feature Importance**. 
   * *Result:* Statistically proved that `payment_failures` and `avg_weekly_usage_hours` were the primary mathematical drivers of churn, eliminating guesswork.
3. **Data Modeling (Power BI/DAX):**
   * Built a robust relational data model.
   * Engineered dynamic DAX measures (`CALCULATE`, `DIVIDE`, `COUNTROWS`) to ensure MRR and Churn % metrics responded instantly to cross-filtering by Plan Tier and User Tenure.
4. **UI/UX Dashboard Design:**
   * Designed a "Dark Mode" executive interface using the **F-Pattern visual hierarchy**, prioritizing high-impact financial metrics in the top-left quadrant and explanatory behavioral charts below.

---

## 📊 Key Business Insights & Strategic Recommendations

### 1. The "10-Hour" Engagement Cliff
* **The Data:** Kernel Density Estimation (KDE) reveals that retained users average ~15 hours of weekly usage, while churned users cluster heavily around 5 hours.
* **Recommendation:** The Product Team must implement automated, triggered onboarding emails and in-app tutorials for any user whose weekly usage drops below the 10-hour threshold.

### 2. Billing Friction is a Primary Catalyst
* **The Data:** Churn probability spikes to a critical **64%+** the moment a user experiences their second payment failure.
* **Recommendation:** Introduce a 3-day "grace period" or an automated alternative payment gateway prompt immediately after the *first* payment failure to rescue the account.

### 3. Premium Tier MRR Hemorrhage
* **The Data:** While the "Basic" plan sees a higher raw volume of cancellations, the "Premium" tier represents the vast majority of the $697k MRR loss.
* **Recommendation:** Deploy dedicated human Customer Success Managers (CSMs) exclusively for Premium accounts showing declining login frequency.

---

## 📸 Dashboard Showcase

### 1. The Executive Pulse (Financial KPIs)
*(Showcases total risk, current churn rate, and plan-level breakdown)*
<img src="https://github.com/Sauravx4/Saurav/blob/main/The%20Executive%20Pulse.png" width="80%">

### 2. User Engagement Density (Behavioral Analysis)
*(Highlights the specific usage hours where churn risk is highest)*
<img src="https://github.com/Sauravx4/Saurav/blob/main/User%20Engagement%20Density.png" width="80%">

### 3. The Billing Danger Zone
*(Visualizes the direct correlation between payment failures and attrition)*
<img src="https://github.com/Sauravx4/Saurav/blob/main/The%20Billing%20Danger%20Zone.png" width="80%">

---

## 📂 Repository Structure

```text
├── data/
│   ├── raw_customer_data.csv            # Original dataset
│   └── cleaned_subscription_data.csv    # Processed data ready for BI
├── notebooks/
│   └── exploratory_data_analysis.ipynb  # Python EDA & ML Feature Importance
├── dashboard/
│   ├── VIZ_ly_Retention_Dashboard.pbix  # The Power BI file
│   └── dashboard_mockups/               # High-res PNGs of the dashboard
├── sql/
│   └── user_segmentation_queries.sql    # SQL logic for data extraction
└── README.md.

```
## 🚀 How to Run This Project Locally
git clone [https://github.com/yourusername/viz-ly-churn-analytics.git](https://github.com/yourusername/viz-ly-churn-analytics.git)

## 📬 Let's Connect
# I am a Data Analyst passionate about turning complex datasets into strategic business tools.
# LinkedIn: https://linkedin.com/in/saurav-mourya-596253274
# Email: sauravmourya54@gmail.com
# Portfolio: https://sauravcodease.netlify.app
## If you found this analysis insightful, feel free to ⭐ this repository!
