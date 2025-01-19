# Data Processing:
* Data Processing: Understand the difference between Apache Pig, Apache Hive, Apache MapReduce, and Apache Hadoop
* ETL Pipeline: Design processes to extract, transform, and load data into data warehouse.
* ETL Process: Create and optimize ETL scripts for data migration.
* ETL: Perform efficient data extraction and loading from MySQL to BigQuery.

## Apache Beam
* Apache Beam: Call external services for data enrichment using DoFn processing and batch data to manage requests efficiently.
* Apache Beam: Create a PCollection for processing data within a Dataflow pipeline.
* Apache Beam: Create custom connectors to integrate and stream proprietary data formats.
* Apache Beam: Design streaming pipelines for message ingestion from Pub/Sub.
* Apache Beam: Develop pipelines that interact with databases using JdbcIO for data extraction.
* Apache Beam: Implement data processing logic adaptable for streaming and batch processing modes.
* Apache Beam: Implement SideInputs for joining small datasets efficiently.
* Apache Beam: Use unified batch and streaming data processing model for data pipelines.

## Apache Pig
* Deploy and run Pig scripts efficiently on Dataproc.
* Understand what is checkpointing and how to implement it using Apche Pig.
* Use PigLatin for simplified script-based data processing on Hadoop.

## Apache Spark
* Develop and execute statistical models for customer analysis.
* Implement Spark ML pipelines for retraining models using data from BigQuery.
* Improve job performance with parallel processing and in-memory computing.
* Integrate with existing Hadoop infrastructure for enhanced performance.
* Run PySpark jobs on Dataproc with optimal cluster configurations.
* Transition jobs from on-premises Hadoop cluster to Google Cloud.
* Utilize Avro libraries to process data from Cloud Storage.
* MapReduce: Implement data processing logic in Java or Python to run on Hadoop clusters.

## Cloud Batch

* Automatically provision resources for batch processing workloads.
* Run long-running batch jobs without managing infrastructure.

