# MathCo
<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/ad6daf4a-7c30-4831-b35d-50196b6aa157" />


📅 **Date:** 13 July 2022 - 28 July 2025

👤 **Role:** Data Engineer 2
## Projects:

### **Coca Cola**: Supply and Demand Planner

<img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/3bbea12d-509e-43b1-a695-936b9f8b347b" />

#### 📅 **Date:** Nov 2024 – July 2025

#### **◉ Tools Used** 
Azure Data Factory, Azure Synapse Analytics, Azure Data Lake Gen2, Azure ML Studio, Python, PySpark, SQL, Azure DevOps, Git, Power BI

#### **◉ Project Overview**

Designed and developed an **end-to-end Supply & Demand Planner** tool to automate demand forecasting and supply chain balancing across multiple bottling locations. The solution ensured plants closest to distribution centers were notified to produce the required goods while considering factors like **shelf life, STO lead time, production line changeover, CIP (clean-in-place), and line downtime**.

The system integrated multiple data sources (on-premises databases, Amazon S3, REST APIs) via **Azure Data Factory** into a **Medallion Architecture** on **Azure Data Lake Storage Gen2**. Using **Azure Synapse**, data was modeled into a **star schema** with fact and dimension tables to enable fast querying and analytics.

On the ML side, **Azure ML Studio** was leveraged to develop batch demand forecasting models using historical sales and production data. Additionally, **automated DQM pipelines** validated upstream data quality and triggered anomaly reports via email, ensuring reliability of downstream processes.

#### **◉ Responsibilities**

* Led a **team of 2 data engineers**, collaborating with **data scientists and business stakeholders** to deliver a scalable forecasting solution.
* Designed and developed **ETL pipelines** in Azure Synapse, integrated with Medallion architecture for efficient ingestion, transformation, and aggregation.
* Built and automated **Data Quality Management (DQM) pipelines** to validate nulls, format issues, duplicates, invalid ranges, and foreign key mismatches.
* Worked with data scientists to integrate ML forecasting models into production, enabling **batch demand forecasting**.
* Implemented **CI/CD pipelines** using Azure DevOps for automated deployment and version control of ETL and ML workflows.
* Ensured system scalability and performance optimization using **PySpark** for ETL and model scoring.

#### **◉ Key Achievements**
* Successfully delivered a **Supply & Demand Planner tool** that automated end-to-end demand forecasting and supply balancing.
* Reduced **manual data quality checks by 90%**, with DQM pipelines detecting **97% of anomalies in real time**.
* Improved forecasting accuracy and timeliness, enabling better production planning while reducing stockouts and wastage.
* Established a **robust data foundation** using star schema modeling in SQL Server for fast analytics and reporting.
* Ensured seamless collaboration across cross-functional teams (engineering, data science, and business), delivering a **production-grade solution**.

#### **◉ Challenges**

* **Complex Supply Chain Logic**: Factoring in shelf life, STO lead time, line downtime, changeovers, and CIP into the planning algorithm.
* **Data Quality Issues**: Frequent nulls, format mismatches, and anomalies in upstream data required designing automated, scalable DQM pipelines.
* **Cross-Functional Alignment**: Balancing priorities between business stakeholders, data scientists, and engineering teams while ensuring timely delivery.
* **Scalability & Performance**: Optimizing PySpark jobs and Synapse pipelines to handle large-scale historical and real-time data efficiently.

---

### **Project Development Life Cycle (PDLC)**: NucliOS App development

<img width="300" height="75" alt="image" src="https://github.com/user-attachments/assets/f758073b-3833-4667-af2e-977c7187c0aa" />

#### 📅 **Date:** Apr 2024 - Nov 2024

#### **◉ Tools Used** 
NucliOS, SQL Server, Python, SQL, draw.io

#### **◉ Project Overview**

The **Project Development Life Cycle (PDLC)** project was an internal initiative to build a fully integrated **in-house project management solution**—designed as a replacement for commercial tools like Jira and Azure Boards.

The tool provided role-based dashboards and features such as:

* **Project Dashboard** – project-level tracking and KPIs
* **Team Dashboard** – team assignments, progress, and workload
* **Sprint Progress** – sprint velocity, burndown charts, and task tracking

Key features included **user management, role-based access control, and creation of features/stories/tasks/bugs**. Access permissions were **role-specific** (e.g., managers could add/remove team members, while developers could manage tasks assigned to them).

On the backend, the system was powered by **SQL Server**, with **Star and Snowflake schema modeling**, and implemented **Slowly Changing Dimensions (SCD)** and **Change Data Capture (CDC)** design patterns to handle evolving project and team data.

#### **◉ Responsibilities**

* **End-to-End Involvement**: Contributed from the ground up, including requirements gathering, design, and implementation.
* **Data Modeling**: Designed and developed backend tables in **SQL Server** using **Star & Snowflake schema** principles.
* **Design Patterns**: Implemented **SCD** and **CDC** to ensure historical accuracy and real-time data updates.
* **Documentation**: Authored **BRD (Business Requirement Document)** and **TRD (Technical Requirement Document)**.
* **Project Management**:
  * Drove **standup calls** and **client interactions**.
  * Created **Weekly Business Reports (WBR)** and **Monthly Business Reports (MBR)**.
