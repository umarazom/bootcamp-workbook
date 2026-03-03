# ☁️ Week 5 Portfolio – Azure Data Fundamentals  
**Data Technician Bootcamp (Level 3)**  
**Umar Azom**

---

## 📌 Focus Areas
Cloud Computing | Azure Services | Data Governance | Relational & NoSQL Databases | Analytics | Power BI | UK Data Law | Cloud Architecture

---

# 📖 Overview

Week 5 focused on Microsoft Azure fundamentals and enterprise cloud data architecture.

This week covered:

- Cloud service models (IaaS, PaaS, SaaS)
- Cloud deployment models
- UK data protection legislation
- Relational vs Non-relational databases
- Azure SQL Database
- Azure Cosmos DB
- Power BI analytics
- Business cloud architecture proposal

---

# 🌍 Day 1 – Cloud Fundamentals

Cloud computing enables organisations to:

- Scale infrastructure instantly
- Reduce hardware and maintenance costs
- Enable secure remote collaboration
- Improve disaster recovery capability
- Access analytics and AI services without on-prem infrastructure

## Cloud Service Models

### IaaS
Virtual machines, storage and networking infrastructure.

### PaaS
Managed development platforms for building and deploying applications.

### SaaS
Fully managed applications delivered via browser (e.g. Microsoft 365, Salesforce).

---

# ⚖️ Day 2 – Data Protection & UK Law

## Legislation Covered

- Computer Misuse Act 1990  
- Police and Justice Act 2006  
- Data Protection Act 2018  
- UK GDPR  
- Copyright, Designs and Patents Act 1988  
- Consumer Rights Act 2015  

## Key Legal Principles

- Lawful processing of data  
- Data minimisation  
- Accuracy and retention control  
- Protection against unauthorised access  
- Criminalisation of hacking and malware  

---

# 🗄 Day 3 – Azure Practical Labs

---

## 🔷 Task 1 – Relational Data in Azure SQL

Used Azure SQL Database (AdventureWorks dataset).

Executed structured SQL queries including JOIN operations.

### Example Query

```sql
SELECT 
    p.ProductID,
    p.Name AS ProductName,
    c.Name AS Category,
    p.ListPrice
FROM SalesLT.Product AS p
INNER JOIN SalesLT.ProductCategory AS c
ON p.ProductCategoryID = c.ProductCategoryID;
```

### Lab Evidence

![Azure SQL Relational Query](./images/week5-day3-relational-azure-sql.png)

**Skills Demonstrated:**
- Relational schema understanding  
- INNER JOIN logic  
- Structured cloud querying  

---

## 🔷 Task 2 – Non-Relational Data (Azure Cosmos DB)

Worked with Azure Cosmos DB using a NoSQL document model.

### Example Query

```sql
SELECT *
FROM c
WHERE CONTAINS(c.name, "Helmet")
```

### Lab Evidence

![Cosmos DB NoSQL Query](./images/week5-day3-cosmosdb-nosql-query.png)

**Skills Demonstrated:**
- Document database structure  
- JSON data handling  
- Schema flexibility  

---

## 🔷 Task 3 – Data Analytics with Power BI

Built interactive dashboards using Power BI.

Created:
- Revenue by Category chart  
- Category distribution visual  
- Data relationships  

### Lab Evidence

![Power BI Dashboard](./images/week5-day3-powerbi-analytics-dashboard.png)

**Skills Demonstrated:**
- Data modelling  
- Business intelligence principles  
- Visual analytics  
- Interactive reporting  

---

# 📝 Day 4 – DP-900 Practice Exam

**Score: 46/50 (92%)**

Demonstrated strong understanding of:

- Azure data services  
- Relational vs non-relational workloads  
- Analytics solutions  
- Data governance  
- Cloud security fundamentals  

---

# 🐾 Paws & Whiskers – Azure Modernisation Proposal

Designed a secure and scalable Azure data solution for a growing UK pet shop transitioning from spreadsheets to cloud infrastructure.

## Recommended Architecture

- Azure SQL Database (structured data)  
- Azure Blob Storage (raw data ingestion)  
- Azure Data Factory (ETL automation)  
- Azure Synapse Analytics (warehouse analytics)  
- Power BI (visual dashboards)  
- Azure AD & Encryption (security & compliance)  

---

# 🛠 Skills Demonstrated

✔ Azure SQL Database  
✔ Azure Cosmos DB  
✔ Power BI Reporting  
✔ Cloud Architecture Planning  
✔ Data Governance Awareness  
✔ UK Data Law Knowledge  
✔ Relational vs NoSQL Comparison  
✔ Enterprise Cloud Design  

---

# 🎯 Week 5 Summary

Week 5 strengthened both theoretical and practical cloud data knowledge.

I demonstrated the ability to:

- Explain cloud service and deployment models  
- Apply UK data legislation to business scenarios  
- Work with relational and NoSQL databases  
- Build analytical dashboards  
- Design scalable Azure solutions  

This week marked a progression from database fundamentals to enterprise-level cloud data strategy.
