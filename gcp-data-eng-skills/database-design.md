# Database Design

## General Concepts
* Database Design: Avoid self-joins to enhance query efficiency and resource utilization.
* Database Design: Choose the right NoSQL database type between Key-Value, Wide, and Document DB.
* Database Design: Normalize tables to improve performance and scalability by reducing redundancy.
* Database Design: Understand the difference between OLTP and OLAP data models

## Firebase
* Firebase Analytics: Enable integration to automatically export event data into BigQuery for analysis.

## PostgreSQL
* PostgreSQL: Use custom connectors to catalog Postgres databases.

## Redis
* Redis: Implement encryption for data stored in memory and at rest using Cloud KMS.

## Cloud Datastore
* Cloud Datastore: Use managed export for backup and recovery.

## Cloud Bigtable
* Cloud Bigtable: Increase cluster nodes to support more concurrent connections and reduce write latency.
* Cloud Bigtable: Store and manage sparse, time-series datasets as key-value pairs for high throughput and scalability.
* Cloud Bigtable: Store predictions for efficient retrieval and low-latency access per user request.
* Cloud Bigtable: Use row key design for optimal query performance with single-digit millisecond latency.
* Cloud Bigtable: Access data using row keys for efficient data retrieval.
* Cloud Bigtable: Assess pressure indices using Key Visualizer for performance insights.
* Cloud Bigtable: Avoid hot-spotting by incorporating high-cardinality fields into row keys.
* Cloud Bigtable: Avoid hotspotting by ensuring row keys do not cause sequential access patterns.
* Cloud Bigtable: Configure app profiles to use replicas only for failover to maintain data consistency.
* Cloud Bigtable: Configure multiple clusters to enhance read and write efficiency.
* Cloud Bigtable: Create separate tables for different data types, for optimized querying.
* Cloud Bigtable: Design effective row keys to prevent hot spotting.
* Cloud Bigtable: Design efficient row-key to evenly distribute data and avoid hotspots.
* Cloud Bigtable: Design key schema for efficient IoT data storage and retrieval.
* Cloud Bigtable: Design multitenant row keys to ensure effective segregation and retrieval of tenant data.
* Cloud Bigtable: Design narrow tables with composite row keys for efficient querying of time-series data.
* Cloud Bigtable: Design row keys to optimize read performance by distributing read and write loads evenly.
* Cloud Bigtable: Design row keys to optimize read/write performance and evenly distribute load.
* Cloud Bigtable: Design row keys to prevent hotspotting by distributing writes evenly.
* Cloud Bigtable: Design row keys using reverse timestamps for efficient retrieval of recent data.
* Cloud Bigtable: Design rowkey schema to optimize query performance for time-series data.
* Cloud Bigtable: Design tall and narrow tables for efficient data storage.
* Cloud Bigtable: Implement data locality by organizing related data in contiguous row ranges.
* Cloud Bigtable: Implement single-cluster routing to ensure strong consistency during read operations.
* Cloud Bigtable: Manage large-scale data efficiently with minimal operational overhead.
* Cloud Bigtable: Migrate HBase data to Bigtable to leverage cloud infrastructure and run Apache Hadoop jobs.
* Cloud Bigtable: Monitor write latency to determine when to scale the cluster size.
* Cloud Bigtable: Optimize for high write throughput accommodating continuous data ingestion.
* Cloud Bigtable: Optimize performance by adding clusters to separate write and batch operations.
* Cloud Bigtable: Optimize performance by avoiding hotspots in row key design.
* Cloud Bigtable: Optimize row key design to prevent hotspots in time-series data.
* Cloud Bigtable: Provide fast scans for specific time range rows with millisecond response times.
* Cloud Bigtable: Query data for low latency reads and real-time results display.
* Cloud Bigtable: Redefine schema to distribute reads/writes across row space for optimal performance.
* Cloud Bigtable: Scale horizontally to handle high-write throughput from IoT devices transmitting every second.
* Cloud Bigtable: Set garbage collection rules on the timestamp to delete data after certain period of time.
* Cloud Bigtable: Store and manage large volumes of semi-structured data with single key access efficiently.
* Cloud Bigtable: Store and quickly retrieve large-scale label data for fast filtering based on viewing history for recommendation engines.
* Cloud Bigtable: Store large volumes of key-value data for low-latency access.
* Cloud Bigtable: Store large-scale, time-series data with high write throughput and low-latency reads.
* Cloud Bigtable: Structure data as tall and narrow tables for better performance with time-series data.
* Cloud Bigtable: Troubleshoot and resolve read consistency issues in replicated environments.
* Cloud Bigtable: Understand the difference between single cluster routing and multiple cluster routing.
* Cloud Bigtable: Understand the key differences between live-traffic app profile and batch-analytics profile.
* Cloud Bigtable: Use efficient schema design allowing future growth for large datasets.
* Cloud Bigtable: Use for consistent, scalable performance supporting HBase API.
* Cloud Bigtable: Use HBase API for seamless migration from an on-premises HBase cluster.
* Cloud Bigtable: Use Key Visualizer to identify and analyze query performance issues.
* Cloud Bigtable: Use single-cluster routing for workload isolation between real-time and analytical jobs.
* Cloud Bigtable: Use timestamp range filters to restrict data retrieval to a specific timeframe.

