# Data Engineering Tools

This page lists important tools and software that are commonly used in the field of data engineering. These tools help data engineers to build, maintain, and optimize data pipelines, databases, and analytics systems.
You can use it as a reference to explore and learn about the tools that are widely used in the industry and to find the right tools for your data engineering projects.

## Table of Contents

- [Programming Languages](#programming-languages)
  - [Python](#python)
  - [Java](#java)
- [Operating System](#operating-system)
- [Networking](#networking)
- [Basic Authentication and Authorization](#basic-authentication-and-authorization)
- [Web Frameworks and API Development](#web-frameworks-and-api-development)
- [Cache](#cache)
- [Testing](#testing)
- [Version Control System](#version-control-system)
- [Version Control Hosting](#version-control-hosting)
- [Databases](#databases)
  - [Relational](#relational)
  - [NoSQL](#nosql)
- [Data Integration](#data-integration)
  - [ETL](#etl)
  - [ELT](#elt)
  - [Reverse ETL](#reverse-etl)
  - [CDC](#cdc)
- [Storage](#storage)
  - [Block Storage](#block-storage)
  - [Object Storage](#object-storage)
- [Query Engine](#query-engine)
- [In Memory Analytical Databases](#in-memory-analytical-databases)
- [Data Processing](#data-processing)
  - [Batch](#batch)
  - [Hybrid](#hybrid)
  - [Stream](#stream)
- [Pipeline Orchestration](#pipeline-orchestration)
- [Messaging and Streaming Platform](#messaging-and-streaming-platform)
- [Data Governance](#data-governance)
  - [Data Quality](#data-quality)
  - [Data Security](#data-security)
  - [Data Lineage](#data-lineage)
  - [Data Visualization](#data-visualization)
- [Containerization](#containerization)
- [Container Orchestration](#container-orchestration)
- [CICD](#cicd)
- [Infrastructure as Code](#infrastructure-as-code)
  - [Configuration Management](#configuration-management)
  - [Infrastructure Provisioning](#infrastructure-provisioning)
- [Observability](#observability)
  - [Logging](#logging)
  - [Monitoring](#monitoring)
  - [Tracing](#tracing)

## Programming Languages

### Python

#### Package manager

- [UV](https://github.com/astral-sh/uv) (recommended) - A fast and extensible Python version manager.
- [Poetry](https://github.com/python-poetry/poetry) - A tool for dependency management and packaging in Python.

#### Type Checker

- [Mypy](https://github.com/python/mypy) - A static type checker for Python.

#### Linter and Code Formatter

- [Ruff](https://github.com/astral-sh/ruff) - A fast and extensible Python linter and code formatter implemented in rust.
- [Black](https://github.com/psf/black) - The uncompromising Python code formatter.
- [Flake8](https://github.com/PyCQA/flake8) - A tool that enforces PEP 8 style guide.

#### Data Validation

- [Pydantic](https://github.com/pydantic/pydantic) - Data validation and settings management using Python type hints.

#### Document Generator

- [Sphinx](https://github.com/sphinx-doc/sphinx) - A tool that makes it easy to create intelligent and beautiful documentation.
- [Mkdocs](https://github.com/mkdocs/mkdocs) - A fast, simple, and downright gorgeous static site generator that's geared towards building project documentation.

#### Doc-string Generator

- [autoDocstring in VSCode](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) - A Visual Studio Code extension that generates docstrings for Python functions.

#### Test and Coverage Tools

- [Pytest](https://github.com/pytest-dev/pytest) - A testing framework that makes it easy to write simple and scalable tests.
- [tox](https://github.com/tox-dev/tox) - A generic virtualenv management and test command line tool.
- [nox](https://github.com/wntrblm/nox) - A flexible test automation tool that allows you to run tests in different environments.
- [Lettuce](https://github.com/gabrielfalcao/lettuce) - A BDD tool that allows you to write tests in plain English.

#### Version Manager

- [semantic-release](https://github.com/semantic-release/semantic-release/) - Fully automated version management and package publishing.
- [bump-my-version](https://github.com/callowayproject/bump-my-version) - A simple CLI tool to bump the version of your project.
- [bump2version](https://github.com/c4urself/bump2version) - A tool to simplify releasing software by updating all version strings in your source code by the correct increment.
- [python-semantic-release](https://github.com/python-semantic-release/python-semantic-release) - Fully automated version management and package publishing for Python projects.

#### Changelog Generator

- [git-cliff](https://github.com/orhun/git-cliff) - A highly customizable Changelog Generator that follows Conventional Commit specifications.
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) - A tool that generates a changelog from git metadata.

### Java

#### Package Manager

- [Maven](https://github.com/apache/maven) - A build automation tool used primarily for Java projects.
- [Gradle](https://github.com/gradle/gradle) - A build automation tool that is used for multi-language development.

#### Document Generator

- [Javadoc](https://www.oracle.com/java/technologies/javase/javadoc-tool.html) - A tool that generates API documentation in HTML format from doc comments in source code.

#### Test and Coverage Tools

- [JUnit](https://github.com/junit-team/junit5) - A simple framework to write repeatable tests in Java.

## Operating System

- [Linux](https://github.com/torvalds/linux) - Most popular unix-based open-source operating system that is widely used for servers and embedded systems.
  - [Ubuntu](https://ubuntu.com/) - A Debian-based Linux operating system that is widely used for personal computers, servers, and cloud computing.
  - [Debian](https://www.debian.org/) - A Unix-like operating system that is composed entirely of free software.
  - [CentOS](https://www.centos.org/) - A Linux distribution that provides a free, community-supported computing platform.
  - [Fedora](https://getfedora.org/) - A Linux distribution that is sponsored by Red Hat.
  - [Arch Linux](https://www.archlinux.org/) - A lightweight and flexible Linux distribution that targets experienced users.
- [Windows](https://www.microsoft.com/en-us/windows) - A series of operating systems developed by Microsoft.
- [macOS](https://www.apple.com/macos) - A series of unix-based operating systems developed by Apple Inc.

## Networking

- [OpenSSH](https://www.openssh.com/) - A free version of the SSH connectivity tools that technical users rely on.
- [OpenVPN](https://openvpn.net/) - An open-source software application that implements virtual private network (VPN) techniques for creating secure point-to-point or site-to-site connections in routed or bridged configurations and remote access facilities.
- [ufw](https://help.ubuntu.com/community/UFW) - A user-friendly way to create an IPv4 or IPv6 host-based firewall.
- [iptables](https://netfilter.org/) - A user-space utility program that allows a system administrator to configure the IP packet filter rules of the Linux kernel firewall, implemented as different Netfilter modules.
- [nftables](https://netfilter.org/projects/nftables/) - A subsystem of the Linux kernel providing filtering and classification of network packets/datagrams/frames.
- [Nginx](https://github.com/nginx/nginx) - A web server that can also be used as a reverse proxy, load balancer, mail proxy, and HTTP cache.
- [HAProxy](https://www.haproxy.org/) - A free, very fast, and reliable solution offering high availability, load balancing, and proxying for TCP and HTTP-based applications.

## Basic Authentication and Authorization

- [OAuth2](https://oauth.net/2/) - An authorization framework that enables a third-party application to obtain limited access to an HTTP service.
- [JWT](https://jwt.io/) - An open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
- [OAuth2 Proxy](https://oauth2-proxy.github.io/oauth2-proxy/) - A reverse proxy and static file server that provides authentication using Providers (Google, GitHub, and others) to validate accounts by email, domain, or group.
- [Keycloak](https://www.keycloak.org/) - An open-source Identity and Access Management solution aimed at modern applications and services.
- [Ory Kratos](https://www.ory.sh/kratos/docs/) - An identity and user management server that is designed to be easily integrated into existing systems.
- [Ory Keto](https://www.ory.sh/keto/docs/) - A policy decision point that is designed to be easily integrated into existing systems.

## Web Frameworks and API Development

### Python

- [FastAPI](https://github.com/fastapi/fastapi) - A modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
- [Flask](https://github.com/pallets/flask) - A lightweight WSGI web application framework.
- [Django](https://github.com/django/django) - A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- [Falcon](https://github.com/falconry/falcon) - A high-performance Python framework for building cloud APIs and web app backends.

### Go

- [Gin](https://github.com/gin-gonic/gin) - A web framework written in Go (Golang).
- [Echo](https://github.com/labstack/echo) - A high-performance, minimalist Go web framework.
- [Fiber](https://github.com/gofiber/fiber) - An Express.js inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go.

### Java

- [Spring Boot](https://github.com/spring-projects/spring-boot) - An open-source Java-based framework used to create stand-alone, production-grade Spring-based Applications.
- [Micronaut](https://github.com/micronaut-projects/micronaut-core) - A modern, JVM-based, full-stack framework for building modular, easily testable microservice and serverless applications.

### Rust

- [Actix](https://github.com/actix/actix-web) - A powerful, pragmatic, and extremely fast web framework for Rust.
- [Rocket](https://github.com/rwf2/Rocket) - A web framework for Rust.

## Cache

- [Redis](https://github.com/redis/redis) - An open-source, in-memory data structure store that can be used as a database, cache, and message broker.
- [Memcached](https://github.com/memcached/memcached) - A high-performance, distributed memory object caching system.
- [Varnish](https://github.com/varnishcache/varnish-cache) - An open-source web application accelerator that is used to cache web content.
- [Nginx](https://github.com/nginx/nginx) - A web server that can also be used as a reverse proxy, load balancer, mail proxy, and HTTP cache.
- [Squid](https://github.com/squid-cache/squid) - A caching proxy for the Web supporting HTTP, HTTPS, FTP, and more.
- [Apache Ignite](https://github.com/apache/ignite) - An open-source distributed database, caching, and processing platform designed to store and compute on large volumes of data across a cluster of nodes.
- [Hazelcast](https://github.com/hazelcast/hazelcast) - An open-source in-memory data grid that is used to distribute data across a cluster of nodes.

## Testing

### Integration Testing

- [Postman](https://www.postman.com/) - A collaboration platform for API development that allows you to design, mock, document, and test APIs.
- [Insomnia](https://github.com/Kong/insomnia) - A powerful REST API client that is used to design, debug, and test APIs.
- [Pact](https://docs.pact.io/) - A contract testing tool that is used to ensure that services can communicate with each other.

### Functional Testing

- [Selenium](https://github.com/SeleniumHQ/selenium) - A portable framework for testing web applications.
- [Cypress](https://github.com/cypress-io/cypress) - A fast, easy, and reliable testing for anything that runs in a browser.
- [Playwright](https://github.com/microsoft/playwright) - A Node.js library to automate the Chromium, WebKit, and Firefox browsers with a single API.
- [TestCafe](https://github.com/DevExpress/testcafe) - A Node.js tool to automate end-to-end web testing.
- [Karate](https://github.com/karatelabs/karate) - A unified framework for API test automation, mocks, performance testing, and even UI automation.
- [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework for acceptance testing and acceptance test-driven development (ATDD).

### Load Testing

- [Locust](https://github.com/locustio/locust) - An open-source load testing tool that is used to test the performance of web applications. Write scalable load tests in plain Python.
- [K6](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript. Tests as code and configurable load generation.
- [JMeter](https://github.com/apache/jmeter) - Load testing tool for analyzing and measuring the performance of a variety of services.
- [Gatling](https://github.com/gatling/gatling) - Modern Load Testing as Code. Officially supports HTTP, WebSocket, Server-Sent-Events, JMS, gRPC and MQTT.
- [Artillery](https://github.com/artilleryio/artillery) - Everything you need for production-grade load tests. Serverless & distributed. Load test HTTP APIs, GraphQL, WebSocket, and more.

### A/B Testing

- [GrowthBook](https://github.com/growthbook/growthbook) - Feature Flagging and A/B Testing Platform.
- [Unleash](https://github.com/Unleash/unleash) - An open-source feature toggle/flag service.
- [Flagsmith](https://github.com/Flagsmith/flagsmith) - An open-source, fully supported, Feature Flag and Remote Config service.
- [Argo Rollouts](https://github.com/argoproj/argo-rollouts) - A Kubernetes controller and set of CRDs which provide advanced deployment capabilities such as blue-green, canary, canary analysis, experimentation, and progressive delivery features to Kubernetes.

## Version Control System

- [Git](https://git-scm.com/) - A distributed version control system that is widely used for source code management.
- [Mercurial](https://www.mercurial-scm.org/) - A distributed version control system that is easy to learn.

## Version Control Hosting

- [GitHub](https://github.com) - A web-based platform for git version control and collaboration.
- [GitLab](https://gitlab.com) - A web-based platform for git and DevOps lifecycle tooling.
- [Bitbucket](https://bitbucket.org) - A web-based platform for Git and Mercurial version control.

## Databases

### Relational

- [PostgreSQL](https://github.com/postgres/postgres) - An open-source and powerful relational database management system.
- [MySQL](https://github.com/mysql/mysql-server) - One of the most famous open-source relational database management systems.
- [CockroachDB](https://github.com/cockroachdb/cockroach) - An open-source, distributed SQL database that is ACID compliant and horizontally scalable.
- [TiDB](https://github.com/pingcap/tidb) - An open-source, distributed SQL database that supports Hybrid Transactional and Analytical Processing (HTAP).
- [SQLite](https://github.com/sqlite/sqlite) - A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- [MariaDB](https://github.com/MariaDB/server) - An open-source relational database management system that is a fork of MySQL.
- [Oracle Database](https://www.oracle.com/database/) - A multi-model database management system produced and marketed by Oracle Corporation.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - A relational database management system developed by Microsoft.

### NoSQL

#### Columnar

- [Cassandra](https://github.com/apache/cassandra) - A distributed NoSQL database management system designed to handle large amounts of data across many commodity servers.
- [HBase](https://github.com/apache/hbase) - An open-source, distributed, versioned, non-relational database modeled after Google's Bigtable.
- [ClickHouse](https://github.com/ClickHouse/ClickHouse) - An open-source column-oriented database management system that allows generating analytical data reports in real-time.
- [Apache Druid](https://github.com/apache/druid) - A high-performance, column-oriented, distributed data store that is optimized for OLAP queries on event data.
- [Pinot](https://github.com/apache/pinot) - A real-time distributed OLAP datastore that is designed for high-performance and low-latency.

#### Document Based

- [MongoDB](https://github.com/mongodb/mongo) - Most famous cross-platform document-oriented database program.
- [Elasticsearch](https://github.com/elastic/elasticsearch) - A distributed, RESTful search and analytics engine that is based on Apache Lucene.
- [Couchbase](https://www.couchbase.com/) - An open-source, distributed, multi-model NoSQL document-oriented database.
- [CouchDB](https://github.com/apache/couchdb) - An open-source database that uses JSON for documents, JavaScript for MapReduce indexes, and regular HTTP for its API.
- [RethinkDB](https://github.com/rethinkdb/rethinkdb) - An open-source, distributed document-oriented database that makes it easy to build and scale real-time web applications.
- [ArangoDB](https://github.com/arangodb/arangodb) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
- [RavenDB](https://github.com/ravendb/ravendb) - A NoSQL document database that is fully transactional (ACID) across your database.

#### Key-Value

- [Redis](https://github.com/redis/redis) - An open-source, in-memory data structure store that can be used as a database, cache, and message broker.
- [KeyDB](https://github.com/Snapchat/KeyDB) - A high-performance fork of Redis with multithreading support.
- [TiKV](https://github.com/tikv/tikv) - A distributed transactional key-value database that provides transactional guarantees.
- [etcd](https://github.com/etcd-io/etcd) - A distributed key-value store that provides a reliable way to store data across a cluster of machines.
- [ArangoDB](https://github.com/arangodb/arangodb) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
- [Valkey](https://github.com/valkey-io/valkey) - A distributed key-value store that is designed for high availability and scalability, forked from Redis.
- [Dragonfly](https://github.com/dragonflydb/dragonfly) - An in-memory data store built for modern application workloads and fully compatible with Redis and Memcached APIs.

#### Time-series

- [InfluxDB](https://github.com/influxdata/influxdb) - An open-source time-series database that is optimized for fast, high-availability storage and retrieval of time series data in fields such as operations monitoring, application metrics, Internet of Things sensor data, and real-time analytics.
- [Prometheus](https://github.com/prometheus/prometheus) - An open-source monitoring and alerting toolkit based on a time-series database.
- [TimescaleDB](https://github.com/timescale/timescaledb) - An open-source time-series database that is built on top of PostgreSQL.
- [OpenTSDB](https://github.com/OpenTSDB/opentsdb) - A distributed, scalable time-series database that is built on top of HBase.
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - A fast, cost-effective, and scalable time-series database that is compatible with Prometheus.
- [QuestDB](https://github.com/questdb/questdb) - An open-source time-series database that is designed for high-performance and real-time analytics.
- [KairosDB](https://github.com/kairosdb/kairosdb) - A distributed time-series database that is built on top of Cassandra.
- [M3DB](https://github.com/m3db/m3) - A distributed time-series database that is designed for high availability and scalability.

#### Vector

- [Milvus](https://github.com/milvus-io/milvus) - A high-performance, cloud-native vector database built for scalable vector ANN search
- [Qdrant](https://github.com/qdrant/qdrant) - A vector search engine that is designed for similarity search and clustering.
- [Weaviate](https://github.com/weaviate/weaviate) - An open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database.
- [pgvector](https://github.com/pgvector/pgvector) - A PostgreSQL extension that provides vector search capabilities.

#### Graph

- [ArangoDB](https://github.com/arangodb/arangodb) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
- [Neo4j](https://github.com/neo4j/neo4j) - An open-source graph database that is optimized for storing and querying graphs.
- [JanusGraph](https://github.com/JanusGraph/janusgraph) - A highly scalable graph database optimized for storing and querying large graphs with billions of vertices and edges distributed across a multi-machine cluster.
- [OrientDB](https://github.com/orientechnologies/orientdb) - An open-source, distributed graph database that is optimized for storing and querying graphs.
- [Dgraph](https://github.com/hypermodeinc/dgraph) - A horizontally scalable and distributed GraphQL database with a graph backend which provides ACID transactions, consistent replication, and linearizable reads.

#### NewSQL

- [CockroachDB](https://github.com/cockroachdb/cockroach) - An open-source, distributed SQL database that is ACID compliant and horizontally scalable.
- [TiDB](https://github.com/pingcap/tidb) - An open-source, distributed SQL database that supports Hybrid Transactional and Analytical Processing (HTAP).

## Data Integration

### ETL

- [Apache Airflow](https://github.com/apache/airflow) - A platform to programmatically author, schedule, and monitor workflows.
- [Apache NiFi](https://github.com/apache/nifi) - An open-source data integration tool that is used to automate the flow of data between systems.
- [Airbyte](https://github.com/airbytehq/airbyte) - An open-source ETL/ELT platform that helps you replicate your data in your warehouses, lakes, and databases.

### ELT

- [Airbyte](https://github.com/airbytehq/airbyte) - An open-source ETL/ELT platform that helps you replicate your data in your warehouses, lakes, and databases.
- [dlt](https://github.com/dlt-hub/dlt) - A data pipeline framework that is designed to be simple, scalable, and extensible.

### CDC

- [Debezium](https://github.com/debezium/debezium) - An open-source distributed platform that captures row-level changes in databases so your applications can see and respond to those changes.

## Storage

### Block Storage

- [Longhorn](https://github.com/longhorn/longhorn) - A distributed block storage system for Kubernetes.
- [Ceph](https://github.com/ceph/ceph) - A distributed object, block, and file storage platform.
- [OpenEBS](https://github.com/openebs/openebs) - A Kubernetes-native storage solution.

### Object Storage

- [MinIO](https://github.com/minio/minio) - A high-performance object storage server compatible with Amazon S3 APIs.
- [Ceph](https://github.com/ceph/ceph) - A distributed object, block, and file storage platform.
- [Swift](https://github.com/openstack/swift) - A highly available, distributed, and scalable object storage system.

## Query Engine

- [Presto](https://github.com/prestodb/presto) - An open-source distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Spark SQL](https://spark.apache.org/sql/) - A module for working with structured data in Spark.
- [Trino](https://github.com/trinodb/trino) - A distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Velox](https://github.com/facebookincubator/velox) - A high-performance, distributed, in-memory data engine for analytics.
- [Apache Drill](https://github.com/apache/drill) - An open-source, low-latency SQL query engine for big data exploration.
- [Apache Calcite](https://github.com/apache/calcite) - A dynamic data management framework that provides tools to build SQL engines.

## In Memory Analytical Databases

- [GlareDB](https://github.com/GlareDB/glaredb) - A SQL query engine optimized for working with distributed data across multiple sources.
- [chDB](https://github.com/chdb-io/chdb) - An embeddable ClickHouse-based analytical database for fast SQL queries.
- [Apache DataFusion](https://github.com/apache/arrow-datafusion) - A high-performance, extensible query engine built on Apache Arrow.
- [DuckDB](https://github.com/duckdb/duckdb) - An in-process SQL OLAP database designed for analytics workloads.

## Data Processing

### Batch

- [dbt](https://github.com/dbt-labs/dbt-core) - A command-line tool that enables data analysts and engineers to transform data in their warehouse more effectively.
- [Apache Arrow](https://github.com/apache/arrow) - A cross-language development platform for in-memory data.

### Stream

- [Apache Kafka](https://github.com/apache/kafka) - A distributed event streaming platform that is used for building real-time data pipelines and streaming applications.
- [Apache Pulsar](https://github.com/apache/pulsar) - A distributed pub-sub messaging platform that is used for building real-time data pipelines and streaming applications.
- [Apache Storm](https://github.com/apache/storm) - A free and open-source distributed real-time computation system.
- [Apache Samza](https://github.com/apache/samza) - A distributed stream processing framework.

### Hybrid

- [Apache Spark](https://github.com/apache/spark) - An open-source, distributed computing system that is used for big data processing.
- [Apache Flink](https://github.com/apache/flink) - An open-source stream processing framework that is used to build real-time applications.
- [Apache NiFi](https://github.com/apache/nifi) - An open-source data integration tool that is used to automate the flow of data between systems.
- [Apache Beam](https://github.com/apache/beam) - An open-source, unified model for defining both batch and streaming data-parallel processing pipelines.

## Pipeline Orchestration

- [Apache Airflow](https://github.com/apache/airflow) - A platform to programmatically author, schedule, and monitor workflows.
- [Prefect](https://github.com/PrefectHQ/prefect) - A new workflow management system, designed for modern infrastructure and powered by the open-source Prefect Core workflow engine.
- [Dagster](https://github.com/dagster-io/dagster) - A data orchestrator for machine learning, analytics, and ETL.
- [Mage](https://github.com/mage-ai/mage-ai) - A workflow orchestrator for machine learning and data science.

## Messaging and Streaming Platform

- [Kafka](https://github.com/apache/kafka) - A distributed event streaming platform that is used for building real-time data pipelines and streaming applications.
- [Apache Pulsar](https://github.com/apache/pulsar) - A distributed pub-sub messaging platform that is used for building real-time data pipelines and streaming applications.
- [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server) - An open-source message broker that is used for building distributed systems.
- [NATS](https://github.com/nats-io/nats-server) - An open-source, high-performance messaging system that is used for building distributed systems.
- [MQTT](https://mqtt.org/) - A lightweight messaging protocol that is used for building IoT applications.
- [Redis Streams](https://redis.io/topics/streams-intro) - A data structure that is used for building real-time data pipelines and streaming applications.
- [ActiveMQ](https://github.com/apache/activemq) - An open-source message broker that is used for building distributed systems.

## Data Governance

### Data Quality

- [Great Expectations](https://github.com/great-expectations/great_expectations) - An open-source library that helps you to maintain data quality by defining, documenting, and testing data expectations.
- [Soda](https://github.com/sodadata/soda-core) - An open-source data quality monitoring and testing tool.

### Data Security

- [Apache Ranger](https://github.com/apache/ranger) - A framework to enable, monitor, and manage data security across the Hadoop platform.
- [Apache Knox](https://github.com/apache/knox) - A gateway for providing secure access to the data and processing resources of Hadoop clusters.

### Data Lineage

- [DataHub](https://github.com/datahub-project/datahub) - An open-source metadata search and discovery tool that is used to manage data assets.
- [OpenMetadata](https://github.com/open-metadata/OpenMetadata) - A unified metadata platform for data discovery, data observability, and data governance powered by a central metadata repository, in-depth column level lineage, and seamless team collaboration.
- [Amundsen](https://github.com/amundsen-io/amundsen) - A metadata driven application for improving the productivity of data analysts, data scientists, and engineers when interacting with data.
- [Apache Atlas](https://github.com/apache/atlas) - A scalable and extensible set of core foundational governance services that enables enterprises to effectively and efficiently meet their compliance requirements within Hadoop and allows integration with the complete data ecosystem.

### Data Visualization

- [Metabase](https://github.com/metabase/metabase) - The simplest, fastest way to get business intelligence and analytics to everyone in your company.
- [Superset](https://github.com/apache/superset) - A modern data exploration and data visualization platform that can replace or augment proprietary business intelligence tools for many teams.
- [Redash](https://github.com/getredash/redash) - Connect to any data source, easily visualize, dashboard and share your data.

## Containerization

- [Docker](https://www.docker.com/) - Most popular containerization platform that enables packaging the application and its dependencies into a container.
- [Podman](https://github.com/containers/podman) - A daemonless container engine for developing, managing, and running OCI containers.
- [CRI-O](https://github.com/cri-o/cri-o) - A lightweight container runtime for Kubernetes.
- [runc](https://github.com/opencontainers/runc) - A CLI tool for spawning and running containers according to the OCI specification.
- [containerd](https://github.com/containers/buildah) - An industry-standard container runtime with an emphasis on simplicity, robustness and portability.
- [LXC](https://github.com/containers/buildah) - A userspace interface for the Linux kernel containment features.
- [Buildah](https://github.com/containers/buildah) - A tool that facilitates building OCI images.

## Container Orchestration

- [Kubernetes](https://github.com/kubernetes/kubernetes) - An open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - A native clustering and scheduling tool for Docker containers.
- [Rancher](https://github.com/rancher/rancher) - An open-source platform for managing Kubernetes and Docker in production.
- [Nomad](https://github.com/hashicorp/nomad) - A simple and flexible workload orchestrator to deploy and manage containers and non-containerized applications.
- [Mesos](http://github.com/apache/mesos) - A distributed systems kernel that abstracts CPU, memory, storage, and other compute resources away from machines.
- [K3s](https://github.com/k3s-io/k3s) - A lightweight Kubernetes distribution that is optimized for edge computing.

## CICD

- [Jenkins](https://www.jenkins.io/) - An open-source automation server that enables developers around the world to reliably build, test, and deploy their software.
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) - A continuous integration and continuous deployment tool built into GitLab.
- [GitHub Actions](https://docs.github.com/en/actions) - A CI/CD service that allows you to automate your workflow directly in your GitHub repository.
- [CircleCI](https://circleci.com/) - A modern continuous integration and continuous delivery (CI/CD) platform.
- [Travis CI](https://www.travis-ci.com/) - A continuous integration service that is used to build and test software projects hosted at GitHub.
- [Argo CD](https://argoproj.github.io/argo-cd/) - A declarative, GitOps continuous delivery tool for Kubernetes.
- [Drone](https://www.drone.io/) - A continuous integration and continuous delivery platform built on container technology.
- [GoCD](https://www.gocd.org/) - An open-source continuous delivery server that helps you automate and streamline the build-test-release cycle for worry-free, continuous delivery of your product.

## Infrastructure as Code

### Configuration Management

- [Ansible](https://github.com/ansible/ansible) - A simple IT automation tool that automates configuration management, application deployment, intra-service orchestration, and many other IT needs.
- [Puppet](https://github.com/puppetlabs/puppet) - An open-source configuration management tool that automates the configuration and management of servers.
- [Chef](https://github.com/chef/chef) - A configuration management tool that automates the building, deployment, and management of infrastructure.
- [Salt](https://github.com/saltstack/salt) - A Python-based open-source configuration management and remote execution tool.

### Infrastructure Provisioning

- [Terraform](https://github.com/hashicorp/terraform) - An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services.
- [Pulumi](https://github.com/pulumi/pulumi) - An open-source infrastructure as code software tool that allows you to define infrastructure using familiar languages.

## Observability

### Logging

- [Fluentd](https://github.com/fluent/fluentd) - An open-source data collector for unified logging layer.
- [Fluent Bit](https://github.com/fluent/fluent-bit) - A fast and lightweight log processor and forwarder for Linux, Windows, and OSX.
- [Logstash](https://github.com/elastic/logstash) - An open-source server-side data processing pipeline that ingests data from multiple sources simultaneously.
- [Filebeat](https://github.com/elastic/beats) - A lightweight shipper for forwarding and centralizing log data.
- [Logrotate](https://github.com/logrotate/logrotate) - A simple utility for managing log files.

### Monitoring

- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - A fast, cost-effective, and scalable time-series database that is compatible with Prometheus.
- [Prometheus](https://github.com/prometheus/prometheus) - An open-source monitoring and alerting toolkit based on a time-series database.
- [Grafana](https://github.com/grafana/grafana) - An open-source analytics and monitoring platform that allows you to query, visualize, alert on, and understand your metrics.
- [Sentry](https://github.com/getsentry/sentry) - An open-source error tracking software that helps developers monitor and fix crashes in real-time.
- [Netdata](https://github.com/netdata/netdata) - An open-source real-time performance and health monitoring tool for systems and applications.
- [Zabbix](https://github.com/zabbix/zabbix) - An open-source monitoring software tool for diverse IT components, including networks, servers, virtual machines, and cloud services.
- [Nagios](https://github.com/NagiosEnterprises/nagioscore) - An open-source computer system monitoring, network monitoring, and infrastructure monitoring software application.
- [Icinga](https://github.com/Icinga/icinga2) - An open-source monitoring software tool that monitors availability and performance, gives you simple access to relevant data, and raises alerts to keep you in the loop.

### Tracing

- [Jaeger](https://github.com/jaegertracing/jaeger) - An open-source end-to-end distributed tracing system.
- [Zipkin](https://github.com/openzipkin/zipkin) - An open-source distributed tracing system.
- [OpenTelemetry](https://opentelemetry.io/) - An observability framework for cloud-native software.
