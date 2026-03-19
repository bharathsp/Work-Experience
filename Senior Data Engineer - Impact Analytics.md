# Impact Analytics

<img width="150" height="336" alt="image" src="https://github.com/user-attachments/assets/a12eac82-e802-420f-a38e-9d879ef6d5e5" />

📅 **Date:** 22 Oct 2025 - Present

👤 **Role:** Senior Data Engineer

## Projects:

### **IA Product**

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
Building an AI-driven platform (Agentic Studio) that combines Generative and Agentic AI to deliver contextual insights, automate complex workflows, and improve decision support for retail and other domains. Key focus areas include Text2SQL agents (ALAN Chatbot), data ingestion pipelines, dashboard validation, SOP RAG agents, and multi-client support (PSP, TSC, NRF, IB, etc.).

#### **◉ Tools Used** 
Python, OpenAI API, BigQuery, Snowflake, Google Cloud Storage (GCS), SFTP, Postgres (for RAG), OCR (for image-based PDFs), NotebookLM, Cursor, Bitbucket/FastAPI (platform), XLOOKUP in Excel, Gemini for labeling.

#### **◉ Responsibilities**
Developed and automated validation frameworks for Text2SQL agents (question generation, semantic checks, API automation, confidence score validation).
Designed and implemented data ingestion pipelines (PDFs → GCS → BigQuery, Excel merging, XBRL extraction, upsert logic with hashing).
Created synthetic/dummy datasets, data dictionaries, ER diagrams, validation checklists, and fiscal calendars.
Performed extensive manual + automated testing of chatbots, dashboards, and agents (PSP StoreHub, ALAN, SOP Navigator, Store Data Analyst, IB Agent, etc.).
Conducted Exploratory Data Analysis (EDA), sentiment & category classification (LLM + rule-based), data gap analysis, and referential integrity checks.
Prepared KPI context documents, golden Q&A pairs, ambiguous/generic/complex question sets, and validation reports.
Handled schema reviews, table partitioning/clustering, deduplication, and updates (e.g., district-store mapping, sentiment columns).
Supported cross-team KT, interviews, PPTs, flowcharts, and client communications on data issues.
Worked on generalization of pipelines and scaling solutions (Snowflake optimizations, latency improvements).

#### **◉ Key Achievements**
Automated Text2SQL validation for Monday Smart ALAN Chatbot (question generation qualifying qualitative/quantitative/complexity requirements + semantic check).
Ingested large volumes of PSP data: 1752+ NRR PDFs, Revv comments, SOP files (321+ new), with image handling, deduplication, and incremental updates.
Built and validated PSP StoreHub chatbot (~50%+ accuracy improvements), dashboard KPIs (including fiscal calendar), and data pipeline (SFTP → GCS → BigQuery).
Created comprehensive NRF Agents datasets (Store Data Analyst, SOP Navigator) with synthetic data, location mapping, golden questions — achieved 84% accuracy on SOP Agent.
Successfully ingested and structured IB financial data from EDGAR 10K/10Q/XBRL (multiple companies: TSC, Costco, AutoZone, O'Reilly), derived KPIs, deduplication, and RAG-ready context.
Optimized TSC Promo Reco customer segmentation in Snowflake (loyalty layers, multi-stage joins, reduced execution time to ~15 min/week).
Designed ERDs, data dictionaries, validation checklists, and fiscal calendar for multiple projects; resolved numerous data gaps and schema issues.
Implemented advanced features like comment sentiment/category classification, autofail flagging, image URL validation, and source link management.

#### **◉ Challenges**
Handling inconsistent/unstructured PDF data (varying formats, images, missing fields) and ensuring no duplicate ingestion.
Managing complex joins and timeouts in Snowflake/BigQuery with large retail datasets (millions of transactions).
Achieving high accuracy in LLM-based classification and Text2SQL responses for ambiguous/complex retail queries.
Data gaps/mismatches across client sources (e.g., promo mapping ~10 matches only, missing UPCs/stores).
Scaling ingestion/validation for high-volume files while maintaining referential integrity and performance.
Coordinating cross-team dependencies (data engineering for SFTP/GCS, backend for agent updates).

---

### **Pet Supplies Plus: StoreHub dashboard + chatbot**
<img width="100" height="230" alt="image" src="https://github.com/user-attachments/assets/7ea36789-d21a-4a47-a878-81c251a4f0fc" />

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
End-to-end development and validation of PSP StoreHub platform including Revv/NRR comment ingestion, StoreHub dashboard, ALAN Text2SQL chatbot, SOP RAG, and data pipeline for Pet Supplies Plus retail operations.

#### **◉ Tools Used** 
Python, BigQuery, GCS, Postgres (RAG), OCR, LLM prompts (Gemini/OpenAI), Excel.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).

