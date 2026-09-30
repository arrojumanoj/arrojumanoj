<h1 align="center">Hi, I'm Manoj Kumar Arroju 👋</h1>
<h3 align="center">Workday Integration Developer · Workday HCM · Payroll · Benefits · Compensation</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/manojarroju/"><img src="https://img.shields.io/badge/LinkedIn-manojarroju-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:manoj.a@savemymails.com"><img src="https://img.shields.io/badge/Email-manoj.a%40savemymails.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Relocate-2EA44F?style=for-the-badge" alt="Open to Relocate"/>
</p>

---

## 🚀 About Me

Workday Integration Developer with **3+ years** building and supporting **Workday Studio, EIB, Core Connector, PECI and Orchestrate** integrations across Workday HCM, Payroll, Benefits and Compensation. Skilled in **XSLT, Workday Web Services (REST/SOAP), RaaS, calculated fields and ISU/ISSG security**.

- 🏦 Currently a **Workday Integration Developer at Charles Schwab**, supporting SOX-controlled feeds for **30K+ workers**
- 📉 Cut failed integration runs by **35%** and halved release regression time
- 🌍 Previously delivered Workday implementations and AMS support for US clients at **Accenture**
- 🎓 M.S. in Information Systems Technologies, Wilmington University

---

## 💼 Experience

### Workday Integration Developer — Charles Schwab, USA
*Jun 2025 – Present*

- Manage **25+ Workday Studio and Core Connector integrations** to benefits, 401(k), payroll-tax and background-screening vendors; added error handlers and retry logic that reduced failed runs **35%**
- Mapped effective-dated changes for **PECI payroll** and **Cloud Connect for Benefits** carrier feeds in **XSLT 3.0**, delivering PGP-encrypted, changes-only files over SFTP
- Adopted **Workday Orchestrate** for event-driven termination feeds to IAM — access removal now happens same day instead of overnight
- Delivered mass changes across **30K+ worker records** via inbound EIBs; pre-load validation reports cut post-load corrections **40%**
- Audited ISU/ISSG access to least privilege and produced **SOX/ITGC** evidence and ServiceNow change records
- Built **60+ calculated fields** and Advanced, Matrix and Composite reports, exposing **15+ as RaaS / outbound EIB** feeds
- Regression-tested integrations through 2025R2, 2026R1 and 2026R2 with Python-based output comparison and PII masking — each cycle dropped from two weeks to one

### Workday Developer — Accenture, India
*Mar 2021 – Jul 2023*

- Converted worker, position and compensation data for a **15K+ employee** US client through inbound EIBs; load errors fell **~60%** across three mock conversions
- Built **10+ outbound integrations** for benefits carriers and payroll vendors using Core Connector: Benefits, PICOF and Workday Studio (Get_Workers SOAP)
- Used Document Transformation (XSLT 2.0) on Core Connector: Worker to meet new vendor layouts while keeping built-in change detection
- Configured hire and job-change business processes with condition rules and security policies
- Executed **150+ SIT, UAT and payroll parallel** test cases in Agile/Scrum sprints; promoted fixes with Object Transporter
- Resolved AMS tickets on failed integration events and stuck business processes within SLA

---

## 🛠️ Projects

### 🔍 Workday Integration Health Monitor
`Python` `Workday SOAP/REST APIs` `RaaS` `JSON` `ServiceNow API`

Support teams often learn about failed, partial or zero-record integration runs only when a vendor reports a missing file.
- Python poller reads integration events via the Workday SOAP API and a RaaS JSON feed, classifying failures as authentication, schema, SFTP or data errors
- Routes each failure class to its owner as a ServiceNow incident with a runbook link — **85%** correctly triaged across 2K+ synthetic events

### 💰 Payroll Interface Reconciliation Toolkit
`XSLT 3.0` `XPath` `Python (pandas)` `PECI` `Core Connector: Payroll Interface`

