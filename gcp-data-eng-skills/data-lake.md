# Data Lake & Lakehousing

## Apache Hive
* Apache Hive: Use HiveQL for SQL-like query operations on data stored in Hadoop.
* Apache Hive: Utilize external tables for ORC data and replicate to native tables for higher performance in Dataproc.

## BigQuery Omni
* BigQuery Omni: Query AWS S3 data directly from BigQuery without moving data across clouds.
* BigQuery Omni: Query data across AWS and Azure without data movement.

## BigLake
* BigLake: Create a unified table view for Cloud Storage data.
* BigLake: Create tables over Cloud Storage and S3 for seamless querying in BigQuery.
* BigLake: Integrate and analyze files stored in multiple cloud providers.
* BigLake: Provide unified data access for BigQuery and Spark without moving data.
* BigLake: Upgrade external Hive tables to BigLake to improve query performance with metadata caching.

## Apache Hadoop
* Apache Hadoop: Access data stored in Avro format on Cloud Storage.
* Apache Hadoop: Chain MapReduce jobs to ensure sequential data processing steps.
* Apache Hadoop: Configure jobs to store intermediate data on native HDFS for improved performance.
* Apache Hadoop: Evaluate and optimize computational steps to reduce processing time.
* Apache Hadoop: Execute MapReduce jobs in a managed cluster environment.
* Apache Hadoop: Identify limitations when managing increased data volumes.
* Apache Hadoop: Migrate ELT workloads to a more scalable, managed solution.
* Apache Hadoop: Migrate Hadoop jobs to leverage cloud infrastructure for data processing.
* Apache Hadoop: Modify MapReduce jobs to include new processing steps efficiently.
* Apache Hadoop: Transition away from maintaining long-lived clusters by using managed services.
* HDFS: Transfer and manage ORC data locally to leverage distributed storage benefits.