## Cloud Dataflow
* Analyse pipeline output with a fixed dataset to troubleshoot message processing.
* Build batch pipelines to process and validate CSV data from Cloud Storage and Store the result in BigQuery.
* Implement fixed windows to handle late-arriving data.
* Implement streaming pipelines using tumbling windows for fixed, non-overlapping time intervals.
* Monitor pipeline performance for resource optimization.
* Monitor pipeline performance using Cloud Monitoring alerts to detect execution delays.
* Process streaming data with low latency.
* Route malformed or corrupted data to a dead-letter table for error analysis.
* Scale the number of workers to handle increased load.
* Understand the difference between Tumbling, Hopping and Session windows
* Understand Windowing Strategies with Apache Beam.
* Upgrade instance types for better performance during peak loads.
* Allow late data handling to capture and process data arriving after the watermark.
* Analyze execution details via Dataflow console to identify bottlenecks.
* Apply Google-recommended security practice for controlling access between Dataflow workers by using network tags and associated firewall rules.
* Apply transformations to streaming data before storage.
* Apply triggering strategies to handle data emitting at specific points in time.
* Configure autoscaling by setting the maximum number of workers to manage dynamic workloads.
* Configure instances to only use internal IP addresses for compliance with security constraints.
* Configure triggers to handle late-arriving data effectively.
* Configure worker region to ensure high availability and mitigate zonal failures.
* Create a workflow to read and process log data, identifying and correcting out-of-range values.
* Create reusable templates for standardized data processing patterns.
* Debug and resolve exceptions in DoFn worker code during pipeline execution.
* Deploy a pipeline for real-time data streaming using Apache Beam custom connectors.
* Deploy and execute data processing pipelines within a specific Google Cloud project.
* Deploy new version of a Dataflow pipeline without losing data or creating inconsistencies.
* Deploy pipeline using Shared VPC ensuring network permissions for worker VMs.
* Design pipelines to handle high throughput with efficient batch processing to minimize backpressure.
* Design pipelines to support both streaming and batch data loading.
* Design pipelines with windowing strategies for time-based data aggregation.
* Design windowed stream processing for ordered message handling within one-hour windows.
* Detect and handle anomalies in near real-time streaming data.
* Distribute data evenly across keys to avoid hotspotting and improve job performance.
* Execute cross-regional pipeline deployment to uphold RPO requirements.
* Execute ETL processes using Python in a serverless environment with minimal operational overhead.
* Handle late arriving data using windowing and triggers.
* Identify and troubleshoot data duplication issues in pipelines.
* Implement Apache Beam to process streaming data using PubSubIO and BigQueryIO.
* Implement data pipelines to preprocess and mask data efficiently with Cloud DLP.
* Implement different windowing algorithms for enhanced data processing strategies.
* Implement error handling using try-catch in DoFn to manage pipeline reliability.
* Implement exception handling in DoFn to manage errors during message processing.
* Implement hopping window to process streaming data with overlapping intervals.
* Implement hopping windows for grouping data with overlapping time intervals.
* Implement monitoring for pipeline execution status.
* Implement pipelines to transfer and process BigQuery prediction results effectively to Bigtable.
* Implement real-time data processing pipelines for streaming data.
* Implement Reshuffle transform to optimize performance by preventing fusion in streaming pipelines.
* Implement session windows for grouping data by periods of activity with specified gap durations.
* Implement side outputs in Apache Beam pipelines.
* Implement sliding time window for real-time analytics.
* Implement sliding windows to compute real-time moving averages of streaming data.
* Implement sliding windows to manage late-arriving data and calculate rolling aggregates.
* Implement stream processing to handle late data and compute averages.
* Implement stream processing to identify and cleanse longtail and outlier data points.
* Implement timestamp tracking to process out-of-order event data.
* Implement windowing functions to organize data streaming into time intervals correctly.
* Leverage Google-provided templates to read from Pub/Sub and write to BigQuery.
* Monitor logs to identify performance issues such as hot keys.
* Optimize pipeline to handle high throughput and reduce data freshness delays.
* Perform real-time data aggregation to capture supply-demand trends.
* Process and analyze real-time streaming data with autoscaling capabilities.
* Process and sanitize streaming data before ingestion into BigQuery.
* Process and transform IoT messages from Cloud Pub/Sub in real-time.
* Process and transform real-time data with Apache Beam model.
* Process and transform streaming data from Cloud Pub/Sub for real-time analysis.
* Process bid events using pull subscription to determine first bid for each item.
* Process real-time data and save the processed data into Bigtable for real-time result visualization and to BigQuery for post analysis.
* Process streaming data for real-time analytics and integration between Cloud Storage and BigQuery through Pub/Sub.
* Process streaming data with minimal latency.
* Scale pipeline by increasing maxNumWorkers for handling more data efficiently.
* Scale processing pipelines to handle large volumes of data efficiently.
* Scale the number of workers to improve pipeline processing speed and reduce message latency.
* Schedule batch processing jobs from App Engine.
* Set maxNumWorkers to limit the scale of processing resources in pipeline execution.
* Stream and aggregate data efficiently for real-time processing.
* Stream sensor data continuously for real-time ingestion.
* Take a snapshot of a streaming pipeline for state preservation and seamless pipeline updates.
* Transform and compress text files to Avro format for efficient loading into BigQuery.
* Transform and load data into GCP using a fully managed service for batch and stream processing.
* Transform and load Kafka data into Cloud Storage.
* Transform JSON event payloads to Avro format.
* Troubleshoot network tags and firewall rule issues.
* Understand how Dataflow workers communicate with each other with the TCP.
* Understand how to stop Dataflow pipeline without losing data using Snapshot or drain flag.
* Understand the difference between fixed-time window, sliding time window, session windows, global window and their corresponding use cases
* Understand the difference between Global and Non-global windowing functions.
* Understand the difference between Session, Hopping, and Tumbling windows in Dataflow pipelines and their corresponding use cases.
* Understand the difference between SideInput and SideOuput.
* Understand the difference between System Lag and and Data Freshness.
* Understand the differences between all the possible causes of failed Apache Beam pipelines like Graph or Pipeline construction errors, Errors in Job Validation, Exception in Worker Code, and how to detect them.
* Understand the importance of timestamps in Beam pipelines and assign timestamp to streaming data to ensure proper windowing and processing.
* Understand what are triggers and their utilities in Dataflow and Apache Beam pipelines.
* Understand what is backpressure on HTTP services and how to avoid or minimize it.
* Understand what is GroupByKey and Partition  transforms and their roles in Dataflow and Apache Beam pipelines.
* Understand when and how to use Google-provided Dataflow templates.
* Use autoscaling to adjust worker instances based on input data volume.
* Use BigQueryIO to efficiently read only necessary fields in Dataflow pipelines using the .fromQuery operator.
* Use CoGroupByKey for efficient joining of large datasets.
* Use Kafka IO to ingest data from an Apache Kafka stream.
* Use ParDo transform to filter out corrupt data from the streaming pipeline.
* Use Reshuffle to prevent step fusion and better distribute workload across workers.
* Use side inputs in Apache Beam to incorporate static reference data into a streaming pipeline.
* Use side outputs to capture and separate erroneous data during pipeline processing.
* Use sideOutput to reprocess and store erroneous data separately in a Pub/Sub topic.
* Use snapshots to save and restore the state of streaming pipelines for disaster recovery.
* Use the drain option to gracefully shut down pipelines without data loss.
* Use the Drain option to gracefully stop the pipeline processing current data without loss.
* Use the monitoring interface to identify and troubleshoot pipeline errors.
* Use tumbling windows for aggregating events over disjoint time intervals.
* Use watermarks to manage late-arriving data in streaming pipelines.
* Use watermarks to track event time progress and handle late-arriving data in streaming pipelines.
* Write error records to a dead-letter queue for debugging.