#### **◉ Key Achievements**
Fully automated Revv/NRR ingestion & categorization (sentiment, comment/question categories, autofail flagging).
Validated and enhanced StoreHub dashboard KPIs with fiscal calendar support.
Improved StoreHub ALAN Chatbot accuracy through context updates, generic/ambiguous question handling, and validation reports.
Resolved multiple data gaps and performed referential integrity checks across Transaction, Revv, NRR, Store Master tables.

#### **◉ Challenges**
Incomplete audits, missing store/district mappings, image handling in PDFs, and ensuring incremental updates without duplicates.

#### **◉ More about this project**
https://github.com/bharathsp/IA-Agent-Studio/blob/main/Projects/StoreHub%20%26%20Alan%20Chatbot.md

---

### **Pet Supplies Plus: SOP RAG**
<img width="100" height="230" alt="image" src="https://github.com/user-attachments/assets/7ea36789-d21a-4a47-a878-81c251a4f0fc" />

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
End-to-end development and validation of PSP StoreHub platform including Revv/NRR comment ingestion, StoreHub dashboard, ALAN Text2SQL chatbot, SOP RAG, and data pipeline for Pet Supplies Plus retail operations.

#### **◉ Tools Used** 
Python, BigQuery, GCS, Postgres (RAG), OCR, LLM prompts (Gemini/OpenAI), Excel.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).

#### **◉ Key Achievements**
Fully automated Revv/NRR ingestion & categorization (sentiment, comment/question categories, autofail flagging).
Validated and enhanced StoreHub dashboard KPIs with fiscal calendar support.
Improved StoreHub ALAN Chatbot accuracy through context updates, generic/ambiguous question handling, and validation reports.
Resolved multiple data gaps and performed referential integrity checks across Transaction, Revv, NRR, Store Master tables.

#### **◉ Challenges**
Incomplete audits, missing store/district mappings, image handling in PDFs, and ensuring incremental updates without duplicates.

#### **◉ More about this project**
https://github.com/bharathsp/IA-Agent-Studio/blob/main/Projects/Store%20SOP.md

---

### **Pet Supplies Plus: Label Compliance Checker**
<img width="100" height="230" alt="image" src="https://github.com/user-attachments/assets/7ea36789-d21a-4a47-a878-81c251a4f0fc" />

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
End-to-end development and validation of PSP StoreHub platform including Revv/NRR comment ingestion, StoreHub dashboard, ALAN Text2SQL chatbot, SOP RAG, and data pipeline for Pet Supplies Plus retail operations.

#### **◉ Tools Used** 
Python, BigQuery, GCS, Postgres (RAG), OCR, LLM prompts (Gemini/OpenAI), Excel.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).

#### **◉ Key Achievements**
Fully automated Revv/NRR ingestion & categorization (sentiment, comment/question categories, autofail flagging).
Validated and enhanced StoreHub dashboard KPIs with fiscal calendar support.
Improved StoreHub ALAN Chatbot accuracy through context updates, generic/ambiguous question handling, and validation reports.
Resolved multiple data gaps and performed referential integrity checks across Transaction, Revv, NRR, Store Master tables.

