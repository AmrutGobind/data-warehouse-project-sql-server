# SQL Server Data Warehouse Project

Welcome to my **personal Data Warehouse project** using SQL Server! 🚀  
This hands-on portfolio project demonstrates modern data warehousing with Medallion Architecture (Bronze, Silver, Gold layers), ETL pipelines, star schema modeling, and SQL analytics. Built to showcase data engineering skills for senior roles.

## 🏗️ Data Architecture

Follows Medallion Architecture:
- **Bronze Layer**: Raw data ingestion from CSV sources (ERP/CRM) into SQL Server.
- **Silver Layer**: Cleansing, standardization, and normalization.
- **Gold Layer**: Star schema for reporting and BI analytics.

## 📖 Project Overview

Key components:
1. **Data Architecture**: Medallion layers for scalable warehousing.
2. **ETL Pipelines**: Extract, transform, load via SQL scripts.
3. **Data Modeling**: Fact/dimension tables optimized for queries.
4. **Analytics**: SQL reports on sales trends, customer behavior, product performance.

Perfect for Data Engineers/DevOps pros learning cloud-ready data pipelines.

## 🛠️ Tools & Resources

- **Datasets**: CSV files in `/datasets/` (ERP + CRM sales data).
- **SQL Server Express**: Free database hosting.
- **SSMS**: Database management GUI.
- **DrawIO**: For architecture diagrams in `/docs/`.
- **GitHub**: Version control for scripts.

## 🚀 Requirements

- Import/cleanse latest sales data from CSV sources.
- Build ETL for data quality and integration.
- Create analytical star schema (no historization needed).
- Document models for stakeholders.

See `/docs/requirements.md` for details.

## 📂 Repository Structure

```
sql-server-data-warehouse/
├── datasets/                  # Raw CSV data (ERP/CRM)
├── docs/                      # Diagrams & docs
│   ├── data_architecture.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
├── scripts/                   # SQL ETL scripts
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/                     # Data quality tests
└── README.md
```

## 🛡️ License

MIT License - Free to use/modify with attribution.

## 🌟 About Me

Data Engineer & DevOps professional from Bhubaneswar, Odisha. Passionate about SQL optimization, AWS/Docker/K8s, and building production-ready pipelines. Open to collaborations!