Retro and effective-date mismatches in payroll interface files often surface only after payroll close.
- XSLT 3.0 transform with XPath keys flattens PECI and CCPI XML into one row per worker, pay component and effective date
- pandas matching against vendor return files flags retro and effective-date breaks — caught **90%** of seeded errors on a 5K+ worker synthetic payroll

---

## 🧰 Skills

**Workday Integrations**
![Workday Studio](https://img.shields.io/badge/Workday%20Studio-005CB9?style=flat-square)
![EIB](https://img.shields.io/badge/EIB-005CB9?style=flat-square)
![Core Connectors](https://img.shields.io/badge/Core%20Connectors-005CB9?style=flat-square)
![Web Services](https://img.shields.io/badge/Web%20Services%20(REST%2FSOAP)-005CB9?style=flat-square)
![Orchestrate](https://img.shields.io/badge/Orchestrate-005CB9?style=flat-square)
![PECI](https://img.shields.io/badge/PECI-005CB9?style=flat-square)
![RaaS](https://img.shields.io/badge/RaaS-005CB9?style=flat-square)
![PICOF](https://img.shields.io/badge/PICOF-005CB9?style=flat-square)
![CCB](https://img.shields.io/badge/Cloud%20Connect%20for%20Benefits-005CB9?style=flat-square)
![Document Transformation](https://img.shields.io/badge/Document%20Transformation-005CB9?style=flat-square)
![CCPI](https://img.shields.io/badge/CCPI-005CB9?style=flat-square)

**Workday HCM & Reporting**
![Custom Reports](https://img.shields.io/badge/Advanced%20%7C%20Matrix%20%7C%20Composite%20Reports-F38B00?style=flat-square)
![Calculated Fields](https://img.shields.io/badge/Calculated%20Fields-F38B00?style=flat-square)
![Payroll](https://img.shields.io/badge/Payroll-F38B00?style=flat-square)
![Benefits](https://img.shields.io/badge/Benefits-F38B00?style=flat-square)
![Compensation](https://img.shields.io/badge/Compensation-F38B00?style=flat-square)
![Business Processes](https://img.shields.io/badge/Business%20Process%20Config-F38B00?style=flat-square)
![Data Conversion](https://img.shields.io/badge/Data%20Conversion-F38B00?style=flat-square)
![Object Transporter](https://img.shields.io/badge/Object%20Transporter-F38B00?style=flat-square)

**Data, Security & Controls**
![XSLT](https://img.shields.io/badge/XSLT%202.0%2F3.0-4B5563?style=flat-square)
![XML](https://img.shields.io/badge/XML%20%2F%20XPath-4B5563?style=flat-square)
![JSON](https://img.shields.io/badge/JSON-4B5563?style=flat-square&logo=json)
![Python](https://img.shields.io/badge/Python%20(pandas)-3776AB?style=flat-square&logo=python&logoColor=white)
![ISU/ISSG](https://img.shields.io/badge/ISU%20%2F%20ISSG%20Security-4B5563?style=flat-square)
![SFTP/PGP](https://img.shields.io/badge/SFTP%20%2F%20PGP-4B5563?style=flat-square)
![SOX](https://img.shields.io/badge/SOX%20%2F%20ITGC-4B5563?style=flat-square)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white)

**Testing & Delivery**
![Agile](https://img.shields.io/badge/Agile%20%2F%20Scrum-6B7280?style=flat-square)
![Testing](https://img.shields.io/badge/SIT%20%7C%20UAT%20%7C%20Parallel%20%7C%20Regression-6B7280?style=flat-square)
![AMS](https://img.shields.io/badge/AMS%20Production%20Support-6B7280?style=flat-square)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=flat-square&logo=jira&logoColor=white)

---

## 🎓 Education

- **M.S. in Information Systems Technologies** — Wilmington University, New Castle, DE *(Sep 2023 – May 2025)*
- **B.Tech. in Computer Science** — Bharath Institute of Higher Education and Research, India *(Aug 2019 – May 2023)*

---

<p align="center">📫 Open to Workday Integration / HCM Developer opportunities — let's connect on <a href="https://www.linkedin.com/in/manojarroju/">LinkedIn</a>.</p>
