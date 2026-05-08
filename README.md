# 🦷 Dental Clinic Profitability Dashboard

An end-to-end Healthcare Analytics and Business Intelligence project built using Power BI to analyze dental clinic profitability, operational efficiency, patient behavior, and treatment performance.

This project transforms raw healthcare operational data into actionable business insights using interactive dashboards, KPI tracking, DAX measures, and data modeling techniques.

---

# 📌 Project Objective

The primary goal of this project is to identify:

- Why certain dental clinics are more profitable than others
- Which operational inefficiencies reduce profitability
- How treatment types impact revenue generation
- How wait times and no-show rates affect clinic performance
- Which strategies can improve operational efficiency and profit margins

---

# 📊 Dashboard Features

The dashboard includes:

## Executive KPI Cards
- Total Revenue
- Total Profit
- Profit Margin
- Average Wait Time
- No-Show Rate
- Revenue Per Patient

## Operational Analytics
- Clinic-wise performance comparison
- Wait time analysis
- No-show trend analysis
- Appointment efficiency tracking

## Financial Insights
- Revenue trends
- Profitability analysis
- Treatment contribution analysis
- Cost structure analysis

## Interactive Features
- Dynamic filters
- Year-over-Year comparison
- Interactive visuals
- Custom HTML KPI cards
- Responsive dashboard layout

---

# 🏗️ Project Architecture

## Data Processing Workflow

1. Raw Healthcare Data Collection
2. Data Cleaning & Transformation
3. Data Modeling
4. DAX KPI Calculations
5. Dashboard Development
6. Business Insight Generation

---

# 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

- Removed duplicate appointment IDs
- Standardized clinic location names
- Fixed data type inconsistencies
- Created dynamic calendar/date table
- Optimized Power BI data model
- Cleaned missing and invalid values

---

# 🗂️ Data Model

The project uses a Star Schema Model.

## Fact Table
Contains:
- Appointments
- Revenue
- Costs
- Treatments
- Patient metrics

## Dimension Tables
- Date Table
- Location Table
- Treatment Table

---

# 📈 Key KPIs

| KPI | Description |
|---|---|
| Total Revenue | Overall clinic revenue |
| Total Profit | Revenue after operational costs |
| Profit Margin | Profitability percentage |
| Avg Wait Time | Average patient waiting duration |
| No-Show Rate | Missed appointment percentage |
| Revenue Per Patient | Revenue generated per patient |

---

# 🔍 Key Business Insights

## High Performing Clinics
New York clinics generated the highest profit margins because of:
- Better operational efficiency
- Lower wait times
- Strong treatment mix
- Higher-value procedures

## Underperforming Clinics
Chicago and Houston experienced:
- High patient wait times
- Increased no-show rates
- Lower operational efficiency
- Margin decline

## Treatment Insights
High-margin treatments such as:
- Whitening
- Fillings
generated significantly more revenue than basic procedures.

---

# 💡 Strategic Recommendations

Based on the analysis:

- Reduce patient wait times
- Improve appointment scheduling
- Implement automated reminders
- Promote high-value treatments
- Replicate operational models from top-performing clinics

---

# 🛠️ Tech Stack

## Tools & Technologies
- Power BI
- DAX
- Power Query
- Data Modeling
- Healthcare Analytics

---

# 📸 Dashboard Preview

## Executive Dashboard
(Add Screenshot Here)

## KPI Overview
(Add Screenshot Here)

## Operational Efficiency Analysis
(Add Screenshot Here)

## Treatment Performance Analysis
(Add Screenshot Here)

---

# 📂 Repository Structure

```text
Dental-Clinic-Profitability-Dashboard/
│
├── dashboard/
├── dataset/
├── presentation/
├── dax-measures/
├── documentation/
├── screenshots/
└── README.md
