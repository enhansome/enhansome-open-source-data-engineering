# Awesome Open Source Data Engineering with stars

A curated list of open source tools used in analytics platforms and data engineering ecosystem
![Open Source Data Engineering Landscape 2025](https://github.com/user-attachments/assets/fe9e97a8-abd8-47a9-8429-15130055785c)

For more information about the above compiled landscape for 2025, please refer to the published blog post on [Pracdata.io](https://www.pracdata.io/p/open-source-data-engineering-landscape-2025)

## Table of contents

* [Storage Systems](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#storage-systems) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Data Lake Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-lake-platform) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Data Integration](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-integration) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Data Processing & Computation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-processing-and-computation) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Workflow Management & DataOps](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#workflow-management--dataops) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Data Infrastructure](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-infrastructure) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Metadata Management](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#metadata-management) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [Analytics & Visualisation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#analytics--visualisation) ⭐ 600 | 🐛 17 | 📅 2025-03-12
* [ML/AI Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#mlai-platform) ⭐ 600 | 🐛 17 | 📅 2025-03-12

## STORAGE SYSTEMS

### Relational DBMS

* [Supabase](https://github.com/supabase/supabase) ⭐ 108,503 | 🐛 1,039 | 🌐 TypeScript | 📅 2026-08-28 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,919 | 🐛 0 | 🌐 C | 📅 2026-08-28 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,406 | 🐛 42 | 🌐 C++ | 📅 2026-08-27 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,356 | 🐛 23 | 🌐 C | 📅 2026-08-27 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,149 | 🐛 475 | 🌐 C++ | 📅 2026-08-28 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,478 | 🐛 6,843 | 🌐 Go | 📅 2026-08-28 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,428 | 🐛 8,345 | 🌐 Go | 📅 2026-08-26 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 22,974 | 🐛 557 | 🌐 Rust | 📅 2026-05-25 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,790 | 🐛 217 | 🌐 Java | 📅 2026-08-28 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,733 | 🐛 1,064 | 🌐 C | 📅 2026-08-27 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,501 | 🐛 8,322 | 🌐 C | 📅 2026-08-28 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,258 | 🐛 585 | 🌐 C++ | 📅 2026-08-28 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,429 | 🐛 321 | 🌐 Java | 📅 2026-08-28 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 76,126 | 🐛 2,918 | 🌐 C | 📅 2026-08-27 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,048 | 🐛 300 | 🌐 C++ | 📅 2026-08-27 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,259 | 🐛 103 | 🌐 C | 📅 2026-07-10 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,272 | 🐛 100 | 🌐 Rust | 📅 2026-08-27 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,079 | 🐛 878 | 🌐 Java | 📅 2026-08-27 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,511 | 🐛 32 | 🌐 C++ | 📅 2026-08-28 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 26,994 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,576 | 🐛 16 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,057 | 🐛 447 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,943 | 🐛 368 | 🌐 Erlang | 📅 2026-08-27 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 3,993 | 🐛 71 | 🌐 C# | 📅 2026-08-27 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 32,948 | 🐛 744 | 🌐 Rust | 📅 2026-08-21 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,266 | 🐛 832 | 🌐 C++ | 📅 2026-08-28 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,170 | 🐛 948 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,983 | 🐛 356 | 🌐 Java | 📅 2026-08-26 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,780 | 🐛 96 | 🌐 Go | 📅 2026-08-27 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,152 | 🐛 241 | 🌐 Java | 📅 2026-08-24 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,062 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,367 | 🐛 678 | 🌐 C++ | 📅 2026-05-18 - A distributed, horizontal scalability, fast open-source graph database
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,829 | 🐛 598 | 🌐 Java | 📅 2026-08-18 - A highly scalable distributed graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 5,666 | 🐛 634 | 🌐 Rust | 📅 2026-08-27 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [Apache Age](https://github.com/apache/age) ⭐ 4,783 | 🐛 239 | 🌐 C | 📅 2026-08-26 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,158 | 🐛 390 | 🌐 Java | 📅 2026-08-26 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,193 | 🐛 329 | 🌐 Go | 📅 2026-08-27 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 26,995 | 🐛 885 | 🌐 C | 📅 2026-08-27 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,816 | 🐛 1,798 | 🌐 Rust | 📅 2026-08-28 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,649 | 🐛 764 | 🌐 C++ | 📅 2026-08-28 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,023 | 🐛 104 | 🌐 Go | 📅 2026-08-24 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,405 | 🐛 242 | 🌐 C++ | 📅 2026-08-26 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,027 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,723 | 🐛 3,625 | 🌐 C++ | 📅 2026-08-28 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,083 | 🐛 474 | 🌐 Java | 📅 2026-08-28 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,553 | 🐛 377 | 🌐 Java | 📅 2026-08-27 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,163 | 🐛 337 | 🌐 Java | 📅 2026-08-25 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,367 | 🐛 402 | 🌐 C++ | 📅 2026-03-11 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,020 | 🐛 1,627 | 🌐 C++ | 📅 2026-08-27 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,760 | 🐛 66 | 🌐 Go | 📅 2026-08-28 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 77,872 | 🐛 5,936 | 🌐 Java | 📅 2026-08-28 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,108 | 🐛 318 | 🌐 Rust | 📅 2026-08-27 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,590 | 🐛 3,135 | 🌐 Java | 📅 2026-08-27 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,552 | 🐛 804 | 🌐 Rust | 📅 2026-08-27 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,204 | 🐛 188 | 🌐 Rust | 📅 2026-08-28 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,829 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,669 | 🐛 164 | 🌐 Java | 📅 2026-08-28 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,292 | 🐛 1,616 | 🌐 Rust | 📅 2026-08-28 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,363 | 🐛 667 | 🌐 Rust | 📅 2026-08-28 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,848 | 🐛 151 | 🌐 C# | 📅 2026-08-28 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,248 | 🐛 80 | 🌐 C++ | 📅 2026-08-13 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,114 | 🐛 964 | 🌐 Java | 📅 2026-08-28 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 315 | 🐛 1,324 | 🌐 Java | 📅 2026-08-28 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,723 | 🐛 2,157 | 🌐 Rust | 📅 2026-08-25 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,090 | 🐛 450 | 🌐 C | 📅 2026-08-24 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,434 | 🐛 398 | 🌐 C | 📅 2026-08-27 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,284 | 🐛 938 | 🌐 Java | 📅 2026-08-27 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,578 | 🐛 241 | 🌐 Rust | 📅 2026-08-28 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,383 | 🐛 725 | 🌐 Java | 📅 2026-08-28 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,564 | 🐛 8 | 🌐 Scala | 📅 2026-08-28 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,762 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,424 | 🐛 563 | 🌐 Rust | 📅 2026-08-28 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,039 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,913 | 🐛 9 | 🌐 C++ | 📅 2026-08-26 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 477 | 🐛 110 | 🌐 C | 📅 2026-08-27 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 49,497 | 🐛 7,192 | 🌐 C++ | 📅 2026-08-28 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 15,828 | 🐛 1,241 | 🌐 C++ | 📅 2026-08-28 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,046 | 🐛 782 | 🌐 Java | 📅 2026-08-28 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,048 | 🐛 1,326 | 🌐 Java | 📅 2026-08-28 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,128 | 🐛 1,374 | 🌐 Java | 📅 2026-08-27 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,774 | 🐛 79 | 🌐 Java | 📅 2026-07-16 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 40,748 | 🐛 784 | 🌐 C++ | 📅 2026-08-27 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,211 | 🐛 2,108 | 🌐 Rust | 📅 2026-08-28 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,362 | 🐛 184 | 🌐 Rust | 📅 2026-08-27 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,881 | 🐛 38 | 🌐 Python | 📅 2026-08-27 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,021 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,212 | 🐛 119 | 🌐 C++ | 📅 2026-07-17 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,003 | 🐛 14 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 685 | 🐛 18 | 🌐 Rust | 📅 2025-11-09 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,639 | 🐛 205 | 🌐 Java | 📅 2026-08-27 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,366 | 🐛 194 | 🌐 Go | 📅 2026-08-28 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,220 | 🐛 280 | 🌐 C | 📅 2026-08-28 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 16,972 | 🐛 1,296 | 🌐 C++ | 📅 2026-08-28 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,268 | 🐛 126 | 🌐 Java | 📅 2026-08-27 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,068 | 🐛 2,585 | 🌐 C++ | 📅 2026-08-28 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 6,980 | 🐛 1,065 | 🌐 Rust | 📅 2026-08-28 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,301 | 🐛 229 | 🌐 Java | 📅 2026-08-27 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,158 | 🐛 382 | 🌐 Rust | 📅 2026-08-28 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,556 | 🐛 87 | 🌐 Thrift | 📅 2026-08-27 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 770 | 🐛 21 | 🌐 Java | 📅 2026-08-13 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,179 | 🐛 906 | 🌐 Java | 📅 2026-08-28 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 8,962 | 🐛 938 | 🌐 Scala | 📅 2026-08-28 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,224 | 🐛 2,852 | 🌐 Java | 📅 2026-08-28 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,385 | 🐛 723 | 🌐 Java | 📅 2026-08-28 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 397 | 🐛 79 | 🌐 Java | 📅 2026-08-28 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,290 | 🐛 172 | 🌐 Rust | 📅 2026-08-27 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,122 | 🐛 246 | 🌐 Python | 📅 2026-08-25 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 280 | 🐛 101 | 🌐 Rust | 📅 2026-08-15- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,208 | 🐛 186 | 🌐 Java | 📅 2026-08-26 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,169 | 🐛 48 | 🌐 Java | 📅 2026-08-27 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 21,967 | 🐛 2,350 | 🌐 Python | 📅 2026-08-28 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,596 | 🐛 671 | 🌐 Java | 📅 2026-08-28 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,301 | 🐛 68 | 🌐 Java | 📅 2026-08-27 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,210 | 🐛 35 | 🌐 Java | 📅 2026-08-27 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,784 | 🐛 415 | 🌐 Python | 📅 2026-08-27 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,613 | 🐛 145 | 🌐 Python | 📅 2026-08-27 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-07-31 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,497 | 🐛 9 | 🌐 Java | 📅 2026-08-27 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 964 | 🐛 255 | 🌐 Rust | 📅 2026-08-27 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 33,637 | 🐛 525 | 🌐 Java | 📅 2026-08-28 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,052 | 🐛 99 | 🌐 Java | 📅 2026-08-27 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,737 | 🐛 326 | 🌐 Go | 📅 2026-08-28 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,468 | 🐛 106 | 🌐 Java | 📅 2026-08-27 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,477 | 🐛 52 | 🌐 Go | 📅 2026-08-27 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,254 | 🐛 198 | 🌐 Go | 📅 2026-08-28 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,580 | 🐛 161 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 966 | 🐛 36 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,218 | 🐛 50 | 🌐 Go | 📅 2026-08-26 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,885 | 🐛 16 | 🌐 Go | 📅 2026-08-27 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 894 | 🐛 44 | 🌐 Go | 📅 2026-08-27 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,935 | 🐛 16 | 🌐 Go | 📅 2026-08-24 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,030 | 🐛 59 | 🌐 Scala | 📅 2026-06-26 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,499 | 🐛 167 | 🌐 Go | 📅 2026-08-27 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,047 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-27 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,569 | 🐛 79 | 🌐 Java | 📅 2026-08-25 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,747 | 🐛 270 | 🌐 Java | 📅 2026-08-27 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,637 | 🐛 525 | 🌐 Java | 📅 2026-08-28 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,774 | 🐛 77 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,573 | 🐛 579 | 🌐 Java | 📅 2026-08-26 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,316 | 🐛 1,736 | 🌐 Java | 📅 2026-08-28 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,495 | 🐛 549 | 🌐 C++ | 📅 2026-08-22 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,582 | 🐛 56 | 🌐 Java | 📅 2026-08-27 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,439 | 🐛 108 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,671 | 🐛 174 | 🌐 Ruby | 📅 2026-08-28 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 43,894 | 🐛 498 | 🌐 Scala | 📅 2026-08-28 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,653 | 🐛 3,967 | 🌐 Java | 📅 2026-08-28 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,754 | 🐛 226 | 🌐 Java | 📅 2026-08-25 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,067 | 🐛 537 | 🌐 Rust | 📅 2026-08-28 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,639 | 🐛 205 | 🌐 Java | 📅 2026-08-27 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 519 | 🐛 73 | 🌐 Java | 📅 2026-08-24 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,298 | 🐛 368 | 🌐 Java | 📅 2026-08-28 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,276 | 🐛 901 | 🌐 Scala | 📅 2026-08-26 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,698 | 🐛 36 | 🌐 Java | 📅 2026-08-27 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,318 | 🐛 105 | 🌐 Python | 📅 2026-08-27 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,248 | 🐛 140 | 🌐 Rust | 📅 2026-08-25 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,018 | 🐛 121 | 🌐 Rust | 📅 2026-08-20 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,248 | 🐛 80 | 🌐 C++ | 📅 2026-08-13 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,112 | 🐛 152 | 🌐 Go | 📅 2026-08-26 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,047 | 🐛 37 | 🌐 Python | 📅 2026-06-20 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 846 | 🐛 43 | 🌐 Java | 📅 2026-08-20 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 43,894 | 🐛 498 | 🌐 Scala | 📅 2026-08-28 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 39,524 | 🐛 2,866 | 🌐 Rust | 📅 2026-08-27 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,068 | 🐛 2,585 | 🌐 C++ | 📅 2026-08-28 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,737 | 🐛 1,311 | 🌐 C++ | 📅 2026-08-28 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,508 | 🐛 552 | 🌐 Python | 📅 2026-04-01 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,646 | 🐛 528 | 🌐 Python | 📅 2026-08-26 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,731 | 🐛 390 | 🌐 Rust | 📅 2026-08-26 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 533 | 🐛 21 | 🌐 Python | 📅 2026-08-27 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 43,633 | 🐛 3,536 | 🌐 Python | 📅 2026-08-28 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,898 | 🐛 1,314 | 🌐 Python | 📅 2026-08-24 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,392 | 🐛 715 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,799 | 🐛 99 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,116 | 🐛 211 | 🌐 Python | 📅 2026-08-26 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,575 | 🐛 3 | 🌐 Python | 📅 2026-08-27 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 46,623 | 🐛 1,973 | 🌐 Python | 📅 2026-08-27 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 27,941 | 🐛 684 | 🌐 Java | 📅 2026-08-27 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 23,700 | 🐛 857 | 🌐 Python | 📅 2026-08-27 - A Python based workflow orchestration tool
* [Temporal](https://github.com/temporalio/temporal) ⭐ 22,573 | 🐛 928 | 🌐 Go | 📅 2026-08-28 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,767 | 🐛 170 | 🌐 Python | 📅 2026-07-18 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 17,704 | 🐛 837 | 🌐 Rust | 📅 2026-08-28 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 16,943 | 🐛 1,254 | 🌐 Go | 📅 2026-08-27 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,068 | 🐛 2,587 | 🌐 Python | 📅 2026-08-28 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,450 | 🐛 143 | 🌐 Java | 📅 2026-08-26 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,421 | 🐛 203 | 🌐 Go | 📅 2026-08-27 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,814 | 🐛 620 | 🌐 Python | 📅 2026-08-13 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,284 | 🐛 165 | 🌐 Go | 📅 2026-08-28 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,508 | 🐛 801 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,830 | 🐛 57 | 🌐 Java | 📅 2026-08-26 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 28,830 | 🐛 754 | 🌐 Python | 📅 2026-08-27 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,616 | 🐛 58 | 🌐 Python | 📅 2026-08-24 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,731 | 🐛 41 | 🌐 Go | 📅 2026-08-27 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 28,647 | 🐛 577 | 🌐 Python | 📅 2026-08-27 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,743 | 🐛 40 | 🌐 Python | 📅 2026-08-28 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,443 | 🐛 446 | 🌐 Python | 📅 2026-08-27 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,643 | 🐛 68 | 🌐 Scala | 📅 2026-07-21 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,419 | 🐛 198 | 🌐 Python | 📅 2026-08-27 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,286 | 🐛 703 | 🌐 Go | 📅 2026-08-28 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,847 | 🐛 201 | 🌐 Python | 📅 2026-08-24 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,445 | 🐛 479 | 🌐 Go | 📅 2026-08-27 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,498 | 🐛 439 | 🌐 Go | 📅 2026-08-19 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,810 | 🐛 96 | 🌐 Python | 📅 2026-08-28 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,497 | 🐛 166 | 🌐 Java | 📅 2026-08-27 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 13,703 | 🐛 1,561 | 🌐 Rust | 📅 2026-08-27 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,258 | 🐛 275 | 🌐 Python | 📅 2026-08-28 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,400 | 🐛 24 | 🌐 HTML | 📅 2026-08-27 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 125,307 | 🐛 2,971 | 🌐 Go | 📅 2026-08-28 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,639 | 🐛 205 | 🌐 Java | 📅 2026-08-27 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,367 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,025 | 🐛 12 | 🌐 Go | 📅 2026-08-27 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,311 | 🐛 142 | 🌐 Java | 📅 2026-08-28 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 504 | 🐛 56 | 🌐 Java | 📅 2026-08-24 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,073 | 🐛 131 | 🌐 Java | 📅 2026-08-27 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 601 | 🐛 37 | 🌐 C | 📅 2026-08-17 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 219 | 🐛 10 | 🌐 Java | 📅 2026-08-27 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,723 | 🐛 2,157 | 🌐 Rust | 📅 2026-08-25 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,217 | 🐛 810 | 🌐 Go | 📅 2026-08-28 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,065 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,895 | 🐛 225 | 🌐 Go | 📅 2026-08-17 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 65,866 | 🐛 887 | 🌐 Go | 📅 2026-08-28 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,604 | 🐛 781 | 🌐 Go | 📅 2026-08-28 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,315 | 🐛 108 | 🌐 Go Template | 📅 2026-08-27 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 76,459 | 🐛 3,327 | 🌐 TypeScript | 📅 2026-08-28 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,265 | 🐛 14,291 | 🌐 TypeScript | 📅 2026-08-28 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,325 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-27 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,469 | 🐛 2,518 | 🌐 Rust | 📅 2026-08-27 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,076 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,775 | 🐛 424 | 🌐 Go | 📅 2026-08-26 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,927 | 🐛 2,257 | 🌐 Java | 📅 2026-08-27 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,581 | 🐛 136 | 🌐 Ruby | 📅 2026-08-24 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,065 | 🐛 785 | 🌐 C | 📅 2026-08-27 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,708 | 🐛 296 | 🌐 Go | 📅 2026-08-26 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,006 | 🐛 845 | 🌐 TypeScript | 📅 2026-08-28 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,599 | 🐛 1,260 | 🌐 Python | 📅 2026-08-28 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,106 | 🐛 836 | 🌐 Python | 📅 2026-08-27 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⭐ 4,783 | 🐛 66 | 🌐 Python | 📅 2026-08-20 - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,268 | 🐛 250 | 🌐 Java | 📅 2026-08-26 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,138 | 🐛 157 | 🌐 Java | 📅 2026-08-27 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,426 | 🐛 125 | 🌐 Java | 📅 2026-07-08 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,006 | 🐛 845 | 🌐 TypeScript | 📅 2026-08-28 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,629 | 🐛 349 | 🌐 Java | 📅 2026-08-26 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 921 | 🐛 41 | 🌐 Java | 📅 2026-08-27 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,015 | 🐛 107 | 🌐 Java | 📅 2026-08-27 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,501 | 🐛 420 | 🌐 Java | 📅 2026-08-26 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,188 | 🐛 1,064 | 🌐 Java | 📅 2026-08-28 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,463 | 🐛 391 | 🌐 Java | 📅 2026-08-28 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,043 | 🐛 374 | 🌐 Java | 📅 2026-08-28 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,426 | 🐛 109 | 🌐 Rust | 📅 2026-08-27 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 74,499 | 🐛 626 | 🌐 Python | 📅 2026-08-28 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 48,967 | 🐛 4,485 | 🌐 Clojure | 📅 2026-08-28 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,766 | 🐛 802 | 🌐 Python | 📅 2026-08-18 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,096 | 🐛 1,030 | 🌐 TypeScript | 📅 2026-08-28 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 45,624 | 🐛 1,196 | 🌐 Python | 📅 2026-08-28 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,388 | 🐛 536 | 🌐 Python | 📅 2026-08-27 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 6,886 | 🐛 29 | 🌐 TypeScript | 📅 2026-08-26 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,351 | 🐛 4 | 🌐 Python | 📅 2026-08-27 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,783 | 🐛 43 | 🌐 Python | 📅 2026-08-28 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,377 | 🐛 47 | 🌐 Rust | 📅 2026-08-22 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,774 | 🐛 1,277 | 🌐 Python | 📅 2026-08-26 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,326 | 🐛 1,899 | 🌐 Jupyter Notebook | 📅 2026-08-24 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,413 | 🐛 710 | 🌐 Python | 📅 2026-08-14 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,655 | 🐛 61 | 🌐 Java | 📅 2026-08-26 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,280 | 🐛 237 | 🌐 TypeScript | 📅 2026-08-20 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,410 | 🐛 34 | 🌐 JavaScript | 📅 2026-08-27 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,724 | 🐛 2,948 | 🌐 Java | 📅 2026-08-27 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,188 | 🐛 2,719 | 🌐 Java | 📅 2026-08-28 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,015 | 🐛 107 | 🌐 Java | 📅 2026-08-27 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,118 | 🐛 201 | 🌐 Rust | 📅 2026-08-27 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,022 | 🐛 126 | 🌐 Java | 📅 2026-08-25 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,285 | 🐛 8 | 🌐 C++ | 📅 2026-08-27 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 20,727 | 🐛 1,141 | 🌐 Rust | 📅 2026-08-28 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,231 | 🐛 1,048 | 🌐 Java | 📅 2025-04-29 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,348 | 🐛 318 | 🌐 Rust | 📅 2026-08-27 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,406 | 🐛 174 | 🌐 Java | 📅 2026-08-19 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,592 | 🐛 978 | 🌐 Scala | 📅 2026-08-28 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 958 | 🐛 142 | 🌐 Scala | 📅 2026-08-28 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 45,838 | 🐛 1,331 | 🌐 Go | 📅 2026-08-28 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 34,231 | 🐛 711 | 🌐 Rust | 📅 2026-08-28 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,168 | 🐛 806 | 🌐 Rust | 📅 2026-08-27 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 22,787 | 🐛 14 | 🌐 C | 📅 2026-08-20 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,757 | 🐛 692 | 🌐 Go | 📅 2026-08-27 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,298 | 🐛 603 | 🌐 Rust | 📅 2026-08-28 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,230 | 🐛 66 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,072 | 🐛 250 | 🌐 Java | 📅 2026-08-27 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,029 | 🐛 194 | 🌐 Python | 📅 2026-08-08 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,719 | 🐛 148 | 🌐 Go | 📅 2026-08-28 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 43,633 | 🐛 3,536 | 🌐 Python | 📅 2026-08-28 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 27,701 | 🐛 2,054 | 🌐 Python | 📅 2026-08-28 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,860 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,835 | 🐛 0 | 📅 2026-08-21 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 10,974 | 🐛 143 | 🌐 Python | 📅 2026-08-27 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,531 | 🐛 389 | 🌐 Python | 📅 2026-08-28 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,248 | 🐛 487 | 🌐 Python | 📅 2026-08-27 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,811 | 🐛 209 | 🌐 Python | 📅 2026-08-26 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,308 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,236 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 153,705 | 🐛 963 | 🌐 TypeScript | 📅 2026-08-28 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 90,260 | 🐛 7,136 | 🌐 Python | 📅 2026-08-28 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 30,300 | 🐛 349 | 🌐 Python | 📅 2026-08-27 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,346 | 🐛 115 | 🌐 Python | 📅 2026-08-27 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,317 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
