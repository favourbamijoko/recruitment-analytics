# Recruitment Analytics Dashboard

## Project Overview

This project analyses a simulated recruitment dataset to identify patterns in hiring performance, recruitment funnel conversion, time-to-hire, and recruitment source effectiveness.

The goal is to show how HR data can support recruitment decisions and identify where candidates are lost during the hiring process.

## Project Objectives

* Analyse the recruitment funnel from application to hire.
* Measure conversion rates at each recruitment stage.
* Identify the largest candidate drop-off point.
* Analyse time-to-hire across the recruitment process.
* Compare recruitment sources based on hiring and offer acceptance rates.
* Present the findings through an interactive Power BI dashboard.

## Dataset

The dataset contains **500 candidate records** and includes information such as:

* Candidate ID
* Department
* Role
* Application Date
* Application Source
* Screening Status and Score
* Assessment Status and Score
* Interview Status and Score
* Offer Made
* Offer Accepted
* Recruitment Status
* Hire Date

## Tools Used

* **Microsoft Excel** — data preparation and initial analysis
* **Microsoft Power BI** — dashboard development and data visualisation

## Analysis

### Recruitment Funnel

The recruitment funnel tracks candidates through each major stage:

| Recruitment Stage | Candidates |
| ----------------- | ---------: |
| Applications      |        500 |
| Screening Passed  |        414 |
| Assessment Passed |        355 |
| Interview Passed  |        309 |
| Offers Made       |        225 |
| Offers Accepted   |        194 |
| Hired             |        194 |

The overall hiring rate was **38.8%**.

The largest candidate drop-off occurred between the interview and offer stages, where **84 candidates** were lost. The interview-to-offer conversion rate was **72.8%**.

### Time-to-Hire

| Metric               | Result |
| -------------------- | -----: |
| Average Days to Hire |   40.5 |
| Median Days to Hire  |     41 |
| Minimum Days to Hire |     18 |
| Maximum Days to Hire |     62 |

Average time-to-hire by application source:

| Application Source          | Average Days to Hire |
| --------------------------- | -------------------: |
| LinkedIn                    |                 41.1 |
| Employee Referral           |                 41.9 |
| Company Careers Page        |                 38.5 |
| Job Board                   |                 41.6 |
| University/Graduate Program |                 38.5 |

### Recruitment Source Performance

| Application Source          | Hiring Rate | Offer Acceptance Rate |
| --------------------------- | ----------: | --------------------: |
| Employee Referral           |       45.7% |                 95.6% |
| Company Careers Page        |       43.9% |                 88.7% |
| LinkedIn                    |       41.5% |                 86.8% |
| University/Graduate Program |       31.3% |                 68.2% |
| Job Board                   |       27.5% |                 81.1% |

## Key Findings

* **38.8%** of applicants were ultimately hired.
* **84 candidates** were lost between the interview and offer stages, the largest drop-off in the recruitment funnel.
* The interview-to-offer conversion rate was **72.8%**.
* **Employee referrals** had the highest hiring rate at **45.7%**.
* **Job boards** had the lowest hiring rate at **27.5%**.
* Employee referrals also had the highest offer acceptance rate at **95.6%**.
* University/graduate programmes had the lowest offer acceptance rate at **68.2%**.
* Average time-to-hire was **40.5 days**.

## HR Implications

The findings suggest that the transition from interviews to offers deserves attention because it represents the largest candidate drop-off in the recruitment process.

Employee referrals performed strongly on both hiring rate and offer acceptance rate. This makes referrals an important recruitment source to monitor when assessing channel effectiveness.

The differences in offer acceptance rates across sources also show why recruitment analysis should look beyond application volume and consider candidate outcomes at later stages.

## Dashboard

The Power BI dashboard contains three pages:

1. **Recruitment Overview** — key recruitment KPIs and candidate outcomes.
2. **Recruitment Funnel** — candidate movement through each recruitment stage.
3. **Source Performance** — comparison of recruitment sources based on hiring and offer acceptance performance.

## Project Outcome

This project demonstrates how recruitment data can be transformed into practical HR insights through data analysis and dashboard design. It focuses on recruitment funnel performance, time-to-hire, and source effectiveness to support better recruitment decision-making.
