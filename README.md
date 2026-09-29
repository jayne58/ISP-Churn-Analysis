# ISP-Churn-Analysis
Prepaid ISP Customer Retention and Churn Analysis in Power BI &amp; Predictive Machine Learning in Python

## Overview

This project analyzes customer churn within an ISP environment to identify patterns in customer attrition and understand the factors associated with churn.

The analysis focuses on **customer tenure, service experience, complaints, and payment behaviour** to identify periods and customer behaviours associated with higher churn.

The goal was to understand the key churn patterns and translate the findings into actionable business recommendations to support customer retention.

---

## Tools Used

* Power BI (data cleaning, data modelling, analysis and visualization)
* SQL
---

## Business Questions Answered

* At what stage of the customer lifecycle does most churn occur?
* How does churn vary by customer tenure?
* What types of churn are observed among new customers?
* How does complaint frequency relate to churn?
* How does missed-payment behaviour relate to churn?
* What customer behaviours are associated with higher churn?
* What actions can the business take to improve customer retention?

---

## Key Insights

### Tenure & Churn

* **21% of the installed cohort churns within the first 6 months**, highlighting early tenure as an important period for customer retention.
* The largest customer losses occur during the early stages of the customer lifecycle.
* The nature of churn changes as customers progress through different tenure periods.

---

### Service Experience & Churn

* Silent churn accounts for **56% of churn among customers in months 0–3**.
* By months 4–6, service-friction churn becomes more prominent, accounting for **56% of churn**.
* This suggests that the nature of customer churn may change as the customer relationship develops.

---

### Complaints & Churn

* Churn rates increase as complaint frequency increases.
* Customers with **5+ complaints per month have an 83% churn rate**, compared with 58% among customers with no complaints.
* Customers with repeated complaints represent a group that may require proactive attention.

---

### Payment Behaviour & Churn

* Customers with no missed payments have a **55% churn rate**.
* Churn increases with missed-payment frequency.
* Customers with five missed payments have a **77% churn rate**.
* Payment behaviour therefore provides an important indicator of differences in churn behaviour.

---

## Business Recommendations

### Improve Early Customer Engagement

* Introduce **customer onboarding 7–14 days after installation** to capture the customer's initial experience and identify early issues.
* Introduce **customer health checks 14–20 days during a customer's subscription** to identify service or customer-experience issues and address them proactively.

### Align Sales Incentives with Customer Retention

* Split sales commissions across **M1, M2 and M3** instead of paying the full commission upfront.
* Link subsequent commission payments to continued customer activity.
* This would align sales incentives with **customer acquisition quality and retention**, rather than acquisition alone.

### Proactively Address Customer Friction

* Monitor customers with repeated complaints and prioritize them for proactive intervention.

### Monitor Payment Behaviour

* Identify customers developing repeated missed-payment patterns.
* Introduce discounts for customers showing increasing payment irregularity.

---

## Dashboard Features

* New customer retention analysis
* Silent vs. service-friction churn analysis
* Churn rate by complaint frequency
* Churn rate by missed payments
* Interactive filtering and segmentation

---

## Project Outcome

The analysis identified several customer characteristics and behaviours associated with higher churn, particularly **early tenure, repeated complaints, and irregular payment behaviour**.

These findings provide a basis for developing targeted customer-retention strategies and form the foundation for the next stage of the project: **churn prediction**.

---

## Files Included

* Power BI Dashboard (`.pbix`)
* Dashboard screenshots
* Presentation (`.pptx`)