* **Tool Development**: Assisted in building the tool using **NucliOS (Python-based)** for integration and UI.

#### **◉ Key Achievements**

* Successfully developed and deployed an **in-house project management tool** used across multiple company projects.
* Delivered a **cost saving of \~25 Million INR** by reducing reliance on external tools like Jira and Azure DevOps Boards.
* Standardized **data models and reporting structures**, ensuring consistency across all project management modules.
* Enhanced **role-based access control**, improving security and usability across diverse project teams.

#### **◉ Challenges**

* **Complex Role-Specific Access**: Designing dynamic role-based permissions for dashboards and modules.
* **Data Consistency**: Implementing **SCD & CDC** patterns to track evolving project data while ensuring historical accuracy.
* **Cross-Functional Alignment**: Balancing requirements between managers, developers, and leadership to design a unified tool.
* **Scalability & Adoption**: Ensuring the tool could scale across multiple projects and gain adoption over established industry tools like Jira.

---

### **Merck Sharp & Dohme (MSD)**: Budget Allocation Optimization

<img width="300" height="90" alt="image" src="https://github.com/user-attachments/assets/907eb7b9-13fd-4f54-af00-0867cd4daaf2" />

#### 📅 **Date:** Feb 2024 – Apr 2024

#### **◉ Project Overview**

This was a **Proof of Concept (POC)** project for **Merck**, focused on optimizing **budget allocation across multiple marketing channels** (newspapers, banners, television ads, etc.) based on historical performance data.

The Merck team provided **logarithmic curve formulas** for each marketing mode, derived from historical spend vs. ROI data. Using these curves, we built an **optimization engine** that fit current data to predict future profits and optimized budget distribution to maximize ROI.

The solution involved:

* Developing a **budget optimization engine** with greedy algorithms.
* Using **Databricks (PySpark, SQL)** for data cleaning, transformation, and modeling.
* Integrating results with **NucliOS-based UI** and **Power BI dashboards** for scenario simulations and visualization.
* Running **regression-based forecasting** to generate multiple marketing spend scenarios.

The POC lasted one month, and due to its success, it was later converted into a **full-scale project**.

#### **◉ Tools Used** 
Python, Databricks, SQL, Power BI, Excel, NucliOS, Jira

#### **◉ Responsibilities**

* Designed and implemented the **budget optimization engine** using **greedy algorithms** with logarithmic ROI curves.
* Cleaned, transformed, and modeled large-scale sales and spend datasets using **PySpark** and **SQL** on **Databricks notebooks**.
* Integrated optimizer results with **NucliOS UI** and **Power BI dashboards** to enable business users to run real-time simulations.
* Built **scenario-based forecasting models** to evaluate potential ROI under varying spend conditions.
* Collaborated with cross-functional teams, tracked tasks on **Jira**, and maintained documentation on **Confluence**.

#### **◉ Key Achievements**

* Successfully delivered a **functional POC in just one month**, exceeding client expectations.
* Developed a **budget optimization engine** capable of reallocating spend dynamically across marketing channels to maximize ROI.
* Enabled **real-time budget simulations** and visualizations via UI and dashboards, enhancing decision-making for business users.
* Built a scalable data pipeline on **Databricks**, ensuring performance and flexibility for future expansion.
* Contributed to converting the **POC into a long-term full-scale project**, generating significant client value.

#### **◉ Challenges**

* **Complex ROI Curves**: Each marketing mode had different logarithmic curve formulas, requiring careful integration into the optimization model.
* **Data Quality Issues**: Historical spend and sales data needed heavy cleaning and transformation before modeling.
* **Time Constraint**: Delivering a robust POC with multiple components (optimization, forecasting, UI, dashboards) within a **1-month timeline**.
* **Scalability Concerns**: Ensuring the POC could later scale into a production-grade solution without significant rework.

---

### **Walmart**: Code and Airflow DAG Optimization

<img width="300" height="70" alt="image" src="https://github.com/user-attachments/assets/86398180-591e-4edb-9842-39c027349cd7" />

#### 📅 **Date:** Aug 2023 – Jan 2024

#### **◉ Project Overview**

This project focused on **optimizing and refactoring an existing real-time streaming pipeline** to achieve faster execution and near real-time dashboard refreshes. The pipeline processed **\~6 billion retail records every 30 minutes**, covering item-related data such as **name, description, availability, impressions, clicks, activities, and orders**.

The scope included:

* Migrating legacy **SQL-based pipelines** to **PySpark** for scalability and fault tolerance.
* Refactoring **Airflow DAGs** to improve task parallelism and reduce runtime.
* Handling **high-velocity JSON payloads** from Apache Kafka via **Google Dataproc**, with downstream analytics powered by **Google BigQuery**.
* Debugging and maintaining the **Airflow pipelines** to ensure resilience against schema changes and upstream data issues.

