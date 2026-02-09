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
- **`Consultation.txt`** - Patient consultation records.  
- **`Dept info.txt`** - Departmental details within the hospital.  
- **`Diagnosis.txt`** - Diagnosis records associated with patient visits.  
- **`Doc. info.txt`** - Doctor details and their specializations.  
- **`Ins info.txt`** - Insurance details linked to patient records.  
- **`Pt. info.txt`** - Patient demographic data.  
- **`Treatment Costs.txt`** - Cost details of various treatments.  
- **`Treatment.txt`** - Treatment procedures associated with diagnoses.  
- **`README.md`** - Documentation of this project.

## Author
Janaki Ramya Namburu\
email: janakiramyan36@gmail.com\
LinkedIn: www.linkedin.com/in/janakiramya 
