# Awesome Open Source Data Engineering with stars

A curated list of open source tools used in analytics platforms and data engineering ecosystem
![Open Source Data Engineering Landscape 2025](https://github.com/user-attachments/assets/fe9e97a8-abd8-47a9-8429-15130055785c)

For more information about the above compiled landscape for 2025, please refer to the published blog post on [Pracdata.io](https://www.pracdata.io/p/open-source-data-engineering-landscape-2025)

## Table of contents

* [Storage Systems](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#storage-systems)
* [Data Lake Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-lake-platform)
* [Data Integration](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-integration)
* [Data Processing & Computation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-processing-and-computation)
* [Workflow Management & DataOps](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#workflow-management--dataops)
* [Data Infrastructure](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#data-infrastructure)
* [Metadata Management](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#metadata-management)
* [Analytics & Visualisation](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#analytics--visualisation)
* [ML/AI Platform](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file#mlai-platform)

## STORAGE SYSTEMS

### Relational DBMS

* [Supabase](https://github.com/supabase/supabase) ⭐ 111,436 | 🐛 1,149 | 🌐 TypeScript | 📅 2026-10-13 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,380 | 🐛 0 | 🌐 C | 📅 2026-10-13 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,458 | 🐛 120 | 🌐 C++ | 📅 2026-10-06 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,664 | 🐛 25 | 🌐 C | 📅 2026-10-12 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,357 | 🐛 543 | 🌐 C++ | 📅 2026-10-12 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,640 | 🐛 7,295 | 🌐 Go | 📅 2026-10-12 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,566 | 🐛 8,290 | 🌐 Go | 📅 2026-10-03 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 23,194 | 🐛 573 | 🌐 Rust | 📅 2026-08-31 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,804 | 🐛 197 | 🌐 Java | 📅 2026-10-12 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,809 | 🐛 1,063 | 🌐 C | 📅 2026-10-12 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,589 | 🐛 8,298 | 🌐 C | 📅 2026-10-13 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,322 | 🐛 603 | 🌐 C++ | 📅 2026-10-10 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,444 | 🐛 338 | 🌐 Java | 📅 2026-10-12 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 76,765 | 🐛 3,037 | 🌐 C | 📅 2026-10-12 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,782 | 🐛 333 | 🌐 C++ | 📅 2026-10-12 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,291 | 🐛 110 | 🌐 C | 📅 2026-09-11 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,291 | 🐛 117 | 🌐 Rust | 📅 2026-10-12 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,084 | 🐛 908 | 🌐 Java | 📅 2026-10-12 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,637 | 🐛 36 | 🌐 C++ | 📅 2026-10-13 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,003 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,580 | 🐛 17 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,095 | 🐛 449 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,975 | 🐛 377 | 🌐 Erlang | 📅 2026-10-12 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 4,003 | 🐛 82 | 🌐 C# | 📅 2026-10-12 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 33,121 | 🐛 657 | 🌐 Rust | 📅 2026-10-08 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,278 | 🐛 861 | 🌐 C++ | 📅 2026-10-13 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,173 | 🐛 948 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,990 | 🐛 376 | 🌐 Java | 📅 2026-10-12 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,805 | 🐛 104 | 🌐 Go | 📅 2026-10-12 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,308 | 🐛 244 | 🌐 Java | 📅 2026-10-09 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,063 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,425 | 🐛 690 | 🌐 C++ | 📅 2026-09-08 - A distributed, horizontal scalability, fast open-source graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 9,359 | 🐛 999 | 🌐 Rust | 📅 2026-10-12 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,856 | 🐛 581 | 🌐 Java | 📅 2026-10-12 - A highly scalable distributed graph database
* [Apache Age](https://github.com/apache/age) ⭐ 4,885 | 🐛 255 | 🌐 C | 📅 2026-10-12 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,193 | 🐛 387 | 🌐 Java | 📅 2026-10-13 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,352 | 🐛 382 | 🌐 Go | 📅 2026-10-12 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 27,407 | 🐛 951 | 🌐 C | 📅 2026-10-12 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,906 | 🐛 1,878 | 🌐 Rust | 📅 2026-10-12 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,774 | 🐛 785 | 🌐 C++ | 📅 2026-10-13 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,042 | 🐛 114 | 🌐 Go | 📅 2026-10-05 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,457 | 🐛 262 | 🌐 C++ | 📅 2026-10-12 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,027 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,788 | 🐛 3,861 | 🌐 C++ | 📅 2026-10-12 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,119 | 🐛 556 | 🌐 Java | 📅 2026-10-10 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,565 | 🐛 415 | 🌐 Java | 📅 2026-10-12 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,176 | 🐛 343 | 🌐 Java | 📅 2026-10-09 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,487 | 🐛 421 | 🌐 C++ | 📅 2026-10-08 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,192 | 🐛 1,731 | 🌐 C++ | 📅 2026-10-12 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,783 | 🐛 76 | 🌐 Go | 📅 2026-10-10 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 78,246 | 🐛 6,156 | 🌐 Java | 📅 2026-10-13 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,553 | 🐛 321 | 🌐 Rust | 📅 2026-10-12 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,853 | 🐛 3,250 | 🌐 Java | 📅 2026-10-12 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,711 | 🐛 835 | 🌐 Rust | 📅 2026-10-12 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,397 | 🐛 248 | 🌐 Rust | 📅 2026-10-13 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,827 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,685 | 🐛 215 | 🌐 Java | 📅 2026-10-12 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,366 | 🐛 1,748 | 🌐 Rust | 📅 2026-10-13 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,380 | 🐛 774 | 🌐 Rust | 📅 2026-10-13 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,868 | 🐛 148 | 🌐 C# | 📅 2026-10-12 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,269 | 🐛 75 | 🌐 C++ | 📅 2026-10-12 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,206 | 🐛 1,081 | 🌐 Java | 📅 2026-10-12 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 315 | 🐛 1,329 | 🌐 Java | 📅 2026-10-13 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,760 | 🐛 2,179 | 🌐 Rust | 📅 2026-10-12 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,157 | 🐛 442 | 🌐 C | 📅 2026-10-08 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,677 | 🐛 425 | 🌐 C | 📅 2026-10-12 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,439 | 🐛 1,160 | 🌐 Java | 📅 2026-10-13 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,732 | 🐛 290 | 🌐 Rust | 📅 2026-10-13 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,411 | 🐛 760 | 🌐 Java | 📅 2026-10-13 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,571 | 🐛 9 | 🌐 Scala | 📅 2026-10-01 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,761 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,463 | 🐛 383 | 🌐 Rust | 📅 2026-10-13 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,043 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,914 | 🐛 9 | 🌐 C++ | 📅 2026-10-12 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 484 | 🐛 102 | 🌐 C | 📅 2026-10-12 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 50,379 | 🐛 8,296 | 🌐 C++ | 📅 2026-10-13 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 16,078 | 🐛 1,383 | 🌐 Java | 📅 2026-10-13 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,064 | 🐛 766 | 🌐 Java | 📅 2026-10-11 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,166 | 🐛 1,472 | 🌐 Java | 📅 2026-10-12 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,152 | 🐛 1,332 | 🌐 Java | 📅 2026-10-12 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,777 | 🐛 79 | 🌐 Java | 📅 2026-10-12 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 42,142 | 🐛 1,098 | 🌐 C++ | 📅 2026-10-12 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,438 | 🐛 2,409 | 🌐 Rust | 📅 2026-10-12 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,486 | 🐛 194 | 🌐 Rust | 📅 2026-10-12 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,917 | 🐛 48 | 🌐 Python | 📅 2026-10-09 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,024 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,264 | 🐛 132 | 🌐 C++ | 📅 2026-07-17 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,006 | 🐛 15 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 692 | 🐛 14 | 🌐 Rust | 📅 2026-10-09 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,687 | 🐛 252 | 🌐 Java | 📅 2026-10-12 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,528 | 🐛 239 | 🌐 Go | 📅 2026-10-12 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,257 | 🐛 328 | 🌐 C | 📅 2026-09-23 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 17,112 | 🐛 1,680 | 🌐 C++ | 📅 2026-10-12 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,315 | 🐛 123 | 🌐 Java | 📅 2026-10-12 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,249 | 🐛 2,453 | 🌐 C++ | 📅 2026-10-12 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 7,144 | 🐛 1,258 | 🌐 Rust | 📅 2026-10-12 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,307 | 🐛 259 | 🌐 Java | 📅 2026-10-11 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,257 | 🐛 377 | 🌐 Rust | 📅 2026-10-13 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,613 | 🐛 88 | 🌐 Thrift | 📅 2026-10-11 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 770 | 🐛 22 | 🌐 Java | 📅 2026-10-08 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,324 | 🐛 919 | 🌐 Java | 📅 2026-10-12 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,041 | 🐛 984 | 🌐 Scala | 📅 2026-10-13 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,306 | 🐛 3,025 | 🌐 Java | 📅 2026-10-12 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,417 | 🐛 772 | 🌐 Java | 📅 2026-10-13 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 399 | 🐛 106 | 🌐 Java | 📅 2026-10-11 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,332 | 🐛 160 | 🌐 Rust | 📅 2026-10-12 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,154 | 🐛 263 | 🌐 Python | 📅 2026-10-11 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 280 | 🐛 91 | 🌐 Rust | 📅 2026-10-09- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,281 | 🐛 171 | 🌐 Java | 📅 2026-10-12 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,189 | 🐛 66 | 🌐 Java | 📅 2026-10-12 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 22,215 | 🐛 2,590 | 🌐 Python | 📅 2026-10-13 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,710 | 🐛 844 | 🌐 Java | 📅 2026-10-12 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,366 | 🐛 60 | 🌐 Java | 📅 2026-10-12 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,255 | 🐛 45 | 🌐 Java | 📅 2026-10-12 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,960 | 🐛 466 | 🌐 Python | 📅 2026-10-12 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,654 | 🐛 144 | 🌐 Python | 📅 2026-10-13 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,269 | 🐛 142 | 🌐 Java | 📅 2026-09-24 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,504 | 🐛 25 | 🌐 Java | 📅 2026-09-16 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 983 | 🐛 243 | 🌐 Rust | 📅 2026-10-12 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 33,947 | 🐛 638 | 🌐 Java | 📅 2026-10-13 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,211 | 🐛 135 | 🌐 Java | 📅 2026-10-12 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,785 | 🐛 359 | 🌐 Go | 📅 2026-10-12 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,482 | 🐛 91 | 🌐 Java | 📅 2026-10-12 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,498 | 🐛 45 | 🌐 Go | 📅 2026-10-12 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,302 | 🐛 207 | 🌐 Go | 📅 2026-10-12 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,578 | 🐛 177 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 970 | 🐛 37 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,451 | 🐛 38 | 🌐 Go | 📅 2026-10-08 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 4,010 | 🐛 28 | 🌐 Go | 📅 2026-10-12 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 912 | 🐛 22 | 🌐 Go | 📅 2026-10-12 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,983 | 🐛 26 | 🌐 Go | 📅 2026-10-07 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,037 | 🐛 59 | 🌐 Scala | 📅 2026-06-26 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,542 | 🐛 160 | 🌐 Go | 📅 2026-10-12 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,107 | 🐛 47 | 🌐 TypeScript | 📅 2026-10-12 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,573 | 🐛 85 | 🌐 Java | 📅 2026-10-05 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,756 | 🐛 250 | 🌐 Java | 📅 2026-09-23 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,947 | 🐛 638 | 🌐 Java | 📅 2026-10-13 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,771 | 🐛 80 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,634 | 🐛 847 | 🌐 Java | 📅 2026-10-13 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,343 | 🐛 1,776 | 🌐 Java | 📅 2026-10-13 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,607 | 🐛 520 | 🌐 C++ | 📅 2026-10-08 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,909 | 🐛 65 | 🌐 Java | 📅 2026-10-12 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,444 | 🐛 110 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,681 | 🐛 200 | 🌐 Ruby | 📅 2026-10-13 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,186 | 🐛 663 | 🌐 Scala | 📅 2026-10-13 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,682 | 🐛 3,877 | 🌐 Java | 📅 2026-10-13 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,770 | 🐛 30 | 🌐 Java | 📅 2026-08-25 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,121 | 🐛 585 | 🌐 Rust | 📅 2026-10-13 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,687 | 🐛 252 | 🌐 Java | 📅 2026-10-12 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 520 | 🐛 77 | 🌐 Java | 📅 2026-10-08 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,402 | 🐛 400 | 🌐 Java | 📅 2026-10-12 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,278 | 🐛 900 | 🌐 Scala | 📅 2026-10-12 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,695 | 🐛 45 | 🌐 Java | 📅 2026-10-12 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,370 | 🐛 90 | 🌐 Python | 📅 2026-10-12 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,256 | 🐛 139 | 🌐 Rust | 📅 2026-08-30 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,054 | 🐛 130 | 🌐 Rust | 📅 2026-10-12 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,269 | 🐛 75 | 🌐 C++ | 📅 2026-10-12 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,163 | 🐛 156 | 🌐 Go | 📅 2026-10-09 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,056 | 🐛 37 | 🌐 Python | 📅 2026-10-12 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 845 | 🐛 44 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 44,186 | 🐛 663 | 🌐 Scala | 📅 2026-10-13 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 40,109 | 🐛 2,973 | 🌐 Rust | 📅 2026-10-12 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,249 | 🐛 2,453 | 🌐 C++ | 📅 2026-10-12 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,775 | 🐛 1,408 | 🌐 C++ | 📅 2026-10-13 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,517 | 🐛 554 | 🌐 Python | 📅 2026-04-01 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,675 | 🐛 543 | 🌐 Python | 📅 2026-10-13 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,796 | 🐛 421 | 🌐 Rust | 📅 2026-10-08 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 535 | 🐛 25 | 🌐 Python | 📅 2026-10-11 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 44,012 | 🐛 3,570 | 🌐 Python | 📅 2026-10-12 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,934 | 🐛 1,361 | 🌐 Python | 📅 2026-09-29 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,390 | 🐛 723 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,796 | 🐛 99 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,229 | 🐛 215 | 🌐 Python | 📅 2026-10-12 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,678 | 🐛 4 | 🌐 Python | 📅 2026-10-12 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,152 | 🐛 1,857 | 🌐 Python | 📅 2026-10-12 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 29,525 | 🐛 856 | 🌐 Java | 📅 2026-10-12 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 24,008 | 🐛 908 | 🌐 Python | 📅 2026-10-12 - A Python based workflow orchestration tool
* [Temporal](https://github.com/temporalio/temporal) ⭐ 23,645 | 🐛 1,061 | 🌐 Go | 📅 2026-10-13 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,783 | 🐛 183 | 🌐 Python | 📅 2026-10-07 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 18,166 | 🐛 868 | 🌐 Rust | 📅 2026-10-12 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 17,035 | 🐛 1,315 | 🌐 Go | 📅 2026-10-12 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,268 | 🐛 2,583 | 🌐 Python | 📅 2026-10-12 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,515 | 🐛 134 | 🌐 Java | 📅 2026-10-12 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,489 | 🐛 204 | 🌐 Go | 📅 2026-10-12 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,826 | 🐛 628 | 🌐 Python | 📅 2026-10-09 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,684 | 🐛 194 | 🌐 Go | 📅 2026-10-12 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,511 | 🐛 802 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,844 | 🐛 38 | 🌐 Java | 📅 2026-10-06 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 28,963 | 🐛 752 | 🌐 Python | 📅 2026-10-12 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,652 | 🐛 62 | 🌐 Python | 📅 2026-10-12 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,737 | 🐛 41 | 🌐 Go | 📅 2026-10-09 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 29,002 | 🐛 583 | 🌐 Python | 📅 2026-10-11 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,870 | 🐛 51 | 🌐 Python | 📅 2026-10-12 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,478 | 🐛 459 | 🌐 Python | 📅 2026-10-13 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,648 | 🐛 61 | 🌐 Scala | 📅 2026-10-13 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,437 | 🐛 201 | 🌐 Python | 📅 2026-10-12 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,628 | 🐛 590 | 🌐 Go | 📅 2026-10-13 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,912 | 🐛 221 | 🌐 Python | 📅 2026-10-12 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,544 | 🐛 491 | 🌐 Go | 📅 2026-10-01 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,555 | 🐛 444 | 🌐 Go | 📅 2026-10-07 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,826 | 🐛 115 | 🌐 Python | 📅 2026-10-13 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,520 | 🐛 170 | 🌐 Java | 📅 2026-10-12 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 14,000 | 🐛 1,753 | 🌐 Rust | 📅 2026-10-12 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,317 | 🐛 323 | 🌐 Python | 📅 2026-10-12 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,421 | 🐛 11 | 🌐 HTML | 📅 2026-10-12 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 128,308 | 🐛 3,266 | 🌐 Go | 📅 2026-10-12 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,687 | 🐛 252 | 🌐 Java | 📅 2026-10-12 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,365 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,033 | 🐛 25 | 🌐 Go | 📅 2026-10-08 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,312 | 🐛 118 | 🌐 Java | 📅 2026-10-12 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 505 | 🐛 69 | 🌐 Java | 📅 2026-10-08 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,080 | 🐛 133 | 🌐 Java | 📅 2026-10-12 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 606 | 🐛 41 | 🌐 C | 📅 2026-09-05 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 220 | 🐛 13 | 🌐 Java | 📅 2026-10-12 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,760 | 🐛 2,179 | 🌐 Rust | 📅 2026-10-12 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,253 | 🐛 896 | 🌐 Go | 📅 2026-10-13 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,064 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,904 | 🐛 174 | 🌐 Go | 📅 2026-10-01 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,520 | 🐛 990 | 🌐 Go | 📅 2026-10-13 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,846 | 🐛 777 | 🌐 Go | 📅 2026-10-12 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,469 | 🐛 109 | 🌐 Go Template | 📅 2026-10-12 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,283 | 🐛 3,301 | 🌐 TypeScript | 📅 2026-10-13 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,309 | 🐛 14,856 | 🌐 TypeScript | 📅 2026-10-13 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,335 | 🐛 149 | 🌐 TypeScript | 📅 2026-10-09 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,691 | 🐛 2,499 | 🌐 Rust | 📅 2026-10-12 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,071 | 🐛 91 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,852 | 🐛 422 | 🌐 Go | 📅 2026-10-12 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,966 | 🐛 2,257 | 🌐 Java | 📅 2026-10-12 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,605 | 🐛 130 | 🌐 Ruby | 📅 2026-10-11 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,145 | 🐛 783 | 🌐 C | 📅 2026-10-13 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,769 | 🐛 339 | 🌐 Go | 📅 2026-10-07 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,447 | 🐛 919 | 🌐 TypeScript | 📅 2026-10-13 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,816 | 🐛 1,384 | 🌐 Python | 📅 2026-10-13 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,129 | 🐛 868 | 🌐 Python | 📅 2026-10-12 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⚠️ Archived - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,288 | 🐛 252 | 🌐 Java | 📅 2026-10-11 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,153 | 🐛 169 | 🌐 Java | 📅 2026-10-12 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,436 | 🐛 145 | 🌐 Java | 📅 2026-09-22 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,447 | 🐛 919 | 🌐 TypeScript | 📅 2026-10-13 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,701 | 🐛 386 | 🌐 Java | 📅 2026-10-12 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 925 | 🐛 30 | 🌐 Java | 📅 2026-10-06 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,028 | 🐛 130 | 🌐 Java | 📅 2026-10-12 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,553 | 🐛 444 | 🌐 Java | 📅 2026-10-11 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,246 | 🐛 1,098 | 🌐 Java | 📅 2026-10-13 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,467 | 🐛 395 | 🌐 Java | 📅 2026-10-13 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,088 | 🐛 400 | 🌐 Java | 📅 2026-10-12 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,480 | 🐛 112 | 🌐 Rust | 📅 2026-10-12 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,117 | 🐛 548 | 🌐 Python | 📅 2026-10-13 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 49,633 | 🐛 4,587 | 🌐 Clojure | 📅 2026-10-13 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,833 | 🐛 813 | 🌐 Python | 📅 2026-10-08 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,182 | 🐛 1,119 | 🌐 TypeScript | 📅 2026-10-13 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 45,967 | 🐛 1,191 | 🌐 Python | 📅 2026-10-13 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,446 | 🐛 434 | 🌐 Python | 📅 2026-10-09 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 7,003 | 🐛 15 | 🌐 TypeScript | 📅 2026-10-09 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,355 | 🐛 4 | 🌐 Python | 📅 2026-09-14 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,802 | 🐛 37 | 🌐 Python | 📅 2026-10-12 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,383 | 🐛 44 | 🌐 Rust | 📅 2026-10-12 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,793 | 🐛 1,322 | 🌐 Python | 📅 2026-10-09 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,433 | 🐛 1,892 | 🌐 Jupyter Notebook | 📅 2026-10-12 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,513 | 🐛 691 | 🌐 Python | 📅 2026-10-13 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,663 | 🐛 67 | 🌐 Java | 📅 2026-10-11 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,294 | 🐛 239 | 🌐 TypeScript | 📅 2026-09-16 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,407 | 🐛 17 | 🌐 JavaScript | 📅 2026-10-12 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,757 | 🐛 2,994 | 🌐 Java | 📅 2026-10-13 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,326 | 🐛 2,717 | 🌐 Java | 📅 2026-10-13 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,028 | 🐛 130 | 🌐 Java | 📅 2026-10-12 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,145 | 🐛 157 | 🌐 Rust | 📅 2026-10-12 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,026 | 🐛 129 | 🌐 Java | 📅 2026-10-08 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,290 | 🐛 8 | 🌐 C++ | 📅 2026-10-12 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 20,995 | 🐛 1,177 | 🌐 Rust | 📅 2026-10-13 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,247 | 🐛 1,048 | 🌐 Java | 📅 2026-09-01 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,411 | 🐛 358 | 🌐 Rust | 📅 2026-10-10 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,411 | 🐛 182 | 🌐 Java | 📅 2026-10-08 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,603 | 🐛 1,035 | 🌐 Scala | 📅 2026-10-12 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 960 | 🐛 148 | 🌐 Scala | 📅 2026-09-01 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 46,365 | 🐛 1,401 | 🌐 Go | 📅 2026-10-13 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 35,051 | 🐛 764 | 🌐 Rust | 📅 2026-10-12 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,488 | 🐛 932 | 🌐 Rust | 📅 2026-10-12 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 23,326 | 🐛 17 | 🌐 C | 📅 2026-10-08 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,877 | 🐛 804 | 🌐 Go | 📅 2026-10-12 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,653 | 🐛 743 | 🌐 Rust | 📅 2026-10-13 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,250 | 🐛 64 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,126 | 🐛 262 | 🌐 Java | 📅 2026-10-12 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,028 | 🐛 195 | 🌐 Python | 📅 2026-09-03 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,734 | 🐛 148 | 🌐 Go | 📅 2026-10-13 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 44,012 | 🐛 3,570 | 🌐 Python | 📅 2026-10-12 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 28,353 | 🐛 2,192 | 🌐 Python | 📅 2026-10-13 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,859 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,901 | 🐛 1 | 📅 2026-09-30 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 11,018 | 🐛 128 | 🌐 Python | 📅 2026-10-12 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,699 | 🐛 477 | 🌐 Python | 📅 2026-10-13 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,301 | 🐛 521 | 🌐 Python | 📅 2026-10-12 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,899 | 🐛 228 | 🌐 Python | 📅 2026-10-05 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,311 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,245 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 158,282 | 🐛 1,110 | 🌐 TypeScript | 📅 2026-10-13 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 93,667 | 🐛 8,726 | 🌐 Python | 📅 2026-10-13 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 32,109 | 🐛 680 | 🌐 Python | 📅 2026-10-12 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,728 | 🐛 158 | 🌐 Python | 📅 2026-10-12 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,325 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-13._
