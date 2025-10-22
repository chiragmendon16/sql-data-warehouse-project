# Data Warehouse and Analysis Project

Welcome to the **Data Warehouse and Analysis Project** repository 🚀
This project demonstrate a comprehensive data warehousing and analytics solution, from the building of the data warehouse to the generatung the actionable insights.
Designed as a portfolio project which highlights the industry best practices in the data engineering and the analytics

---
<h2>🏗️ Data Architecture</h2>
      <p>This project follows a Medallion Architecture (Bronze → Silver → Gold) approach to organize and mature data as it flows from sources to analytics.</p>
<section class="card">
  <h2>📊 Data Architecture Diagram</h2>
  <img src="docs/data_architecture.png" alt="Architecture Overview" width="700">
</section>


<ul class="layers">
        <li><strong>Bronze Layer:</strong> Raw ingestion of source CSV files into SQL Server (as-is snapshots).</li>
        <li><strong>Silver Layer:</strong> Cleansing, standardization and normalization for consistent, analysis-ready records.</li>
        <li><strong>Gold Layer:</strong> Business-ready star-schema models (fact and dimension tables) designed for fast analytic queries.</li>
      </ul>
---
 <h2>📖 Project Overview</h2>
<p>This project includes the full lifecycle:</p>
- 1. ## Data Architecture -  Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
  2. ## ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse
  3. ## Data Modeling: Developing fact and dimension tables optimized for analytical queries.
  4. ## Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

This repository is an excellent resource for professionals and students looking to showcase expertise in:
<li>
SQL Development
Data Architect
Data Engineering
ETL Pipeline Developer
Data Modeling
Data Analytics
</li>

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
To develop a modern data warehouse using the SQL Server to consolidate the sales data, enabling the analytical reporting and informed decisions - making.

#### Specifications
- **Data Sources** -> Import the Data from the two source system (ERP and CRM) provided as a CSV files.
- **Data Quality** -> Cleanse and resolve the data quality issues prior to analysis.
- **Intergration** -> Combine both the sources into a single, user - friendly data model designed fro the analytical queries.
- **Scope** -> Focus on the clear latest dataset only; historization of the data us not required.
- **Documentation** -> Provide clear documentation of the data model is to support both the business stakeholders and the analytics teams.


---

<section id="structure" class="card">
      <h2>📂 Repository Structure</h2>
      <pre class="tree">
data-warehouse-project/
│
├── datasets/           # Raw CSVs (ERP, CRM)
├── docs/               # Architecture diagrams & documentation
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── naming-conventions.md
├── scripts/
│   ├── bronze/         # raw ingestion scripts
│   ├── silver/         # cleaning & transformation scripts
│   └── gold/           # modeling & analytical scripts
├── tests/              # data quality and test scripts
├── README.html         # this file
├── LICENSE
└── requirements.txt
      </pre>
    </section>
---
<h2>🛠️ Tools & Resources</h2>
      <p>All tools used in this project are free or have free tiers. Typical stack:</p>
      <ul>
        <li>Datasets: CSV files (included in <code>datasets/</code>)</li>
        <li>SQL Server Express — lightweight database engine</li>
        <li>SQL Server Management Studio (SSMS) — GUI for database management</li>
        <li>Git & GitHub — source control</li>
        <li>Draw.io — architecture and data model diagrams</li>
        <li>Notion (optional) — project checklist & template</li>
      </ul>
</section>
---
### BI: Analytical & Reporting (Data Analytics)

#### Objective
Develop SQL - based analytics to deliver the detailed insights into:
- **Customer Behaviour**
- **Product Perfromance**
- **Sales Trends**

These are the insights empowers the Stakeholders with the key business metrics, enabling the 
strategic decision-making

---

## 🪪 License
This Project is licensed under the [MIT License].(LICENSE). You guys are free to use, modify and share this project with the proper attribution.

## 🙋‍♂️ About Me
Hi there!! I'm **Chirag Mendon**, im a Computer Engineer and im very passionate about the Data and stuffs.
