# Retail-Data-Azure-Databricks-project-
Data Engineering project using powerful tools like Azure Databricks, Delta Live Tables, Spark Streaming, and PySpark. Explored real-world use cases such as Dimensional Data Modeling and handling Slowly Changing Dimensions in Databricks.

1. Implemented a Medallion architecture (Bronze → Silver → Gold) enabling raw data ingestion from a cloud-hosted Azure SQL Database, enrichment and governance via Delta Lake and Unity Catalog, and consumption-ready dimensional models.

2. Designed fully parameterised streaming pipelines delivering incremental loads and idempotency capabilities via Spark Autoloader with code reuse through OOP-based PySpark utilities and registered functions.

3. Built Gold-layer star-schema fact and dimension tables, including implementation of Slowly Changing Dimensions (SCD) Type 1 and Type 2 logic via Delta Live Tables for automatic change-history management.
