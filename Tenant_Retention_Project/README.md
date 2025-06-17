# 🏠 Behavioral Insights for Tenant Retention

This project uses **survival analysis** to explore the behavioral and policy-driven factors that influence tenant churn. The dataset simulates housing data for 15,000 tenants in Lisbon and models their tenancy duration, with churn defined as tenants moving out.

---

## 📌 Objective

To identify key risk factors that lead tenants to leave their homes and simulate how housing policies—like **rent control** and **subsidies**—impact tenant retention.

---

## 📊 Dataset Overview

The dataset is **simulated** to reflect Lisbon’s rental housing dynamics and includes:

- `tenant_id`, `duration_months`, `status` (churn or not)
- Socioeconomic data: `income`, `employment_status`, `household_size`
- Housing details: `monthly_rent`, `rent_change_pct`, `district`
- Policy variables: `rent_control_applied`, `subsidy_received`

---

## 🧠 Methodology

### 1. Kaplan-Meier Estimator
- Used to estimate surviv
