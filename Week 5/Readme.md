# ☁️ Week 5 Portfolio – Azure Data Fundamentals  
**Data Technician Bootcamp (Level 3)**  
**Umar Azom**

---

## 📌 Focus Areas
Cloud Computing | Azure Services | Data Governance | Relational & NoSQL Databases | Analytics | Power BI | UK Data Law | Cloud Architecture

---

# 📖 Overview

Week 5 focused on Microsoft Azure fundamentals and enterprise cloud data architecture.

The week covered:

- Cloud service models (IaaS, PaaS, SaaS)
- Cloud deployment models
- UK data protection legislation
- Relational vs Non-relational databases
- Azure SQL Database
- Azure Cosmos DB
- Power BI analytics
- Business cloud architecture proposal

This week bridged theory with practical Azure lab experience.

---

# 🌍 Day 1 – Cloud Fundamentals

## What Cloud Computing Provides

Cloud computing allows organisations to:

- Scale infrastructure instantly
- Reduce hardware and maintenance costs
- Enable secure remote collaboration
- Improve disaster recovery capability
- Access AI and analytics services without owning servers

## Business Benefits

- Reduced capital expenditure
- Pay-as-you-go pricing model
- High availability and redundancy
- Global accessibility
- Built-in compliance and security controls

---

# 🏗 Cloud Service Models

## IaaS (Infrastructure as a Service)

Provides virtual machines, storage, and networking infrastructure.

**Use cases:**
- Hosting websites
- Development environments
- High-performance computing
- Backup and disaster recovery

---

## PaaS (Platform as a Service)

Provides managed development platforms.

**Use cases:**
- API development
- Application deployment
- DevOps automation
- IoT data processing

---

## SaaS (Software as a Service)

Fully managed applications delivered via web browser.

**Examples:**
- Microsoft 365
- Salesforce
- Slack
- Zoom

---

# ⚖️ Day 2 – Data Protection & UK Law

## Legislation Covered

- Computer Misuse Act 1990
- Police and Justice Act 2006
- Data Protection Act 2018
- UK GDPR
- Copyright, Designs and Patents Act 1988
- Consumer Rights Act 2015

## Computer Misuse Act – Key Areas

1. Unauthorised access (hacking)
2. Access with intent to commit further offences
3. Impairing operation of a computer system

## Police & Justice Act Enhancements

- Increased sentencing powers
- Criminalisation of hacking tool distribution
- Expanded definition of system impairment (e.g. DDoS)

---

# 🗄 Day 3 – Azure Practical Labs

---

## 🔷 Task 1 – Relational Data in Azure SQL

Used Azure SQL Database (AdventureWorks dataset).

Executed structured SQL queries including JOIN operations to retrieve related product and category data.

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

![Azure SQL Relational Query](images/week5-day3-relational-azure-sql.png)

**Skills Demonstrated:**
- Relational schema understanding
- INNER JOIN logic
- Structured query execution
- Cloud-hosted database interaction

---

## 🔷 Task 2 – Non-Relational Data (Azure Cosmos DB)

Worked with Azure Cosmos DB using a NoSQL document model.

Queried JSON documents using SQL-style syntax.

### Example Query

```sql
SELECT *
FROM c
WHERE CONTAINS(c.name, "Helmet")
```

### Lab Evidence

![Cosmos DB NoSQL Query](images/week5-day3-cosmosdb-nosql-query.png)

**Skills Demonstrated:**
- Document-based database structure
- Schema flexibility
- JSON data querying
- NoSQL concepts

---

## 🔷 Task 3 – Data Analytics with Power BI

Created interactive reports using Power BI connected to Azure data sources.

Built:

- Revenue by Category visual
- Category distribution pie chart
- Data model relationships
- Interactive filtering

### Lab Evidence

![Power BI Dashboard](images/week5-day3-powerbi-analytics-dashboard.png)

**Skills Demonstrated:**
- Data modelling
- Business intelligence principles
- Visual analytics
- Report interactivity

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

## Objective

Design a secure, scalable Azure data solution for a growing UK pet shop transitioning from spreadsheets to cloud infrastructure.

---

## Compliance Requirements

- UK GDPR
- Data Protection Act 2018
- PCI DSS (payment processing)
- PECR (marketing communications)

Implemented principles:

- Data minimisation
- Encryption at rest and in transit
- Role-based access control
- Data retention policies
- Audit logging

---

## Recommended Azure Architecture

### Storage Layer
- Azure SQL Database (structured operational data)
- Azure Blob Storage (raw data ingestion)

### Integration
- Azure Data Factory (ETL automation)

### Analytics
- Azure Synapse Analytics
- Power BI dashboards

### Security
- Azure AD authentication
- Transparent Data Encryption
- Private endpoints
- Geo-redundant backups

---

# 🛠 Skills Demonstrated

✔ Cloud architecture understanding  
✔ Azure SQL Database  
✔ Azure Cosmos DB  
✔ Power BI reporting  
✔ UK data law knowledge  
✔ Relational vs NoSQL comparison  
✔ Enterprise cloud planning  
✔ Data governance awareness  

---

# 🎯 Week 5 Summary

Week 5 strengthened both theoretical and practical cloud data knowledge.

I demonstrated the ability to:

- Explain cloud service and deployment models
- Apply UK data legislation to business scenarios
- Work with relational and NoSQL databases
- Build analytical dashboards
- Design scalable Azure solutions
- Translate business requirements into technical architecture

This week marked a transition from database fundamentals toward enterprise-level cloud data strategy.

---
