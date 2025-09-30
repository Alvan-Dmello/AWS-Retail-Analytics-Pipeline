# AWS Retail Analytics Pipeline

This project features a **scalable, end-to-end data pipeline** built using **AWS** and **PySpark** to process and analyze a retail store dataset. The pipeline automates data ingestion, transformation, storage, and visualization, while integrating **AWS SageMaker Autopilot** for machine learning and **AWS QuickSight** for interactive dashboards.

---

## ✨ Features & Pipeline Automation

The pipeline is designed for robustness and scalability, automating the entire journey from raw data to actionable insights:

* **Automated ETL Pipeline:** Uses **cron jobs** to schedule data processing, ensuring continuous and up-to-date data ingestion and transformation.
* **Big Data Processing:** Utilizes **PySpark** and **Spark SQL** for efficient data transformation, cleaning, and aggregation across large retail datasets.
* **Scalable AWS Integration:** Stores raw and processed data in **AWS S3** for secure, cost-effective, and scalable storage.
* **Machine Learning Integration:** Leverages **AWS SageMaker Autopilot** to automatically train and optimize machine learning models on the processed data.
* **Data Visualization:** Creates **interactive dashboards** using **AWS QuickSight** to present key business metrics and derived insights.

---

## 🛠️ Technology Stack

| Category | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Cloud Infrastructure** | **AWS Services (S3, SageMaker, QuickSight)** | Hosting, storage, machine learning, and business intelligence platform. |
| **Data Processing** | **PySpark, Spark SQL** | Efficient Big Data transformation, cleaning, and complex querying. |
| **Automation** | **Cron Jobs** | Scheduled execution of the pipeline scripts for data updates. |

---

## 📁 Project Structure & Files

This repository contains the complete codebase and documentation for the pipeline, showcasing the entire data lifecycle.

| Folder / File Name | Contents and Purpose |
| :--- | :--- |
| **`Dataset.csv`** | **Raw Data Source.** The original, uncleaned retail dataset used as the source for the entire pipeline. |
| **`Preprocessed Data/`** | **Intermediate Data.** The final, cleaned, and transformed dataset ready for machine learning (SageMaker) or reporting. |
| **`Aggregated Data/`** | **Final Output Data.** Results after running various PySpark aggregation queries, used for QuickSight dashboards. |
| **`data_preprocessing_pyspark.ipynb`** | **Primary ETL Script.** PySpark code for data cleaning, transformation, and ingestion logic. |
| **`SQL_Queries.py`** | **Spark SQL Logic.** Contains reusable Spark SQL scripts for efficient querying and aggregation within the PySpark pipeline. |
| **`Project_Report.pdf`** | **Detailed Documentation.** Full report on pipeline architecture, PySpark methodology, ETL logic, and SageMaker Autopilot results. |
| **`Quicksight_Dashboard.pdf`** | **Visualization Preview.** Static views of the final interactive dashboard and key business insights. |

---

## 🚀 How to Use & View

For a step-by-step guide on setting up the AWS services, running PySpark scripts, and automating the entire pipeline process, **refer to `Project_Report.pdf`**.

### Results & Insights

* **Detailed analysis and insights** are documented in **`Project_Report.pdf`**.
* **Visualization of key business metrics** can be found in **`Quicksight_Dashboard.pdf`**.
* **Aggregated query results** are available in the **`Aggregated Data/`** directory.