## Cloud Firestore
* Cloud Firestore: Create composite indexes for querying across multiple fields.
* Cloud Firestore: Design a schema to support flexible types and attributes.
* Cloud Firestore: Design databases using flexible schemas for dynamic, scalable data storage.
* Cloud Firestore: Exclude properties from indexing to reduce index size and improve write performance.
* Cloud Firestore: Implement efficient updates using simple and complex entities, considering access patterns and relationships.
* Cloud Firestore: Implement transaction support for reliable data manipulation.
* Cloud Firestore: Manually configure composite indexes to optimize query performance and avoid combinatorial explosion in the number of indexes.
* Cloud Firestore: Migrate data from MongoDB to Firestore for scalable, serverless, and flexible NoSQL document storage.
* Cloud Firestore: Model hierarchical data using nested entities for flexible and scalable database design.
* Cloud Firestore: Optimize storage by using strings for atomic data fields and entities for complex data structures.
* Cloud Firestore: Understand default indexing behavior and its limitations.
* Cloud Firestore: Understand that Cloud Firestore stores data redundantly when multiple indexes are used.

## Cloud Memorystore
* Cloud Memorystore: Apply optimal eviction policy to manage cache memory effectively.
* Cloud Memorystore: Configure proper TTLs to control memory usage.
* Cloud Memorystore: Configure read replicas in to scale read capacity.
* Cloud Memorystore: Configure Redis for high availability with Standard Tier in a production environment.
* Cloud Memorystore: Deploy Redis instances in a development environment to simulate production scenarios safely.
* Cloud Memorystore: Import Redis data using native RDB snapshot to prevent vendor lock-in.
* Cloud Memorystore: Leverage high availability for Redis to ensure uptime.
* Cloud Memorystore: Perform manual failover using the limited-data-loss mode for disaster recovery testing.
* Cloud Memorystore: Store aggregated data for low-latency access in dashboards.
* Cloud Memorystore: Understand the difference between Basics and Standar Tiers Cloud Memorystore instance and when to use each of them.
* Cloud Memorystore: Understand the difference between limited-data-loss and force-data-loss data protection mode and how to use them. 
* Cloud Memorystore: Use the import export features to transfer Redis data to one instance to another.

