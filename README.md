# Awesome Open Source Data Engineering with stars

A curated list of open source tools used in analytics platforms and data engineering ecosystem
![Open Source Data Engineering Landscape 2025](https://github.com/user-attachments/assets/fe9e97a8-abd8-47a9-8429-15130055785c)

For more information about the above compiled landscape for 2025, please refer to the published blog post on [Pracdata.io](https://www.pracdata.io/p/open-source-data-engineering-landscape-2025)

## Table of contents

* [Storage Systems](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#storage-systems) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Data Lake Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-lake-platform) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Data Integration](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-integration) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Data Processing & Computation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-processing-and-computation) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Workflow Management & DataOps](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#workflow-management--dataops) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Data Infrastructure](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-infrastructure) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Metadata Management](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#metadata-management) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [Analytics & Visualisation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#analytics--visualisation) ⭐ 598 | 🐛 14 | 📅 2025-03-12
* [ML/AI Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#mlai-platform) ⭐ 598 | 🐛 14 | 📅 2025-03-12

## STORAGE SYSTEMS

### Relational DBMS

* [Supabase](https://github.com/supabase/supabase) ⭐ 108,093 | 🐛 1,280 | 🌐 TypeScript | 📅 2026-08-17 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,815 | 🐛 0 | 🌐 C | 📅 2026-08-17 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,383 | 🐛 36 | 🌐 C++ | 📅 2026-07-31 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,283 | 🐛 22 | 🌐 C | 📅 2026-08-17 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,108 | 🐛 452 | 🌐 C++ | 📅 2026-08-17 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,441 | 🐛 6,785 | 🌐 Go | 📅 2026-08-17 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,394 | 🐛 8,195 | 🌐 Go | 📅 2026-08-07 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 22,879 | 🐛 552 | 🌐 Rust | 📅 2026-05-25 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,775 | 🐛 324 | 🌐 Java | 📅 2026-08-17 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,701 | 🐛 1,065 | 🌐 C | 📅 2026-08-17 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,474 | 🐛 8,241 | 🌐 C | 📅 2026-08-17 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,244 | 🐛 584 | 🌐 C++ | 📅 2026-08-17 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,418 | 🐛 337 | 🌐 Java | 📅 2026-08-17 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 76,021 | 🐛 2,908 | 🌐 C | 📅 2026-08-17 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,009 | 🐛 299 | 🌐 C++ | 📅 2026-08-17 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,250 | 🐛 102 | 🌐 C | 📅 2026-07-10 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,270 | 🐛 88 | 🌐 Rust | 📅 2026-08-14 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,075 | 🐛 875 | 🌐 Java | 📅 2026-08-17 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,498 | 🐛 31 | 🌐 C++ | 📅 2026-08-17 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 26,995 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,572 | 🐛 16 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,042 | 🐛 447 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,936 | 🐛 369 | 🌐 Erlang | 📅 2026-08-17 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 3,988 | 🐛 68 | 🌐 C# | 📅 2026-08-17 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 32,899 | 🐛 743 | 🌐 Rust | 📅 2026-08-17 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,260 | 🐛 827 | 🌐 C++ | 📅 2026-08-17 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,172 | 🐛 948 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,980 | 🐛 357 | 🌐 Java | 📅 2026-08-17 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,773 | 🐛 94 | 🌐 Go | 📅 2026-08-16 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,075 | 🐛 228 | 🌐 Java | 📅 2026-08-07 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,057 | 🐛 93 | 🌐 Go | 📅 2026-08-16 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,348 | 🐛 681 | 🌐 C++ | 📅 2026-05-18 - A distributed, horizontal scalability, fast open-source graph database
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,829 | 🐛 598 | 🌐 Java | 📅 2026-07-23 - A highly scalable distributed graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 5,571 | 🐛 631 | 🌐 Rust | 📅 2026-08-17 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [Apache Age](https://github.com/apache/age) ⭐ 4,752 | 🐛 222 | 🌐 C | 📅 2026-08-15 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,152 | 🐛 392 | 🌐 Java | 📅 2026-08-17 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,123 | 🐛 317 | 🌐 Go | 📅 2026-08-15 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 26,906 | 🐛 864 | 🌐 C | 📅 2026-08-17 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,803 | 🐛 1,808 | 🌐 Rust | 📅 2026-08-17 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,608 | 🐛 769 | 🌐 C++ | 📅 2026-08-17 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,022 | 🐛 103 | 🌐 Go | 📅 2026-08-03 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,395 | 🐛 241 | 🌐 C++ | 📅 2026-08-12 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,027 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,710 | 🐛 3,565 | 🌐 C++ | 📅 2026-08-17 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,069 | 🐛 461 | 🌐 Java | 📅 2026-08-17 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,551 | 🐛 369 | 🌐 Java | 📅 2026-08-17 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,160 | 🐛 341 | 🌐 Java | 📅 2026-08-17 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,332 | 🐛 400 | 🌐 C++ | 📅 2026-03-11 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 31,972 | 🐛 1,616 | 🌐 C++ | 📅 2026-08-17 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,749 | 🐛 69 | 🌐 Go | 📅 2026-08-17 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 77,802 | 🐛 6,017 | 🌐 Java | 📅 2026-08-17 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 58,993 | 🐛 306 | 🌐 Rust | 📅 2026-08-14 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,535 | 🐛 3,082 | 🌐 Java | 📅 2026-08-17 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,501 | 🐛 802 | 🌐 Rust | 📅 2026-08-17 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,168 | 🐛 191 | 🌐 Rust | 📅 2026-08-17 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,829 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,659 | 🐛 177 | 🌐 Java | 📅 2026-08-17 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,266 | 🐛 1,574 | 🌐 Rust | 📅 2026-08-17 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,355 | 🐛 723 | 🌐 Rust | 📅 2026-08-17 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,841 | 🐛 148 | 🌐 C# | 📅 2026-08-17 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,240 | 🐛 80 | 🌐 C++ | 📅 2026-08-13 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,096 | 🐛 944 | 🌐 Java | 📅 2026-08-17 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 313 | 🐛 1,320 | 🌐 Java | 📅 2026-08-17 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,703 | 🐛 2,148 | 🌐 Rust | 📅 2026-08-17 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,065 | 🐛 446 | 🌐 C | 📅 2026-08-16 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,339 | 🐛 384 | 🌐 C | 📅 2026-08-17 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,260 | 🐛 921 | 🌐 Java | 📅 2026-08-17 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,549 | 🐛 222 | 🌐 Rust | 📅 2026-08-17 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,381 | 🐛 756 | 🌐 Java | 📅 2026-08-17 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,562 | 🐛 7 | 🌐 Scala | 📅 2026-08-13 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,762 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,414 | 🐛 544 | 🌐 Rust | 📅 2026-08-17 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,039 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,911 | 🐛 9 | 🌐 C++ | 📅 2026-08-17 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 475 | 🐛 104 | 🌐 C | 📅 2026-08-17 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 49,296 | 🐛 6,932 | 🌐 C++ | 📅 2026-08-17 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 15,785 | 🐛 1,235 | 🌐 C++ | 📅 2026-08-17 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,043 | 🐛 774 | 🌐 Java | 📅 2026-08-17 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,019 | 🐛 1,289 | 🌐 Java | 📅 2026-08-17 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,122 | 🐛 1,428 | 🌐 Java | 📅 2026-08-17 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,772 | 🐛 78 | 🌐 Java | 📅 2026-07-16 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 40,311 | 🐛 812 | 🌐 C++ | 📅 2026-08-17 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,153 | 🐛 2,077 | 🌐 Rust | 📅 2026-08-17 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,311 | 🐛 176 | 🌐 Rust | 📅 2026-08-17 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,870 | 🐛 36 | 🌐 Python | 📅 2026-08-17 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,020 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,193 | 🐛 113 | 🌐 C++ | 📅 2026-07-17 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,000 | 🐛 14 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 683 | 🐛 18 | 🌐 Rust | 📅 2025-11-09 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,632 | 🐛 201 | 🌐 Java | 📅 2026-08-17 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,329 | 🐛 192 | 🌐 Go | 📅 2026-08-17 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,220 | 🐛 292 | 🌐 C | 📅 2026-02-16 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 16,945 | 🐛 1,292 | 🌐 C++ | 📅 2026-08-17 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,258 | 🐛 129 | 🌐 Java | 📅 2026-08-17 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,029 | 🐛 2,565 | 🌐 C++ | 📅 2026-08-17 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 6,943 | 🐛 1,039 | 🌐 Rust | 📅 2026-08-17 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,297 | 🐛 210 | 🌐 Java | 📅 2026-08-16 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,141 | 🐛 360 | 🌐 Rust | 📅 2026-08-17 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,536 | 🐛 90 | 🌐 Thrift | 📅 2026-08-02 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 769 | 🐛 21 | 🌐 Java | 📅 2026-08-13 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,142 | 🐛 911 | 🌐 Java | 📅 2026-08-17 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 8,942 | 🐛 927 | 🌐 Scala | 📅 2026-08-17 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,214 | 🐛 2,945 | 🌐 Java | 📅 2026-08-17 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,374 | 🐛 704 | 🌐 Java | 📅 2026-08-17 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 395 | 🐛 78 | 🌐 Java | 📅 2026-08-14 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,284 | 🐛 213 | 🌐 Rust | 📅 2026-08-17 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,113 | 🐛 238 | 🌐 Python | 📅 2026-08-15 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 280 | 🐛 86 | 🌐 Rust | 📅 2026-08-15- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,202 | 🐛 169 | 🌐 Java | 📅 2026-08-17 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,165 | 🐛 57 | 🌐 Java | 📅 2026-08-17 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 21,904 | 🐛 2,341 | 🌐 Python | 📅 2026-08-17 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,560 | 🐛 662 | 🌐 Java | 📅 2026-08-17 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,289 | 🐛 36 | 🌐 Java | 📅 2026-08-17 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,198 | 🐛 38 | 🌐 Java | 📅 2026-08-17 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,747 | 🐛 420 | 🌐 Python | 📅 2026-08-17 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,594 | 🐛 150 | 🌐 Python | 📅 2026-08-17 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-07-31 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,496 | 🐛 11 | 🌐 Java | 📅 2026-08-14 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 960 | 🐛 263 | 🌐 Rust | 📅 2026-08-17 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 33,528 | 🐛 500 | 🌐 Java | 📅 2026-08-17 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,022 | 🐛 123 | 🌐 Java | 📅 2026-08-17 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,732 | 🐛 319 | 🌐 Go | 📅 2026-08-17 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,460 | 🐛 113 | 🌐 Java | 📅 2026-08-14 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,472 | 🐛 51 | 🌐 Go | 📅 2026-08-17 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,239 | 🐛 207 | 🌐 Go | 📅 2026-08-17 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,578 | 🐛 159 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 963 | 🐛 35 | 🌐 Java | 📅 2026-08-17 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,050 | 🐛 46 | 🌐 Go | 📅 2026-08-07 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,843 | 🐛 16 | 🌐 Go | 📅 2026-08-17 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 890 | 🐛 39 | 🌐 Go | 📅 2026-08-17 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,916 | 🐛 22 | 🌐 Go | 📅 2026-08-17 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,028 | 🐛 59 | 🌐 Scala | 📅 2026-06-26 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,481 | 🐛 164 | 🌐 Go | 📅 2026-08-17 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,033 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-17 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,566 | 🐛 79 | 🌐 Java | 📅 2026-08-01 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,746 | 🐛 269 | 🌐 Java | 📅 2026-08-17 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,528 | 🐛 500 | 🌐 Java | 📅 2026-08-17 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,768 | 🐛 77 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,557 | 🐛 566 | 🌐 Java | 📅 2026-08-16 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,314 | 🐛 1,727 | 🌐 Java | 📅 2026-08-17 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,457 | 🐛 616 | 🌐 C++ | 📅 2026-08-17 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,509 | 🐛 71 | 🌐 Java | 📅 2026-08-14 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,437 | 🐛 108 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,670 | 🐛 166 | 🌐 Ruby | 📅 2026-08-15 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 43,826 | 🐛 460 | 🌐 Scala | 📅 2026-08-17 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,645 | 🐛 3,981 | 🌐 Java | 📅 2026-08-17 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,747 | 🐛 224 | 🌐 Java | 📅 2026-07-25 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,043 | 🐛 510 | 🌐 Rust | 📅 2026-08-17 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,632 | 🐛 201 | 🌐 Java | 📅 2026-08-17 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 519 | 🐛 74 | 🌐 Java | 📅 2026-08-16 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,269 | 🐛 380 | 🌐 Java | 📅 2026-08-17 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,276 | 🐛 907 | 🌐 Scala | 📅 2026-08-17 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,698 | 🐛 38 | 🌐 Java | 📅 2026-08-11 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,306 | 🐛 102 | 🌐 Python | 📅 2026-08-17 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,242 | 🐛 140 | 🌐 Rust | 📅 2026-08-11 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 4,998 | 🐛 119 | 🌐 Rust | 📅 2026-08-11 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,240 | 🐛 80 | 🌐 C++ | 📅 2026-08-13 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,100 | 🐛 145 | 🌐 Go | 📅 2026-08-17 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,042 | 🐛 37 | 🌐 Python | 📅 2026-06-20 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 846 | 🐛 44 | 🌐 Java | 📅 2026-05-15 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 43,826 | 🐛 460 | 🌐 Scala | 📅 2026-08-17 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 39,375 | 🐛 2,848 | 🌐 Rust | 📅 2026-08-17 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,029 | 🐛 2,565 | 🌐 C++ | 📅 2026-08-17 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,729 | 🐛 1,324 | 🌐 C++ | 📅 2026-08-17 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,509 | 🐛 552 | 🌐 Python | 📅 2026-04-01 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,631 | 🐛 522 | 🌐 Python | 📅 2026-08-14 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,717 | 🐛 345 | 🌐 Rust | 📅 2026-08-17 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 528 | 🐛 21 | 🌐 Python | 📅 2026-08-15 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 43,537 | 🐛 3,506 | 🌐 Python | 📅 2026-08-17 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,891 | 🐛 1,309 | 🌐 Python | 📅 2026-08-17 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,391 | 🐛 713 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,802 | 🐛 100 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,091 | 🐛 213 | 🌐 Python | 📅 2026-08-17 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,536 | 🐛 2 | 🌐 Python | 📅 2026-08-17 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 46,514 | 🐛 1,870 | 🌐 Python | 📅 2026-08-17 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 27,839 | 🐛 545 | 🌐 Java | 📅 2026-08-17 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 23,631 | 🐛 866 | 🌐 Python | 📅 2026-08-17 - A Python based workflow orchestration tool
* [Temporal](https://github.com/temporalio/temporal) ⭐ 22,369 | 🐛 898 | 🌐 Go | 📅 2026-08-17 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,764 | 🐛 166 | 🌐 Python | 📅 2026-07-18 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 17,567 | 🐛 816 | 🌐 Rust | 📅 2026-08-17 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 16,907 | 🐛 1,258 | 🌐 Go | 📅 2026-08-17 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,012 | 🐛 2,590 | 🌐 Python | 📅 2026-08-14 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,430 | 🐛 143 | 🌐 Java | 📅 2026-08-12 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,404 | 🐛 185 | 🌐 Go | 📅 2026-08-14 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,804 | 🐛 619 | 🌐 Python | 📅 2026-08-13 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,209 | 🐛 161 | 🌐 Go | 📅 2026-08-17 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,506 | 🐛 801 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,823 | 🐛 34 | 🌐 Java | 📅 2026-08-11 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 28,788 | 🐛 801 | 🌐 Python | 📅 2026-08-17 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,609 | 🐛 60 | 🌐 Python | 📅 2026-08-01 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,726 | 🐛 48 | 🌐 Go | 📅 2026-08-11 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 28,561 | 🐛 579 | 🌐 Python | 📅 2026-08-17 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,713 | 🐛 39 | 🌐 Python | 📅 2026-08-17 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,433 | 🐛 452 | 🌐 Python | 📅 2026-08-17 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,640 | 🐛 70 | 🌐 Scala | 📅 2026-07-21 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,411 | 🐛 199 | 🌐 Python | 📅 2026-08-17 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,203 | 🐛 708 | 🌐 Go | 📅 2026-08-17 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,823 | 🐛 198 | 🌐 Python | 📅 2026-08-17 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,428 | 🐛 483 | 🌐 Go | 📅 2026-08-07 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,487 | 🐛 438 | 🌐 Go | 📅 2026-08-17 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,807 | 🐛 93 | 🌐 Python | 📅 2026-08-17 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,494 | 🐛 162 | 🌐 Java | 📅 2026-08-17 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 13,650 | 🐛 1,524 | 🌐 Rust | 📅 2026-08-17 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,245 | 🐛 268 | 🌐 Python | 📅 2026-08-12 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,390 | 🐛 25 | 🌐 HTML | 📅 2026-08-17 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 124,520 | 🐛 2,932 | 🌐 Go | 📅 2026-08-17 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,632 | 🐛 201 | 🌐 Java | 📅 2026-08-17 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,367 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,022 | 🐛 14 | 🌐 Go | 📅 2026-08-17 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,310 | 🐛 150 | 🌐 Java | 📅 2026-08-17 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 503 | 🐛 55 | 🌐 Java | 📅 2026-08-13 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,070 | 🐛 134 | 🌐 Java | 📅 2026-08-17 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 601 | 🐛 36 | 🌐 C | 📅 2026-08-08 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 219 | 🐛 8 | 🌐 Java | 📅 2026-08-17 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,703 | 🐛 2,148 | 🌐 Rust | 📅 2026-08-17 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,210 | 🐛 814 | 🌐 Go | 📅 2026-08-17 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,068 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,892 | 🐛 220 | 🌐 Go | 📅 2026-08-17 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 65,697 | 🐛 886 | 🌐 Go | 📅 2026-08-17 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,551 | 🐛 765 | 🌐 Go | 📅 2026-08-17 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,275 | 🐛 107 | 🌐 Go Template | 📅 2026-08-17 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 76,250 | 🐛 3,356 | 🌐 TypeScript | 📅 2026-08-17 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,246 | 🐛 14,256 | 🌐 TypeScript | 📅 2026-08-17 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,318 | 🐛 152 | 🌐 TypeScript | 📅 2026-08-17 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,382 | 🐛 2,516 | 🌐 Rust | 📅 2026-08-17 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,073 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,757 | 🐛 385 | 🌐 Go | 📅 2026-08-17 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,921 | 🐛 2,249 | 🌐 Java | 📅 2026-08-17 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,580 | 🐛 137 | 🌐 Ruby | 📅 2026-08-17 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,038 | 🐛 762 | 🌐 C | 📅 2026-08-17 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,681 | 🐛 292 | 🌐 Go | 📅 2026-08-11 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 14,896 | 🐛 866 | 🌐 TypeScript | 📅 2026-08-17 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,537 | 🐛 1,228 | 🌐 Python | 📅 2026-08-17 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,096 | 🐛 833 | 🌐 Python | 📅 2026-08-17 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⭐ 4,779 | 🐛 64 | 🌐 Python | 📅 2026-08-01 - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,260 | 🐛 249 | 🌐 Java | 📅 2026-08-11 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,132 | 🐛 147 | 🌐 Java | 📅 2026-08-13 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,422 | 🐛 123 | 🌐 Java | 📅 2026-07-08 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 14,896 | 🐛 866 | 🌐 TypeScript | 📅 2026-08-17 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,604 | 🐛 347 | 🌐 Java | 📅 2026-08-17 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 920 | 🐛 50 | 🌐 Java | 📅 2026-08-17 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,009 | 🐛 97 | 🌐 Java | 📅 2026-08-17 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,493 | 🐛 438 | 🌐 Java | 📅 2026-08-17 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,182 | 🐛 1,042 | 🌐 Java | 📅 2026-08-17 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,461 | 🐛 393 | 🌐 Java | 📅 2026-08-17 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,034 | 🐛 367 | 🌐 Java | 📅 2026-08-17 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,420 | 🐛 105 | 🌐 Rust | 📅 2026-08-17 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 74,288 | 🐛 611 | 🌐 Python | 📅 2026-08-17 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 48,805 | 🐛 4,366 | 🌐 Clojure | 📅 2026-08-17 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,750 | 🐛 797 | 🌐 Python | 📅 2026-08-10 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,055 | 🐛 1,271 | 🌐 TypeScript | 📅 2026-08-17 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 45,557 | 🐛 1,200 | 🌐 Python | 📅 2026-08-17 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,373 | 🐛 537 | 🌐 Python | 📅 2026-08-17 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 6,858 | 🐛 272 | 🌐 JavaScript | 📅 2026-08-17 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,348 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,776 | 🐛 39 | 🌐 Python | 📅 2026-08-16 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,375 | 🐛 48 | 🌐 Rust | 📅 2026-08-15 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,771 | 🐛 1,294 | 🌐 Python | 📅 2026-08-07 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,304 | 🐛 1,908 | 🌐 Jupyter Notebook | 📅 2026-08-17 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,383 | 🐛 708 | 🌐 Python | 📅 2026-08-14 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,652 | 🐛 67 | 🌐 Java | 📅 2026-08-16 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,275 | 🐛 236 | 🌐 TypeScript | 📅 2026-08-11 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,409 | 🐛 36 | 🌐 JavaScript | 📅 2026-08-17 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,717 | 🐛 2,959 | 🌐 Java | 📅 2026-08-17 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,151 | 🐛 2,711 | 🌐 Java | 📅 2026-08-17 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,009 | 🐛 97 | 🌐 Java | 📅 2026-08-17 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,111 | 🐛 193 | 🌐 Rust | 📅 2026-08-17 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,022 | 🐛 129 | 🌐 Java | 📅 2026-08-11 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,282 | 🐛 8 | 🌐 C++ | 📅 2026-08-17 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 20,653 | 🐛 1,110 | 🌐 Rust | 📅 2026-08-17 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,227 | 🐛 1,047 | 🌐 Java | 📅 2025-04-29 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,321 | 🐛 311 | 🌐 Rust | 📅 2026-08-17 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,405 | 🐛 175 | 🌐 Java | 📅 2026-08-12 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,586 | 🐛 984 | 🌐 Scala | 📅 2026-08-17 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 956 | 🐛 140 | 🌐 Scala | 📅 2026-08-12 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 45,666 | 🐛 1,281 | 🌐 Go | 📅 2026-08-17 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 34,029 | 🐛 705 | 🌐 Rust | 📅 2026-08-17 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,077 | 🐛 792 | 🌐 Rust | 📅 2026-08-17 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 22,656 | 🐛 14 | 🌐 C | 📅 2026-08-15 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,734 | 🐛 693 | 🌐 Go | 📅 2026-08-17 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,170 | 🐛 622 | 🌐 Rust | 📅 2026-08-17 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,224 | 🐛 63 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,052 | 🐛 254 | 🌐 Java | 📅 2026-08-17 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,022 | 🐛 191 | 🌐 Python | 📅 2026-08-08 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,716 | 🐛 150 | 🌐 Go | 📅 2026-08-17 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 43,537 | 🐛 3,506 | 🌐 Python | 📅 2026-08-17 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 27,544 | 🐛 2,039 | 🌐 Python | 📅 2026-08-17 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,862 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,816 | 🐛 0 | 📅 2026-07-10 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 10,955 | 🐛 151 | 🌐 Python | 📅 2026-08-17 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,502 | 🐛 370 | 🌐 Python | 📅 2026-08-17 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,223 | 🐛 480 | 🌐 Python | 📅 2026-08-17 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,788 | 🐛 207 | 🌐 Python | 📅 2026-08-03 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,304 | 🐛 939 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,234 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 152,712 | 🐛 1,007 | 🌐 TypeScript | 📅 2026-08-17 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 89,273 | 🐛 6,668 | 🌐 Python | 📅 2026-08-17 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 30,079 | 🐛 383 | 🌐 Python | 📅 2026-08-17 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,234 | 🐛 104 | 🌐 Python | 📅 2026-08-17 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,313 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
