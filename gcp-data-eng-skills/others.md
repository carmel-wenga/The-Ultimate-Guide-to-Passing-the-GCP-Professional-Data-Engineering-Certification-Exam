# Data Sharing & Transfer
## BigQuery Data Transfer Service
* Schedule and automate data transfers into BigQuery from external sources.

## Analytics Hub
* Allow departments to discover and subscribe to data for shared analytics.
* Create a private data exchange to securely publish and share datasets within the organization.
* Facilitate low-cost, current data sharing with third parties.
* Implement access controls to manage data sharing with partners securely.
* Publish datasets for centralized data sharing across teams.
* Share BigQuery datasets securely with external partners for collaborative analysis.
* Subscribe to external datasets for seamless cross-project querying.

# Data Deduplication
* Data Deduplication: Use the Hash value of the data to identify duplicate values.

# Data Migration
* Data Migration: Understand prioritization strategies when migrating data.

# Data Regulation
* Data Regulation: Understand the difference between HIPAA, GDPR, COPPA, FedRAMP regulations

# Data Storage
* Data Storage: Understand the difference between ORC, Parquet and other file format.
* Data Storage: Understand with is Optimized Row Columnar (ORC) and when to use it.

# IaC
* Terraform: Use infrastructure as code to provision Kubernetes clusters with specific hardware requirements.

# Big Data
* Big Data: Separate separate analytical and operational data to optimize cost and performance.

# Business Intelligence
## Looker
* Looker: Develop and deploy business intelligence reports to enhance decision-making and sales performance.
* Looker: Enable users to create reports and dashboards by abstracting data complexities.
* Looker: Model and abstract complex data sources for simplified analysis by analysts.

# Data Visualization
## Looker Studio
* Looker Studio: Create dashboards combining tabular and visual data insights for comprehensive reporting.
* Looker Studio: Create dynamic reports with real-time filtering and sorting.
* Looker Studio: Create dynamic visualizations with filter capabilities to adapt to different criteria.
* Looker Studio: Create shareable dashboards for data visualization and insights.
* Looker Studio: Design interactive charts to visualize key metrics effectively.
* Looker Studio: Disable caching to ensure visualizations display the most recent data.
* Looker Studio: Integrate with BigQuery to generate interactive and simplified reports for end-users.
* Looker Studio: Integrate with BigQuery to visualize data with minimal latency.
* Looker Studio: Use custom metric calculations to highlight suboptimal links.
* Looker Studio: Use data source settings to display region-specific data in reports.
* Looker Studio: Use extracted data source for faster dashboard updates by leveraging static data snapshots.
* Looker Studio: Use live data source connection for real-time data updates in reports.

# CI/CD
## Cloud Build
* Cloud Build: Automate Docker container building and deployment using customizable build pipelines.
* Cloud Build: Automate testing and deployment of Dataflow jobs triggered by code updates.
* Cloud Build: Build CI/CD pipelines to deploy Cloud Composer DAGs from staging to production Cloud Storage buckets.
* Cloud Build: Implement event-based triggers for automated CI/CD pipeline deployment on GKE.
* Cloud Build: Integrate with Cloud Source Repositories for seamless CI/CD workflow.

# Data Integration
## Cloud Data Fusion
* CDAP: Leverage open-source capabilities for creating and managing data integration solutions.
* Cloud Data Fusion: Build data pipelines using a graphical interface without managing infrastructure.
* Cloud Data Fusion: Design visual data pipelines to maintain data quality and consistency.
* Cloud Data Fusion: Implement custom transformations using SQL or Java code.
* Cloud Data Fusion: Use built-in transformations for data type conversion and data cleansing.
* Cloud Data Fusion: Use GUI to visually connect, transform, and move data across Google Cloud and external Services.

## Cloud Datastream
* Cloud Datastream: Capture and record each data change in the source system for real-time integration.
* Cloud Datastream: Implement continuous data replication from databases like MySQL, Mongo DB, PostgreSQL, Oracle to BigQuery.
* Cloud Datastream: Replicate data securely from on-premises databases to BigQuery.
* Cloud Datastream: Set up continuous data replication from Cloud SQL to BigQuery for efficient querying.
* Cloud Datastream: Use private connectivity configuration to communicate with VPC.

# Infrastructure & Compute

## General Concept
* Infrastructure & Compute: Understand the difference between CPU, GPU and TPU

## App Engine
* App Engine: Configure the app.yaml file to specify runtime environments for containerized applications.
* App Engine: Implement exponential backoff strategy to handle database query retries during outages.
* App Engine: Use App Engine Cron Service to schedule Cloud Dataflow job to run at a specific daily time.

## Cloud GPU
* Cloud GPU: Implement GPU kernel support for custom TensorFlow ops to accelerate matrix multiplications.
* Cloud GPU: Leverage parallel processing capabilities for high-precision arithmetic in machine learning tasks.
* Cloud GPU: Offload parallelizable math operations to reduce training time efficiently.