## Cloud Storage
* Cloud Storage: Access data securely from Dataflow pipelines that runs on VMs using internal IP addresses.
* Cloud Storage: Apply a locked retention policy to make data immutable.
* Cloud Storage: Apply and lock retention policies to prevent data modification or deletion.
* Cloud Storage: Apply the principle of least privileges when assigning roles to users according to their needs
* Cloud Storage: Assign sufficient roles to allow write permissions.
* Cloud Storage: Avoid sequential naming to prevent write hotspot issues.
* Cloud Storage: Configure bucket permissions to allow read-only object access.
* Cloud Storage: Configure Customer-Managed Encryption Keys for enhanced data security.
* Cloud Storage: Configure lifecycle policies for cost-effective data retention.
* Cloud Storage: Configure object-level access using ACLs for granular control.
* Cloud Storage: Configure service account permissions to read files securely.
* Cloud Storage: Design cost-effective storage strategies using storage class management.
* Cloud Storage: Design dual-region buckets to ensure high availability and resilience against regional failures.
* Cloud Storage: Design scalable and cost-effective storage solutions for large datasets in a data lake.
* Cloud Storage: Efficiently handle transfer and storage of large batch files using TAR.
* Cloud Storage: Enable Autoclass to automatically manage storage class transitions for cost optimization.
* Cloud Storage: Enable object retention to store files immutably for required duration.
* Cloud Storage: Enable turbo replication to minimize Recovery Point Objective (RPO) by ensuring rapid data replication.
* Cloud Storage: Evaluate access frequency to select appropriate storage class for cost efficiency.
* Cloud Storage: Evaluate and manage access permissions to ensure data integrity and security.
* Cloud Storage: Export BigQuery data and store backups with compression for cost-effective storage.
* Cloud Storage: Export multi-region BigQuery data to dual/multi-region buckets for cross-regional backup.
* Cloud Storage: Handle schema evolution by storing data in its original format.
* Cloud Storage: Implement data archiving with encryption using CSEK for enhanced security.
* Cloud Storage: Implement data retention policies for compliance and auditing requirements.
* Cloud Storage: Implement encryption and manage access through IAM for compliance with data protection standards.
* Cloud Storage: Implement IAM policies for secure and controlled access to data in the data lake.
* Cloud Storage: Implement Object Lifecycle Management policies for automated data transition between storage classes.
* Cloud Storage: Manage access permissions for different user groups effectively.
* Cloud Storage: Manage access to restricted data using IAM roles.
* Cloud Storage: Manage data curation through landing and transforming stages.
* Cloud Storage: Migrate data from Persistent Disk to Cloud Storage to reduce storage costs.
* Cloud Storage: Migrate HDFS to Cloud Storage for scalable data access.
* Cloud Storage: Optimize network configuration for faster data transfer throughput from on premise data center to Google Cloud.
* Cloud Storage: Optimize storage costs for archival data by choosing the appropriate storage class.
* Cloud Storage: Re-encrypt data by copying it to a new bucket.
* Cloud Storage: Replace on-premises HDFS with Cloud Storage for data storage.
* Cloud Storage: Securely store and manage diverse file types for data exploration and processing.
* Cloud Storage: Securely store audit logs with controlled access permissions.
* Cloud Storage: Securely store sensitive data in transit with access controls and encryption.
* Cloud Storage: Select bucket location and processing strategy to prevent data loss in cas of a regional outage with an RPO of 15 minutes.
* Cloud Storage: Set event-driven processing with Cloud Function and Cloud Pub/Sub based on file uploads.
* Cloud Storage: Set retention period to meet compliance requirements.
* Cloud Storage: Set up event notifications for file uploads to invoke downstream services.
* Cloud Storage: Set up log export to meet audit retention requirements.
* Cloud Storage: Share access across projects using IAM roles for different user groups.
* Cloud Storage: Store and access Apache Hive partitioned data efficiently.
* Cloud Storage: Store and access data as part of the Apache Spark job migration.
* Cloud Storage: Store and access large datasets with flexible cost-management using bucket-level configurations.
* Cloud Storage: Store and expose datasets as files for batch analysis.
* Cloud Storage: Store and manage batch historical data exports efficiently.
* Cloud Storage: Store and manage images for processing by Cloud Vision API.
* Cloud Storage: Store and manage large CSV datasets for processing in BigQuery.
* Cloud Storage: Store and manage preprocessed and temporary data for workflows.
* Cloud Storage: Store and manage raw data accessible by BigQuery for analysis.
* Cloud Storage: Store and manage unprocessed raw data efficiently.
* Cloud Storage: Store Avro files in Cloud Storage for common workload between with Hadoop/Spark jobs and BigQuery.
* Cloud Storage: Store backups using Nearline or Coldline for cost-effective long-term archiving.
* Cloud Storage: Store both original and processed log data for compliance and future reference.
* Cloud Storage: Store dependencies securely within your VPC for isolated access.
* Cloud Storage: Store Hadoop cluster data for fault tolerance and cost-effectiveness.
* Cloud Storage: Store incoming JSON data efficiently for processing.
* Cloud Storage: Store ingested data as Avro files for cost-effective, long-term storage.
* Cloud Storage: Store large CSV files for scalable and durable data access.
* Cloud Storage: Store large datasets in an cost effective and scalable manner.
* Cloud Storage: Store large datasets in Avro format for efficient querying through external tables in BigQuery.
* Cloud Storage: Store large unstructured files in a scalable and cost-effective manner.
* Cloud Storage: Store large volumes of data as part of a data lake solution.
* Cloud Storage: Store large volumes of data reliably and securely for analysis.
* Cloud Storage: Store ORC files for cost-effective, durable data storage.
* Cloud Storage: Store processed data reliably for long-term access.
* Cloud Storage: Store RDB backup files for Redis data migration.
* Cloud Storage: Store unstructured and structured data for a versatile data lake.
* Cloud Storage: Track used storage bytes using Cloud Storage metrics like instance/storage/used_bytes to ensure successful data sinking.
* Cloud Storage: Transfer small to medium size datasets from on-premises systems to Google Cloud Storage efficiently using gsutil or gcloud storage commands.
* Cloud Storage: Trigger Cloud Functions upon file upload for automated processing.
* Cloud Storage: Understand Retention Policies and their use cases
* Cloud Storage: Understand the difference between Cloud Storage's storage classes and when to use each of them.
* Cloud Storage: Understand the difference between Multi-regional buckets, dual-region bucket, dual-regional buckets with turbo replication.
* Cloud Storage: Understand the differences between gsutil and gcloud storage commands.
* Cloud Storage: Understand what is RPO and configure a RPO of less than 15min.
* Cloud Storage: Use archive storage class to minimize storage costs for infrequent access.
* Cloud Storage: Use Autoclass feature to optimize storage costs based on dynamic access patterns without retrieval charges.
* Cloud Storage: Use Cloud Pub/Sub notifications to efficiently feed data into streaming pipelines.
* Cloud Storage: Use Cloud Storage as a cost-effective alternative to HDFS.
* Cloud Storage: Use Cloud Storage connector for accessing ORC files directly from Hadoop.
* Cloud Storage: Use Cloud Storage connector to communicate with Dataproc cluster.
* Cloud Storage: Use Cloud storage to store batch ingested data with varying structures and schema-less format.
* Cloud Storage: Use Coldline storage for long-term data retention with minimal access requirements.
* Cloud Storage: Use default CMEK to enforce encryption on all future writes.
* Cloud Storage: Use dual-region buckets with turbo replication for high availability.
* Cloud Storage: Use dual-region buckets with turbo replication to provide faster redundancy across regions.
* Cloud Storage: Use event triggers to initiate Cloud Functions when file are uploaded into a Cloud Storage bucket.
* Cloud Storage: Use for flexible and scalable data storage accessible by multiple Dataproc worker nodes.
* Cloud Storage: Use gsutil cp command to upload encrypted files securely.
* Cloud Storage: Use gsutil for parallel file transfers to increase the upload speed to Cloud Storage.
* Cloud Storage: Use gsutil rsync to synchronize files between local systems and Cloud Storage.
* Cloud Storage: Use lifecycle management to transition storage classes without interfering with retention policies.
* Cloud Storage: Use lifecycle policies for automated file management.
* Cloud Storage: Use multi-region or dual-region buckets for high availability and disaster recovery.
* Cloud Storage: Use multi-regional buckets for high availability of stored data.
* Cloud Storage: Use multi-regional buckets to ensure global availability for large teams.
* gsutil: Transfer Redis Database (RDB) files to Cloud Storage for data migration.
