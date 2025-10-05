# <img width="162" height="49" alt="image" src="https://github.com/user-attachments/assets/26cd9429-9ccb-44ab-9104-5045b97a0b87" />
# Clevertronics BI Projects

This repository documents my work as a **Business Intelligence Developer** at **Clevertronics**, an electronics manufacturing company specialising in emergency lighting solutions.  
It showcases projects across **Power BI**, **SQL Data Warehouse**, **NetSuite ERP**, and **Celigo ETL** integration.

---

## Business Context  
Clevertronics operates across Australia, New Zealand, and the UK.  
As the company expanded rapidly, departments adopted their own specialised software, creating **data silos**, **inconsistent reporting**, and **fragmented workflows**.  
My role was to unify these systems, automate reporting, and modernise the company’s analytics infrastructure.

---

## Objectives
- Centralise fragmented sales and operational data across multiple systems (Syteline ERP, Dynamics 365 CRM, NetSuite)
- Deliver a unified Power BI reporting environment with 34 specialised reports
- Implement ETL pipelines and data warehouse layers for scalable reporting
- Automate data refreshes, subscriptions, and user access management

---

## Major Projects  

### **1. Enterprise Power BI Reporting System (34 Reports)**  
- Delivered **34 specialised sales reports** for BDM (D2D, Projects & Upgrades), CSO (RMA, Quoting, Expediting), and State Manager (summarised performance) levels.  
- Integrated data from **Dynamics 365 CRM**, **Syteline ERP**, and later **NetSuite** to maintain accurate reporting post–NetSuite Go-Live.  
- Implemented **Row-Level Security (RLS)** for over 120 users and set up automated PDF subscriptions via **Power BI Service**.  
- Involved **complex data modelling, mapping, Power Query transformations, SQL scripting, and ETL pipeline development**.  

---

### **2. Sales Budgeting Report**  
- Built a consolidated budgeting dashboard that summarised the 34 reports into **key KPI tables**.  
- Designed **DAX-driven calculations** showing the full sales pipeline — from total opportunity → conversion → open order book → revenue, segmented by **state and national levels**.  
- Focused on **optimised DAX**, **Power Query** efficiency, and **data model performance tuning**.  

---

### **3. Data Warehouse & ETL Integration**  
- Developed a **multi-layer data architecture** (Staging → Silver → Gold) in **SQL Server**.  
- Designed and implemented **8 Celigo pipelines** to extract Product, Finance, Sales, and Supply-Chain data from NetSuite into the Data Warehouse.  
- Reduced Power Query and DAX complexity by shifting heavy transformations to SQL.  
- Deployed a **standard on-premises gateway** for automated, 24/7 Power BI refreshes.  

---

### **4. Data Migration to NetSuite**  
- Converted legacy **Syteline SQL stored procedures** into **NetSuite Saved Searches**.  
- Exported and transformed **D365 CRM tables** using advanced Excel templates for import into NetSuite.  
- Validated and reconciled migrated data to ensure reporting accuracy and continuity across systems.  

---

### **5. Python Custom Visuals in Power BI**  
- Replicated and enhanced **Dynamics 365 and other third-party visuals** using **Python-based Power BI custom visuals**.  
- Embedded interactive visuals as **iFrames within NetSuite**, enabling real-time analytics access directly inside the ERP.  

---

### **6. SharePoint Data Ownership & Automation**  
- Migrated manual Excel-based data sources to **SharePoint Cloud**, allowing business data owners to manage inputs directly.  
- Established **automated Power BI connections** to SharePoint for near real-time updates and reduced maintenance overhead.  

---

## Tech Stack
| Area | Tools & Technologies |
|------|----------------------|
| Visualization | Power BI (Service, Desktop, DAX, RLS, Gateways) |
| Data Warehouse | SQL Server, SSMS, SSIS |
| ETL | Celigo, Power Query |
| ERP/CRM | NetSuite, Dynamics 365 CRM, Infor Syteline |
| Collaboration | SharePoint, Outlook |

---

**© 2025 Abdul Mahi**  
All rights reserved.  
