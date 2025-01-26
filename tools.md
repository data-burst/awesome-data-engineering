# Data Engineering Tools

## Table of Contents

- [Programming Languages](#programming-languages)
  - [Python](#python)
    - [Python version and package manager](#python-version-and-package-manager)
    - [Type Checker](#type-checker)
    - [Linter and Code Formatter](#linter-and-code-formatter)
    - [Data Validation](#data-validation)
    - [Document Generator](#document-generator)
    - [Doc-string Generator](#doc-string-generator)
    - [Test and Coverage Tools](#test-and-coverage-tools)
    - [Software Version Manager](#software-version-manager)
    - [Changelog Generator](#changelog-generator)
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
    - [Columnar](#columnar)
    - [Document Based](#document-based)
    - [Key-Value](#key-value)
    - [Time-series](#time-series)
    - [Vector](#vector)
    - [Graph](#graph)
    - [NewSQL](#newsql)
- [Data Integration](#data-integration)
  - [ETL](#etl)
  - [ELT](#elt)
  - [Reverse ETL](#reverse-etl)
  - [CDC](#cdc)
- [Storage](#storage)
  - [Block Storage](#block-storage)
  - [Object Storage](#object-storage)
- [Query Engine](#query-engine)
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

#### Python version and package manager

- [UV](https://github.com/astral-sh/uv) (recommended) - A fast and extensible Python version manager.
- [Poetry](https://python-poetry.org/) - A tool for dependency management and packaging in Python.

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
- [Mkdocs](https://www.mkdocs.org/) - A fast, simple, and downright gorgeous static site generator that's geared towards building project documentation.

#### Doc-string Generator

- [autoDocstring in VSCode](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) - A Visual Studio Code extension that generates docstrings for Python functions.

#### Test and Coverage Tools

- [Pytest](https://github.com/pytest-dev/pytest) - A testing framework that makes it easy to write simple and scalable tests.
- [tox](https://github.com/tox-dev/tox) - A generic virtualenv management and test command line tool.
- [nox](https://github.com/wntrblm/nox) - A flexible test automation tool that allows you to run tests in different environments.
- [Lettuce](https://github.com/gabrielfalcao/lettuce) - A BDD tool that allows you to write tests in plain English.

#### Software Version Manager

- [semantic-release](https://github.com/semantic-release/semantic-release/) - Fully automated version management and package publishing.
- [bump-my-version](https://github.com/callowayproject/bump-my-version) - A simple CLI tool to bump the version of your project.
- [bump2version](https://github.com/c4urself/bump2version) - A tool to simplify releasing software by updating all version strings in your source code by the correct increment.
- [python-semantic-release](https://github.com/python-semantic-release/python-semantic-release) - Fully automated version management and package publishing for Python projects.

#### Changelog Generator

- [git-cliff](https://github.com/orhun/git-cliff) - A highly customizable Changelog Generator that follows Conventional Commit specifications.
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) - A tool that generates a changelog from git metadata.

## Operating System

- [Linux](https://www.kernel.org/) - Most popular unix-based open-source operating system that is widely used for servers and embedded systems.
- [Windows](https://www.microsoft.com/en-us/windows) - A series of operating systems developed by Microsoft.
- [macOS](https://www.apple.com/macos) - A series of unix-based operating systems developed by Apple Inc.

## Networking

- [OpenSSH](https://www.openssh.com/) - A free version of the SSH connectivity tools that technical users rely on.
- [OpenVPN](https://openvpn.net/) - An open-source software application that implements virtual private network (VPN) techniques for creating secure point-to-point or site-to-site connections in routed or bridged configurations and remote access facilities.
- [ufw](https://help.ubuntu.com/community/UFW) - A user-friendly way to create an IPv4 or IPv6 host-based firewall.
- [iptables](https://netfilter.org/) - A user-space utility program that allows a system administrator to configure the IP packet filter rules of the Linux kernel firewall, implemented as different Netfilter modules.
- [nftables](https://netfilter.org/projects/nftables/) - A subsystem of the Linux kernel providing filtering and classification of network packets/datagrams/frames.
- [Nginx](https://www.nginx.com/) - A web server that can also be used as a reverse proxy, load balancer, mail proxy, and HTTP cache.
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

- [FastAPI](https://fastapi.tiangolo.com/) - A modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
- [Flask](https://flask.palletsprojects.com/) - A lightweight WSGI web application framework.
- [Django](https://www.djangoproject.com/) - A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- [Falcon](https://falconframework.org/) - A high-performance Python framework for building cloud APIs and web app backends.

### Go

- [Gin](https://gin-gonic.com/) - A web framework written in Go (Golang).
- [Echo](https://echo.labstack.com/) - A high-performance, minimalist Go web framework.
- [Fiber](https://gofiber.io/) - An Express.js inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go.

### Java

- [Spring Boot](https://spring.io/projects/spring-boot) - An open-source Java-based framework used to create stand-alone, production-grade Spring-based Applications.
- [Micronaut](https://micronaut.io/) - A modern, JVM-based, full-stack framework for building modular, easily testable microservice and serverless applications.

### Rust

- [Rocket](https://rocket.rs/) - A web framework for Rust.
- [Actix](https://actix.rs/) - A powerful, pragmatic, and extremely fast web framework for Rust.

## Cache

- [Redis](https://redis.io/) - An open-source, in-memory data structure store that can be used as a database, cache, and message broker.
- [Memcached](https://memcached.org/) - A high-performance, distributed memory object caching system.
- [Varnish](https://varnish-cache.org/) - An open-source web application accelerator that is used to cache web content.
- [Nginx](https://www.nginx.com/) - A web server that can also be used as a reverse proxy, load balancer, mail proxy, and HTTP cache.
- [Squid](http://www.squid-cache.org/) - A caching proxy for the Web supporting HTTP, HTTPS, FTP, and more.
- [Apache Ignite](https://ignite.apache.org/) - An open-source distributed database, caching, and processing platform designed to store and compute on large volumes of data across a cluster of nodes.
- [Hazelcast](https://hazelcast.com/) - An open-source in-memory data grid that is used to distribute data across a cluster of nodes.

## Testing

### Integration Testing

- [Postman](https://www.postman.com/) - A collaboration platform for API development that allows you to design, mock, document, and test APIs.
- [Insomnia](https://insomnia.rest/) - A powerful REST API client that is used to design, debug, and test APIs.
- [Pact](https://docs.pact.io/) - A contract testing tool that is used to ensure that services can communicate with each other.

### Functional Testing

- [Selenium](https://www.selenium.dev/) - A portable framework for testing web applications.
- [Cypress](https://www.cypress.io/) - A fast, easy, and reliable testing for anything that runs in a browser.
- [Playwright](https://playwright.dev/) - A Node.js library to automate the Chromium, WebKit, and Firefox browsers with a single API.
- [TestCafe](https://devexpress.github.io/testcafe/) - A Node.js tool to automate end-to-end web testing.
- [Karate](https://github.com/karatelabs/karate) - A unified framework for API test automation, mocks, performance testing, and even UI automation.
- [Robot Framework](https://robotframework.org/) - A generic test automation framework for acceptance testing and acceptance test-driven development (ATDD).

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

- [PostgreSQL](https://www.postgresql.org/) - An open-source and powerful relational database management system.
- [MySQL](https://www.mysql.com/) - One of the most famous open-source relational database management systems.
- [CockroachDB](https://www.cockroachlabs.com/) - An open-source, distributed SQL database that is ACID compliant and horizontally scalable.
- [TiDB](https://pingcap.com/) - An open-source, distributed SQL database that supports Hybrid Transactional and Analytical Processing (HTAP).
- [SQLite](https://www.sqlite.org/) - A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- [MariaDB](https://mariadb.org/) - An open-source relational database management system that is a fork of MySQL.
- [Oracle Database](https://www.oracle.com/database/) - A multi-model database management system produced and marketed by Oracle Corporation.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - A relational database management system developed by Microsoft.

### NoSQL

#### Columnar

- [Cassandra](https://cassandra.apache.org/) - A distributed NoSQL database management system designed to handle large amounts of data across many commodity servers.
- [HBase](https://hbase.apache.org/) - An open-source, distributed, versioned, non-relational database modeled after Google's Bigtable.
- [ClickHouse](https://clickhouse.tech/) - An open-source column-oriented database management system that allows generating analytical data reports in real-time.
- [Apache Druid](https://druid.apache.org/) - A high-performance, column-oriented, distributed data store that is optimized for OLAP queries on event data.
- [Pinot](https://pinot.apache.org/) - A real-time distributed OLAP datastore that is designed for high-performance and low-latency.

#### Document Based

- [MongoDB](https://www.mongodb.com/) - A cross-platform document-oriented database program.
- [Couchbase](https://www.couchbase.com/) - An open-source, distributed, multi-model NoSQL document-oriented database.
- [CouchDB](https://couchdb.apache.org/) - An open-source database that uses JSON for documents, JavaScript for MapReduce indexes, and regular HTTP for its API.
- [RethinkDB](https://rethinkdb.com/) - An open-source, distributed document-oriented database that makes it easy to build and scale real-time web applications.
- [ArangoDB](https://www.arangodb.com/) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
- [RavenDB](https://github.com/ravendb/ravendb) - A NoSQL document database that is fully transactional (ACID) across your database.
- [Elasticsearch](https://www.elastic.co/elasticsearch/) - A distributed, RESTful search and analytics engine that is based on Apache Lucene.

#### Key-Value

- [Redis](https://redis.io/) - An open-source, in-memory data structure store that can be used as a database, cache, and message broker.
- [KeyDB](https://keydb.dev/) - A high-performance fork of Redis with multithreading support.
- [TiKV](https://tikv.org/) - A distributed transactional key-value database that provides transactional guarantees.
- [etcd](https://etcd.io/) - A distributed key-value store that provides a reliable way to store data across a cluster of machines.
- [ArangoDB](https://www.arangodb.com/) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
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

- [ArangoDB](https://www.arangodb.com/) - An open-source, distributed multi-model database that supports key/value, document, and graph data models.
- [Neo4j](https://neo4j.com/) - An open-source graph database that is optimized for storing and querying graphs.
- [JanusGraph](https://janusgraph.org/) - A highly scalable graph database optimized for storing and querying large graphs with billions of vertices and edges distributed across a multi-machine cluster.
- [OrientDB](https://orientdb.com/) - An open-source, distributed graph database that is optimized for storing and querying graphs.
- [Dgraph](https://dgraph.io/) - A horizontally scalable and distributed GraphQL database with a graph backend which provides ACID transactions, consistent replication, and linearizable reads.

#### NewSQL

- [CockroachDB](https://www.cockroachlabs.com/) - An open-source, distributed SQL database that is ACID compliant and horizontally scalable.
- [TiDB](https://pingcap.com/) - An open-source, distributed SQL database that supports Hybrid Transactional and Analytical Processing (HTAP).

## Data Integration

### ETL

- [Apache Airflow](https://airflow.apache.org/) - A platform to programmatically author, schedule, and monitor workflows.
- [Apache NiFi](https://nifi.apache.org/) - An open-source data integration tool that is used to automate the flow of data between systems.

### ELT

- [Airbyte](https://airbyte.io/) - An open-source EL(T) platform that helps you replicate your data in your warehouses, lakes, and databases.

### CDC

- [Debezium](https://debezium.io/) - An open-source distributed platform that captures row-level changes in databases so your applications can see and respond to those changes.

## Storage

### Block Storage

- [Longhorn](https://longhorn.io/) - A distributed block storage system for Kubernetes.
- [Ceph](https://ceph.io/) - A distributed object, block, and file storage platform.
- [OpenEBS](https://openebs.io/) - A Kubernetes-native storage solution.

### Object Storage

- [MinIO](https://min.io/) - A high-performance object storage server compatible with Amazon S3 APIs.
- [Ceph](https://ceph.io/) - A distributed object, block, and file storage platform.
- [Swift](https://github.com/openstack/swift) - A highly available, distributed, and scalable object storage system.

## Query Engine

- [Presto](https://prestodb.io/) - An open-source distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Spark SQL](https://spark.apache.org/sql/) - A module for working with structured data in Spark.]
- [Trino](https://trino.io/) - A distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Velox](https://velox-lib.io/) - A high-performance, distributed, in-memory data engine for analytics.
- [Apache Drill](https://drill.apache.org/) - An open-source, low-latency SQL query engine for big data exploration.
- [Apache Calcite](https://calcite.apache.org/) - A dynamic data management framework that provides tools to build SQL engines.

## Data Processing

### Batch

- [dbt](https://www.getdbt.com/) - A command-line tool that enables data analysts and engineers to transform data in their warehouse more effectively.
- [Apache Arrow](https://arrow.apache.org/) - A cross-language development platform for in-memory data.

### Stream

- [Apache Kafka](https://kafka.apache.org/) - A distributed event streaming platform that is used for building real-time data pipelines and streaming applications.
- [Apache Pulsar](https://pulsar.apache.org/) - A distributed pub-sub messaging platform that is used for building real-time data pipelines and streaming applications.
- [Apache Storm](https://storm.apache.org/) - A free and open-source distributed real-time computation system.
- [Apache Samza](https://samza.apache.org/) - A distributed stream processing framework.

### Hybrid

- [Apache Spark](https://spark.apache.org/) - An open-source, distributed computing system that is used for big data processing.
- [Apache Nifi](https://nifi.apache.org/) - An open-source data integration tool that is used to automate the flow of data between systems.
- [Apache Flink](https://flink.apache.org/) - An open-source stream processing framework that is used to build real-time applications.
- [Apache Beam](https://beam.apache.org/) - An open-source, unified model for defining both batch and streaming data-parallel processing pipelines.

## Pipeline Orchestration

## Messaging and Streaming Platform

- [Kafka](https://kafka.apache.org/) - A distributed event streaming platform that is used for building real-time data pipelines and streaming applications.
- [Pulsar](https://pulsar.apache.org/) - A distributed pub-sub messaging platform that is used for building real-time data pipelines and streaming applications.
- [RabbitMQ](https://www.rabbitmq.com/) - An open-source message broker that is used for building distributed systems.
- [NATS](https://nats.io/) - An open-source, high-performance messaging system that is used for building distributed systems.
- [MQTT](https://mqtt.org/) - A lightweight messaging protocol that is used for building IoT applications.
- [Redis Streams](https://redis.io/topics/streams-intro) - A data structure that is used for building real-time data pipelines and streaming applications.
- [ActiveMQ](https://activemq.apache.org/) - An open-source message broker that is used for building distributed systems.

## Data Governance

### Data Quality

### Data Security

### Data Lineage

### Data Visualization

## Containerization

- [Docker](https://www.docker.com/) - Most popular containerization platform that enables packaging the application and its dependencies into a container.
- [Podman](https://podman.io/) - A daemonless container engine for developing, managing, and running OCI containers.
- [CRI-O](https://cri-o.io/) - A lightweight container runtime for Kubernetes.
- [runc](https://github.com/opencontainers/runc) - A CLI tool for spawning and running containers according to the OCI specification.
- [containerd](https://containerd.io/) - An industry-standard container runtime with an emphasis on simplicity, robustness and portability.
- [LXC](https://linuxcontainers.org/lxc/) - A userspace interface for the Linux kernel containment features.
- [Buildah](https://buildah.io/) - A tool that facilitates building OCI images.

## Container Orchestration

- [Kubernetes](https://kubernetes.io/) - An open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - A native clustering and scheduling tool for Docker containers.
- [Rancher](https://rancher.com/) - An open-source platform for managing Kubernetes and Docker in production.
- [Nomad](https://www.nomadproject.io/) - A simple and flexible workload orchestrator to deploy and manage containers and non-containerized applications.
- [Mesos](http://mesos.apache.org/) - A distributed systems kernel that abstracts CPU, memory, storage, and other compute resources away from machines.
- [K3s](https://k3s.io/) - A lightweight Kubernetes distribution that is optimized for edge computing.

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

- [Ansible](https://www.ansible.com/) - A simple IT automation tool that automates configuration management, application deployment, intra-service orchestration, and many other IT needs.
- [Puppet](https://puppet.com/) - An open-source configuration management tool that automates the configuration and management of servers.
- [Chef](https://www.chef.io/) - A configuration management tool that automates the building, deployment, and management of infrastructure.
- [SaltStack](https://www.saltstack.com/) - A Python-based open-source configuration management and remote execution tool.

### Infrastructure Provisioning

- [Terraform](https://www.terraform.io/) - An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services.
- [Pulumi](https://www.pulumi.com/) - An open-source infrastructure as code software tool that allows you to define infrastructure using familiar languages.

## Observability

### Logging

- [Fluentd](https://www.fluentd.org/) - An open-source data collector for unified logging layer.
- [Fluent Bit](https://fluentbit.io/) - A fast and lightweight log processor and forwarder for Linux, Windows, and OSX.
- [Logstash](https://www.elastic.co/logstash) - An open-source server-side data processing pipeline that ingests data from multiple sources simultaneously.
- [Filebeat](https://www.elastic.co/beats/filebeat) - A lightweight shipper for forwarding and centralizing log data.
- [Logrotate](https://github.com/logrotate/logrotate) - A simple utility for managing log files.

### Monitoring

- [VictoriaMetrics](https://victoriametrics.com/) - A fast, cost-effective, and scalable time-series database that is compatible with Prometheus.
- [Prometheus](https://prometheus.io/) - An open-source monitoring and alerting toolkit based on a time-series database.
- [Grafana](https://grafana.com/) - An open-source analytics and monitoring platform that allows you to query, visualize, alert on, and understand your metrics.
- [Sentry](https://sentry.io/) - An open-source error tracking software that helps developers monitor and fix crashes in real-time.
- [Netdata](https://www.netdata.cloud/) - An open-source real-time performance and health monitoring tool for systems and applications.
- [Zabbix](https://www.zabbix.com/) - An open-source monitoring software tool for diverse IT components, including networks, servers, virtual machines, and cloud services.
- [Nagios](https://www.nagios.org/) - An open-source computer system monitoring, network monitoring, and infrastructure monitoring software application.
- [Icinga](https://icinga.com/) - An open-source monitoring software tool that monitors availability and performance, gives you simple access to relevant data, and raises alerts to keep you in the loop.

### Tracing

- [Jaeger](https://www.jaegertracing.io/) - An open-source end-to-end distributed tracing system.
- [Zipkin](https://zipkin.io/) - An open-source distributed tracing system.
- [OpenTelemetry](https://opentelemetry.io/) - An observability framework for cloud-native software.
