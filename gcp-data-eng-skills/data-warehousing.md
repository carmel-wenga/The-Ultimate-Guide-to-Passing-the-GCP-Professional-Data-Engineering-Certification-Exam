# BigQuery

* Analyze cost-effectiveness of flat-rate billing by evaluating query slot utilization.
* Analyze data access patterns using Cloud Audit Logs for better security insights.
* Analyze geospatial trends using SQL queries on tracking data.
* Analyze query performance using INFORMATION_SCHEMA for insights into job execution.
* Analyze query plans to identify potential data skew issues.
* Append new data efficiently to handle frequent updates in large datasets.
* Apply best practices for star schema optimization in the data model.
* Assess current data warehouse structures to plan for migration.
* Assess data sources compatibility for migration.
* Assign data viewer access at the view level to enforce permissions based on team membership.
* Assign jobUser role to allow users to execute queries without excessive permissions.
* Batch updates and inserts to improve query performance.
* Change BigQuery table's schema by migrating the data to another BigQuery table.
* Change from Google-managed encryption key to Customer-Managed Encryption Key (CMEK) with Cloud KMS.
* Choose on-demand pricing for cost-effective analysis with uncertain usage patterns.
* Configure dataset access permissions for region-based security groups.
* Configure dataset-level permissions for user-specific access control, Viewer, Editor, Owner, ...
* Configure materialized views to refresh automatically for up-to-date insights.
* Configure materialized views with max_staleness and enable_refresh to automate data updates.
* Configure multi-regional datasets for high availability and redundancy.
* Configure output destinations for caching to improve query performance.
* Configure roles to control data access based on sensitivity tags.
* Configure slot reservations and autoscaling to meet specific project needs while managing costs.
* Control data read permissions through IAM roles.
* Convert sharded tables into partitioned tables to handle large date range queries efficiently.
* Create a view to concatenate fields without altering the underlying data.
* Create authorized views for fine-grained access control to limit data visibility.
* Create authorized views to share aggregated data while protecting underlying details.
* Create external tables to query data directly from Cloud Storage.
* Create external tables to query data stored in Cloud Storage and Google Drive without loading it into BigQuery.
* Create external tables using ORC files stored in Cloud Storage.
* Create materialized views for efficient aggregation and reduced query costs.
* Create materialized views to improve query performance for visualization tasks.
* Create permanent external tables to query data stored in Cloud Storage.
* Create separate datasets to segregate data by department.
* Create table's views to simplify and limit data exposure in reports.
* Create views to filter and aggregate Cloud Logging log data efficiently.
* Create views to filter data for cost-effective reporting without additional storage.
* Denormalize relational datasets for optimized read performance in analytical databases.
* Design a denormalized schema using nested and repeated fields for efficient querying and storage.
* Design data models aligned with warehouse requirements.
* Design denormalized schema to optimize query performance for analytic queries.
* Design denormalized schemas to leverage hierarchical data structures for improved query efficiency.
* Design schema with nested and repeated fields for denormalization.
* Design schemas using nested and repeated fields for hierarchical data to improve query performance.
* Efficiently query large datasets to provide near real-time data visualization.
* Efficiently write processed data ensuring compliance with data locality requirements.
* Employ clustering to enhance query performance through more efficient data organization.
* Enable access for seamless integration with Connected Sheets for data analysis.
* Enable analysis on data stored in Cloud Storage using external tables.
* Enable service account to read and write processed data securely.
* Enable streaming inserts to handle high-volume incoming data.
* Establish hierarchical priority for projects to optimize query execution under resource constraints.
* Estimate and accommodate data latency for consistent query results.
* Execute ELT processes to transform data using SQL within the data warehouse.
* Execute SQL queries directly on data in Cloud Storage via external tables.
* Export data from Bigtable to BigQuery for daily analytic tasks.
* Export table data to Cloud Storage for long-term storage.
* Facilitate ad hoc data sharing between projects using IAM roles.
* Handle large-scale data up to petabytes with scalable columnar storage.
* Identify cost optimization opportunities when migrating from on-premises.
* Implement a fault-tolerant architecture for data recovery with minimal RPO.
* Implement access controls to ensure only authorized personnel can view sensitive datasets.
* Implement clustering on frequently queried columns to improve query performance and cost-efficiency.
* Implement clustering on frequently-filtered columns like ID for optimal data retrieval.
* Implement clustering to improve query performance by organizing data based on frequently filtered columns.
* Implement clustering to optimize data retrieval and improve query performance.
* Implement cost-effective solutions for large-scale data analytics.
* Implement customer-managed encryption keys (CMEK) for enhanced data security.
* Implement DRP with a recovery point objectif (RPO) of less than 24 hours.
* Implement Enterprise reservations to control and predict analytics costs.
* Implement flat-rate pricing to manage resource allocation efficiently.
* Implement materialized views to streamline query performance and exposure of latest data records.
* Implement partitioning and clustering to improve query performance.
* Implement per-user crypto-deletion using AEAD functions for data encryption.
* Implement point-in-time recovery using backup tables with time-based suffixing.
* Implement policy tags to restrict column-level access to sensitive data.
* Implement reservations to manage and optimize query costs in BigQuery.
* Implement schema design that reduces JOIN operations by combining related data fields.
* Implement streaming ingestion for real-time data updates.
* Implement table partitioning on date column to optimize query performance and reduce cost.
* Improve query efficiency by organizing data based on query patterns and frequently used fields.
* Include TIMESTAMP columns to enable efficient time-based queries.
* Ingest data securely without using the public internet.
* Integrate domain-specific datasets into Dataplex zones for improved accessibility and management.
* Integrate monitoring to track query processing health.
* Integrate seamlessly with Data Fusion for efficient data loading.
* Integrate with Cloud Bigtable for hybrid data processing tasks.
* Integrate with Looker Studio for real-time data visualization.
* Leverage denormalization techniques to optimize query performance and reduce CPU usage.
* Leverage managed service features to perform analysis without needing infrastructure management.
* Load and query data efficiently using Avro for schema compatibility and serialization.
* Load CSV data using correct encoding to ensure accurate import.
* Load CSV datasets for efficient storage and manage large-scale telemetry data for analysis.
* Load data directly from Cloud Storage for seamless data integration.
* Load data from BigLake for efficient querying and reduced ETL overhead.
* Load data from Cloud Storage into BigQuery using Avro format for optimized performance.
* Load data from MySQL using an ETL tool for large-scale analytics.
* Load processed data for analysis and report generation.
* Maintain up-to-date query results using materialized views with automatic refresh.
* Manage and analyze processed curated data within Dataplex structure.
* Manage cross-cloud queries using external data sources efficiently.
* Manage data access and permissions for datasets in a multi-team setting.
* Manage permissions to securely share datasets with third parties.
* Manage slot capacity and autoscaling for optimal resource allocation.
* Migrate Apache Parquet data to BigQuery.
* Migrate data encrypted with Google-managed key to a new table in order to use customer-managed encryption keys from Cloud KMS.
* Migrate from sharted tables to partitioned table to avoid exceeding the limit of 1000 tables when using table wildcard function.
* Migrate low-risk data first for cloud data warehousing to minimize potential impact on business operations.
* Migrate on-premises data warehouse to reduce maintenance costs and increase feature rollout speed.
* Monitor and manage concurrency to prevent performance degradation.
* Optimize cost and performance by leveraging denormalization.
* Optimize cost by querying external data without loading into BigQuery.
* Optimize data storage by compressing older data for cost-effective analysis.
* Optimize data warehouse updates using DML MERGE, INSERT, UPDATE, and DELETE operations to batch changes.
* Optimize performance with regional tables for lower latency.
* Optimize query execution by using materialized views to leverage cached data efficiently.
* Optimize query performance through denormalization techniques.
* Optimize retrieval of large datasets by selecting specific columns.
* Optimize storage by managing lifecycle of table data for cost efficiency and performance.
* Optimize visualizations using outer joins and analytic functions.
* Optimize workload management with short-term reservations for peak usage times.
* Organize data in columns suitable for machine learning tasks while minimizing coding requirements.
* Organize tables into region-specific datasets to ensure data segregation for several team accross several regions.
* Partition tables to improve query performance and manage data lifecycle.
* Perform aggregate transformations on data using SQL within Cloud Composer pipelines.
* Perform aggregations over petabyte-scale datasets efficiently.
* Perform analytical queries on integrated datasets from Datastream and Google Analytics.
* Perform complex analytics queries including joins.
* Perform complex, time-consuming SQL-based transformations.
* Perform data aggregations immediately after data insertion.
* Perform high-speed analytics on streaming data using BigQuery's native support for real-time inserts.
* Perform near real-time and historical SQL queries on ingested data.
* Prepare data in BigQuery for training machine learning models.
* Process data using Apache Spark with BigQuery for SQL analysis using Spark-BigQuery connector.
* Query CSV and Avro files stored in Cloud Storage using BigQuery's federated query.
* Query several BigQuery tables using table wildcards.
* Query wildcard tables using backticks for correct syntax.
* Reduce operational overhead with serverless architecture and pay-per-use pricing.
* Restrict dataset access to approved users to maintain data security.
* Restrict table access by defining roles with minimal permissions.
* Review data transformations ensure they produce accurate results.
* Schedule exports of datasets to minimize RPO while maintaining cost efficiency.
* Schedule recurring queries to maintain data consistency over time.
* Securely load transformed data securely from Dataflow pipelines that runs on VMs without external IP addresses.
* Set partition expiration for automatic data deletion to manage storage costs and relevancy.
* Set SQL query jobs to interactive priority for time-sensitive ad-hoc queries.
* Share query costs by assigning shared views to different projects.
* Store analytical large datasets.
* Store and analyze data extracted from Natural Language API.
* Store and manage final Dataplex curated data efficiently.
* Store processed data for machine learning model training and querying.
* Test queries to validate performance and correctness in the new setup.
* Train and deploy models using BigQuery ML for prediction tasks.
* Understand all the BigQuery reservation strategies and how to use them to optimize BigQuery costs.
* Understand BigQuery Partitioning and Clustering to improve query performance
* Understand BigQuery roles and capabilities with their use cases
* Understand how BigQuery reservation works and how to use it.
* Understand how preprocessing with TRANSFORM clause work in the training, evaluation, and prediction stage of the machine learning model with BigQuery.
* Understand how the BigQuery Streaming API works and its corresponding use cases.
* Understand how to load CSV with millions of records to a BigQuery table.
* Understand how to share CMEK datasets with external teams.
* Understand quotas and limits for concurrent queries.
* Understand Scheduled Query and Cached Query and how to use them.
* Understand the BigQuery architecture.
* Understand the difference between BATCH and INTERACTIVE job priorities in BigQuey.
* Understand the difference between BigQuery functions LAG and ROW_NUMBER
* Understand the difference between Views and Materialized Views
* Understand what BigQuery schema, that it is immutable and how to define it.
* Understand what is BigQuery slots and how to monitor them.
* Understand what is BigQuery Storage Write API and how to use it.
* Understand what is BigQuery's DML quotas and to avoid going over the quotas.
* Understand what is Table Decorator and how to use it to references the historical version of a table at a specified timestamp.
* Understand when and how to use --dry_run in BigQuery queries
* Undertand the difference between views, authorized views, materialized views, authorized dataset, and their use cases
* Use _PARTITIONTIME in WHERE clause to optimize query performance and reduce data scanned.
* Use allow_non_incremental_definition for materialized views to manage data freshness requirements.
* Use appropriate data types for clustering to optimize query efficiency.
* Use batch mode queries to manage and reduce concurrent query limits.
* Use batch priority for non-time-sensitive SQL pipelines to manage resources efficiently.
* Use BI Engine to accelerate dashboards for faster query performance.
* Use BigQuery  Data Transfer Service to facilitate data migration from Teradata to BigQuery using JDBC driver with FastExport connection.
* Use BigQuery as a data source for Spark jobs to efficiently process large datasets.
* Use BigQuery Storage Write API for high-throughput, exactly-once data ingestion.
* Use BigQuery streaming inserts to enable real-time data ingestion for up-to-date dashboards.
* Use built-in geospatial functions for processing GeoJSON data.
* Use clustering to optimize query performance for specified fields.
* Use columnar storage to efficiently query large datasets with many rows.
* Use data catalog to tag large datasets to improve data searchability.
* Use DDL to create partitioned tables for efficient management of large datasets.
* Use different datasets to segregate data.
* Use federated queries to access real-time data from Cloud SQL without data movement.
* Use Flex Slots to manage and scale for temporary increased demand cost-effectively.
* Use FORMAT function to ensure consistent data formatting.
* Use functions like HASH() to verify data integrity across different datasets.
* Use IAM roles to manage and control dataset access effectively.
* Use ingestion time partitioning to automatically organize data based on the time it was ingested.
* Use ingestion timestamps for maintaining append-only historical records.
* Use materialized views to improve query efficiency by storing precomputed results.
* Use materialized views to improve query performance by caching precomputed results.
* Use materialized views to pre-compute and store query results for faster access.
* Use MERGE statement to replace UPDATE statement when having millions of rows to update into a BigQuery table.
* Use ML.PREDICT to generate predictions from trained machine learning models.
* Use nested and repeated fields to optimize query performance by reducing the need for joins.
* Use nested and repeated fields to optimize query performance for hierarchical data models.
* Use nested and repeated fields to reduce the number of joins in analytical queries.
* Use ODBC and JDBC connections to query data from BigQuery.
* Use on-demand billing to optimize costs for ad-hoc analytical queries.
* Use partitioned tables to efficiently manage and query data based on time-periods.
* Use partitioned tables to filter data by date efficiently.
* Use partitioned tables to minimize query costs for specific date ranges.
* Use partitioning and clustering together to enhance query efficiency and minimize read costs.
* Use partitioning by datetime to efficiently manage and query time-based data.
* Use partitioning on timestamp columns to reduce the data scanned for time-based queries.
* Use partitioning to optimize query performance and reduce scan size.
* Use partitioning to significantly reduce query scan time.
* Use policy tags for column-level access control to manage sensitive data visibility.
* Use quotas and reservations to enforce budget constraints.
* Use REGEXP_REPLACE to normalize phone number formats.
* Use ROW_NUMBER with PARTITION to eliminate duplicates based on unique ID and timestamp during query.
* Use scheduled queries to create backup copies of data for disaster recovery.
* Use service accounts to securely integrate applications without exposing dataset access to end-users.
* Use SQL queries to clean data by handling null values.
* Use SQL syntax for efficient data transformation and processing.
* Use SQL to apply one-hot encoding for categorical variables in machine learning models.
* Use SQL to perform analytics on large datasets.
* Use staging tables to incrementally load and manipulate CDC data.
* Use standard SQL to perform complex queries on large datasets.
* Use streaming inserts to store data in near-real-time.
* Use table partitioning and clustering to optimize query performance
* Use table partitioning to optimize query performance.
* Use table partitioning to reduce query cost and latency by limiting data scanned.
* Use TABLE_DATE_RANGE function to query multiple tables efficiently in legacy SQL.
* Use the BigQuery Hadoop connector for seamless integration between Hadoop and BigQuery to access data for processing.
* Use the streaming API for real-time data ingestion into BigQuery tables.
* Use TRANSFORM clause for consistent preprocessing during model training and prediction.
* Use UNNEST operator to handle nested and repeated data structures efficiently.
* Use window functions with the OVER clause to compute values across row groups efficiently.
* Utilize administrative resource charts to monitor slot usage and job performance over time.
* Utilize ANSI SQL to access real-time and historical data for analysis.
* Utilize partitions to efficiently manage and query time-series data.
* Utilize REGEXP_CONTAINS for identifying patterns within dataset tables.
* Utilize SQL skills for large-scale data analysis with minimal administrative overhead.
* Utilize time travel to access historical data and recover from data corruption events within seven days.
* Validate data encoding to match source files during data import.
* Validate migrated schemas to ensure alignment with existing data structures when migrating from on premise data warehouse to BigQuery.
* Query data stored in Avro format on Cloud Storage.