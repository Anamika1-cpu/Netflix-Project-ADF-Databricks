# Netflix-Project-ADF-Databricks(End-to-End DE Project)

# Overview
This project showcases a complete end-to-end data engineering solution using Azure services, emphasizing dynamic pipeline orchestration, real-time data ingestion, and seamless integration with Power BI for interactive analytics.

# Architecture
<img src='https://github.com/Anamika1-cpu/Netflix-Project-ADF-Databricks/blob/master/Netflix_Project%20Architecture.drawio%20(1).drawio.png'/>
# Highlights
<li>Designed and implemented dynamic ingestion pipelines in Azure Data Factory and Databricks to automate raw file ingestion into ADLS Gen2, applying consistent file naming conventions and schema structures for scalable processing.
<li>Configured external locations and storage credentials in Unity Catalog to ensure secure, governed access to data lakes across staging and production environments.
<li>Utilized Databricks Autoloader for efficient, incremental ingestion of streaming data, reducing latency and eliminating manual tracking of file states.
<li>Built a real-time processing pipeline using Delta Live Tables (DLT) to handle continuous data loads with built-in quality checks, schema enforcement, and lineage tracking, replicating architectures similar to those used by Netflix.
<li>Developed conditional workflows using dynamic parameters and if-else logic to route data through specific transformation paths based on file metadata and business rules.
<li>Enabled business reporting by integrating processed data into Power BI, creating dynamic dashboards and KPI visualizations for real-time insights.
<li>Ensured end-to-end orchestration, monitoring, and troubleshooting using Azure Monitor, Log Analytics, and Databricks notebooks for efficient operational management.

# Tech Stack
<li><b>Azure Data Lake:</b> Scalable, secure cloud storage solution for managing both structured and unstructured data at scale.

<li><b>Azure Data Factory:</b> Enables orchestration of automated, metadata-driven ETL pipelines for seamless data movement and transformation.

<li><b>Databricks Autoloader:</b> Facilitates efficient, incremental ingestion of new files from cloud storage into Delta Lake for real-time processing.

<li><b>Workflow Logic (If-Else):</b> Implements dynamic, rule-based branching in pipelines to automate and route data flows based on custom conditions.

<li><b>Power BI:</b> Empowers business users with real-time, interactive dashboards and data visualizations for actionable decision-making.

<li><b>Delta Live Tables:</b> Automates streaming and batch data transformations with built-in data quality checks, schema enforcement, and lineage tracking for real-time analytics.
