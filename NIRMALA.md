# Project Detail – Nirmala Trading

## Overview
Nirmala Trading is a **custom web-based management system** designed to handle the trading operations of a fish supply and distribution business. The system provides tools for recording purchases, factory deliveries, tonnage discrepancies, and financial summaries — enabling transparent, efficient, and real-time tracking of trading activities.

## Technical Stack
- **Frontend:** PHP (Laragon environment) with Bootstrap for responsive UI  
- **Backend:** Native PHP API with structured modules (CRUD per table)  
- **Database:** MySQL (phpMyAdmin) with normalized schemas for operations and finance  
- **Deployment:** Shared hosting with Apache (public_html structure)  
- **Version Control:** Git (local + remote repository for project backup)  

## Key Features
1. **Fish Purchase Management**
   - Record truck arrivals, tonnage, price per kg, and purchase amount  
   - Integrated modal forms for quick data entry  

2. **Factory Income Recording**
   - Log factory delivery tonnage and revenue generated  
   - Automated calculation of income per delivery note  

3. **Tonnage Discrepancy Tracking**
   - Compare trading vs. factory tonnage  
   - Highlight discrepancies and shrinkage for accountability  

4. **Trading Summary**
   - Monthly/periodic summary of income, purchases, and profit  
   - Automatic calculation of total discrepancy (income – purchases)  

5. **Reporting & Export**
   - Multi-sheet Excel report (purchases, income, discrepancy, summary)  
   - Downloadable by selected month/year  

## Workflow
- **Planning:** Defined entity relationship diagrams (ERD) for operational tables  
- **Development:** Modular PHP scripts (api/ for logic, views/ for UI, database/ for config)  
- **Testing:** Manual verification on data accuracy and calculation formulas  
- **Deployment:** Deployed on Laragon (local) → migrated to hosting for live usage  

## Challenges & Solutions
- **Data Consistency:** Solved by using UUID v4 as primary keys across all tables  
- **Audit Trail:** Implemented created_at, updated_at, deleted_at columns for all entities  
- **Report Accuracy:** Ensured aggregation logic handles duplicate dates and sums correctly  

---

**Status:** 🚧 Actively in Use (operational phase)  
**Next Step:** Expansion with **login system, audit logging, and dynamic financial dashboard**
