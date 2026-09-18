# Awesome Open Source Data Engineering with stars

A curated list of open source tools used in analytics platforms and data engineering ecosystem
![Open Source Data Engineering Landscape 2025](https://github.com/user-attachments/assets/fe9e97a8-abd8-47a9-8429-15130055785c)

For more information about the above compiled landscape for 2025, please refer to the published blog post on [Pracdata.io](https://www.pracdata.io/p/open-source-data-engineering-landscape-2025)

## Table of contents

* [Storage Systems](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#storage-systems) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Data Lake Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-lake-platform) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Data Integration](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-integration) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Data Processing & Computation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-processing-and-computation) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Workflow Management & DataOps](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#workflow-management--dataops) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Data Infrastructure](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-infrastructure) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Metadata Management](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#metadata-management) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [Analytics & Visualisation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#analytics--visualisation) ⭐ 605 | 🐛 18 | 📅 2025-03-12
* [ML/AI Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#mlai-platform) ⭐ 605 | 🐛 18 | 📅 2025-03-12

## STORAGE SYSTEMS

### Relational DBMS

* [Supabase](https://github.com/supabase/supabase) ⭐ 110,116 | 🐛 1,133 | 🌐 TypeScript | 📅 2026-09-18 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,142 | 🐛 0 | 🌐 C | 📅 2026-09-18 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,432 | 🐛 60 | 🌐 C++ | 📅 2026-09-11 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,506 | 🐛 23 | 🌐 C | 📅 2026-09-18 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,243 | 🐛 495 | 🌐 C++ | 📅 2026-09-18 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,549 | 🐛 7,092 | 🌐 Go | 📅 2026-09-18 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,472 | 🐛 8,429 | 🌐 Go | 📅 2026-09-16 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 23,105 | 🐛 562 | 🌐 Rust | 📅 2026-08-31 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,800 | 🐛 220 | 🌐 Java | 📅 2026-09-18 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,776 | 🐛 1,076 | 🌐 C | 📅 2026-09-18 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,542 | 🐛 7,946 | 🌐 C | 📅 2026-09-18 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,282 | 🐛 600 | 🌐 C++ | 📅 2026-09-18 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,436 | 🐛 324 | 🌐 Java | 📅 2026-09-18 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 76,402 | 🐛 2,958 | 🌐 C | 📅 2026-09-17 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,601 | 🐛 305 | 🌐 C++ | 📅 2026-09-18 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,283 | 🐛 107 | 🌐 C | 📅 2026-09-11 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,280 | 🐛 113 | 🌐 Rust | 📅 2026-09-18 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,085 | 🐛 898 | 🌐 Java | 📅 2026-09-18 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,569 | 🐛 36 | 🌐 C++ | 📅 2026-09-18 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 26,998 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,581 | 🐛 16 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,072 | 🐛 448 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,953 | 🐛 376 | 🌐 Erlang | 📅 2026-09-18 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 3,998 | 🐛 86 | 🌐 C# | 📅 2026-09-18 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 33,041 | 🐛 720 | 🌐 Rust | 📅 2026-09-14 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,274 | 🐛 855 | 🌐 C++ | 📅 2026-09-18 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,168 | 🐛 948 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,985 | 🐛 357 | 🌐 Java | 📅 2026-09-17 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,799 | 🐛 100 | 🌐 Go | 📅 2026-09-18 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,244 | 🐛 249 | 🌐 Java | 📅 2026-09-10 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,065 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,396 | 🐛 678 | 🌐 C++ | 📅 2026-09-08 - A distributed, horizontal scalability, fast open-source graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 6,174 | 🐛 706 | 🌐 Rust | 📅 2026-09-18 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,838 | 🐛 597 | 🌐 Java | 📅 2026-09-18 - A highly scalable distributed graph database
* [Apache Age](https://github.com/apache/age) ⭐ 4,828 | 🐛 251 | 🌐 C | 📅 2026-09-18 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,184 | 🐛 362 | 🌐 Java | 📅 2026-09-17 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,274 | 🐛 345 | 🌐 Go | 📅 2026-09-18 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 27,243 | 🐛 908 | 🌐 C | 📅 2026-09-18 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,868 | 🐛 1,812 | 🌐 Rust | 📅 2026-09-18 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,712 | 🐛 767 | 🌐 C++ | 📅 2026-09-18 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,036 | 🐛 112 | 🌐 Go | 📅 2026-09-10 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,433 | 🐛 250 | 🌐 C++ | 📅 2026-09-18 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,026 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,766 | 🐛 3,683 | 🌐 C++ | 📅 2026-09-18 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,098 | 🐛 532 | 🌐 Java | 📅 2026-09-18 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,558 | 🐛 410 | 🌐 Java | 📅 2026-09-18 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,170 | 🐛 336 | 🌐 Java | 📅 2026-09-17 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,426 | 🐛 409 | 🌐 C++ | 📅 2026-03-11 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,110 | 🐛 1,658 | 🌐 C++ | 📅 2026-09-18 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,761 | 🐛 69 | 🌐 Go | 📅 2026-09-08 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 77,931 | 🐛 6,077 | 🌐 Java | 📅 2026-09-18 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,328 | 🐛 308 | 🌐 Rust | 📅 2026-09-17 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,730 | 🐛 3,176 | 🌐 Java | 📅 2026-09-18 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,655 | 🐛 810 | 🌐 Rust | 📅 2026-09-18 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,283 | 🐛 213 | 🌐 Rust | 📅 2026-09-18 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,829 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,673 | 🐛 154 | 🌐 Java | 📅 2026-09-18 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,333 | 🐛 1,695 | 🌐 Rust | 📅 2026-09-18 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,368 | 🐛 711 | 🌐 Rust | 📅 2026-09-18 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,852 | 🐛 148 | 🌐 C# | 📅 2026-09-18 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,260 | 🐛 75 | 🌐 C++ | 📅 2026-09-17 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,155 | 🐛 1,022 | 🌐 Java | 📅 2026-09-18 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 315 | 🐛 1,329 | 🌐 Java | 📅 2026-09-18 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,749 | 🐛 2,185 | 🌐 Rust | 📅 2026-09-18 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,126 | 🐛 435 | 🌐 C | 📅 2026-09-17 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,547 | 🐛 391 | 🌐 C | 📅 2026-09-18 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,330 | 🐛 961 | 🌐 Java | 📅 2026-09-18 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,683 | 🐛 280 | 🌐 Rust | 📅 2026-09-18 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,401 | 🐛 753 | 🌐 Java | 📅 2026-09-18 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,564 | 🐛 8 | 🌐 Scala | 📅 2026-09-18 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,761 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,443 | 🐛 507 | 🌐 Rust | 📅 2026-09-18 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,043 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,914 | 🐛 9 | 🌐 C++ | 📅 2026-09-18 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 482 | 🐛 111 | 🌐 C | 📅 2026-09-18 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 49,960 | 🐛 7,811 | 🌐 C++ | 📅 2026-09-18 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 15,962 | 🐛 1,355 | 🌐 Java | 📅 2026-09-18 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,054 | 🐛 784 | 🌐 Java | 📅 2026-09-18 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,120 | 🐛 1,448 | 🌐 Java | 📅 2026-09-18 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,139 | 🐛 1,351 | 🌐 Java | 📅 2026-09-18 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,773 | 🐛 79 | 🌐 Java | 📅 2026-09-01 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 41,506 | 🐛 894 | 🌐 C++ | 📅 2026-09-18 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,323 | 🐛 2,242 | 🌐 Rust | 📅 2026-09-18 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,418 | 🐛 180 | 🌐 Rust | 📅 2026-09-18 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,900 | 🐛 42 | 🌐 Python | 📅 2026-09-17 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,023 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,242 | 🐛 125 | 🌐 C++ | 📅 2026-07-17 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,003 | 🐛 14 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 688 | 🐛 18 | 🌐 Rust | 📅 2025-11-09 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,663 | 🐛 225 | 🌐 Java | 📅 2026-09-18 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,440 | 🐛 207 | 🌐 Go | 📅 2026-09-18 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,235 | 🐛 322 | 🌐 C | 📅 2026-09-11 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 17,055 | 🐛 1,449 | 🌐 C++ | 📅 2026-09-18 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,289 | 🐛 131 | 🌐 Java | 📅 2026-09-18 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,139 | 🐛 2,548 | 🌐 C++ | 📅 2026-09-18 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 7,093 | 🐛 1,217 | 🌐 Rust | 📅 2026-09-18 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,306 | 🐛 242 | 🌐 Java | 📅 2026-09-15 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,203 | 🐛 330 | 🌐 Rust | 📅 2026-09-18 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,582 | 🐛 82 | 🌐 Thrift | 📅 2026-09-15 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 769 | 🐛 22 | 🌐 Java | 📅 2026-09-02 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,250 | 🐛 930 | 🌐 Java | 📅 2026-09-18 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,001 | 🐛 959 | 🌐 Scala | 📅 2026-09-18 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,259 | 🐛 2,882 | 🌐 Java | 📅 2026-09-18 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,404 | 🐛 761 | 🌐 Java | 📅 2026-09-18 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 399 | 🐛 89 | 🌐 Java | 📅 2026-09-18 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,315 | 🐛 167 | 🌐 Rust | 📅 2026-09-18 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,135 | 🐛 259 | 🌐 Python | 📅 2026-09-18 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 279 | 🐛 84 | 🌐 Rust | 📅 2026-09-18- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,238 | 🐛 187 | 🌐 Java | 📅 2026-09-18 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,181 | 🐛 49 | 🌐 Java | 📅 2026-09-16 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 22,087 | 🐛 2,456 | 🌐 Python | 📅 2026-09-18 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,655 | 🐛 738 | 🌐 Java | 📅 2026-09-18 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,331 | 🐛 39 | 🌐 Java | 📅 2026-09-18 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,233 | 🐛 31 | 🌐 Java | 📅 2026-09-18 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,871 | 🐛 435 | 🌐 Python | 📅 2026-09-18 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,626 | 🐛 148 | 🌐 Python | 📅 2026-09-18 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,271 | 🐛 142 | 🌐 Java | 📅 2026-07-31 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,500 | 🐛 23 | 🌐 Java | 📅 2026-09-16 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 977 | 🐛 259 | 🌐 Rust | 📅 2026-09-18 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 33,750 | 🐛 574 | 🌐 Java | 📅 2026-09-18 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,136 | 🐛 126 | 🌐 Java | 📅 2026-09-18 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,758 | 🐛 332 | 🌐 Go | 📅 2026-09-18 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,476 | 🐛 118 | 🌐 Java | 📅 2026-09-18 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,486 | 🐛 51 | 🌐 Go | 📅 2026-09-18 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,273 | 🐛 207 | 🌐 Go | 📅 2026-09-18 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,578 | 🐛 167 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 967 | 🐛 36 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,392 | 🐛 34 | 🌐 Go | 📅 2026-09-17 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,968 | 🐛 22 | 🌐 Go | 📅 2026-09-18 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 906 | 🐛 38 | 🌐 Go | 📅 2026-09-18 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,956 | 🐛 20 | 🌐 Go | 📅 2026-09-17 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,034 | 🐛 59 | 🌐 Scala | 📅 2026-06-26 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,520 | 🐛 166 | 🌐 Go | 📅 2026-09-18 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,083 | 🐛 45 | 🌐 TypeScript | 📅 2026-09-18 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,570 | 🐛 80 | 🌐 Java | 📅 2026-09-17 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,757 | 🐛 250 | 🌐 Java | 📅 2026-09-17 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,750 | 🐛 574 | 🌐 Java | 📅 2026-09-18 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,777 | 🐛 78 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,606 | 🐛 671 | 🌐 Java | 📅 2026-09-17 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,334 | 🐛 1,741 | 🌐 Java | 📅 2026-09-18 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,555 | 🐛 526 | 🌐 C++ | 📅 2026-08-22 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,789 | 🐛 57 | 🌐 Java | 📅 2026-09-18 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,443 | 🐛 109 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,673 | 🐛 192 | 🌐 Ruby | 📅 2026-09-18 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,012 | 🐛 596 | 🌐 Scala | 📅 2026-09-18 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,668 | 🐛 3,955 | 🌐 Java | 📅 2026-09-18 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,765 | 🐛 29 | 🌐 Java | 📅 2026-08-25 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,090 | 🐛 563 | 🌐 Rust | 📅 2026-09-18 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,663 | 🐛 225 | 🌐 Java | 📅 2026-09-18 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 519 | 🐛 76 | 🌐 Java | 📅 2026-08-24 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,341 | 🐛 378 | 🌐 Java | 📅 2026-09-18 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,279 | 🐛 903 | 🌐 Scala | 📅 2026-09-18 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,695 | 🐛 36 | 🌐 Java | 📅 2026-09-18 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,346 | 🐛 101 | 🌐 Python | 📅 2026-09-18 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,257 | 🐛 139 | 🌐 Rust | 📅 2026-08-30 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,037 | 🐛 126 | 🌐 Rust | 📅 2026-09-18 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,260 | 🐛 75 | 🌐 C++ | 📅 2026-09-17 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,136 | 🐛 150 | 🌐 Go | 📅 2026-09-18 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,051 | 🐛 38 | 🌐 Python | 📅 2026-06-20 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 845 | 🐛 44 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 44,012 | 🐛 596 | 🌐 Scala | 📅 2026-09-18 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 39,781 | 🐛 2,889 | 🌐 Rust | 📅 2026-09-18 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,139 | 🐛 2,548 | 🌐 C++ | 📅 2026-09-18 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,755 | 🐛 1,341 | 🌐 C++ | 📅 2026-09-18 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,508 | 🐛 552 | 🌐 Python | 📅 2026-04-01 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,661 | 🐛 545 | 🌐 Python | 📅 2026-09-17 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,775 | 🐛 389 | 🌐 Rust | 📅 2026-09-17 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 532 | 🐛 23 | 🌐 Python | 📅 2026-09-18 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 43,868 | 🐛 3,596 | 🌐 Python | 📅 2026-09-18 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,921 | 🐛 1,336 | 🌐 Python | 📅 2026-08-24 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,391 | 🐛 715 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,798 | 🐛 99 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,165 | 🐛 209 | 🌐 Python | 📅 2026-09-15 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,626 | 🐛 7 | 🌐 Python | 📅 2026-09-18 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 46,888 | 🐛 2,132 | 🌐 Python | 📅 2026-09-18 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 28,162 | 🐛 657 | 🌐 Java | 📅 2026-09-18 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 23,864 | 🐛 857 | 🌐 Python | 📅 2026-09-18 - A Python based workflow orchestration tool
* [Temporal](https://github.com/temporalio/temporal) ⭐ 23,159 | 🐛 992 | 🌐 Go | 📅 2026-09-18 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,775 | 🐛 177 | 🌐 Python | 📅 2026-07-18 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 17,973 | 🐛 870 | 🌐 Rust | 📅 2026-09-18 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 16,987 | 🐛 1,290 | 🌐 Go | 📅 2026-09-18 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,170 | 🐛 2,576 | 🌐 Python | 📅 2026-09-18 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,484 | 🐛 130 | 🌐 Java | 📅 2026-09-18 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,445 | 🐛 198 | 🌐 Go | 📅 2026-09-18 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,824 | 🐛 624 | 🌐 Python | 📅 2026-09-11 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,527 | 🐛 176 | 🌐 Go | 📅 2026-09-18 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,509 | 🐛 802 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,839 | 🐛 38 | 🌐 Java | 📅 2026-09-16 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 28,897 | 🐛 731 | 🌐 Python | 📅 2026-09-18 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,632 | 🐛 54 | 🌐 Python | 📅 2026-09-10 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,736 | 🐛 45 | 🌐 Go | 📅 2026-09-18 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 28,823 | 🐛 580 | 🌐 Python | 📅 2026-09-18 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,798 | 🐛 44 | 🌐 Python | 📅 2026-09-18 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,457 | 🐛 433 | 🌐 Python | 📅 2026-09-14 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,647 | 🐛 63 | 🌐 Scala | 📅 2026-09-16 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,426 | 🐛 199 | 🌐 Python | 📅 2026-09-18 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,465 | 🐛 578 | 🌐 Go | 📅 2026-09-18 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,878 | 🐛 212 | 🌐 Python | 📅 2026-09-14 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,505 | 🐛 479 | 🌐 Go | 📅 2026-09-02 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,532 | 🐛 443 | 🌐 Go | 📅 2026-09-17 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,820 | 🐛 101 | 🌐 Python | 📅 2026-09-18 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,511 | 🐛 165 | 🌐 Java | 📅 2026-09-17 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 13,866 | 🐛 1,563 | 🌐 Rust | 📅 2026-09-18 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,292 | 🐛 304 | 🌐 Python | 📅 2026-09-16 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,410 | 🐛 11 | 🌐 HTML | 📅 2026-09-17 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 127,814 | 🐛 3,075 | 🌐 Go | 📅 2026-09-18 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,663 | 🐛 225 | 🌐 Java | 📅 2026-09-18 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,367 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,029 | 🐛 16 | 🌐 Go | 📅 2026-09-18 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,313 | 🐛 107 | 🌐 Java | 📅 2026-09-16 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 504 | 🐛 58 | 🌐 Java | 📅 2026-09-17 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,076 | 🐛 137 | 🌐 Java | 📅 2026-09-18 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 605 | 🐛 36 | 🌐 C | 📅 2026-09-05 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 220 | 🐛 9 | 🌐 Java | 📅 2026-09-18 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,749 | 🐛 2,185 | 🌐 Rust | 📅 2026-09-18 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,235 | 🐛 851 | 🌐 Go | 📅 2026-09-18 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,064 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,897 | 🐛 221 | 🌐 Go | 📅 2026-09-18 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,119 | 🐛 902 | 🌐 Go | 📅 2026-09-18 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,740 | 🐛 819 | 🌐 Go | 📅 2026-09-18 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,385 | 🐛 109 | 🌐 Go Template | 📅 2026-09-18 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 76,803 | 🐛 3,310 | 🌐 TypeScript | 📅 2026-09-18 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,290 | 🐛 14,628 | 🌐 TypeScript | 📅 2026-09-18 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,333 | 🐛 149 | 🌐 TypeScript | 📅 2026-09-17 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,583 | 🐛 2,484 | 🌐 Rust | 📅 2026-09-18 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,075 | 🐛 92 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,814 | 🐛 408 | 🌐 Go | 📅 2026-09-18 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,946 | 🐛 2,255 | 🌐 Java | 📅 2026-09-18 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,588 | 🐛 134 | 🌐 Ruby | 📅 2026-09-15 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,114 | 🐛 760 | 🌐 C | 📅 2026-09-18 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,750 | 🐛 306 | 🌐 Go | 📅 2026-09-16 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,252 | 🐛 886 | 🌐 TypeScript | 📅 2026-09-18 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,731 | 🐛 1,314 | 🌐 Python | 📅 2026-09-18 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,116 | 🐛 851 | 🌐 Python | 📅 2026-09-18 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⚠️ Archived - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,282 | 🐛 253 | 🌐 Java | 📅 2026-09-15 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,141 | 🐛 164 | 🌐 Java | 📅 2026-09-18 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,428 | 🐛 136 | 🌐 Java | 📅 2026-09-14 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,252 | 🐛 886 | 🌐 TypeScript | 📅 2026-09-18 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,662 | 🐛 370 | 🌐 Java | 📅 2026-09-18 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 924 | 🐛 28 | 🌐 Java | 📅 2026-09-18 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,023 | 🐛 131 | 🌐 Java | 📅 2026-09-18 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,529 | 🐛 445 | 🌐 Java | 📅 2026-09-18 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,230 | 🐛 1,101 | 🌐 Java | 📅 2026-09-18 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,465 | 🐛 392 | 🌐 Java | 📅 2026-09-18 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,058 | 🐛 389 | 🌐 Java | 📅 2026-09-18 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,457 | 🐛 104 | 🌐 Rust | 📅 2026-09-18 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 74,833 | 🐛 624 | 🌐 Python | 📅 2026-09-18 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 49,334 | 🐛 4,417 | 🌐 Clojure | 📅 2026-09-18 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,800 | 🐛 805 | 🌐 Python | 📅 2026-09-03 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,142 | 🐛 1,107 | 🌐 TypeScript | 📅 2026-09-18 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 45,780 | 🐛 1,167 | 🌐 Python | 📅 2026-09-18 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,412 | 🐛 471 | 🌐 Python | 📅 2026-09-18 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 6,949 | 🐛 39 | 🌐 TypeScript | 📅 2026-09-18 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,353 | 🐛 4 | 🌐 Python | 📅 2026-09-14 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,791 | 🐛 37 | 🌐 Python | 📅 2026-09-18 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,383 | 🐛 47 | 🌐 Rust | 📅 2026-09-14 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,783 | 🐛 1,290 | 🌐 Python | 📅 2026-09-14 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,348 | 🐛 1,896 | 🌐 Jupyter Notebook | 📅 2026-09-17 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,473 | 🐛 669 | 🌐 Python | 📅 2026-09-17 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,656 | 🐛 60 | 🌐 Java | 📅 2026-09-17 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,289 | 🐛 237 | 🌐 TypeScript | 📅 2026-09-16 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,411 | 🐛 32 | 🌐 JavaScript | 📅 2026-09-18 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,739 | 🐛 2,971 | 🌐 Java | 📅 2026-09-18 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,254 | 🐛 2,759 | 🌐 Java | 📅 2026-09-18 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,023 | 🐛 131 | 🌐 Java | 📅 2026-09-18 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,141 | 🐛 190 | 🌐 Rust | 📅 2026-09-18 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,023 | 🐛 127 | 🌐 Java | 📅 2026-09-16 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,287 | 🐛 8 | 🌐 C++ | 📅 2026-09-18 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 20,862 | 🐛 1,189 | 🌐 Rust | 📅 2026-09-18 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,243 | 🐛 1,048 | 🌐 Java | 📅 2026-09-01 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,385 | 🐛 336 | 🌐 Rust | 📅 2026-09-18 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,413 | 🐛 177 | 🌐 Java | 📅 2026-09-13 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,600 | 🐛 998 | 🌐 Scala | 📅 2026-09-18 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 959 | 🐛 146 | 🌐 Scala | 📅 2026-09-01 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 46,156 | 🐛 1,452 | 🌐 Go | 📅 2026-09-18 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 34,664 | 🐛 736 | 🌐 Rust | 📅 2026-09-18 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,326 | 🐛 874 | 🌐 Rust | 📅 2026-09-18 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 23,068 | 🐛 16 | 🌐 C | 📅 2026-09-10 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,821 | 🐛 739 | 🌐 Go | 📅 2026-09-18 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,461 | 🐛 628 | 🌐 Rust | 📅 2026-09-18 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,240 | 🐛 67 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,093 | 🐛 251 | 🌐 Java | 📅 2026-09-18 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,031 | 🐛 196 | 🌐 Python | 📅 2026-09-03 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,728 | 🐛 147 | 🌐 Go | 📅 2026-09-16 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 43,868 | 🐛 3,596 | 🌐 Python | 📅 2026-09-18 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 28,024 | 🐛 2,119 | 🌐 Python | 📅 2026-09-18 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,861 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,870 | 🐛 1 | 📅 2026-08-21 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 11,005 | 🐛 140 | 🌐 Python | 📅 2026-09-18 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,618 | 🐛 433 | 🌐 Python | 📅 2026-09-18 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,273 | 🐛 502 | 🌐 Python | 📅 2026-09-14 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,852 | 🐛 219 | 🌐 Python | 📅 2026-09-07 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,308 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,239 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 156,338 | 🐛 1,109 | 🌐 TypeScript | 📅 2026-09-18 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 92,120 | 🐛 8,136 | 🌐 Python | 📅 2026-09-18 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 30,815 | 🐛 483 | 🌐 Python | 📅 2026-09-18 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,543 | 🐛 163 | 🌐 Python | 📅 2026-09-18 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,321 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-18._
