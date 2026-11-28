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

* [Supabase](https://github.com/supabase/supabase) ⭐ 115,492 | 🐛 1,358 | 🌐 TypeScript | 📅 2026-11-27 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,971 | 🐛 0 | 🌐 C | 📅 2026-11-28 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,533 | 🐛 151 | 🌐 C++ | 📅 2026-11-26 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 11,162 | 🐛 26 | 🌐 C | 📅 2026-11-28 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,663 | 🐛 661 | 🌐 C++ | 📅 2026-11-28 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,782 | 🐛 7,887 | 🌐 Go | 📅 2026-11-28 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,640 | 🐛 7,730 | 🌐 Go | 📅 2026-11-18 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 23,419 | 🐛 591 | 🌐 Rust | 📅 2026-08-31 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,841 | 🐛 280 | 🌐 Java | 📅 2026-11-27 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,872 | 🐛 492 | 🌐 C | 📅 2026-11-27 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,680 | 🐛 9,963 | 🌐 C | 📅 2026-11-28 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,444 | 🐛 614 | 🌐 C++ | 📅 2026-11-27 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,459 | 🐛 332 | 🌐 Java | 📅 2026-11-27 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 77,676 | 🐛 3,157 | 🌐 C | 📅 2026-11-27 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,951 | 🐛 196 | 🌐 C++ | 📅 2026-11-27 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,316 | 🐛 144 | 🌐 C | 📅 2026-11-24 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,305 | 🐛 143 | 🌐 Rust | 📅 2026-11-25 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,089 | 🐛 924 | 🌐 Java | 📅 2026-11-26 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,727 | 🐛 52 | 🌐 C++ | 📅 2026-11-27 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,015 | 🐛 1,336 | 🌐 C++ | 📅 2026-11-16 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,578 | 🐛 20 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,115 | 🐛 456 | 🌐 Go | 📅 2026-11-20 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 7,020 | 🐛 372 | 🌐 Erlang | 📅 2026-11-27 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 4,025 | 🐛 68 | 🌐 C# | 📅 2026-11-27 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 33,366 | 🐛 456 | 🌐 Rust | 📅 2026-11-17 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,303 | 🐛 855 | 🌐 C++ | 📅 2026-11-28 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,191 | 🐛 947 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 5,004 | 🐛 419 | 🌐 Java | 📅 2026-11-25 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,846 | 🐛 123 | 🌐 Go | 📅 2026-11-20 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,499 | 🐛 260 | 🌐 Java | 📅 2026-11-23 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,068 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,478 | 🐛 702 | 🌐 C++ | 📅 2026-09-08 - A distributed, horizontal scalability, fast open-source graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 10,577 | 🐛 881 | 🌐 Rust | 📅 2026-11-28 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,869 | 🐛 586 | 🌐 Java | 📅 2026-10-28 - A highly scalable distributed graph database
* [Apache Age](https://github.com/apache/age) ⭐ 4,957 | 🐛 274 | 🌐 C | 📅 2026-11-23 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,215 | 🐛 384 | 🌐 Java | 📅 2026-11-19 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,661 | 🐛 563 | 🌐 Go | 📅 2026-11-24 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 27,909 | 🐛 1,141 | 🌐 C | 📅 2026-11-27 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,972 | 🐛 2,016 | 🌐 Rust | 📅 2026-11-25 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,878 | 🐛 892 | 🌐 C++ | 📅 2026-11-27 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,054 | 🐛 116 | 🌐 Go | 📅 2026-11-27 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,509 | 🐛 271 | 🌐 C++ | 📅 2026-11-24 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,032 | 🐛 149 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,847 | 🐛 2,839 | 🌐 C++ | 📅 2026-11-27 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,162 | 🐛 582 | 🌐 Java | 📅 2026-11-27 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,571 | 🐛 415 | 🌐 Java | 📅 2026-11-26 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,186 | 🐛 345 | 🌐 Java | 📅 2026-11-27 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,581 | 🐛 442 | 🌐 C++ | 📅 2026-11-12 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,341 | 🐛 1,878 | 🌐 C++ | 📅 2026-11-25 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,847 | 🐛 94 | 🌐 Go | 📅 2026-11-10 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 78,746 | 🐛 6,693 | 🌐 Java | 📅 2026-11-28 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 60,026 | 🐛 320 | 🌐 Rust | 📅 2026-11-26 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 14,083 | 🐛 3,387 | 🌐 Java | 📅 2026-11-28 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,820 | 🐛 849 | 🌐 Rust | 📅 2026-11-27 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,573 | 🐛 256 | 🌐 Rust | 📅 2026-11-27 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,825 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,708 | 🐛 289 | 🌐 Java | 📅 2026-11-27 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,434 | 🐛 1,879 | 🌐 Rust | 📅 2026-11-27 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,417 | 🐛 850 | 🌐 Rust | 📅 2026-11-28 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,891 | 🐛 149 | 🌐 C# | 📅 2026-11-27 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,287 | 🐛 52 | 🌐 C++ | 📅 2026-11-18 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,254 | 🐛 1,156 | 🌐 Java | 📅 2026-11-28 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 318 | 🐛 1,331 | 🌐 Java | 📅 2026-11-28 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,833 | 🐛 2,183 | 🌐 Rust | 📅 2026-11-25 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,214 | 🐛 455 | 🌐 C | 📅 2026-11-27 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,902 | 🐛 476 | 🌐 C | 📅 2026-11-27 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,554 | 🐛 1,642 | 🌐 Java | 📅 2026-11-28 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,844 | 🐛 396 | 🌐 Rust | 📅 2026-11-27 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,435 | 🐛 783 | 🌐 Java | 📅 2026-11-27 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,589 | 🐛 13 | 🌐 Scala | 📅 2026-11-15 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,757 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,509 | 🐛 499 | 🌐 Rust | 📅 2026-11-28 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,040 | 🐛 34 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,919 | 🐛 9 | 🌐 C++ | 📅 2026-11-23 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 489 | 🐛 124 | 🌐 C | 📅 2026-11-27 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics
* [ByConity](https://github.com/ByConity/ByConity) - A cloud-native data warehouse forked from ClickHouse

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 51,204 | 🐛 9,594 | 🌐 C++ | 📅 2026-11-28 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 16,272 | 🐛 1,644 | 🌐 Java | 📅 2026-11-27 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,099 | 🐛 756 | 🌐 Java | 📅 2026-11-26 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,295 | 🐛 1,838 | 🌐 Java | 📅 2026-11-27 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,176 | 🐛 1,255 | 🌐 Java | 📅 2026-11-27 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,784 | 🐛 78 | 🌐 Java | 📅 2026-11-26 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 43,432 | 🐛 1,301 | 🌐 C++ | 📅 2026-11-27 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,679 | 🐛 2,463 | 🌐 Rust | 📅 2026-11-28 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,691 | 🐛 227 | 🌐 Rust | 📅 2026-11-27 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,933 | 🐛 61 | 🌐 Python | 📅 2026-11-26 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,019 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,321 | 🐛 116 | 🌐 C++ | 📅 2026-11-23 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,013 | 🐛 17 | 🌐 Rust | 📅 2026-11-17 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 697 | 🐛 5 | 🌐 Rust | 📅 2026-11-25 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,722 | 🐛 324 | 🌐 Java | 📅 2026-11-27 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,791 | 🐛 259 | 🌐 Go | 📅 2026-11-27 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,273 | 🐛 336 | 🌐 C | 📅 2026-11-25 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 17,273 | 🐛 2,142 | 🌐 C++ | 📅 2026-11-28 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,338 | 🐛 142 | 🌐 Java | 📅 2026-11-27 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,362 | 🐛 2,158 | 🌐 C++ | 📅 2026-11-27 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 7,396 | 🐛 1,186 | 🌐 Rust | 📅 2026-11-27 - A modern columnar data format for ML and LLMs implemented in Rust
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,360 | 🐛 545 | 🌐 Rust | 📅 2026-11-28 - A highly extensible and fast columnar file format
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,317 | 🐛 227 | 🌐 Java | 📅 2026-11-25 - An efficient and fast row-based binary serialisation framework
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,679 | 🐛 93 | 🌐 Thrift | 📅 2026-11-22 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 774 | 🐛 29 | 🌐 Java | 📅 2026-11-09 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,459 | 🐛 962 | 🌐 Java | 📅 2026-11-28 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,085 | 🐛 1,084 | 🌐 Scala | 📅 2026-11-27 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,396 | 🐛 3,311 | 🌐 Java | 📅 2026-11-27 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,459 | 🐛 896 | 🌐 Java | 📅 2026-11-28 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 405 | 🐛 119 | 🌐 Java | 📅 2026-11-27 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,376 | 🐛 181 | 🌐 Rust | 📅 2026-11-27 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,174 | 🐛 319 | 🌐 Python | 📅 2026-11-27 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 283 | 🐛 172 | 🌐 Rust | 📅 2026-11-27- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,364 | 🐛 197 | 🌐 Java | 📅 2026-11-25 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,209 | 🐛 75 | 🌐 Java | 📅 2026-11-27 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 22,456 | 🐛 2,823 | 🌐 Python | 📅 2026-11-26 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,840 | 🐛 978 | 🌐 Java | 📅 2026-11-27 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,428 | 🐛 45 | 🌐 Java | 📅 2026-11-28 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,341 | 🐛 53 | 🌐 Java | 📅 2026-11-26 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 6,146 | 🐛 510 | 🌐 Python | 📅 2026-11-27 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,687 | 🐛 173 | 🌐 Python | 📅 2026-11-28 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-10-15 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,502 | 🐛 25 | 🌐 Java | 📅 2026-11-22 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 998 | 🐛 205 | 🌐 Rust | 📅 2026-11-26 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 34,306 | 🐛 732 | 🌐 Java | 📅 2026-11-27 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,385 | 🐛 148 | 🌐 Java | 📅 2026-11-27 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,815 | 🐛 391 | 🌐 Go | 📅 2026-11-27 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,494 | 🐛 101 | 🌐 Java | 📅 2026-11-25 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,521 | 🐛 47 | 🌐 Go | 📅 2026-11-27 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,327 | 🐛 225 | 🌐 Go | 📅 2026-11-27 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,573 | 🐛 198 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 974 | 🐛 40 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,575 | 🐛 30 | 🌐 Go | 📅 2026-11-27 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 4,054 | 🐛 31 | 🌐 Go | 📅 2026-11-27 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 929 | 🐛 30 | 🌐 Go | 📅 2026-11-25 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 8,024 | 🐛 4 | 🌐 Go | 📅 2026-11-27 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,052 | 🐛 59 | 🌐 Scala | 📅 2026-11-26 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,566 | 🐛 174 | 🌐 Go | 📅 2026-11-28 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,144 | 🐛 79 | 🌐 TypeScript | 📅 2026-11-27 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,569 | 🐛 78 | 🌐 Java | 📅 2026-11-20 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,761 | 🐛 250 | 🌐 Java | 📅 2026-11-27 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 34,306 | 🐛 732 | 🌐 Java | 📅 2026-11-27 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,782 | 🐛 83 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,668 | 🐛 715 | 🌐 Java | 📅 2026-11-27 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,369 | 🐛 508 | 🌐 Java | 📅 2026-11-27 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⚠️ Archived - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,936 | 🐛 69 | 🌐 Java | 📅 2026-11-27 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,443 | 🐛 111 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,650 | 🐛 891 | 🌐 Scala | 📅 2026-11-28 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,729 | 🐛 3,731 | 🌐 Java | 📅 2026-11-27 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,779 | 🐛 19 | 🌐 Java | 📅 2026-11-27 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,185 | 🐛 545 | 🌐 Rust | 📅 2026-11-28 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,722 | 🐛 324 | 🌐 Java | 📅 2026-11-27 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 523 | 🐛 76 | 🌐 Java | 📅 2026-11-22 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,503 | 🐛 467 | 🌐 Java | 📅 2026-11-27 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,295 | 🐛 902 | 🌐 Scala | 📅 2026-11-27 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,705 | 🐛 37 | 🌐 Java | 📅 2026-11-25 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,396 | 🐛 90 | 🌐 Python | 📅 2026-11-28 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,272 | 🐛 141 | 🌐 Rust | 📅 2026-11-05 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,087 | 🐛 140 | 🌐 Rust | 📅 2026-11-25 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,287 | 🐛 52 | 🌐 C++ | 📅 2026-11-18 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,214 | 🐛 160 | 🌐 Go | 📅 2026-11-26 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,076 | 🐛 74 | 🌐 Python | 📅 2026-11-13 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 845 | 🐛 43 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 44,650 | 🐛 891 | 🌐 Scala | 📅 2026-11-28 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 40,550 | 🐛 2,860 | 🌐 Rust | 📅 2026-11-27 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,362 | 🐛 2,158 | 🌐 C++ | 📅 2026-11-27 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,811 | 🐛 1,464 | 🌐 C++ | 📅 2026-11-28 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,518 | 🐛 552 | 🌐 Python | 📅 2026-11-06 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,710 | 🐛 579 | 🌐 Python | 📅 2026-11-27 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,869 | 🐛 489 | 🌐 Rust | 📅 2026-11-09 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 545 | 🐛 5 | 🌐 Python | 📅 2026-11-27 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 44,393 | 🐛 3,885 | 🌐 Python | 📅 2026-11-27 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,960 | 🐛 1,458 | 🌐 Python | 📅 2026-11-26 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,392 | 🐛 728 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,794 | 🐛 100 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,315 | 🐛 222 | 🌐 Python | 📅 2026-11-24 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,821 | 🐛 4 | 🌐 Python | 📅 2026-11-28 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,719 | 🐛 1,943 | 🌐 Python | 📅 2026-11-28 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 30,388 | 🐛 608 | 🌐 Java | 📅 2026-11-27 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Temporal](https://github.com/temporalio/temporal) ⭐ 24,640 | 🐛 1,094 | 🌐 Go | 📅 2026-11-28 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 24,253 | 🐛 810 | 🌐 Python | 📅 2026-11-28 - A Python based workflow orchestration tool
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,798 | 🐛 198 | 🌐 Python | 📅 2026-11-26 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 18,750 | 🐛 861 | 🌐 Rust | 📅 2026-11-27 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 17,126 | 🐛 1,402 | 🌐 Go | 📅 2026-11-27 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,485 | 🐛 2,635 | 🌐 Python | 📅 2026-11-25 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,571 | 🐛 135 | 🌐 Java | 📅 2026-11-27 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,577 | 🐛 215 | 🌐 Go | 📅 2026-11-26 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,851 | 🐛 637 | 🌐 Python | 📅 2026-11-20 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,799 | 🐛 239 | 🌐 Go | 📅 2026-11-26 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,508 | 🐛 800 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,857 | 🐛 37 | 🌐 Java | 📅 2026-11-06 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 29,279 | 🐛 795 | 🌐 Python | 📅 2026-11-27 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,725 | 🐛 115 | 🌐 Python | 📅 2026-11-21 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,743 | 🐛 51 | 🌐 Go | 📅 2026-11-23 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 29,700 | 🐛 655 | 🌐 Python | 📅 2026-11-25 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,953 | 🐛 59 | 🌐 Python | 📅 2026-11-17 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,539 | 🐛 509 | 🌐 Python | 📅 2026-11-24 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,662 | 🐛 66 | 🌐 Scala | 📅 2026-10-20 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,466 | 🐛 217 | 🌐 Python | 📅 2026-11-27 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 25,008 | 🐛 689 | 🌐 Go | 📅 2026-11-25 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 16,002 | 🐛 233 | 🌐 Python | 📅 2026-11-24 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,628 | 🐛 521 | 🌐 Go | 📅 2026-11-27 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,595 | 🐛 453 | 🌐 Go | 📅 2026-11-26 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,832 | 🐛 141 | 🌐 Python | 📅 2026-11-28 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,533 | 🐛 182 | 🌐 Java | 📅 2026-11-27 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 14,223 | 🐛 1,995 | 🌐 Rust | 📅 2026-11-27 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,367 | 🐛 314 | 🌐 Python | 📅 2026-11-27 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,437 | 🐛 26 | 🌐 HTML | 📅 2026-11-27 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 129,260 | 🐛 3,244 | 🌐 Go | 📅 2026-11-27 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,722 | 🐛 324 | 🌐 Java | 📅 2026-11-27 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,368 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,046 | 🐛 30 | 🌐 Go | 📅 2026-11-27 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,311 | 🐛 124 | 🌐 Java | 📅 2026-11-25 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 505 | 🐛 43 | 🌐 Java | 📅 2026-11-12 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,090 | 🐛 138 | 🌐 Java | 📅 2026-11-26 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 613 | 🐛 45 | 🌐 C | 📅 2026-11-24 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 222 | 🐛 9 | 🌐 Java | 📅 2026-11-26 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,833 | 🐛 2,183 | 🌐 Rust | 📅 2026-11-25 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,292 | 🐛 995 | 🌐 Go | 📅 2026-11-27 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,066 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,910 | 🐛 176 | 🌐 Go | 📅 2026-11-14 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 67,906 | 🐛 1,180 | 🌐 Go | 📅 2026-11-27 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 18,229 | 🐛 786 | 🌐 Go | 📅 2026-11-27 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,618 | 🐛 115 | 🌐 Go Template | 📅 2026-11-27 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 78,210 | 🐛 3,269 | 🌐 Go | 📅 2026-11-28 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,394 | 🐛 14,668 | 🌐 TypeScript | 📅 2026-11-28 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,354 | 🐛 166 | 🌐 TypeScript | 📅 2026-11-27 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,986 | 🐛 2,590 | 🌐 Rust | 📅 2026-11-28 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,075 | 🐛 94 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,924 | 🐛 429 | 🌐 Go | 📅 2026-11-27 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,984 | 🐛 2,259 | 🌐 Java | 📅 2026-11-26 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,627 | 🐛 134 | 🌐 Ruby | 📅 2026-11-27 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,212 | 🐛 883 | 🌐 C | 📅 2026-11-27 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,836 | 🐛 384 | 🌐 Go | 📅 2026-11-25 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,896 | 🐛 873 | 🌐 TypeScript | 📅 2026-11-27 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 13,029 | 🐛 1,485 | 🌐 Python | 📅 2026-11-28 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,169 | 🐛 868 | 🌐 Python | 📅 2026-11-25 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⚠️ Archived - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,316 | 🐛 258 | 🌐 Java | 📅 2026-11-23 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,163 | 🐛 168 | 🌐 Java | 📅 2026-11-27 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,442 | 🐛 148 | 🌐 Java | 📅 2026-10-19 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,896 | 🐛 873 | 🌐 TypeScript | 📅 2026-11-27 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,789 | 🐛 417 | 🌐 Java | 📅 2026-11-28 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 925 | 🐛 23 | 🌐 Java | 📅 2026-11-27 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,037 | 🐛 124 | 🌐 Java | 📅 2026-11-26 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,592 | 🐛 554 | 🌐 Java | 📅 2026-11-26 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,436 | 🐛 905 | 🌐 Java | 📅 2026-11-27 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,474 | 🐛 381 | 🌐 Java | 📅 2026-11-28 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,127 | 🐛 452 | 🌐 Java | 📅 2026-11-27 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,527 | 🐛 111 | 🌐 Rust | 📅 2026-11-27 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,710 | 🐛 611 | 🌐 Python | 📅 2026-11-28 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 50,631 | 🐛 4,975 | 🌐 Clojure | 📅 2026-11-28 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,908 | 🐛 786 | 🌐 TypeScript | 📅 2026-11-25 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,257 | 🐛 1,138 | 🌐 TypeScript | 📅 2026-11-28 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 46,527 | 🐛 1,212 | 🌐 Python | 📅 2026-11-27 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,510 | 🐛 409 | 🌐 Python | 📅 2026-11-27 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 7,152 | 🐛 44 | 🌐 TypeScript | 📅 2026-11-27 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,358 | 🐛 4 | 🌐 Python | 📅 2026-10-26 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,828 | 🐛 4 | 🌐 Python | 📅 2026-11-26 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,391 | 🐛 46 | 🌐 Rust | 📅 2026-11-23 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,814 | 🐛 1,272 | 🌐 Python | 📅 2026-11-23 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,486 | 🐛 1,888 | 🌐 Jupyter Notebook | 📅 2026-11-23 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,684 | 🐛 640 | 🌐 Python | 📅 2026-11-26 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,671 | 🐛 70 | 🌐 Java | 📅 2026-11-26 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,304 | 🐛 245 | 🌐 TypeScript | 📅 2026-11-02 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,410 | 🐛 2 | 🌐 JavaScript | 📅 2026-11-27 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,775 | 🐛 3,023 | 🌐 Java | 📅 2026-11-26 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,551 | 🐛 2,805 | 🌐 Java | 📅 2026-11-27 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,037 | 🐛 124 | 🌐 Java | 📅 2026-11-26 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,183 | 🐛 169 | 🌐 Rust | 📅 2026-11-26 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,025 | 🐛 129 | 🌐 Java | 📅 2026-11-24 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,296 | 🐛 9 | 🌐 C++ | 📅 2026-11-27 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 21,307 | 🐛 1,238 | 🌐 Rust | 📅 2026-11-28 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,265 | 🐛 1,066 | 🌐 Java | 📅 2026-09-01 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,507 | 🐛 99 | 🌐 Rust | 📅 2026-11-28 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,415 | 🐛 199 | 🌐 Java | 📅 2026-11-27 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,632 | 🐛 1,170 | 🌐 Scala | 📅 2026-11-27 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 965 | 🐛 147 | 🌐 Scala | 📅 2026-11-27 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 46,752 | 🐛 1,568 | 🌐 Go | 📅 2026-11-28 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 35,745 | 🐛 891 | 🌐 Rust | 📅 2026-11-27 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,798 | 🐛 999 | 🌐 Rust | 📅 2026-11-27 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 23,845 | 🐛 25 | 🌐 C | 📅 2026-11-27 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,970 | 🐛 900 | 🌐 Go | 📅 2026-11-28 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,998 | 🐛 656 | 🌐 Rust | 📅 2026-11-28 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,274 | 🐛 64 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,202 | 🐛 277 | 🌐 Java | 📅 2026-11-27 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⚠️ Archived - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,735 | 🐛 151 | 🌐 Go | 📅 2026-11-27 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 44,393 | 🐛 3,885 | 🌐 Python | 📅 2026-11-27 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 28,993 | 🐛 2,287 | 🌐 Python | 📅 2026-11-28 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,850 | 🐛 25 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,982 | 🐛 1 | 📅 2026-09-30 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 11,064 | 🐛 130 | 🌐 Python | 📅 2026-11-27 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,897 | 🐛 566 | 🌐 Python | 📅 2026-11-28 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,368 | 🐛 538 | 🌐 Python | 📅 2026-11-19 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,949 | 🐛 282 | 🌐 Python | 📅 2026-11-17 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,311 | 🐛 939 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,245 | 🐛 107 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 162,029 | 🐛 1,325 | 🌐 Python | 📅 2026-11-28 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 97,716 | 🐛 11,234 | 🌐 Python | 📅 2026-11-28 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 33,677 | 🐛 1,123 | 🌐 Python | 📅 2026-11-28 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 27,122 | 🐛 185 | 🌐 Python | 📅 2026-11-27 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,327 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-28._
