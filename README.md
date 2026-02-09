# SmileSync: Integrated Dental EHR & Billing Platform

## Project Overview
SmileSync is an end-to-end healthcare data project that simulates a real-world **dental EHR and insurance billing system**. The goal of this project was to model how outpatient dental data flows from **patient encounters to procedures, insurance claims, and payments**, and to analyze both **clinical utilization and revenue performance**.

---

## Objectives
- Design a relational database that reflects real dental EHR and billing workflows  
- Simulate encounter-level charge creation, payer adjustments, and patient responsibility  
- Analyze visit patterns, procedure utilization, and revenue trends using SQL  
- Build stakeholder-friendly dashboards for operational and financial insights  

---

## Tech Stack
- **Database:** MySQL  
- **Programming:** Python (ETL and billing automation)  
- **Analytics:** MySQL  
- **Visualization:** Tableau  
- **Domain:** Dental EHR, Insurance Claims, Revenue Cycle Analytics  

---

## Data Model
The database schema integrates core healthcare entities:
- **Patients** – demographic and identifier data  
- **Providers** – dentist and specialist information  
- **Encounters** – visit-level clinical records  
- **Procedures** – dental procedure codes and charges  
- **Insurance Plans** – payer details and coverage rules  
- **Payments** – payer payments, adjustments, and patient responsibility  

Primary and foreign keys were used to maintain relational integrity and support encounter-level and procedure-level analysis.

---

## Key Features
- Automated **Python–MySQL billing workflow** that calculates:
  - Allowed amounts  
  - Payer adjustments  
  - Patient out-of-pocket responsibility  
- SQL analyses to evaluate:
  - Procedure utilization trends  
  - Visit frequency and provider productivity  
  - Revenue by payer and procedure category  
- Tableau dashboard highlighting:
  - Monthly revenue trends  
  - Insurance mix and reimbursement patterns  
  - High-volume and high-value procedures  

---

## Why This Project Matters
SmileSync mirrors real healthcare analytics work:
- Uses **claims-style billing logic**, not simple aggregations  
- Reflects **outpatient EHR and revenue cycle workflows**  
- Combines clinical, financial, and operational data analysis   

---

## Repository Structure

### Raw Data
Synthetic source files representing dental EHR, clinical encounters, and insurance information:
- **`Consultation.csv`** - Patient consultation records
- **`Dept info.csv`** - Departmental details within the hospital
- **`Diagnosis.csv`** - Diagnosis records associated with patient visits  
- **`Doc. info.csv`** - Doctor details and their specializations 
- **`Ins info.csv`** - Insurance details linked to patient records  
- **`Pt. info.csv`** - Patient demographic data
- **`Treatment.csv`** - Treatment procedures associated with diagnoses
- **`Treatment Costs.csv`** - Cost details of various treatments

### Database Schema
Core database design and documentation:
- `01_database_schema.sql` – DDL scripts to create normalized tables and relationships  
- `SmileSync_ER_Diagram.pdf` – Entity Relationship diagram illustrating the data model  

### Data Pipeline & Analytics
End-to-end data processing, validation, and analysis workflow:
- `02_generate_billing.py` – Python script to simulate billing logic, payer adjustments, and patient responsibility  
- `03_data_cleaning.sql` – Data cleaning and standardization queries  
- `04_referential_integrity_tests.sql` – Validation checks for primary and foreign key consistency  
- `05_eda_clinical.sql` – Exploratory analysis of clinical encounters and procedures  
- `06_eda_revenue.sql` – Revenue, payer mix, and reimbursement analysis  
- `07_audit_data_integrity.sql` – Audit queries to identify data quality and billing anomalies  
- `db_config.py` – Database connection and configuration settings  

### Dashboards
Visualization assets for financial and operational reporting:
- `SmileSync_Revenue_Integrity_Dashboard.png` – Static snapshot of key revenue insights  
- `SmileSync_Revenue_Integrity_Dashboard.twbx` – Interactive Tableau dashboard workbook  

---

## Author
Janaki Ramya Namburu\
email: janakiramyan36@gmail.com\
LinkedIn: www.linkedin.com/in/janakiramya 