## Cloud Dataprep
* Create and schedule recurring data transformation jobs using existing recipes.
* Design transformations using a graphical interface accessible for non-developer analysts.
* Explore and assess data quality to prepare it for further machine learning tasks.
* Export datasets in CSV or JSON format for compatibility.
* Identify and transform null values in sample source data for preprocessing.
* Profile datasets to understand data distribution and identify missing or misconfigured data.
* Schedule execution of transformation recipes to automate data processing tasks.
* Use a low-code interface to cleanse and explore data within Cloud Storage.
* Use GZIP compression to reduce file size for exports.
* Use recipes to perform data cleansing and transformation without programming.
* Automate data wrangling tasks for consistent reproducibility.
* Perform visual data cleaning and transformation without programming.

## Cloud Dataproc 
* Employ ephemeral clusters to efficiently execute small, high-priority jobs with isolation.
* Manage cluster lifecycles by provisioning and deallocating clusters as needed.
* Process large datasets using distributed nodes with intermediate storage in Cloud Storage.
* Run PySpark batch jobs without managing clusters
* Configure clusters for resiliency and rapid redeployment in different regions.
* Configure clusters for running Hive with performance optimization using HDFS.
* Configure ephemeral clusters for each job to optimize resource utilization and cost.
* Deploy cost-effective clusters using preemptible workers for batch processing.
* Deploy HBase within a managed Hadoop cluster for scalable processing.
* Enable autoscaling for single-job clusters to optimize resources and manage scaling effectively.
* Enhance Spark job performance in Dataproc by switching from HDDs to SSDs for fast data access.
* Execute Apache Spark jobs using a managed Hadoop cluster.
* Execute large-scale data processing and transformations efficiently.
* Execute Spark jobs on BigQuery Data in a serverless environment to minimize infrastructure management.
* Execute Spark Scala jobs using a service account with appropriate permissions.
* Handle Hadoop workloads efficiently on GCP infrastructure.
* Integrate with Cloud Storage for processing data efficiently.
* Migrate and manage Hadoop clusters with less overhead.
* Migrate and run existing Spark ML models on a managed Hadoop and Spark service in Google Cloud.
* Migrate Apache Hadoop jobs with minimal cluster management overhead.
* Migrate Apache Spark jobs to a managed service minimizing code changes.
* Migrate Hadoop clusters to Google Cloud with minimal changes.
* Migrate on-premise Spark and Hive jobs to reduce infrastructure management.
* Migrate scripts by switching references from HDFS to Cloud Storage.
* Optimize costs using pre-emptible VMs for ephemeral workloads.
* Optimize performance by configuring persistent disk for disk I/O intensive Hadoop jobs.
* Process data in Cloud Storage directly for batch analysis.
* Schedule regular execution of data processing jobs.
* Understand how master and worker nodes work in a dataproc cluster, it's not possible to change the number of master nodes.
* Understand when to use dataproc autoscaling on Google Cloud
* Use Apache Hive on a Dataproc cluster to process ORC files.
* Use Dataproc to run Spark jobs in a managed Hadoop ecosystem.
* Use graceful decommissioning to preserve work in progress when scaling with preemptible nodes.
* Use Hadoop ecosystem for processing Kafka data.
* Use initialization actions to configure cluster nodes and install cluster dependencies or requirements at startup.
* Use monitoring to detect cluster performance issues.
* Use persistent disk to ensure data persists across cluster restarts.
* Use preemptible workers to reduce cost while balancing workload performance with non-preemptible workers.
* Utilize Hadoop ecosystem tools to process and transform data efficiently.
* Utilize HDFS local storage in Dataproc for temporary data processing to decrease read/write latency.

## Connected Sheets
* Analyze BigQuery data directly in Google Spreadsheets.
* Visualize BigQuery data directly in Google Sheets without complex data export.

## Cloud Dataform
* Manage SQL-based data transformation pipelines with version control and scheduling capabilities.
* Use assertions to perform data quality checks like uniqueness and null value checks in pipelines.