**Project Title:** Fintech Loan Performance & Cash Flow Analysis (GCP)

**Project Overview**
As a Cloud Data Analyst at TheLook Fintech, a high-growth startup, I designed an end-to-end data solution within Google Cloud Platform. 
The project involved transforming raw, unstructured loan data into a validated, queryable environment in BigQuery to support the Treasury Department’s scaling efforts.

**Business Understanding**
The Treasury Department, led by the Head of Treasury (Trevor), identified three critical areas to track the company's financial stability:

- **Cash Flow Management:** Ensuring loan payments did not exceed incoming capital.

- **Risk Mitigation (Loan Purpose):** Identifying high-risk loan reasons to improve repayment forecasting.

**Geographic Concentration:** Mapping borrower locations to prevent "collective default risk" caused by over-exposure in specific regions.

**Data Understanding & Process**
I managed the first three stages of the data journey (Collect, Process, Store) using BigQuery. My approach leveraged my 7 years of QA experience to ensure 100% data integrity before analysis:

**Environment Setup:** Configured the BigQuery ecosystem to handle fintech-scale datasets.

**Data Ingestion & Cleaning:** Imported raw CSV files and state classifications. 
I used SQL to perform Deduplication (using SELECT DISTINCT) and Data Validation to ensure no duplicate loan IDs skewed the cash flow metrics.

**Data Transformation:** Performed Table Joins between loan records and geographic data to create a master reporting table.

**Storage Architecture:** Used CTAS (Create Table As Select) to generate optimized tables for the purpose data, ensuring efficient query performance for the Treasury team.
**Snapshot of SQL Environment:**
*<img width="1214" height="653" alt="Screenshot 2026-02-23 215552" src="https://github.com/user-attachments/assets/7720723e-f5dc-437d-b2f6-6bda9f4e3baa" />

**Conclusion & Impact**
The project successfully provided the Treasury department with a "Single Source of Truth." By the end of the technical implementation, I produced a comprehensive report detailing:

Total loans issued by day/year, allowing for real-time cash flow monitoring.

Loan Purpose Distribution, helping the risk team correlate loan reasons with repayment reliability.

Geographic Mapping, enabling the company to diversify its loan portfolio across regions and reduce regional default risks.






**Project Title:** Interactive Loan Health Dashboard (Looker Enterprise)

**Project Overview**
Building on my data engineering work in BigQuery, I developed a high-level Business Intelligence (BI) dashboard using Looker Enterprise. 
The goal was to transform complex loan datasets into a visual interface for the Treasury team to monitor the company’s financial exposure and borrower health in real-time.

**Business Understanding** (The "Simple 4" Questions)
To help Trevor (Head of Treasury) manage risk, the dashboard answers four critical questions:

**Total Exposure:** Exactly how much money is currently owed to us? (Total Outstanding Balance).

**Repayment Health:** What percentage of our loans are "Current" vs. "Late" or "In Default"?

**Geographic Risk:** Are we lending too much in one specific state?

**Target Profiles:** Which borrowers are the most stable (e.g., homeowners with current loans)?

**Data Understanding & Visualization**
I utilized the "Analyze and Activate" stages of the data journey. Leveraging my 7 years of QA experience, I ensured that the visuals accurately reflected the underlying data through cross-validation.

**KPI Tiles:** Created a clear view of the Total Outstanding Amount to track overall financial risk.

**Distribution Charts:** Built visualizations showing the percentage of loans by status, allowing the team to spot rising default rates instantly.

**Geographic Mapping:** Visualized the Top 10 states with the highest loan counts to identify regional concentration.

**Advanced Filtering:** Developed a detailed table for the Homeowner Income Index, specifically filtering for high-stability customers (Homeowners + Current status).

**Interactivity:** Enabled Cross-filtering and Auto-refresh so stakeholders can click on one chart to filter the entire dashboard.
**Snapshot of Looker Dashboard:**
*<img width="823" height="457" alt="Screenshot 2026-02-23 215403" src="https://github.com/user-attachments/assets/10a00cb1-1a31-4661-851f-0a026bef3da5" />

**Conclusion & Impact**
The Looker dashboard successfully moved the Treasury department from "Reading Rows" to "Seeing Insights."

**Immediate Insight:** Trevor can now see the company's total risk in 5 seconds instead of running a manual report.

**Risk Mitigation:** The team can now identify "high-risk" states and loan statuses early, allowing for faster intervention.

**Strategic Growth:** By identifying the "Homeowner" segments, the marketing team can now tailor products to the most reliable borrowers.

## 📬 Contact Me: 732-277-8415
* **LinkedIn:** (https://www.linkedin.com/in/chaya-seethepalli/)
* **Background:** 7 years of QA Manual & Automation Testing | Specialized in Data Validation & GCP
