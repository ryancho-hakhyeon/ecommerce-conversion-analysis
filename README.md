# E-commerce Customer Behavior & Conversion Analysis

**Status:** In Progress

## Project Overview
This project analyzes user behavior and purchase conversion patterns using the Google Analytics 4 E-commerce public dataset from the Google Merchandise Store.

The goal is to identify opportunities to improve conversion rates, understand customer acquisition performance, and reduce drop-offs in the purchase funnel.

## Business Problem
How can an e-commerce business improve purchase conversions by understanding user behavior, traffic acquisition channels, and the customer purchase journey?

## Dataset
- **Source:** Google Analytics 4 E-commerce Sample Dataset
- **Platform:** Google BigQuery
- **Period:** November 2020 – January 2021
- **Data Type:** Anonymized user event data

## Tools & Technologies
- SQL (Google BigQuery)
- Python (Pandas, Matplotlib)
- Power BI or Tableau
- GitHub

## Key Business Questions
1. How do purchasing and non-purchasing users behave differently?
2. Which traffic sources generate the highest purchase conversion rates?
3. At which stage of the purchase funnel do users drop off?
4. Which customer segments represent the greatest conversion improvement opportunities?

## Project Roadmap
- [x] Define business objectives and KPIs
- [ ] Explore and validate the dataset
- [ ] Transform data using SQL
- [ ] Analyze customer behavior and conversion funnels
- [ ] Build an interactive dashboard
- [ ] Present findings and business recommendations

## Key Findings
*To be added after analysis.*

## Business Recommendations
*To be added after analysis.*


---


# Step 1 — Business Problem & KPI Definition

## Business Scenario
Google Merchandise Store is an e-commerce website that sells Google-branded merchandise. This project uses anonymized GA4 event data to investigate website engagement, customer acquisition, purchase behavior, and conversion opportunities.

## Business Problem
How can Google Merchandise Store identify opportunities to improve purchase conversion performance and revenue through customer behavior analysis?

## Project Objectives
1. Understand website sessions and purchasing behavior.
2. Compare conversion performance across user segments.
3. Evaluate traffic acquisition channels.
4. Identify drop-off points in the purchase funnel.
5. Recommend data-driven business improvements.

## Project Focusing
Main         - End-to-End E-commerce Conversion Analysis  
Extension A  - Conversion Funnel Optimization  
Extension B  - Marketing Channel Performance  

## Primary KPIs
- Total Sessions
- Session Purchase Conversion Rate
- Purchasing Users
- Purchase Revenue
- Average Order Value
- Funnel Step Conversion Rates
- Traffic Channel Conversion Rates

## Analytical Approach
Use BigQuery SQL to reconstruct sessions, calculate conversion metrics, and analyze the customer purchase journey. Use Python and a BI dashboard to communicate findings and business recommendations.

## Data Limitations
The dataset is anonymized and may contain missing or obfuscated values. Event completeness, session identification, traffic attribution, and revenue consistency will be validated before finalizing metric calculations.

## Expected Outcome
A set of actionable, evidence-based recommendations to prioritize opportunities for improving e-commerce conversion performance.
