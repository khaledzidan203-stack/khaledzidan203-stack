<div align="center">

# Khaled Zidan

### Healthcare Data Analytics · Business Intelligence · Analytics Engineering

**I build governed analytics systems that connect source data, business logic, semantic models, validation, and decision support — not just dashboards.**

<p>
  <img src="https://img.shields.io/badge/Healthcare%20Analytics-0B5CAD?style=for-the-badge" alt="Healthcare Analytics">
  <img src="https://img.shields.io/badge/Business%20Intelligence-1F6FEB?style=for-the-badge" alt="Business Intelligence">
  <img src="https://img.shields.io/badge/Analytics%20Engineering-2EA043?style=for-the-badge" alt="Analytics Engineering">
</p>

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=000" alt="Power BI">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=fff" alt="SQL">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=fff" alt="Python">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=fff" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=fff" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/FHIR-E34F26?style=flat-square" alt="FHIR">
</p>

[**LinkedIn**](https://www.linkedin.com/in/khaled-zidan-7400a51a3) · [**Flagship Healthcare Platform**](https://github.com/khaledzidan203-stack/healthcare-interoperability-claims-intelligence) · [**Full Repository Portfolio**](https://github.com/khaledzidan203-stack?tab=repositories)

</div>

---

## What I Build

I work at the intersection of **healthcare domain knowledge, business intelligence, data analytics, and analytics engineering**.

My projects typically follow this pattern:

**Source → Data Quality → Canonical Model → SQL / Python → Semantic Model → Governed KPIs → BI Delivery → Independent Validation → Decision Support**

The goal is not to make a chart look impressive. The goal is to make the **number behind the chart defensible**.

That means I consistently focus on:

- explicit analytical grain before aggregation;
- governed KPI definitions and ratio-of-totals logic;
- missing / suppressed / unavailable values that remain semantically distinct from zero;
- independent reconciliation across SQL, Python, DAX, Excel, or source artifacts;
- preservation of source anomalies instead of silently “cleaning” them away;
- lineage, reproducibility, tests, and CI as part of analytics delivery;
- clear boundaries between descriptive evidence and unsupported causal claims.

---

## Evidence at Scale

These are not generic demo claims — they come from implemented, documented projects in this GitHub account.

| Project | Selected validated engineering evidence |
|---|---|
| **Healthcare Interoperability & Claims Intelligence** | CMS Blue Button/FHIR pipeline · OAuth 2.0 + PKCE · PostgreSQL · **94 regression tests** · **22 business tables** · **50 relationships** · **7-page PBIR report** |
| **Healthcare Data Governance & Quality Control Center** | **2,801,660 published profiles** · **70,052,393 represented line items** · **19 governed DQ rules** · SQL/Python/DAX reconciliation · 7-page Power BI delivery |
| **CMS Transparency in Coverage PUF Analytics** | **4,956 plans** · **348 issuers** · **30 states** · **43 DAX measures** · **11 PBIR pages** · **63 DAX reconciliation checks / 0 failures** |
| **Hospital360** | **5,000 synthetic patients** · **5,515,928 healthcare RAW rows** · **36-month enterprise extension** · PostgreSQL RAW→STAGING→ANALYTICS · **13-page Power BI report** |
| **Online Retail Growth & Customer Intelligence** | **1,044,848 canonical transaction rows** · RFM + cohorts + retention · **50 DAX measures** · **10 Power BI pages** · SQL-driven Excel management outputs |
| **Regional Sales Performance Analytics** | **18-page analytical engine** · LFL / AST / recovery / lifecycle analysis · XLSX export · reproducible offline frontend · Tauri/Rust desktop packaging architecture |

---

## Flagship Projects

### 🏥 Healthcare Interoperability & Claims Intelligence Platform
[View repository →](https://github.com/khaledzidan203-stack/healthcare-interoperability-claims-intelligence)

My most complete interoperability and claims-engineering project.

**CMS Blue Button sandbox → OAuth 2.0 + PKCE → FHIR Patient/Coverage/EOB → governed RAW → canonical claims grains → PostgreSQL analytics → TMDL semantic model → PBIR report → CI validation**

**Why it matters:** healthcare claims data contains multiple nested grains. The project preserves claim, item, diagnosis, procedure, care-team, supporting-information, terminology, and financial meaning rather than flattening everything into one misleading table.

---

### 🛡️ Healthcare Data Governance & Quality Control Center
[View repository →](https://github.com/khaledzidan203-stack/healthcare-data-governance-quality-control-center)

A governance-first implementation built on public CMS Medicare data.

**RAW → STAGING → ANALYTICS + GOVERNANCE → DQ rules → lineage → governed KPI contracts → SQL/Python reconciliation → source-controlled Power BI**

Highlights include **source fingerprinting, field-level lineage, preserved source conflicts, weighted utilization/payment metrics, and explicit publication boundaries**.

---

### 🧾 CMS Transparency in Coverage PUF Analytics
[View repository →](https://github.com/khaledzidan203-stack/transparency-in-coverage-puf)

A payer-transparency analytics implementation where **availability is modeled as data**, not guessed from blanks.

The project separates issuer and plan grains, preserves source anomalies, uses ratio-of-totals KPI semantics, and reconciles the saved Power BI model against independent Python baselines.

---

### 🇸🇦 Saudi Healthcare Analytics 2021–2024
[View repository →](https://github.com/khaledzidan203-stack/saudi-healthcare-analytics)

Official Saudi Ministry of Health yearbooks transformed into a governed canonical model across **capacity, activity, workforce, and regional healthcare resources**.

**Python discovery → canonical CSVs → SQL Server star schema → DAX semantic model → 7-page PBIR report → layered validation**

---

### 🏨 Hospital360
[View repository →](https://github.com/khaledzidan203-stack/Hospital360)

A production-style synthetic hospital analytics platform combining:

**clinical activity · claims · finance · budget · workforce · operations · capacity · technology**

The project uses PostgreSQL, dimensional modeling, explicit fact grains, SQL regression, Python analytics, Power BI, and scale testing up to a 20K synthetic source generation benchmark.

---

### 🛍️ Online Retail Growth & Customer Intelligence
[View repository →](https://github.com/khaledzidan203-stack/online-retail-growth-customer-intelligence)

End-to-end customer and growth analytics built from the public UCI Online Retail II dataset.

**Transaction governance → SQL Server star schema → repeat behavior → RFM → acquisition cohorts → retention → cancellations → Power BI → SQL-driven Excel management outputs**

---

## Specialized Analytics Systems

| Domain | Project | Core focus |
|---|---|---|
| **Reconciliation** | [Transaction Reconciliation & Exception Intelligence](https://github.com/khaledzidan203-stack/transaction-reconciliation-anomaly-detection-analytics) | Explainable 8-level matching · discrepancy exposure · anomaly rules · prioritized review queues |
| **Regional Performance** | [Regional Sales Performance Analytics](https://github.com/khaledzidan203-stack/regional-sales-analytics-portfolio) | Budget gap · LFL · traffic · weighted AST · recovery scenarios · lifecycle · Tauri desktop architecture |
| **Category Management** | [Pharmacy Category Management Analytics](https://github.com/khaledzidan203-stack/pharmacy-category-management) | Margin · assortment · inventory risk · supplier service · pricing · descriptive promotion analysis |
| **Inventory** | [Pharmacy Inventory & Expiry Analytics](https://github.com/khaledzidan203-stack/pharmacy-stock-analytics-portfolio) | 90-day demand · stock cover · expiry · dead/slow stock · deterministic generation |
| **Product / Assortment** | [Pharmacy Product Analytics](https://github.com/khaledzidan203-stack/pharmacy-product-analytics-portfolio) | SKU status · TGM · zero-sales risk · top-N · supplier dependency |
| **Prescription Operations** | [Prescription Operations Analytics](https://github.com/khaledzidan203-stack/prescription-operations-analytics) | Multi-branch workflow analytics · completion · backlog · shortages · publication safety |
| **E-commerce** | [Pharmacy E-commerce Category Analytics](https://github.com/khaledzidan203-stack/pharmacy-ecommerce-category-analytics) | Digital category performance · commercial KPIs · decision support |
| **Branch Performance** | [Branch Performance KPI Dashboard](https://github.com/khaledzidan203-stack/branch-performance-kpi-dashboard) | Branch sales · customers · basket · employee/category performance |

---

## My Analytics Engineering Standard

I use a simple rule:

> **If a KPI cannot survive grain review, reconciliation, and evidence review, it is not ready for a dashboard.**

### 1. Grain before aggregation
Every fact table starts with an explicit business grain and key contract.

### 2. Data quality before storytelling
Duplicates, orphan keys, missing mappings, availability states, impossible values, and source conflicts stay visible.

### 3. One definition per KPI
SQL, Python, DAX, Excel, and UI outputs should reconcile to the same governed business meaning.

### 4. Separate facts that belong at different grains
Claims are not flattened into claim items. Finance is not joined directly to operations. Issuer metrics are not duplicated across plan rows.

### 5. Preserve uncertainty
Unknown, unavailable, suppressed, mapping-pending, zero, and not-applicable are different analytical states.

### 6. Evidence over decoration
Screenshots, dashboards, or presentation graphics never override the source, model, tests, or reconciliation evidence.

### 7. Automate validation
Where possible, repositories include regression tests, reproducibility checks, source/generated parity, privacy controls, and GitHub Actions quality gates.

---

## Technical Stack

<table>
<tr>
<td valign="top" width="25%">

### BI & Semantic Modeling
Power BI  
DAX  
Power Query  
PBIP  
PBIR  
TMDL  
Excel

</td>
<td valign="top" width="25%">

### Data & Engineering
SQL Server  
PostgreSQL  
Python  
pandas  
NumPy  
openpyxl  
Dimensional Modeling

</td>
<td valign="top" width="25%">

### Healthcare Data
FHIR  
CMS Blue Button  
Claims Analytics  
Payer Transparency  
Healthcare Governance  
OAuth 2.0 / PKCE

</td>
<td valign="top" width="25%">

### Delivery & Quality
Git / GitHub  
GitHub Actions  
HTML / CSS / JavaScript  
Chart.js  
Tauri / Rust  
Regression Testing  
Data Reconciliation

</td>
</tr>
</table>

---

## Domain Perspective

My background combines **pharmacy / healthcare domain knowledge** with **business and analytics training**.

That helps me work on problems where technical correctness alone is not enough — the analyst also needs to understand the operational meaning of claims, utilization, inventory, commercial performance, supplier service, customer behavior, and management KPIs.

**Pharmacy background · MBA · Data Analyst Associate · Healthcare / BI / Analytics Engineering focus**

---

## What I Am Interested In

I am focused on full-time opportunities in:

**Data Analytics · Business Intelligence · Healthcare Analytics · BI / Reporting · Commercial & Performance Analytics · Revenue Cycle / Claims Analytics · Analytics Engineering**

Especially roles where **Power BI + SQL + Python + domain knowledge + data quality + decision support** are used together.

---

<div align="center">

### Build the model correctly. Validate the number independently. Then tell the story.

[LinkedIn](https://www.linkedin.com/in/khaled-zidan-7400a51a3) · [Repositories](https://github.com/khaledzidan203-stack?tab=repositories)

</div>
