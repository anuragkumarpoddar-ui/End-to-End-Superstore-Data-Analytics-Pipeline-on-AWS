# 🛒 End-to-End-Superstore-Data-Analytics-Pipeline-on-AWS

![AWS](https://img.shields.io/badge/Cloud-AWS-orange?style=for-the-badge&logo=amazon-aws)
![Python](https://img.shields.io/badge/Data--Pipeline-ETL-blue?style=for-the-badge&logo=python)
![QuickSight](https://img.shields.io/badge/BI-QuickSight-purple?style=for-the-badge&logo=amazonaws)

A complete, end-to-end cloud data engineering and business intelligence project built on **Amazon Web Services (AWS)**. This project demonstrates how to ingest raw retail data, secure access, catalog schemas, run serverless SQL queries, and build insightful executive dashboards.

---

## 👨‍💻 Author & Contact
* **Name:** Anurag Kumar Poddar
* **Role:** Data Analyst
* **Contact:** +91 97487 48405

---

## 🏗️ Architecture & Workflow


[ Raw CSV Data ] 

       │
       ▼
   ( Amazon S3 ) ──► [ AWS IAM (Access Control) ]
   
       │
       ▼
  ( AWS Glue )   ──► (Data Catalog & Schema Crawler)
  
       │
       ▼
  ( AWS Athena ) ──► (Serverless SQL Analytics)
  
       │
       ▼
( Amazon Quicksight ) ──► (Interactive Dashboards & Visualization)



# 🛠️ Tech Stack & Services Used

AWS IAM: Configured secure, least-privilege roles and policies for data governance across services.


Amazon S3: Acted as the secure central cloud data lake storage for raw transactional inputs.


AWS Glue: Used for automated crawling and creating structured data catalog tables.


AWS Athena: Enabled serverless ANSI SQL querying directly over data stored in S3.


Amazon QuickSight: Connected securely as the BI layer to build visual charts and business reports.


# 📊 Key Highlights & Visualizations

Category Performance Analysis: Evaluated sales and order volume across product segments like Office Supplies and Furniture.

Geographic Insights: Mapped sales distribution across major metropolitan cities (such as Huntsville, Jacksonville, Los Angeles, and Franklin) to identify top-performing regions.

# 🚀 Future Enhancements
Implementing automated event-
driven ingestion using AWS Lambda and Amazon EventBridge.

Optimizing Athena query performance using partitioning and columnar file formats (like Parquet).

# ⭐ Feel free to fork or clone this repository if you find it helpful!
