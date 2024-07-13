# Analytics Engineer Portfolio
The subdivision about analytics engineering, it covers dbt with high-level features and involves the usage of BI tools.

Some projects are part of projects in my [data science projects portfolio](https://github.com/xiangivyli/data-science-portfolio/blob/main/README.md). Some links show the material I created when I followed online courses.

It mainly involves 2 parts, dbt and BI reports. I hope it shows my passion for analytics engineering, I enjoy scaling data transformation in strategy.
# Table of Contents

## Part A dbt

### [Job Postings on Linkedin](https://github.com/xiangivyli/data-science-portfolio/tree/main/part_a_job_posting_linkedin_pipeline/airflow/dags/dbt)
Tag: My Design

Tools:
 - Data Transformation: **dbt**
 - Data Orchestration: **Airflow**
 - Data Visualisation: **Power BI**
 - Data Quality Testing: **Soda** and **dbt test**
 - Data Lake: **Google Cloud Storage**
 - Data Warehouse: **BigQuery**

Summary:
This project aims to build an end-to-end data pipeline from a bigger picture. For the dbt part, I used **DbtDag** as the downstream of a data ingestion dag, and it is triggered by Dataset (which means once new data is in the big query, dbt starts to transform)

Lineage Graph:
