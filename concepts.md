# Data Engineering Concepts

This page provides an overview of key concepts in data engineering, including data processing, storage, modeling, and architecture. Understanding these concepts is essential for building scalable and reliable data systems.

## Fundamental Concepts

### Distributed Systems

- [CAP Theorem](https://wiki.databurst.tech/docs/roadmap/distributed-systems-concepts/cap/)
  - Consistency
  - Availability
  - Partition Tolerance
- ACID Properties
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

- Batch Processing
- Stream Processing
- Lambda Architecture
- Kappa Architecture
- Event-Driven Architecture
- Change Data Capture (CDC)
- Extract, Transform, Load (ETL)
- Extract, Load, Transform (ELT)
- Extract, Load, Transform, Load (ELTL)

## Data Storage & Management

### Database Concepts

- Database Models
  - Relational
  - Document
  - Key-Value
  - Wide-Column
  - Graph
  - Time-Series
  - Vector
- Indexing
  - B-Tree
  - Hash Index
  - Bitmap Index
  - Inverted Index
- Partitioning Strategies
  - Horizontal (Sharding)
  - Vertical
  - Directory-Based
  - Hash-Based
  - Range-Based
- Replication
  - Master-Slave
  - Multi-Master
  - Quorum-Based

### Data Modeling

- Normalization Forms
  - 1NF
  - 2NF
  - 3NF
  - BCNF
  - 4NF
  - 5NF
- Dimensional Modeling
  - Star Schema
  - Snowflake Schema
  - Galaxy Schema
- Data Vault Modeling
  - Hubs
  - Links
  - Satellites
- Slowly Changing Dimensions (SCD)
  - Type 1
  - Type 2
  - Type 3
  - Type 4
  - Type 6

## Data Architecture

### Modern Data Stack

- Data Lake
  - Bronze/Raw Layer
  - Silver/Cleaned Layer
  - Gold/Business Layer
- Data Warehouse
  - Staging Area
  - Data Warehouse Core
  - Data Marts
- Data Lakehouse
- Data Mesh
  - Domain-Oriented
  - Data as a Product
  - Self-Serve Infrastructure
  - Federated Governance
- Data Fabric

### Data Formats & Serialization

- Row-Based
  - CSV
  - JSON
  - XML
  - Avro
  - Protobuf
- Column-Based
  - Parquet
  - ORC
  - Arrow
- Delta Format
  - Delta Lake
  - Iceberg
  - Hudi

## Data Quality & Governance

### Data Quality

- Data Quality Dimensions
  - Accuracy
  - Completeness
  - Consistency
  - Timeliness
  - Validity
  - Uniqueness
- Data Profiling
- Data Cleansing
- Data Validation

### Data Governance

- Metadata Management
- Data Lineage
- Data Catalog
- Master Data Management
- Data Security
  - Authentication
  - Authorization
  - Encryption
    - At Rest
    - In Transit
    - In Use
  - Data Masking
  - Access Control
    - RBAC
    - ABAC
  - Auditing

## Data Integration

### Data Collection Methods

- Real-time Collection
  - API Integration
  - Change Data Capture
  - Event Streaming
- Batch Collection
  - File Transfer
  - Database Dumps
  - ETL Jobs
- Hybrid Collection
  - Micro-batch
  - Lambda Architecture

### Data Access Patterns

- Request/Response
- Publish/Subscribe
- Event Sourcing
- CQRS
- Materialized Views
- Caching Strategies
  - Read-Through
  - Write-Through
  - Write-Behind
  - Cache-Aside

## Performance & Optimization

### Query Optimization

- Query Planning
- Index Optimization
- Materialized Views
- Query Caching
- Partitioning Strategies

### Performance Patterns

- Write-Ahead Logging
- Read Replicas
- Connection Pooling
- Bulk Operations
- Data Compression
- Query Optimization
- Caching Strategies

## Observability

### Monitoring

- System Metrics
- Application Metrics
- Business Metrics
- SLIs/SLOs/SLAs

### Logging

- Structured Logging
- Log Levels
- Log Aggregation
- Log Analysis

### Tracing

- Distributed Tracing
- Trace Sampling
- Trace Context
- Span Management
