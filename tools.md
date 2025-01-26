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

### Programming Languages

#### Python

##### Python version and package manager

- [UV](https://github.com/astral-sh/uv) (recommended)
- [Poetry](https://python-poetry.org/)

##### Type Checker

- [Mypy](https://github.com/python/mypy)

##### Linter and Code Formatter

- [Ruff](https://github.com/astral-sh/ruff)
- [Black](https://github.com/psf/black)
- [Flake8](https://github.com/PyCQA/flake8)

##### Data Validation

- [Pydantic](https://github.com/pydantic/pydantic)

##### Document Generator

- [Sphinx](https://github.com/sphinx-doc/sphinx)
- [Mkdocs](https://www.mkdocs.org/)

##### Doc-string Generator

- [autoDocstring in VSCode](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

##### Test and Coverage Tools

- [Pytest](https://github.com/pytest-dev/pytest)
- [tox](https://github.com/tox-dev/tox)
- [nox](https://github.com/wntrblm/nox)
- [Lettuce](https://github.com/gabrielfalcao/lettuce)

##### Software Version Manager

- [semantic-release](https://github.com/semantic-release/semantic-release/)
- [bump-my-version](https://github.com/callowayproject/bump-my-version)
- [bump2version](https://github.com/c4urself/bump2version)
- [python-semantic-release](https://github.com/python-semantic-release/python-semantic-release)

##### Changelog Generator

- [git-cliff](https://github.com/orhun/git-cliff)
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog)

### Operating System

### Networking

### Basic Authentication and Authorization

### Web Frameworks and API Development

### Cache

### Testing

### Version Control System

- [Git](https://git-scm.com/) - A distributed version control system that is widely used for source code management.
- [Mercurial](https://www.mercurial-scm.org/) - A distributed version control system that is easy to learn.

### Version Control Hosting

- [GitHub](https://github.com) - A web-based platform for git version control and collaboration.
- [GitLab](https://gitlab.com) - A web-based platform for git and DevOps lifecycle tooling.
- [Bitbucket](https://bitbucket.org) - A web-based platform for Git and Mercurial version control.

### Databases

#### Relational

- [PostgreSQL](https://www.postgresql.org/) - An open-source and powerful relational database management system.
- [MySQL](https://www.mysql.com/) - One of the most famous open-source relational database management systems.
- [CockroachDB](https://www.cockroachlabs.com/) - An open-source, distributed SQL database that is ACID compliant and horizontally scalable.
- [TiDB](https://pingcap.com/) - An open-source, distributed SQL database that supports Hybrid Transactional and Analytical Processing (HTAP).
- [SQLite](https://www.sqlite.org/) - A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- [MariaDB](https://mariadb.org/) - An open-source relational database management system that is a fork of MySQL.
- [Oracle Database](https://www.oracle.com/database/) - A multi-model database management system produced and marketed by Oracle Corporation.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - A relational database management system developed by Microsoft.

#### NoSQL

##### Columnar

##### Document Based

##### Key-Value

##### Time-series

##### Vector

##### Graph

##### NewSQL

### Data Integration

#### ETL

#### ELT

#### Reverse ETL

#### CDC

### Storage

#### Block Storage

- [Longhorn](https://longhorn.io/) - A distributed block storage system for Kubernetes.
- [Ceph](https://ceph.io/) - A distributed object, block, and file storage platform.
- [OpenEBS](https://openebs.io/) - A Kubernetes-native storage solution.

#### Object Storage

- [MinIO](https://min.io/) - A high-performance object storage server compatible with Amazon S3 APIs.
- [Ceph](https://ceph.io/) - A distributed object, block, and file storage platform.
- [Swift](https://github.com/openstack/swift) - A highly available, distributed, and scalable object storage system.

### Query Engine

- [Presto](https://prestodb.io/) - An open-source distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Spark SQL](https://spark.apache.org/sql/) - A module for working with structured data in Spark.]
- [Trino](https://trino.io/) - A distributed SQL query engine for running interactive analytic queries against data sources of all sizes.
- [Velox](https://velox-lib.io/) - A high-performance, distributed, in-memory data engine for analytics.
- [Apache Drill](https://drill.apache.org/) - An open-source, low-latency SQL query engine for big data exploration.
- [Apache Calcite](https://calcite.apache.org/) - A dynamic data management framework that provides tools to build SQL engines.

### Data Processing

#### Batch

#### Hybrid

#### Stream

### Pipeline Orchestration

### Messaging and Streaming Platform

### Data Governance

#### Data Quality

#### Data Security

#### Data Lineage

#### Data Visualization

### Containerization

- [Docker](https://www.docker.com/) - Most popular containerization platform that enables packaging the application and its dependencies into a container.
- [Podman](https://podman.io/) - A daemonless container engine for developing, managing, and running OCI containers.
- [CRI-O](https://cri-o.io/) - A lightweight container runtime for Kubernetes.
- [runc](https://github.com/opencontainers/runc) - A CLI tool for spawning and running containers according to the OCI specification.
- [containerd](https://containerd.io/) - An industry-standard container runtime with an emphasis on simplicity, robustness and portability.
- [LXC](https://linuxcontainers.org/lxc/) - A userspace interface for the Linux kernel containment features.
- [Buildah](https://buildah.io/) - A tool that facilitates building OCI images.

### Container Orchestration

- [Kubernetes](https://kubernetes.io/) - An open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - A native clustering and scheduling tool for Docker containers.
- [Rancher](https://rancher.com/) - An open-source platform for managing Kubernetes and Docker in production.
- [Nomad](https://www.nomadproject.io/) - A simple and flexible workload orchestrator to deploy and manage containers and non-containerized applications.
- [Mesos](http://mesos.apache.org/) - A distributed systems kernel that abstracts CPU, memory, storage, and other compute resources away from machines.
- [K3s](https://k3s.io/) - A lightweight Kubernetes distribution that is optimized for edge computing.

### CICD

- [Jenkins](https://www.jenkins.io/) - An open-source automation server that enables developers around the world to reliably build, test, and deploy their software.
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) - A continuous integration and continuous deployment tool built into GitLab.
- [GitHub Actions](https://docs.github.com/en/actions) - A CI/CD service that allows you to automate your workflow directly in your GitHub repository.
- [CircleCI](https://circleci.com/) - A modern continuous integration and continuous delivery (CI/CD) platform.
- [Travis CI](https://www.travis-ci.com/) - A continuous integration service that is used to build and test software projects hosted at GitHub.
- [Argo CD](https://argoproj.github.io/argo-cd/) - A declarative, GitOps continuous delivery tool for Kubernetes.
- [Drone](https://www.drone.io/) - A continuous integration and continuous delivery platform built on container technology.
- [GoCD](https://www.gocd.org/) - An open-source continuous delivery server that helps you automate and streamline the build-test-release cycle for worry-free, continuous delivery of your product.

### Infrastructure as Code

#### Configuration Management

- [Ansible](https://www.ansible.com/) - A simple IT automation tool that automates configuration management, application deployment, intra-service orchestration, and many other IT needs.
- [Puppet](https://puppet.com/) - An open-source configuration management tool that automates the configuration and management of servers.
- [Chef](https://www.chef.io/) - A configuration management tool that automates the building, deployment, and management of infrastructure.
- [SaltStack](https://www.saltstack.com/) - A Python-based open-source configuration management and remote execution tool.

#### Infrastructure Provisioning

- [Terraform](https://www.terraform.io/) - An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services.
- [Pulumi](https://www.pulumi.com/) - An open-source infrastructure as code software tool that allows you to define infrastructure using familiar languages.

### Observability

#### Logging

- [Fluentd](https://www.fluentd.org/) - An open-source data collector for unified logging layer.
- [Fluent Bit](https://fluentbit.io/) - A fast and lightweight log processor and forwarder for Linux, Windows, and OSX.
- [Logstash](https://www.elastic.co/logstash) - An open-source server-side data processing pipeline that ingests data from multiple sources simultaneously.
- [Filebeat](https://www.elastic.co/beats/filebeat) - A lightweight shipper for forwarding and centralizing log data.
- [Logrotate](https://github.com/logrotate/logrotate) - A simple utility for managing log files.

#### Monitoring

- [Prometheus](https://prometheus.io/) - An open-source monitoring and alerting toolkit based on a time-series database.
- [Grafana](https://grafana.com/) - An open-source analytics and monitoring platform that allows you to query, visualize, alert on, and understand your metrics.
- [Sentry](https://sentry.io/) - An open-source error tracking software that helps developers monitor and fix crashes in real-time.
- [Netdata](https://www.netdata.cloud/) - An open-source real-time performance and health monitoring tool for systems and applications.
- [Zabbix](https://www.zabbix.com/) - An open-source monitoring software tool for diverse IT components, including networks, servers, virtual machines, and cloud services.
- [Nagios](https://www.nagios.org/) - An open-source computer system monitoring, network monitoring, and infrastructure monitoring software application.
- [Icinga](https://icinga.com/) - An open-source monitoring software tool that monitors availability and performance, gives you simple access to relevant data, and raises alerts to keep you in the loop.

#### Tracing

- [Jaeger](https://www.jaegertracing.io/) - An open-source end-to-end distributed tracing system.
- [Zipkin](https://zipkin.io/) - An open-source distributed tracing system.
- [OpenTelemetry](https://opentelemetry.io/) - An observability framework for cloud-native software.
