# Data Engineering Pipelines

A collection of data engineering projects focused on building end-to-end data pipelines to handle data from various sources, apply complex transformations, and efficiently load and store data using a variety of technologies. These pipelines leverage SQL/NoSQL databases, big data tools (Kafka, Spark, etc.), and cloud solutions to manage data processing tasks at scale. Each project provides a unique data engineering solution with practical applications in industry and academia.

## Projects

### 1. [E-Patent (Patent Analysis)](https://github.com/hamzaae/Big-Data-Project-Patent-Analysis)
An academic project analyzing patents related to Artificial Intelligence in education, aiming to provide insights through a user-friendly web application. Key features include:

- **Data Collection**: Gathers data through APIs and web scraping.
- **Storage**: Uses MongoDB, PostgreSQL, and HDFS for data storage.
- **Transformation**: Utilizes Apache Spark for data processing.
- **Visualization**: Implements Flask for the frontend and PowerBI for data visualization.

The goal is to deliver both personalized and general analyses of patents, making research more accessible.

### 2. [Real-Time People Count Pipeline](https://github.com/hamzaae/Real_Time_People_Monitor)
A Lambda architecture pipeline designed to count people in various zones of a market in real-time, generating valuable insights based on the flow of individuals. Main features:

- **Object Detection**: Uses YOLOv5 with Python to detect and count people.
- **Big Data Tools**: Processes and streams data with Kafka, HDFS, and Spark.
- **Workflow Management**: Utilizes Apache Airflow for scheduling tasks.
- **Visualization**: Data insights visualized in Power BI.
- **Containerization**: Dockerized for easy deployment.

This project demonstrates the use of real-time data processing for operational intelligence in commercial settings.

### 3. [GitHub Trending Repos](https://github.com/hamzaae/GitHub-Trending-Repos)
![image](https://github.com/user-attachments/assets/b42ee071-c48d-4ee5-9f1f-18006c705d13)

An end-to-end data engineering project tracking and displaying daily trending GitHub repositories. Designed to showcase the complete data engineering process, it combines data collection, transformation, storage, and visualization using various tools and platforms:

- **Data Collection**: Uses the GitHub REST API to collect insights on trending repositories.
- **Streaming**: Employs Kafka for streaming and managing data flow in real-time.
- **Storage**: Data stored in Azure Blob Storage, providing a scalable storage solution.
- **Transformation**: Uses PySpark on Azure Databricks for data processing.
- **Orchestration**: Azure Data Factory manages data flow from Azure Blob to Azure SQL.
- **Structured Storage and Querying**: Stores refined data in Azure SQL.
- **Visualization**: Power BI for dynamic data visualization, displaying trends and repository insights.

> **Note**: This project is designed with an educational focus, demonstrating the use of various tools across different stages of data engineering.

### 4. [Avito Product Tracking](https://github.com/hamzaae/Avito-Product-Track)
![image](https://github.com/user-attachments/assets/362f8956-1981-4150-9543-ba867cb0aabe)

An exciting data engineering project focused on tracking product data on Avito to analyze market trends and pricing. The pipeline includes data extraction, transformation, and storage, using key data engineering tools and techniques:

- **Data Extraction**: Web scraping with BeautifulSoup in Python to collect product data from Avito.
- **Data Transformation**: Data cleaning and processing with Python to ensure accuracy and consistency.
- **Orchestration and Deployment**: Managed with Apache Airflow on an Azure Virtual Machine for scalable, reliable task scheduling.
- **Storage**: Processed data stored in Azure Blob Storage for cloud-based persistence.

This project showcases the integration of web scraping, cloud storage, and workflow orchestration for comprehensive product tracking.

---

Each project showcases a distinct approach to data pipeline development, employing a variety of tools to meet different data engineering needs. Let’s keep pushing the boundaries of Data Engineering!
