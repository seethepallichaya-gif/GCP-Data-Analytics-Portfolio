# 🚀 Data Analytics Portfolio: Fintech Loan Analysis (GCP)
**By Chaya Seethepalli | Google Cloud Certified | 7 Years QA Expertise**

---

## 🎯 Executive Summary
As a **Cloud Data Analyst** with a 7-year background in **Quality Assurance (Manual & Automation)**, I specialize in the intersection of data integrity and business intelligence. 

This portfolio showcases an end-to-end data pipeline built within **Google Cloud Platform (GCP)** for *TheLook Fintech*. I transitioned raw, unstructured loan data into a validated "Single Source of Truth" in BigQuery, culminating in an executive-level Looker dashboard for Treasury risk management.

---

## 🛠️ Project 1: Data Engineering & Transformation (BigQuery)
**Goal:** Transform raw fintech datasets into a queryable, validated environment to support the Treasury Department’s scaling efforts.

### 🔍 Business Understanding
The Head of Treasury required a robust system to track:
* **Cash Flow Management:** Balancing loan payouts vs. incoming capital.
* **Risk Mitigation:** Identifying high-risk loan purposes to improve forecasting.
* **Geographic Concentration:** Mapping borrower locations to prevent "collective default risk."

### ⚙️ Technical Implementation (The QA Lens)
Leveraging my **7 years of QA experience**, I ensured 100% data integrity before analysis:
* **Data Ingestion:** Imported raw CSV files and state classifications into the **BigQuery** ecosystem.
* **Deduplication & Validation:** Used `SELECT DISTINCT` and SQL validation scripts to ensure no duplicate loan IDs skewed cash flow metrics.
* **Storage Architecture:** Utilized **CTAS (Create Table As Select)** to generate optimized tables, ensuring high-performance querying for the Treasury team.
* **Data Transformation:** Executed complex `JOIN` logic between loan records and geographic data to create a master reporting table.

**Snapshot of SQL Environment:**
<img width="1214" height="653" alt="BigQuery SQL Workspace" src="https://github.com/user-attachments/assets/7720723e-f5dc-437d-b2f6-6bda9f4e3baa" />

---

## 📊 Project 2: Business Intelligence & Insights (Looker)
**Goal:** Develop a high-level **Looker Enterprise** dashboard to move the Treasury team from "Reading Rows" to "Seeing Insights."

### 💡 The "Simple 4" Business Questions
The dashboard was engineered to answer:
1.  **Total Exposure:** Exactly how much money is currently owed?
2.  **Repayment Health:** What % of loans are "Current" vs. "Late/Default"?
3.  **Geographic Risk:** Are we over-indexed in specific states?
4.  **Target Profiles:** Which borrowers are most stable (e.g., homeowners with current loans)?

### 🎨 Visualization & Features
* **KPI Tiles:** Real-time tracking of Total Outstanding Amount.
* **Distribution Charts:** Instant spotting of rising default rates via status percentages.
* **Advanced Filtering:** Developed a **Homeowner Income Index** to segment high-stability customers.
* **Interactivity:** Enabled Cross-filtering and Auto-refresh for real-time stakeholder decision-making.

**Snapshot of Looker Dashboard:**
<img width="823" height="457" alt="Looker Loan Health Dashboard" src="https://github.com/user-attachments/assets/10a00cb1-1a31-4661-851f-0a026bef3da5" />

---

## 📈 Conclusion & Impact
This end-to-end solution provided the Treasury department with:
* **Immediate Insight:** Executive risk visibility in 5 seconds rather than manual reporting hours.
* **Strategic Growth:** Identified the "Homeowner" segment for targeted marketing to reliable borrowers.
* **Risk Mitigation:** Early identification of regional default risks through geographic mapping.

---

## 📬 Let's Connect
* **Phone:** 732-277-8415
* **LinkedIn:** [Your LinkedIn Profile Link]
* **Specialties:** Data Validation | SQL | Google Cloud Platform | Looker | QA Automation
