# Bala Viswanathan

**Analytics Engineer.** I build the modeled, tested data layer that finance and revenue teams run on, and I prove every number against the source before it ships.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-balavis-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/balavis/)

Working with data since 2019, across data engineering, BI and applied ML. Currently at **Safe Streets USA** on the Data Engineering team: dbt and Snowflake models, pull-request reviews, and Claude Code agents that I direct and verify.

---

## Featured project

### [olist-analytics-dbt](https://github.com/balasubramanianvusa22/olist-analytics-dbt) (*in progress*)
An end-to-end dbt project on the Brazilian Olist e-commerce dataset, running on DuckDB so anyone can build it locally.
Sources and staging are done for all eight tables. Next: tests, marts, and an order-to-payment reconciliation mart like the ones I build at work. [Roadmap](https://github.com/balasubramanianvusa22/olist-analytics-dbt#roadmap)

---

## Selected work

**Reporting-layer migration** (Safe Streets USA)
Moved ~50 reporting objects off a stale CRM replica in staged waves, each with a backup and rollback script. Retired ~26 unused objects based on 13 months of access history, and listed source defects for the data engineering fix.

**Legacy dashboards rebuilt as tested dbt models** (Safe Streets USA)
Rebuilt finance executive and upsell dashboard logic as dbt models with formula-level parity checks against production, and redeployed the upsell dashboard on a new web BI layer. The checks found a budget bug double-counting part of the year, duplicate billing on rescheduled work, a hidden filter, "net" funding that was actually gross, and a billing table frozen since a pipeline failure.

**Automated commissions engine** (Safe Streets USA)
Turned a biweekly, ~8-hour manual commissions and payables process for four programs into minutes using Claude Code skills. Validated by rebuilding past paid periods to an exact match.

**Delinquency cure-probability model** (Safe Streets USA)
Predicts which past-due accounts will cure, by aging bucket (31–60, 61–90, 91–120 days). XGBoost and LightGBM performed best (AUC ≈ 0.87 on 31–60). Scores map to outreach tiers for the Revenue Retention team. Built in Snowflake notebooks; presented to Finance leadership.

**Revenue assurance and reporting rebuilds** (Safe Streets USA)
Reconciliation logic that flagged missed collection opportunities on at-risk accounts (~$120K collected by the Revenue Retention team). Invoice-aging model across orders, invoices, payments, credits and refunds. Rebuilt a 1,580-line legacy chargeback query into two lean Snowflake models.

**Cloud ETL and alerting** (Outset Medical, Data Engineering Intern, 2023)
AWS Glue and Step Functions pipelines, Lambda validation, SNS alerting, and an Athena layer of modular views.

**Retail data warehouse** (LTI Mindtree, Data Engineer, 2019–2022)
Azure Data Factory, SSIS and SQL Server pipelines for a retail and inventory warehouse processing 1 TB+ batches.

---

## How I work with AI

Claude Code writes most of the first draft. I own the business rules, the root causes and the quality bar: parallel review agents, stress tests, and parity checks against production before anything merges.

---

## Stack

| Area | Tools |
|---|---|
| Warehouse & modeling | Snowflake, dbt, SQL Server, PostgreSQL, Athena, DuckDB |
| Pipelines | Azure Data Factory, SSIS, AWS Glue, Step Functions, Lambda |
| ML | Python, XGBoost, LightGBM, scikit-learn |
| BI | Tableau, Excel |
| Workflow | Git, pull requests, Jira, Claude Code |

---

## Education
**M.S. Management Information Systems**, University of Arizona, Eller College of Management (2023)
Eller Master's Excellence Award · 3× Dean's List
**B.E. Electronics and Communication Engineering**, Sri Sai Ram Institute of Technology, affiliated to Anna University (2019)
