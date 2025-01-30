# Data Engineering Concepts

This page provides an overview of key concepts in data engineering, including data processing, storage, modeling, and architecture. Understanding these concepts is essential for building scalable and reliable data systems.

## Fundamental Concepts

### Distributed Systems

- [CAP Theorem](https://wiki.databurst.tech/docs/roadmap/distributed-systems-concepts/cap/)
  - Consistency
  - Availability
  - Partition Tolerance
- [ACID Properties](https://wiki.databurst.tech/docs/roadmap/distributed-systems-concepts/acid/)
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- BASE Properties
  - Basically Available
  - Soft State
  - Eventually Consistent
- Consistency Models
  - Strong Consistency
  - Eventual Consistency
  - Causal Consistency
  - Sequential Consistency

### Data Processing Patterns

- [Batch Processing](https://wiki.databurst.tech/docs/roadmap/data-processing/#batch)
- [Stream Processing](https://wiki.databurst.tech/docs/roadmap/data-processing/#stream)
- [Lambda Architecture](https://wiki.databurst.tech/docs/roadmap/data-architecture/lambda/)
- [Kappa Architecture](https://wiki.databurst.tech/docs/roadmap/data-architecture/kappa/)
- [Change Data Capture (CDC)](https://wiki.databurst.tech/docs/roadmap/data-integration/cdc/)
- ETL Basics
- [ELT (Extract, Load, Transform)](https://wiki.databurst.tech/docs/roadmap/data-integration/etl/)
- [ELTL (Extract, Load, Transform, Load)](https://wiki.databurst.tech/docs/roadmap/data-integration/elt/)

## Data Storage & Management

### Database Concepts

- Database Models
  - [Relational](https://wiki.databurst.tech/docs/roadmap/databases/relational/)
  - [Document](https://wiki.databurst.tech/docs/roadmap/databases/nosql/document-based/)
  - [Key-Value](https://wiki.databurst.tech/docs/roadmap/databases/nosql/key-value/)
  - Wide-Column
  - [Graph](https://wiki.databurst.tech/docs/roadmap/databases/nosql/graph/)
  - [Time-Series](https://wiki.databurst.tech/docs/roadmap/databases/nosql/time-series/)
  - [Vector](https://wiki.databurst.tech/docs/roadmap/databases/nosql/vector/)
- [Indexing Strategies](https://wiki.databurst.tech/docs/roadmap/data-storage/indexing/)
  - B-Tree
  - Hash Index
  - Bitmap Index
  - Inverted Index
- [Partitioning Strategies](https://wiki.databurst.tech/docs/roadmap/data-storage/partitioning/)
  - Horizontal (Sharding)
  - Vertical
  - Directory-Based
  - Hash-Based
  - Range-Based
- [Replication Models](https://wiki.databurst.tech/docs/roadmap/data-storage/replication/)
  - Master-Slave
  - Multi-Master
  - Quorum-Based

### [Data Modeling](https://wiki.databurst.tech/docs/roadmap/data-modeling/dimensional/)

- [Normalization Guide](https://wiki.databurst.tech/docs/roadmap/data-modeling/normalization/)
  - 1NF
  - 2NF
  - 3NF
  - BCNF
  - 4NF
  - 5NF
- Dimensional Modeling
  - [Star Schema](https://wiki.databurst.tech/docs/roadmap/data-modeling/star-schema/)
  - [Snowflake Schema](https://wiki.databurst.tech/docs/roadmap/data-modeling/snowflake/)
  - Galaxy Schema
- [Data Vault Modeling](https://wiki.databurst.tech/docs/roadmap/data-modeling/data-vault/)
  - Hubs
  - Links
  - Satellites
- [SCD Types](https://wiki.databurst.tech/docs/roadmap/data-modeling/scd-types/)
  - Type 1
  - Type 2
  - Type 3
  - Type 4
  - Type 6

## Data Architecture

### Modern Data Stack

- [Data Lake Fundamentals](https://wiki.databurst.tech/docs/roadmap/data-management-architecture/data-lake/)
  - Bronze/Raw Layer
  - Silver/Cleaned Layer
  - Gold/Business Layer
- Data Warehouse Basics
  - Staging Area
  - Data Warehouse Core
  - [Data Marts](https://wiki.databurst.tech/docs/roadmap/data-management-architecture/data-mart/)
- [Data Lakehouse](https://wiki.databurst.tech/docs/roadmap/data-management-architecture/data-lakehouse/)
- [Data Mesh Principles](https://wiki.databurst.tech/docs/roadmap/data-management-architecture/data-mesh/)
  - Domain-Oriented
  - Data as a Product
  - Self-Serve Infrastructure
  - Federated Governance
- Data Fabric

### Data Formats & Serialization

- [File Format Comparison](https://wiki.databurst.tech/docs/roadmap/file-formats-and-serialization/)
  - Row-Based
    - [CSV](https://wiki.databurst.tech/docs/roadmap/file-formats-and-serialization/file-formats/csv/)
    - [JSON](https://wiki.databurst.tech/docs/roadmap/file-formats-and-serialization/file-formats/json/)
    - [Avro](https://wiki.databurst.tech/docs/roadmap/file-formats-and-serialization/serialization/avro/)
  - Column-Based
    - Parquet
    - ORC
  - Delta Formats
    - Delta Lake
    - Iceberg

## Data Quality & Governance

### [Data Quality](https://wiki.databurst.tech/docs/roadmap/file-formats-and-serialization/serialization/avro/)

- Data Quality Framework
  - Accuracy
  - Completeness
  - Consistency
  - Timeliness
  - Validity
  - Uniqueness
- Data Profiling
- Data Cleansing
- Data Validation

### [Data Governance](https://wiki.databurst.tech/docs/roadmap/data-governance/)

- [Data Security Essentials](https://wiki.databurst.tech/docs/roadmap/data-governance/)
  - Authentication
  - Authorization
  - Encryption
  - Data Masking
- Metadata Management
- [Data Lineage](https://wiki.databurst.tech/docs/roadmap/data-governance/)
- Data Catalog

## Data Integration

### Data Collection Methods

- [Real-time Collection](https://wiki.databurst.tech/docs/roadmap/data-governance/)
  - API Integration
  - Event Streaming
- [Batch Collection](https://wiki.databurst.tech/docs/roadmap/data-governance/)
  - File Transfer
  - Database Dumps

## Performance & Optimization

### Query Optimization

- Query Optimization Guide
  - Query Planning
  - Index Optimization
  - Materialized Views

## Observability

### Monitoring

- [System Metrics](https://wiki.databurst.tech/docs/roadmap/observability/monitoring/)
- Application Metrics
- [SLO Fundamentals](https://wiki.databurst.tech/docs/roadmap/sql-fundamentals/basic-sql/)

---

🔗 **Contribute Documentation**  
Help us expand the wiki! Missing a concept? [Submit documentation request](https://github.com/data-burst/data-engineering-wiki)