#### **◉ Challenges**
Incomplete audits, missing store/district mappings, image handling in PDFs, and ensuring incremental updates without duplicates.

#### **◉ More about this project**
https://github.com/bharathsp/IA-Agent-Studio/blob/main/Projects/Label%20Compliance%20Checker.md

---

### **Pet Supplies Plus: Store Navigator**
<img width="100" height="230" alt="image" src="https://github.com/user-attachments/assets/7ea36789-d21a-4a47-a878-81c251a4f0fc" />

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
End-to-end development and validation of PSP StoreHub platform including Revv/NRR comment ingestion, StoreHub dashboard, ALAN Text2SQL chatbot, SOP RAG, and data pipeline for Pet Supplies Plus retail operations.

#### **◉ Tools Used** 
Python, BigQuery, GCS, Postgres (RAG), OCR, LLM prompts (Gemini/OpenAI), Excel.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).
Generated comprehensive synthetic datasets (Transaction, Inventory, Product, Promotion, Store, Store Layout, etc.) with product images and location hierarchy.
Created golden Q&A pairs and achieved 84% accuracy on SOP Agent validation.
Prepared Wow Questions, ERDs, and demo materials.

#### **◉ Key Achievements**
Fully automated Revv/NRR ingestion & categorization (sentiment, comment/question categories, autofail flagging).
Validated and enhanced StoreHub dashboard KPIs with fiscal calendar support.
Improved StoreHub ALAN Chatbot accuracy through context updates, generic/ambiguous question handling, and validation reports.
Resolved multiple data gaps and performed referential integrity checks across Transaction, Revv, NRR, Store Master tables.

#### **◉ Challenges**
Incomplete audits, missing store/district mappings, image handling in PDFs, and ensuring incremental updates without duplicates.

#### **◉ More about this project**
https://github.com/bharathsp/IA-Agent-Studio/blob/main/Projects/Store%20Navigator.md

---

### **Tractor Supplies Company: Promo Recommendation**
<img width="200" height="1031" alt="image" src="https://github.com/user-attachments/assets/0d766e65-b97b-4f70-98ac-b9a4aee22a88" />


#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
Customer segmentation and Promo Recommendation solution for Tractor Supply Co. using Snowflake.

#### **◉ Tools Used** 
Snowflake, Python, Cursor, Excel/CSV.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).

#### **◉ Key Achievements**
Implemented IA-defined + loyalty (NC vs Non-NC) customer segmentation with optimized multi-stage joins.
Created data dictionaries, ERDs, validation checklists, and segmentation reports.
Migrated logic and prepared data for backend development.

#### **◉ Challenges**
Low promo match rates, query timeouts on large joins, and data availability across Sales/Order/Promo tables.

---

### **Interstate Batteries: Chatbot Agent**
<img width="206" height="258" alt="image" src="https://github.com/user-attachments/assets/5d2490a6-f9ed-4caa-92f7-34419426abaf" />

#### 📅 **Date:** Oct 2025 - Present

#### **◉ Project Overview**
RAG + structured data pipeline for financial analysis from EDGAR filings (10K, 10Q, 8K, XBRL).

#### **◉ Tools Used** 
Snowflake, Python, Cursor, Excel/CSV.

#### **◉ Responsibilities**
All PSP-specific tasks listed in context (data ingestion from PDFs/Excel, categorization, dashboard/KPI validation, chatbot testing, fiscal calendar, etc.).

#### **◉ Key Achievements**
Ingested and structured data for multiple companies with KPI extraction, derived KPIs (YoY/QoQ), deduplication.
Built RAG-consumable context, tables (kpi_fact, document_catalog, etc.), and chatbot validation with latency improvements.
Added column descriptions, source links, and scaling validations.

#### **◉ Challenges**
Extracting consistent data from XBRL/EDGAR, handling missing KPIs/stores, and query issues in agent.
Interview conduction, KT sessions, and cross-project support (Ad Banner validation, web scraping, etc.).
Research on NRF events and retail trends.
