# Reducing-Churn-Customer-Insights-and-Strategies-for-ConnectCom

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

In this case study, I analyzed customer churn for **ConnectCom**, a fictional telecommunications provider offering internet, TV, and phone services across the United States**. Using Tableau, I examined customer behavior to uncover key churn drivers and develop targeted retention strategies. The insights from this analysis help marketing and customer success teams** identify high-risk customers, optimize service offerings, and implement strategies to improve customer loyalty and profitability.**

Interactive Tableau Dashboard for exploring churn trends can be found [here.](https://public.tableau.com/app/profile/seana.parker/viz/CustomerChurnRateDashboard_17419175374080/ChurnRateDashboard)
Raw dataset can be found [here.](Exploration/ConnectCom_Telco_Customer_Churn_Dataset.csv)

---

## Data Structure & Initial Checks

The dataset, sourced from IBM’s TechXchange Community, contains 7,043 customer records covering the following key attributes:

- **Demographics** – Gender, senior citizen status, partner/dependent status.  
- **Account Information** – Contract type, tenure, payment method.  
- **Service Usage** – Internet service type, streaming services, phone lines.  
- **Billing & Charges** – Monthly charges, total charges.  
- **Churn Status** – Whether the customer stayed or left.  

---

## Executive Summary

Churn at ConnectCom is highest among month-to-month customers (42.7%), while those on two-year contracts have the lowest churn (2.8%), making contract incentives a key retention lever. Additionally, fiber optic customers without streaming services have the highest churn (45.3%), while bundling streaming improves retention across both DSL and fiber plans. This suggests that service bundling plays a crucial role in customer loyalty. Since 36% of churned customers leave within the first five months, early engagement efforts could significantly reduce customer loss.

<img src="Visualizations/Churn%20Rate%20Dashboard.png" alt="Churn Rate Dashboard" width="750">

---

## Insights Deep Dive

### Customer Retention & Churn Over Time

- Customer retention at ConnectCom has declined over time, with newer customer groups churning at significantly higher rates than those who joined earlier.

  - Customers who joined between 2019 and 2022 have stronger retention, with over 75 percent staying long term.

  - Recent customers from 2023 to 2024 are churning at a much faster rate, with retention dropping to 40.89 percent.

  - This suggests that recent changes in pricing, service offerings, or competitive pressure may be contributing to higher churn.

<img src="Visualizations/Cohort%20Over%20Time.png" alt="Cohort Over Time" width="600">

- Given this trend, early intervention strategies such as enhanced customer onboarding, proactive support, and personalized retention offers may help curb churn and improve long term loyalty.

### Contract Type & Customer Retention

- Customer churn is strongly influenced by contract length, with short-term contracts showing the highest churn rates. The analysis reveals a clear trend: the shorter the commitment, the higher the likelihood of customer attrition.

  - 42.71% of Month-to-Month customers churned, making them the most volatile group.

  - One-Year contracts had a significantly lower churn rate of 11.27%, indicating that a longer commitment improves retention.

  - Two-Year contracts had the lowest churn at just 2.83%, suggesting that customers who commit long-term are far more likely to stay.

- This pattern suggests that short-term customers may be more price-sensitive or more likely to switch providers. Since month-to-month plans drive the highest churn, understanding what influences their decisions, whether pricing, service quality, or promotional offers, could be key to improving retention.

### Service Bundling & Churn Rates

- Churn rates vary by internet type and whether customers bundle streaming services. Surprisingly, DSL customers retain better than fiber optic customers, and bundling streaming further improves retention.

  - DSL customers without streaming had a churn rate of 22.7%, meaning 77.3% stayed. Despite being an older technology, DSL users may have fewer alternatives or be less price-sensitive.

  - Adding streaming services to DSL improved retention to 86.7%, suggesting that bundled services increase customer loyalty.

  - Fiber optic customers had the highest churn, particularly those without streaming. Only 54.7% of fiber optic users without streaming stayed, while 45.3% churned - the highest in this analysis. Even fiber optic users with streaming had a 39.3% churn rate, showing that churn is a concern even for customers with premium services.

  - Customers without internet had the lowest churn at just 7.4%, likely because this group includes TV or landline-only customers with fewer reasons to switch.

- The data suggests that fiber optic customers may be more price-sensitive or have more competitive alternatives. It also highlights the value of service bundling, as customers with both internet and streaming services are more likely to stay.

### Customer Tenure & Early Churn Risk

- Churn at ConnectCom is highest in the first few months and gradually declines over time. Customers who stay past the first year are far more likely to remain long-term.

  - The first four months have the highest churn, with 680 customers leaving immediately. By month five, churn drops to 243 customers, a 64% decrease.

  - After nearly two years, churn stabilizes. Between months 25 and 55, around 60-80 customers leave per interval, showing a slower but steady pattern.

  - Customers who stay past five years (60+ months) are the most stable. At this point, churn is at its lowest, with fewer than 50 customers leaving per interval. 

- These patterns suggest that the first few months are the most critical for retention. Customers who leave early may be experiencing service issues, pricing concerns, or unmet expectations. If ConnectCom can improve the early customer experience, it could prevent a large share of these losses and increase long-term loyalty.

### Pricing Sensitivity & Payment Behavior

- Churn rates show a clear relationship with both monthly charges and total charges. Customers paying higher monthly fees are more likely to churn, while those with higher total charges tend to stay longer.

  - Customers with high monthly charges ($70–$100+) churn at a higher rate. A noticeable concentration of churned customers in this range suggests that price sensitivity may be a key factor driving cancellations.

  - Customers with low total charges (under $2,000) are more likely to churn, meaning they left early in their tenure. This aligns with previous findings that early-stage customers are at the highest risk of leaving.

  - Customers with high total charges ($4,000+) are more likely to stay. The majority of long-tenured customers, who have spent more over time, appear to be less likely to churn.

- These patterns indicate that pricing and perceived value play a key role in retention. Customers paying higher monthly fees may expect more from their service, while those who have stayed longer are less likely to switch providers.

---

## Recommendations
Based on the findings, the Customer Experience and Revenue Teams should prioritize the following strategies to improve retention and reduce churn:

### Increase Contract Commitment
- Develop discounted annual contract plans to encourage customers to transition from month-to-month subscriptions.
- Introduce early renewal incentives to reduce churn among high-risk contract expirations and improve retention ahead of contract renewal periods.
### Strengthen Service Bundling
- Promote fiber upgrades to DSL users to encourage migration to higher-value plans, aiming for a steady increase in fiber adoption.
- Expand streaming service bundles to appeal to high-churn customer segments and improve overall customer satisfaction.
### Enhance Early Retention Efforts
- Launch a 6-month retention initiative with personalized onboarding, engagement touchpoints, and proactive customer outreach to address early churn risks.
- Strengthen first-contact resolution in customer support to ensure a smoother service experience for new subscribers, reducing frustration-driven churn.
### Address Pricing Sensitivities
- Develop loyalty-based pricing discounts to improve renewal rates among long-tenured customers who may be considering switching providers.
- Test a tiered pricing model to provide more flexible options for different customer segments while maintaining profitability.
### Optimize Payment Methods
- Encourage credit card and bank transfer payments to reduce churn among customers using high-risk payment methods like electronic checks.
- Simplify and streamline payment processing workflows to enhance the customer experience and minimize payment-related support issues.

---

## Assumptions & Caveats
Throughout the analysis, several assumptions were made due to data limitations and external factors not captured in the dataset:

- The dataset does not specify why customers churned (e.g., service issues, competitor switching, or pricing concerns), so insights are based on behavioral trends rather than direct feedback.
- Involuntary churn due to payment failures was not explicitly recorded, meaning some churned customers may have left due to billing issues rather than voluntary cancellation.
- External factors such as competitor promotions and customer satisfaction surveys were not included but may influence churn rates.

---

- The Interactive Tableau Dashboard for exploring churn trends can be found here.
- Raw dataset can be found here.
- For more of my projects and data journey, visit my portfolio website and reach out!
  
