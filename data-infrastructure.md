# Data Infrastructure

Object storage, databases, search, and streaming.

Section page: [Data Infrastructure for AI Systems: Object Storage, Databases, Search & AI Data Architecture](https://www.glukhov.org/data-infrastructure/)

[Index of all sections](README.md)

## Databases

- [Neo4j graph database for GraphRAG, install, Cypher, vectors, ops](https://www.glukhov.org/data-infrastructure/databases/neo4j/) — Senior-engineer guide to Neo4j for property graphs and GraphRAG. Cypher, ACID, Neo4j vs Neptune and TigerGraph, Docker and AuraDB, ports and neo4j.conf, vector indexes, hybrid retrieval, and Python neo4j-graphrag.

## Integrations

- [Airtable for Developers & DevOps - Free Plan Limits, API, Webhooks, and Go/Python Integration Examples](https://www.glukhov.org/data-infrastructure/integrations/airtable-for-developers-and-devops/) — Airtable for developers: Free plan limits, competitors, and Go and Python examples for CRUD, pagination, rate limits, and webhooks.
- [Apache Airflow for MLOPS and ETL - Description, Benefits and Examples](https://www.glukhov.org/data-infrastructure/integrations/apache-airflow/) — How to use Apache Airflow for MLOPS and ETL - Description, Benefits and Examples

## Messaging

- [Rabbitmq on Eks vs Sqs hosting cost comparison](https://www.glukhov.org/data-infrastructure/messaging/rabbitmq-on-eks-vs-sqs/) — Rabbitmq on Eks vs Sqs features and hosting cost comparison

## Object storage

- [Garage - S3 compatible object storage Quickstart](https://www.glukhov.org/data-infrastructure/object-storage/garage-quickstart/) — Garage quickstart for S3-compatible object storage. Run Garage with Docker, set layout and replication, add TLS via reverse proxy, create buckets and keys, and apply production tips for self-hosted storage.
- [Garage vs MinIO vs AWS S3: Object Storage Comparison and Feature Matrix](https://www.glukhov.org/data-infrastructure/object-storage/garage-vs-minio-vs-s3/) — Compare MinIO, Garage, and AWS S3 for object storage. Feature matrix, cost model, operational complexity, and when to choose each—managed S3, self-hosted Garage, or MinIO with broad S3 parity.
- [MinIO as Aws S3 alternative. Minio overview and install](https://www.glukhov.org/data-infrastructure/object-storage/minio-vs-aws-s3/)
- [MinIO CE in 2026: Retired Upstream, Source-Only, and What to Use](https://www.glukhov.org/data-infrastructure/object-storage/minio-dead/) — MinIO CE is archived, source-only, and operationally high risk. Here is the timeline, community verdict, and safer alternatives for S3 compatible storage.
- [MinIO Commandline Parameters Cheatsheet](https://www.glukhov.org/data-infrastructure/object-storage/minio-cheatsheet/)
- [Self-Hosted S3 Alternatives in 2026 (RustFS, Garage, SeaweedFS, Ceph)](https://www.glukhov.org/data-infrastructure/object-storage/self-hosted-s3-alternatives/) — Compare RustFS, Garage, SeaweedFS, Ceph RGW, VersityGW, S3Proxy, and rclone for self-hosted S3. Native object stores vs filesystem-backed S3 gateways.

## Search

- [Elasticsearch Cheatsheet: Essential Commands and Tips](https://www.glukhov.org/data-infrastructure/search/elasticsearch-cheatsheet/) — Complete Elasticsearch cheatsheet covering CRUD operations, search queries, aggregations, index management, and performance optimization. Quick reference for developers working with Elasticsearch cluster.
- [PostgreSQL Full Text Search vs Elasticsearch Comparison](https://www.glukhov.org/data-infrastructure/search/postgresql-full-text-search-vs-elasticsearch/) — A practical comparison of PostgreSQL full text search and Elasticsearch across relevance, scale, latency, cost, and operations for modern apps.
- [Self-hosting SearXNG](https://www.glukhov.org/data-infrastructure/search/selfhosting-searxng/)

## Streaming

- [Apache Flink on K8s and Kafka: PyFlink, Go, ops, and managed pricing](https://www.glukhov.org/data-infrastructure/stream-processing/apache-flink/) — DevOps guide to Flink. Stateful streaming, JobManager and TaskManagers, checkpoints vs savepoints, vs Spark and Kafka Streams, K8s Operator, Helm, PyFlink, Go, managed pricing.
- [Apache Kafka Quickstart - Install Kafka 4.2 with CLI and Local Examples](https://www.glukhov.org/data-infrastructure/stream-processing/apache-kafka/) — Learn Apache Kafka 4.2 fast with tarball or Docker, start a local KRaft broker, master key CLI tools, and run practical producer, consumer, and Connect examples.
- [Building Event-Driven Microservices with AWS Kinesis](https://www.glukhov.org/data-infrastructure/stream-processing/service-oriented-and-microservices-with-aws-kinesis/) — Comprehensive guide to implementing scalable event-driven microservices architecture using AWS Kinesis Data Streams, including real-time data processing, service decoupling, and best practices for production deployments.
