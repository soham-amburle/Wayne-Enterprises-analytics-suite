# Wayne Enterprises | Business Intelligence Suite (Power BI)  
**by Soham S. Amburle**
 
Start Date: 10 April, 2026 
End Date: 22 August, 2026

## Project Overview 

This project simulates an **enterprise-grade Business Intelligence solution** for a diversified conglomerate similar to Wayne Enterprises, built using **Power BI** and a large-scale **synthetic dataset (~100,000 records)**.

The objective is to demonstrate how executive leadership, R&D divisions, defense operations, corporate departments, and strategic intelligence units can leverage data-driven dashboards to monitor **financial performance, operational efficiency, innovation impact, risk exposure, and city-level intelligence insights**.

This solution uniquely combines **real-world corporate analytics** with **cinematic elements from Gotham City**, creating a hybrid BI ecosystem.

The system is designed as a **15-dashboard enterprise analytics suite**, similar to BI platforms used in multinational corporations.

---

## Dashboard Suite Structure

1. Executive Strategy Overview  
2. Finance & Investment Analytics  
3. Applied Sciences (R&D) Insights  
4. Defense Contract Performance  
5. Global Supply Chain Command Centre  
6. Global Operations Dashboard  
7. Marketing & Brand Performance  
8. Sales & Partnerships Analytics  
9. Human Resources Insights  
10. Wayne Tech Product Performance  
11. Bat-Tech Operations Dashboard  
12. Gotham City Intelligence Analysis  
13. Security & Risk Management  
14. Sustainability & CSR Impact  
15. Innovation Pipeline Dashboard  

---

## Key Business Areas Covered

* Executive-level KPI monitoring and strategic alignment  
* Financial performance and investment return analysis  
* R&D efficiency and innovation impact tracking  
* Defense contracts profitability and risk assessment  
* Supply chain efficiency and operational bottlenecks  
* Regional performance and global operations insights  
* Marketing campaign effectiveness and brand perception  
* Sales growth and strategic partnerships analysis  
* Employee performance, retention, and workforce insights  
* Product adoption and lifecycle performance  
* Specialized asset utilization (Bat-Tech operations)  
* Crime pattern analysis and response effectiveness in Gotham  
* Enterprise security risks and vulnerability assessment  
* Environmental impact and corporate social responsibility  
* Future innovation and high-potential project tracking  

---

## Dataset

* **Dataset Size:** ~100,000 synthetic records  
* **Data Structure:** Hybrid Star Schema (Star + selective Snowflake normalization)  
* **Time Period:** Simulated multi-year enterprise activity  

The dataset is fully synthetic and does **not** contain any real corporate data. It is created strictly for **analytics, visualization, and portfolio demonstration purposes**.

---

## Data Model Structure

### Fact Tables (Transactional / Event-Level Data)

1. **Fact_Finance** – Revenue, cost, profit, investments  
2. **Fact_Sales** – Product sales and client transactions  
3. **Fact_Operations** – Operational efficiency and delays  
4. **Fact_Marketing** – Campaign performance metrics  
5. **Fact_HR** – Employee performance and attrition  
6. **Fact_RnD** – Innovation projects and investments  
7. **Fact_DefenseContracts** – Contract value, cost, and risk  
8. **Fact_BatOperations** – Mission-level asset usage and outcomes  
9. **Fact_CrimeData** – Gotham crime incidents and response metrics  
10. **Fact_SupplyChain** – Logistics, suppliers, and delivery performance  

---

### Dimension Tables (Descriptive Data)

**Organizational Dimensions**

* Dim_Department  
* Dim_Employee  

**Business Dimensions**

* Dim_Product / Asset  
* Dim_Client / Partner  

**Geographic Dimensions**

* Dim_Region (Country, City, Gotham)  

**Time Dimensions**

* Dim_Date (Year, Quarter, Month, Week)  

---

## Dataset Tables Overview

### Fact Tables

1. Fact_Finance  
2. Fact_Sales  
3. Fact_Operations  
4. Fact_Marketing  
5. Fact_HR  
6. Fact_RnD  
7. Fact_DefenseContracts  
8. Fact_BatOperations  
9. Fact_CrimeData  
10. Fact_SupplyChain  

### Dimension Tables

11. Dim_Date  
12. Dim_Department  
13. Dim_Region  
14. Dim_Employee  
15. Dim_Product  
16. Dim_Client  

---

## Data Model Design

* **Hybrid Star Schema architecture**
* Multiple fact tables for domain-specific analytics  
* Shared dimension tables enabling cross-functional insights  
* Optimized for Power BI performance and scalability  
* Advanced DAX measures for KPIs and time intelligence  
* Drill-down capabilities across departments and regions  
* Interactive navigation across dashboards  

---

## Tools & Technologies

* Power BI Desktop  
* DAX (advanced KPIs and calculations)  
* Data Modeling (Star Schema + Hybrid design)  
* Synthetic data generation (Python / Excel)  
* Dashboard design and storytelling  

---

## Project Goals

* Simulate a real-world **enterprise BI ecosystem**  
* Demonstrate advanced **Power BI dashboard development**  
* Build **decision-driven dashboards** aligned with business questions  
* Showcase **cross-domain analytics** (finance, operations, intelligence)  
* Combine **storytelling with data analytics** for portfolio differentiation  

---

## Disclaimer

This project is **not affiliated with DC Comics or any real organization**.  
All data is synthetic and created solely for **educational and portfolio purposes**.