#### **◉ Tools Used** 
PySpark, Apache Airflow, SQL, Apache Kafka, JSON, GitHub Actions, Docker, DBeaver

#### **◉ Responsibilities**

* **Pipeline Refactoring**: Converted SQL-heavy legacy code into **PySpark** pipelines to improve scalability and performance.
* **Airflow Optimization**: Re-structured DAG task dependencies to enable **parallel execution** and reduce overall runtime by 75%.
* **Streaming Ingestion**: Built streaming pipelines in **Google Dataproc** to process high-velocity JSON data from **Apache Kafka** topics.
* **Data Cleansing & Parsing**: Improved JSON parsing by replacing nested loops with **PySpark’s from\_json()**, and implemented **regexp\_replace()** to handle problematic characters (e.g., special symbols, extra quotes) that caused parsing failures.
* **Pipeline Maintenance**: Monitored and debugged **Airflow DAGs**, fixing breakages caused by upstream format changes and coordinating with clients for resolution.
* **Analytics Integration**: Enabled downstream querying and dashboard updates using **Google BigQuery** for near real-time insights.

#### **◉ Key Achievements**

* Reduced pipeline runtime **from 4.5 hours to just 20 minutes**, enabling **near real-time dashboard refreshes**.
* Achieved **75% reduction in peak load runtime** by enabling parallel task execution in Airflow.
* Enhanced **pipeline reliability** by designing robust handling of JSON parsing errors and upstream data format changes.
* Successfully scaled the solution to handle **billions of records every 30 minutes**, ensuring both performance and fault tolerance.
* Improved collaboration with clients by providing timely issue communication and quick fixes to maintain SLAs.

#### **◉ Challenges**

* **Nested JSON Parsing Issues**: The PySpark `from_json()` function failed due to special characters in values, causing pipeline breakages. This was resolved by preprocessing payloads with **regexp\_replace()**.
* **High Data Volume & Velocity**: Ensuring the system could handle **6B+ records in 30-min windows** required heavy refactoring for performance optimization.
* **Airflow DAG Failures**: Pipelines occasionally failed due to **upstream schema/format changes**; resolving these required quick debugging, client communication, and code adjustments.
* **Time Sensitivity**: Strict SLA requirements meant dashboards had to be refreshed within **30 minutes**, leaving little margin for error.

---

### **Abbvie**: Automated Data Quality Monitoring

<img width="300" height="70" alt="image" src="https://github.com/user-attachments/assets/fda59b95-26c2-43c5-a34e-b3ab8c8a311e" />

#### 📅 **Date:** Jan 2023 – Jul 2023

#### **🛠 Tools Used** 
Python, PySpark, LiveRamp, Google BigQuery, Tableau, AWS S3, Jupyter

#### **🛠 Responsibilities**
TBD

#### **🏆 Key Achievements**

* 🛠️ **Automated DQM System:** Developed an *end-to-end Data Quality Monitoring* system to ensure integrity, consistency, and completeness of healthcare datasets.

* 📈 **Anomaly Detection:** Implemented *statistical thresholds* and *pattern recognition* in *PySpark* and *Python* to detect anomalies across millions of patient and prescription records.

* ☁️ **Data Integration:** Ingested and transformed data from multiple third-party vendors via *LiveRamp*, staging on *AWS S3* and *BigQuery* for downstream analysis.

* 📊 **Dashboards & Alerts:** Built *auto-refresh Tableau dashboards* with trend visualizations, data quality scores, and *alert triggers* for critical drifts.

* 📂 **Versioning & Auditability:** Logged and versioned workflows using *Jupyter notebooks* and *Git* for transparent audit trails.

#### **⚠ Challenges**
TBD

---

### **Abbvie**: Access and Reimbursement Dashboard

<img width="300" height="70" alt="image" src="https://github.com/user-attachments/assets/fda59b95-26c2-43c5-a34e-b3ab8c8a311e" />

#### 📅 **Date:** Jan 2022 – Aug 2022

#### **🛠 Tools Used** 
Power BI, Python, SQL, PySpark, PowerPoint, DataIKU, Excel

#### **🛠 Responsibilities**
TBD

#### **🏆 Key Achievements**

* 📊 **Access & Reimbursement Dashboard:** Designed and delivered an *interactive dashboard* for stakeholders to monitor **insurance coverage, copay uptake, and payer adherence**.

* ⚡ **Real-Time Data Processing:** Consumed and processed health data streams from APIs using *DataIKU* and *PySpark*, storing intermediate outputs in structured *SQL tables*.

* 🖥️ **Power BI Analytics:** Built *Power BI dashboards* with advanced *DAX measures* to enable filtering by **region, payer type, and patient demographics**.

* 🔍 **Automated Quality Checks:** Implemented validation logic and freshness monitoring using *Python*, with **alert-based triggers** for anomalies.

* 📑 **Executive Reporting:** Supported leadership communication with *PowerPoint decks* summarizing insights for quarterly reviews.

#### **⚠ Challenges**
TBD