## Cloud TPU
* Cloud TPU: Accelerate TensorFlow model training using distributed computing capabilities.
* Cloud TPU: Leverage TPU for fast processing of large-scale machine learning datasets.
* Cloud TPU: Utilize TPUs for faster model training compared to CPUs for AI and ML workloads.

## Managed Instance Groups
* Managed Instance Groups: Automatically scale the number of instances based on demand.
* Managed Instance Groups: Use autohealing to automatically replace unhealthy instances based on health checks.

## Compute Engine
* Compute Engine: Configure encryption for data stored on instances using Cloud KMS-managed keys.
* Compute Engine: Deploy a Kafka cluster on VM instances for data replication.
* Compute Engine: Deploy and configure VMs running specific OS versions with necessary custom packages.
* Compute Engine: Deploy and manage MariaDB instances on GCE VM Instances.
* Compute Engine: Deploy custom applications on virtual machines for batch processing.
* Compute Engine: Monitor instance health and throughput to ensure optimal performance.
* Compute Engine: Run RStudio server for interactive statistical analysis on virtual machines.
* Compute Engine: Select appropriate VM instance types for balance of cost and performance with custom ML models.
* Compute Engine: Use GPU instances to accelerate model training with compiled Fortran libraries.
* Compute Engine: Use instance templates to define configurations for managed instance groups.
* Compute Engine: Use managed instance groups to handle scalable workloads.

## Edge TPU
* Edge TPU: Deploy machine learning models for low-latency inference on edge devices.

## Google Kubernetes Engine
* Google Kubernetes Engine: Configure autoscaling based on total CPU utilization of a deployment.
* Google Kubernetes Engine: Deploy and manage containerized applications for your workflows.
* Google Kubernetes Engine: Deploy and manage containerized microservices for scalable and efficient ETL processes.
* Google Kubernetes Engine: Deploy applications by creating and managing pods using kubectl.
* Google Kubernetes Engine: Deploy containerized applications with GPUs and local SSDs for high-performance processing.
* Google Kubernetes Engine: Deploy machine learning models as scalable services.
* Google Kubernetes Engine: Monitor CPU utilization metrics for autoscaling decisions.
* Google Kubernetes Engine: Scale deployments using kubectl to increase or decrease the number of replicas for better resource management.
* Google Kubernetes Engine: Utilize Kubernetes autoscaling for efficient resource utilization.

## Premptible VM
* Preemptible VM: Reduce computation and processing cost by using Preemptible VM.

## Shielded VM
* Shielded VMs: Utilize for enhanced security on VMs processing sensitive machine learning data.

# Networking
## Cloud Interconnect
* Cloud Interconnect: Establish a private connection between on-premises data centers and Google Cloud for data transfer.
* Cloud Interconnect: Provide high-bandwidth connectivity between on-premises and Google Cloud for faster data transfer.

## Global Load Balancer
* Global Load Balancer: Configure multi-region traffic distribution for high availability across geographical areas.

## Shared VPC
* Shared VPC: Configure Cloud Composer resources in the correct project for network accessibility.
* Shared VPC: Grant compute.networkUser role for network resource access.
* Shared VPC: Understand how and when to use Shared VPC networks and subnets.
* Shared VPC: Understand what IAM roles should be assigned to the service account dedicated to run Dataflow pipelines inside a Shared VPC network.

## VPC Network Peering
* VPC Network Peering: Enable communication between several Project's VPCs using internal IP addresses to secure data transfers.
* VPC Network Peering: Understand what is VPC Network Peering and how to use it in the context of Google Cloud.

## VPC
* VPC: Implement security perimeters to control network access for Cloud Dataproc clusters.
* VPC: Use Private Google Access to enable access to Google APIs from VMs with only internal IP addresses.
* VPC: Use Serverless Access to connect serverless functions to resources in private subnetworks securely.

## VPC Service Controls
* VPC Service Controls: Configure perimeter to allow specific teams access to specific APIs.
* VPC Service Controls: Create security perimeters to isolate project resources from unauthorized access.
* VPC Service Controls: Design perimeter to restrict service access based on team roles.

# Other
## Cloud IoT Core
* Cloud IoT Core: Collect data from edge devices and process it in real-time.
* Cloud IoT Core: Integrate with other GCP services for advanced data analysis.
* Cloud IoT Core: Manage IoT devices globally and securely connect them to GCP.

## Docker
* Docker: Deploy microservices in containers to enable independent updates and scalability.
* Docker: Isolate services with specific third-party library dependencies.
* Docker: Use Docker containers to encapsulate microservices for consistent development and deployment environments.

## Google Cloud Folders
* Google Cloud Folders: Organize resources to apply consistent policies across different regions.

## Organizations
* Organizations: Understand Google Cloud resource hierarchy between Organizations, Folders and Projects

## Resource Manager
* Resource Manager: use Organization Policy Service to configure policies and enforce regional constraints on GCP resources.

## SOAP
* SOAP: Implement service-oriented architecture using the SOAP protocol for communication.