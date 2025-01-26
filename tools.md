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

### Databases

#### Relational

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

#### Object Storage

### Query Engine

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

### Infrastructure as Code

#### Configuration Management

#### Infrastructure Provisioning

### Observability

#### Logging

#### Monitoring

#### Tracing
