# Reducing-Churn-Customer-Insights-and-Strategies-for-ConnectCom

# **Reducing Customer Churn at ConnectCom: Insights & Recommendations**

## Table of Contents
- [Project Background](#project-background)
- [Data Structure & Initial Checks](#data-structure--initial-checks)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
  - [Customer Retention & Churn Over Time](#customer-retention--churn-over-time)
  - [Contract Type & Customer Retention](#contract-type--customer-retention)
  - [Service Bundling & Churn Rates](#service-bundling--churn-rates)
  - [Customer Tenure & Early Churn Risk](#customer-tenure--early-churn-risk)
  - [Pricing Sensitivity & Payment Behavior](#pricing-sensitivity--payment-behavior)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)

---

## Project Background

In this case study, I analyzed customer churn for **ConnectCom**, a fictional telecommunications provider offering **internet, TV, and phone services across the United States**. Using **Tableau**, I examined customer behavior to uncover key churn drivers and develop targeted retention strategies. The insights from this analysis help **marketing and customer success teams** identify high-risk customers, optimize service offerings, and implement **strategies to improve customer loyalty and profitability.**

📊 **[Interactive Tableau Dashboard](#)**  
📂 **[Raw dataset](#)**

---

## Data Structure & Initial Checks

The dataset, sourced from **IBM’s TechXchange Community**, contains **7,043 customer records** covering the following key attributes:

- **Demographics** – Gender, senior citizen status, partner/dependent status.  
- **Account Information** – Contract type, tenure, payment method.  
- **Service Usage** – Internet service type, streaming services, phone lines.  
- **Billing & Charges** – Monthly charges, total charges.  
- **Churn Status** – Whether the customer stayed or left.  

---

## Executive Summary

Churn at **ConnectCom** is highest among **month-to-month customers (42.7%)**, while those on **two-year contracts have the lowest churn (2.8%)**, making contract incentives a key retention lever. Additionally, **fiber optic customers without streaming services have the highest churn (45.3%)**, while bundling streaming improves retention across both DSL and fiber plans. This suggests that **service bundling plays a crucial role in customer loyalty.** Since **36% of churned customers leave within the first five months**, early engagement efforts could significantly reduce customer loss.

---

## Insights Deep Dive

### Customer Retention & Churn Over Time

Customer retention at **ConnectCom** has declined over time, with **newer customer groups churning at significantly higher rates than those who joined earlier.**

- **Customers who joined between 2019 and 2022 have stronger retention, with over 75 percent staying long term.**
- **Recent customers from 2023 to 2024 are churning at a much faster rate, with retention dropping to 40.89 percent.**
- This suggests that **recent changes in pricing, service offerings, or competitive pressure may be contributing to higher churn.**

Early intervention strategies such as **enhanced customer onboarding, proactive support, and personalized retention offers** may help curb churn and improve **long-term loyalty.**

### Contract Type & Customer Retention

- **42.7% of month-to-month customers churned**, making them the most volatile group.
- **One-Year contracts had a churn rate of 11.3%**, showing that a longer commitment improves retention.
- **Two-Year contracts had the lowest churn at 2.8%**, indicating that customers who commit long-term are far more likely to stay.

Understanding what drives churn in **month-to-month plans** (pricing, service quality, or promotions) could help improve retention.

### Service Bundling & Churn Rates

- **DSL customers without streaming had a churn rate of 22.7%, while bundling streaming improved retention to 86.7%.**
- **Fiber optic customers had the highest churn (45.3% without streaming, 39.3% with streaming).**
- **Customers without internet had the lowest churn at just 7.4%.**

These findings highlight that **bundling services enhances customer loyalty, particularly among DSL users.** Fiber optic customers may be **more price-sensitive or have more competitive alternatives.**

### Customer Tenure & Early Churn Risk

- **The first four months have the highest churn, with 680 customers leaving immediately.**
- **By month five, churn drops to 243 customers (a 64% decrease).**
- **Customers who stay past five years are the most stable, with fewer than 50 leaving per interval.**

Improving **early customer experiences** could prevent a large portion of these early losses.

### Pricing Sensitivity & Payment Behavior

- **Customers with high monthly charges ($70–$100+) churn more frequently.**
- **Customers with total charges under $2,000 churn more, indicating early-stage attrition.**
- **Long-tenured customers with total charges over $4,000 are more likely to stay.**

These insights suggest that **pricing adjustments and retention incentives could help stabilize at-risk customers.**

---

## Recommendations

### Increase Contract Commitment
- Develop **discounted annual contract plans** to reduce reliance on month-to-month customers.
- Offer **early renewal incentives** to improve retention ahead of contract expiration.

### Strengthen Service Bundling
- **Encourage fiber upgrades for DSL users** to migrate customers to higher-value plans.
- **Expand streaming service bundles** to improve satisfaction and retention.

### Enhance Early Retention Efforts
- **Launch a 6-month onboarding & retention initiative** to reduce early-stage churn.
- **Improve first-contact customer support** to prevent frustration-driven churn.

### Address Pricing Sensitivities
- **Offer loyalty-based pricing discounts** for long-tenured customers.
- **Test tiered pricing models** to provide flexible plans while maintaining profitability.

### Optimize Payment Methods
- **Encourage credit card & bank transfer payments** to reduce churn among high-risk payment users.
- **Streamline payment processing** to enhance customer convenience.

---

## Assumptions & Caveats

- **Churn reasons are not explicitly provided** (e.g., service issues, competitor switching, pricing concerns). Insights are based on **behavioral trends** rather than direct feedback.
- **Involuntary churn due to payment failures was not explicitly recorded,** meaning some customers may have left due to billing issues rather than voluntary cancellation.
- **External factors such as competitor promotions and customer satisfaction surveys** were not included but may influence churn rates.

---

This analysis provides **data-driven recommendations** to **reduce churn at ConnectCom** by focusing on **contract incentives, bundling strategies, early engagement, and pricing models.**


