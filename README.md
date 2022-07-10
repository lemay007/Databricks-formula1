# Databricks-formula1
Using databricks to create delta lake/data lakehouse for ingesting, transforming/cleaning, and analyzing data.



### Data Ingestion Requirements
* Ingest all 8 files into data lake
* Ingested data must have schema applied
* Ingested data must have audit columns
* Ingested data must be stored in columnar format
* Must be available for all kinds of workloads such as:
  * Machine Learning
  * Further transformation for reporting
  * Analytical workloads via SQL
* Ingestion logic must be able to handle incremental loads



### Data Transformation Requirements
* Join information from different data sources to create a new table
* Transformed tables must have audit columns
* Stored in a SQL friendly format
* Transformation Logic must also be able to handle incremental loads



### Dashboard Requirements
* Find and rank dominant drivers
* Find and rank dominant teams
* Visualize these outputs within Databricks

### Non functional requirements - satisfied by Delta Lake
* Delete individual records
* Ability to see history and time travel
* Ability to roll back to a previous version