## Cloud Spanner
* Cloud Spanner: Add secondary indexes to optimize range queries on non-key columns.
* Cloud Spanner: Calculate minimum nodes required based on data storage capacity (2 TB per node for efficient scaling).
* Cloud Spanner: Choose UUID version 4 for primary key to evenly distribute writes and reduce hotspotting.
* Cloud Spanner: Deploy a geographically distributed database for low-latency, consistent global access to data.
* Cloud Spanner: Design for horizontal scalability to handle large databases.
* Cloud Spanner: Design globally distributed databases with strong consistency and support for SQL queries.
* Cloud Spanner: Design schemas to prevent hotspotting by avoiding sequentially ordered UUIDs as primary keys - Use UUID version 4
* Cloud Spanner: Implement globally distributed OLTP applications with high availability and scalability.
* Cloud Spanner: Implement locking read-write transactions for full ACID compliance.
* Cloud Spanner: Optimize regional instance performance by maintaining CPU utilization at 65% for sustained operations.
* Cloud Spanner: Provide ANSI SQL support for global-scale transactional databases.
* Cloud Spanner: Scale from a single region to a multi-region setup for global availability.
* Cloud Spanner: Understand Google's Recommendations for the maximum sustained CPU utilization of a regional instance
* Cloud Spanner: Understand how data are distributed accross Cloud Spanner Nodes
* Cloud Spanner: Understand the difference between locking read-write transactions and state read.
* Cloud Spanner: Use hashed primary keys to prevent hotspotting and improve performance.
* Cloud Spanner: Use interleaved tables to optimize join performance for hierarchically related tables.
* Cloud Spanner: Use multi-region configuration for high availability and read scalability.
* Cloud Spanner: Use STRUCT data type for representing document-like structures with diverse data types.

## Cloud SQL
* Cloud SQL Auth Proxy: Establish secure connections without needing authorized networks or static IP addresses.
* Cloud SQL: Automatically handles provisioning, maintenance, and scaling with minimal downtime using Google Cloud's managed service.
* Cloud SQL: Configure access for external querying by BigQuery.
* Cloud SQL: Configure and manage read replicas to optimize database read performance.
* Cloud SQL: Configure automatic backups to enhance data reliability.
* Cloud SQL: Configure database access using internal IP addresses for secure communication.
* Cloud SQL: Configure high availability and set up DRP.
* Cloud SQL: Configure high availability for automated failover to minimize downtime.
* Cloud SQL: Configure high availability for automatic failover across regions to meet low RTO and RPO requirements.
* Cloud SQL: Configure high availability using failover replicas across zones in the same region.
* Cloud SQL: Configure strong user passwords and enforce SSL connections for increased security.
* Cloud SQL: Create cascading read replicas for global read scalability.
* Cloud SQL: Create read replicas for high availability and load balancing.
* Cloud SQL: Deploy managed MySQL or PostgreSQL databases to reduce administrative overhead.
* Cloud SQL: Design relational database schemas to handle structured transactional data with ACID compliance.
* Cloud SQL: Enable high availability to ensure system resiliency and automatic failover.
* Cloud SQL: Ensure SQL database connections are encrypted automatically without complex configuration.
* Cloud SQL: Handle operational workloads with managed relational database service.
* Cloud SQL: Implement auto-backup strategies to Cloud Storage to ensure data durability.
* Cloud SQL: Integrate relational database data for AutoML model training.
* Cloud SQL: Migrate existing relational databases to a managed service with minimal application refactoring.
* Cloud SQL: Migrate on-premises database using Database Migration Service for minimal downtime.
* Cloud SQL: Migrate on-premises PostgreSQL to Cloud SQL for minimal change in database management systems.
* Cloud SQL: Minimize operational load by using Datastream for offloading query workloads.
* Cloud SQL: Monitor activities and potential maintenance on read replicas to minimize downtime.
* Cloud SQL: Optimize cost by leveraging automated backups and scaling features.
* Cloud SQL: Optimize for transactional workloads while supporting analytics in a managed PostgreSQL environment.
* Cloud SQL: Promote a read replica to a primary instance for disaster recovery.
* Cloud SQL: Promote read replicas to minimize downtime during regional failover.
* Cloud SQL: Store and serve API data with low-latency and high throughput, ensuring performance under high QPS load.
* Cloud SQL: Understand network configuration around Cloud SQL like Authorized Networks, CIDR, Authorized Proxy
* Cloud SQL: Understand the difference between cascading read replica and read replica.
* Cloud SQL: Understand what is point-in-time recovery and how to use it.
* Cloud SQL: Update application connection strings to new primary instance after failover.
* Cloud SQL: Use Cloud SQL Proxy to facilitate secure connections to Cloud SQL without managing certificates.
* Cloud SQL: Use standby replicas in HA configuration to ensure continuous database availability.
* Cloud SQL: Utilize automatic backups and high availability features for increased data resilience.
