# telecom-complaint-analytics
Applied quantitative project analyzing telecom customer complaints with severity scoring model and dashboard in Airtable

## Overview

This project focuses on **analyzing telecom customer complaints** to extract actionable insights about service quality across providers and regions.  
It demonstrates applied analytical skills, including:

- **Descriptive statistics**: understanding distributions and averages  
- **Trend analysis**: identifying patterns over time and across regions  
- **Simple modeling**: quantifying complaint severity using a formula  
- **Data visualization**: interactive dashboards in Airtable

The dataset and project structure are designed to showcase **low-code applied quantitative analysis**, making it accessible while highlighting applied data handling and modeling skills.

---

## Dataset

The dataset contains **15 sample telecom complaints**, each with detailed information:

| Field | Description |
|-------|-------------|
| Complaint ID | Unique identifier for each complaint |
| Date | Date the complaint was received |
| Provider | Telecom provider (MTN, Airtel, Glo, 9mobile) |
| Category | Type of complaint (Network Outage, Call Drop, Slow Internet, Billing Issue, Customer Service) |
| Region | Geographic region (Lagos, Abuja, Rivers, Kano, Enugu) |
| Resolution Time (Days) | Number of days taken to resolve the complaint |
| Status | Current status (Resolved / Pending) |
| Satisfaction (1–5) | Customer satisfaction rating, 1 = lowest, 5 = highest |
| Category Weight | Numeric weight assigned to complaint category based on severity |
| Severity Score | Computed numeric score based on Resolution Time, Category Weight, and Satisfaction |
| Risk Level | Classification of severity (Low / Medium / High) |

The dataset is stored in `data/complaints_sample.csv` for reference.

---

## Methods

### 1. Descriptive Statistics

Descriptive statistics were calculated to summarize key metrics:

- **Total complaints per provider**: identifies which provider has the highest complaint load  
- **Total complaints per category**: highlights common customer issues  
- **Average resolution time**: measures operational efficiency  
- **Median satisfaction score**: evaluates overall customer satisfaction  
- **Regional distribution**: shows areas with higher complaint frequency  

> Example: Lagos had the highest complaint frequency, indicating potential network issues in that region.

---

### 2. Trend and Comparative Analysis

- **Complaint trends over time**: identify recurring spikes or monthly patterns  
- **Provider comparison**: understand which providers face more critical complaints  
- **Category comparison**: identify which issues are most severe or frequent  

> Example: Network Outages and Call Drops are the most frequent high-severity complaints, mainly affecting MTN and Airtel.

---

### 3. Applied Modeling: Severity Score

A **Severity Score** formula was created to quantify complaint urgency:




