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

* [Supabase](https://github.com/supabase/supabase) ⭐ 114,490 | 🐛 1,152 | 🌐 TypeScript | 📅 2026-11-04 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,698 | 🐛 0 | 🌐 C | 📅 2026-11-03 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,496 | 🐛 133 | 🌐 C++ | 📅 2026-10-28 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,910 | 🐛 26 | 🌐 C | 📅 2026-11-03 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,523 | 🐛 590 | 🌐 C++ | 📅 2026-11-03 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,707 | 🐛 7,489 | 🌐 Go | 📅 2026-11-03 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,602 | 🐛 8,168 | 🌐 Go | 📅 2026-10-29 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 23,293 | 🐛 588 | 🌐 Rust | 📅 2026-08-31 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,817 | 🐛 269 | 🌐 Java | 📅 2026-11-03 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,839 | 🐛 462 | 🌐 C | 📅 2026-10-30 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,649 | 🐛 9,170 | 🌐 C | 📅 2026-11-04 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,366 | 🐛 610 | 🌐 C++ | 📅 2026-10-31 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,449 | 🐛 318 | 🌐 Java | 📅 2026-11-03 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 77,170 | 🐛 3,100 | 🌐 C | 📅 2026-11-03 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,841 | 🐛 269 | 🌐 C++ | 📅 2026-11-03 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,303 | 🐛 126 | 🌐 C | 📅 2026-09-11 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,298 | 🐛 132 | 🌐 Rust | 📅 2026-11-03 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,090 | 🐛 914 | 🌐 Java | 📅 2026-11-03 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,672 | 🐛 37 | 🌐 C++ | 📅 2026-11-04 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,007 | 🐛 1,344 | 🌐 C++ | 📅 2026-11-03 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,582 | 🐛 17 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,112 | 🐛 449 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 7,000 | 🐛 372 | 🌐 Erlang | 📅 2026-11-03 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 4,014 | 🐛 65 | 🌐 C# | 📅 2026-11-03 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 33,260 | 🐛 427 | 🌐 Rust | 📅 2026-11-03 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,291 | 🐛 805 | 🌐 C++ | 📅 2026-11-04 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,180 | 🐛 949 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,997 | 🐛 396 | 🌐 Java | 📅 2026-11-03 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,819 | 🐛 110 | 🌐 Go | 📅 2026-11-03 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,390 | 🐛 237 | 🌐 Java | 📅 2026-10-23 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,067 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,466 | 🐛 695 | 🌐 C++ | 📅 2026-09-08 - A distributed, horizontal scalability, fast open-source graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 10,501 | 🐛 835 | 🌐 Rust | 📅 2026-11-03 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,863 | 🐛 582 | 🌐 Java | 📅 2026-10-28 - A highly scalable distributed graph database
* [Apache Age](https://github.com/apache/age) ⭐ 4,927 | 🐛 266 | 🌐 C | 📅 2026-10-13 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,198 | 🐛 380 | 🌐 Java | 📅 2026-11-03 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,442 | 🐛 419 | 🌐 Go | 📅 2026-11-03 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 27,601 | 🐛 1,043 | 🌐 C | 📅 2026-11-03 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,937 | 🐛 1,998 | 🌐 Rust | 📅 2026-11-03 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,838 | 🐛 811 | 🌐 C++ | 📅 2026-11-03 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,049 | 🐛 116 | 🌐 Go | 📅 2026-10-21 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,489 | 🐛 295 | 🌐 C++ | 📅 2026-11-03 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,029 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,820 | 🐛 2,654 | 🌐 C++ | 📅 2026-11-03 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,133 | 🐛 566 | 🌐 Java | 📅 2026-11-03 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,569 | 🐛 421 | 🌐 Java | 📅 2026-11-03 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,183 | 🐛 357 | 🌐 Java | 📅 2026-11-03 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,519 | 🐛 429 | 🌐 C++ | 📅 2026-10-08 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,241 | 🐛 1,823 | 🌐 C++ | 📅 2026-11-04 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,798 | 🐛 87 | 🌐 Go | 📅 2026-10-20 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 78,482 | 🐛 6,292 | 🌐 Java | 📅 2026-11-04 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,770 | 🐛 312 | 🌐 Rust | 📅 2026-11-03 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,951 | 🐛 3,323 | 🌐 Java | 📅 2026-11-03 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,764 | 🐛 857 | 🌐 Rust | 📅 2026-11-03 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,474 | 🐛 257 | 🌐 Rust | 📅 2026-11-03 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,826 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,696 | 🐛 275 | 🌐 Java | 📅 2026-11-03 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,397 | 🐛 1,830 | 🌐 Rust | 📅 2026-11-03 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,392 | 🐛 855 | 🌐 Rust | 📅 2026-11-04 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,883 | 🐛 147 | 🌐 C# | 📅 2026-11-03 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,281 | 🐛 75 | 🌐 C++ | 📅 2026-10-30 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,237 | 🐛 1,181 | 🌐 Java | 📅 2026-11-03 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 316 | 🐛 1,330 | 🌐 Java | 📅 2026-11-03 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,797 | 🐛 2,177 | 🌐 Rust | 📅 2026-11-03 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,182 | 🐛 449 | 🌐 C | 📅 2026-11-03 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,794 | 🐛 445 | 🌐 C | 📅 2026-11-03 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,496 | 🐛 1,387 | 🌐 Java | 📅 2026-11-03 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,783 | 🐛 330 | 🌐 Rust | 📅 2026-11-03 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,426 | 🐛 774 | 🌐 Java | 📅 2026-11-03 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,583 | 🐛 9 | 🌐 Scala | 📅 2026-11-01 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,759 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,490 | 🐛 473 | 🌐 Rust | 📅 2026-11-04 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,044 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,916 | 🐛 10 | 🌐 C++ | 📅 2026-11-03 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 485 | 🐛 106 | 🌐 C | 📅 2026-11-03 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 50,736 | 🐛 8,751 | 🌐 C++ | 📅 2026-11-04 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 16,175 | 🐛 1,482 | 🌐 Java | 📅 2026-11-04 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,093 | 🐛 769 | 🌐 Java | 📅 2026-11-03 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,229 | 🐛 1,709 | 🌐 Java | 📅 2026-11-03 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,171 | 🐛 1,270 | 🌐 Java | 📅 2026-11-03 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,784 | 🐛 78 | 🌐 Java | 📅 2026-10-19 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 42,792 | 🐛 1,141 | 🌐 C++ | 📅 2026-11-03 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,566 | 🐛 2,397 | 🌐 Rust | 📅 2026-11-03 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,610 | 🐛 215 | 🌐 Rust | 📅 2026-11-03 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,924 | 🐛 47 | 🌐 Python | 📅 2026-10-31 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,024 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,300 | 🐛 146 | 🌐 C++ | 📅 2026-11-02 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,012 | 🐛 15 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 695 | 🐛 8 | 🌐 Rust | 📅 2026-11-03 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,709 | 🐛 285 | 🌐 Java | 📅 2026-11-03 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,633 | 🐛 245 | 🌐 Go | 📅 2026-11-03 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,268 | 🐛 319 | 🌐 C | 📅 2026-10-24 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 17,198 | 🐛 1,883 | 🌐 C++ | 📅 2026-11-03 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,330 | 🐛 177 | 🌐 Java | 📅 2026-11-04 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,276 | 🐛 2,305 | 🌐 C++ | 📅 2026-11-03 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 7,251 | 🐛 1,085 | 🌐 Rust | 📅 2026-11-04 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,311 | 🐛 271 | 🌐 Java | 📅 2026-11-01 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,302 | 🐛 480 | 🌐 Rust | 📅 2026-11-03 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,637 | 🐛 90 | 🌐 Thrift | 📅 2026-11-02 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 771 | 🐛 29 | 🌐 Java | 📅 2026-11-02 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,404 | 🐛 917 | 🌐 Java | 📅 2026-11-03 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,066 | 🐛 994 | 🌐 Scala | 📅 2026-11-03 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,347 | 🐛 3,072 | 🌐 Java | 📅 2026-11-03 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,441 | 🐛 819 | 🌐 Java | 📅 2026-11-03 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 403 | 🐛 94 | 🌐 Java | 📅 2026-11-03 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,352 | 🐛 195 | 🌐 Rust | 📅 2026-11-03 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,165 | 🐛 323 | 🌐 Python | 📅 2026-11-02 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 281 | 🐛 117 | 🌐 Rust | 📅 2026-11-03- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,316 | 🐛 174 | 🌐 Java | 📅 2026-11-03 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,200 | 🐛 60 | 🌐 Java | 📅 2026-11-01 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 22,312 | 🐛 2,798 | 🌐 Python | 📅 2026-11-04 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,785 | 🐛 855 | 🌐 Java | 📅 2026-11-03 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,390 | 🐛 59 | 🌐 Java | 📅 2026-11-03 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,291 | 🐛 52 | 🌐 Java | 📅 2026-11-03 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 6,051 | 🐛 478 | 🌐 Python | 📅 2026-11-03 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,675 | 🐛 153 | 🌐 Python | 📅 2026-11-03 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-10-15 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,507 | 🐛 25 | 🌐 Java | 📅 2026-09-16 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 987 | 🐛 239 | 🌐 Rust | 📅 2026-11-04 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 34,121 | 🐛 690 | 🌐 Java | 📅 2026-11-03 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,312 | 🐛 147 | 🌐 Java | 📅 2026-11-03 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,793 | 🐛 404 | 🌐 Go | 📅 2026-11-03 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,492 | 🐛 98 | 🌐 Java | 📅 2026-11-03 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,515 | 🐛 48 | 🌐 Go | 📅 2026-11-03 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,313 | 🐛 217 | 🌐 Go | 📅 2026-11-03 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,577 | 🐛 192 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 973 | 🐛 40 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,516 | 🐛 37 | 🌐 Go | 📅 2026-10-28 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 4,039 | 🐛 29 | 🌐 Go | 📅 2026-11-03 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 919 | 🐛 22 | 🌐 Go | 📅 2026-11-03 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,994 | 🐛 32 | 🌐 Go | 📅 2026-11-03 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,048 | 🐛 59 | 🌐 Scala | 📅 2026-10-19 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,549 | 🐛 174 | 🌐 Go | 📅 2026-11-03 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,126 | 🐛 57 | 🌐 TypeScript | 📅 2026-11-03 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,572 | 🐛 80 | 🌐 Java | 📅 2026-11-03 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,759 | 🐛 258 | 🌐 Java | 📅 2026-10-21 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 34,121 | 🐛 690 | 🌐 Java | 📅 2026-11-03 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,774 | 🐛 82 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,649 | 🐛 908 | 🌐 Java | 📅 2026-11-03 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,352 | 🐛 497 | 🌐 Java | 📅 2026-11-03 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,660 | 🐛 515 | 🌐 C++ | 📅 2026-10-08 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,921 | 🐛 67 | 🌐 Java | 📅 2026-11-03 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,443 | 🐛 111 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,684 | 🐛 213 | 🌐 Ruby | 📅 2026-11-03 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,406 | 🐛 755 | 🌐 Scala | 📅 2026-11-03 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,705 | 🐛 3,871 | 🌐 Java | 📅 2026-11-03 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,779 | 🐛 32 | 🌐 Java | 📅 2026-10-22 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,153 | 🐛 612 | 🌐 Rust | 📅 2026-11-04 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,709 | 🐛 285 | 🌐 Java | 📅 2026-11-03 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 522 | 🐛 76 | 🌐 Java | 📅 2026-10-27 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,443 | 🐛 429 | 🌐 Java | 📅 2026-11-03 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,282 | 🐛 903 | 🌐 Scala | 📅 2026-11-03 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,699 | 🐛 36 | 🌐 Java | 📅 2026-11-01 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,391 | 🐛 83 | 🌐 Python | 📅 2026-11-03 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,260 | 🐛 140 | 🌐 Rust | 📅 2026-11-02 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,077 | 🐛 127 | 🌐 Rust | 📅 2026-11-03 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,281 | 🐛 75 | 🌐 C++ | 📅 2026-10-30 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,186 | 🐛 151 | 🌐 Go | 📅 2026-11-02 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,070 | 🐛 76 | 🌐 Python | 📅 2026-10-31 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 844 | 🐛 45 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 44,406 | 🐛 755 | 🌐 Scala | 📅 2026-11-03 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 40,256 | 🐛 2,945 | 🌐 Rust | 📅 2026-11-03 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,276 | 🐛 2,305 | 🌐 C++ | 📅 2026-11-03 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,790 | 🐛 1,509 | 🌐 C++ | 📅 2026-11-04 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,517 | 🐛 556 | 🌐 Python | 📅 2026-10-29 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,691 | 🐛 554 | 🌐 Python | 📅 2026-11-03 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,825 | 🐛 468 | 🌐 Rust | 📅 2026-11-04 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 542 | 🐛 7 | 🌐 Python | 📅 2026-11-03 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 44,195 | 🐛 3,738 | 🌐 Python | 📅 2026-11-04 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,942 | 🐛 1,419 | 🌐 Python | 📅 2026-09-29 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,391 | 🐛 725 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,796 | 🐛 99 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,275 | 🐛 209 | 🌐 Python | 📅 2026-11-04 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,750 | 🐛 10 | 🌐 Python | 📅 2026-11-03 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,355 | 🐛 1,948 | 🌐 Python | 📅 2026-11-04 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 30,142 | 🐛 738 | 🌐 Java | 📅 2026-11-03 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Temporal](https://github.com/temporalio/temporal) ⭐ 24,167 | 🐛 1,122 | 🌐 Go | 📅 2026-11-04 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 24,107 | 🐛 874 | 🌐 Python | 📅 2026-11-03 - A Python based workflow orchestration tool
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,782 | 🐛 193 | 🌐 Python | 📅 2026-10-14 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 18,368 | 🐛 869 | 🌐 Rust | 📅 2026-11-03 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 17,080 | 🐛 1,390 | 🌐 Go | 📅 2026-11-03 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,365 | 🐛 2,620 | 🌐 Python | 📅 2026-11-03 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,550 | 🐛 124 | 🌐 Java | 📅 2026-11-03 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,536 | 🐛 214 | 🌐 Go | 📅 2026-11-03 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,840 | 🐛 639 | 🌐 Python | 📅 2026-10-23 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,845 | 🐛 191 | 🌐 Go | 📅 2026-11-04 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,512 | 🐛 802 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,852 | 🐛 40 | 🌐 Java | 📅 2026-10-30 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 29,133 | 🐛 738 | 🌐 Python | 📅 2026-11-03 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,680 | 🐛 85 | 🌐 Python | 📅 2026-10-26 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,740 | 🐛 51 | 🌐 Go | 📅 2026-11-03 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 29,287 | 🐛 594 | 🌐 Python | 📅 2026-11-03 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,914 | 🐛 59 | 🌐 Python | 📅 2026-11-02 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,508 | 🐛 460 | 🌐 Python | 📅 2026-11-03 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,657 | 🐛 63 | 🌐 Scala | 📅 2026-10-20 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,463 | 🐛 209 | 🌐 Python | 📅 2026-11-03 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,808 | 🐛 681 | 🌐 Go | 📅 2026-11-04 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,955 | 🐛 231 | 🌐 Python | 📅 2026-11-02 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,577 | 🐛 506 | 🌐 Go | 📅 2026-11-01 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,575 | 🐛 456 | 🌐 Go | 📅 2026-11-03 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,830 | 🐛 147 | 🌐 Python | 📅 2026-11-04 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,526 | 🐛 174 | 🌐 Java | 📅 2026-11-03 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 14,116 | 🐛 1,856 | 🌐 Rust | 📅 2026-11-04 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,345 | 🐛 306 | 🌐 Python | 📅 2026-11-03 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,429 | 🐛 26 | 🌐 HTML | 📅 2026-11-03 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 128,643 | 🐛 3,223 | 🌐 Go | 📅 2026-11-03 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,709 | 🐛 285 | 🌐 Java | 📅 2026-11-03 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,367 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,040 | 🐛 31 | 🌐 Go | 📅 2026-11-03 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,313 | 🐛 122 | 🌐 Java | 📅 2026-11-01 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 505 | 🐛 44 | 🌐 Java | 📅 2026-11-03 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,086 | 🐛 136 | 🌐 Java | 📅 2026-11-03 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 607 | 🐛 41 | 🌐 C | 📅 2026-11-03 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 221 | 🐛 18 | 🌐 Java | 📅 2026-11-03 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,797 | 🐛 2,177 | 🌐 Rust | 📅 2026-11-03 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,272 | 🐛 952 | 🌐 Go | 📅 2026-11-03 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,068 | 🐛 541 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,909 | 🐛 171 | 🌐 Go | 📅 2026-10-20 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,931 | 🐛 1,043 | 🌐 Go | 📅 2026-11-03 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 18,001 | 🐛 792 | 🌐 Go | 📅 2026-11-03 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,532 | 🐛 110 | 🌐 Go Template | 📅 2026-11-03 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,669 | 🐛 3,337 | 🌐 TypeScript | 📅 2026-11-04 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,355 | 🐛 14,711 | 🌐 TypeScript | 📅 2026-11-03 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,350 | 🐛 157 | 🌐 TypeScript | 📅 2026-11-03 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,792 | 🐛 2,570 | 🌐 Rust | 📅 2026-11-03 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,074 | 🐛 93 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,896 | 🐛 435 | 🌐 Go | 📅 2026-11-03 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,971 | 🐛 2,261 | 🌐 Java | 📅 2026-11-03 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,611 | 🐛 118 | 🌐 Ruby | 📅 2026-11-02 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,180 | 🐛 846 | 🌐 C | 📅 2026-11-03 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,802 | 🐛 366 | 🌐 Go | 📅 2026-10-29 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,672 | 🐛 985 | 🌐 TypeScript | 📅 2026-11-03 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,946 | 🐛 1,389 | 🌐 Python | 📅 2026-11-04 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,150 | 🐛 871 | 🌐 Python | 📅 2026-11-03 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⚠️ Archived - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,301 | 🐛 257 | 🌐 Java | 📅 2026-10-29 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,163 | 🐛 168 | 🌐 Java | 📅 2026-10-30 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,441 | 🐛 150 | 🌐 Java | 📅 2026-10-19 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,672 | 🐛 985 | 🌐 TypeScript | 📅 2026-11-03 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,740 | 🐛 400 | 🌐 Java | 📅 2026-11-03 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 925 | 🐛 49 | 🌐 Java | 📅 2026-11-03 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,038 | 🐛 133 | 🌐 Java | 📅 2026-11-03 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,569 | 🐛 460 | 🌐 Java | 📅 2026-11-03 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,346 | 🐛 1,302 | 🌐 Java | 📅 2026-11-03 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,471 | 🐛 378 | 🌐 Java | 📅 2026-11-04 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,106 | 🐛 425 | 🌐 Java | 📅 2026-11-03 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,497 | 🐛 110 | 🌐 Rust | 📅 2026-11-03 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,400 | 🐛 617 | 🌐 Python | 📅 2026-11-03 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 50,143 | 🐛 4,664 | 🌐 Clojure | 📅 2026-11-04 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,862 | 🐛 768 | 🌐 TypeScript | 📅 2026-11-03 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,220 | 🐛 1,123 | 🌐 TypeScript | 📅 2026-11-03 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 46,235 | 🐛 1,187 | 🌐 Python | 📅 2026-11-04 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,478 | 🐛 440 | 🌐 Python | 📅 2026-11-03 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 7,085 | 🐛 27 | 🌐 TypeScript | 📅 2026-11-04 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,357 | 🐛 4 | 🌐 Python | 📅 2026-10-26 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,819 | 🐛 5 | 🌐 Python | 📅 2026-11-03 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,386 | 🐛 43 | 🌐 Rust | 📅 2026-10-26 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,797 | 🐛 1,274 | 🌐 Python | 📅 2026-11-02 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,458 | 🐛 1,891 | 🌐 Jupyter Notebook | 📅 2026-10-30 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,538 | 🐛 718 | 🌐 Python | 📅 2026-11-02 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,669 | 🐛 66 | 🌐 Java | 📅 2026-11-03 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,300 | 🐛 240 | 🌐 TypeScript | 📅 2026-11-02 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,410 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-03 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,771 | 🐛 3,018 | 🌐 Java | 📅 2026-11-03 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,444 | 🐛 2,747 | 🌐 Java | 📅 2026-11-04 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,038 | 🐛 133 | 🌐 Java | 📅 2026-11-03 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,166 | 🐛 180 | 🌐 Rust | 📅 2026-11-03 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,026 | 🐛 130 | 🌐 Java | 📅 2026-10-27 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,293 | 🐛 8 | 🌐 C++ | 📅 2026-11-03 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 21,156 | 🐛 1,193 | 🌐 Rust | 📅 2026-11-03 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,257 | 🐛 1,049 | 🌐 Java | 📅 2026-09-01 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,451 | 🐛 340 | 🌐 Rust | 📅 2026-11-03 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,416 | 🐛 189 | 🌐 Java | 📅 2026-11-03 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,616 | 🐛 1,106 | 🌐 Scala | 📅 2026-11-03 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 960 | 🐛 151 | 🌐 Scala | 📅 2026-11-02 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 46,578 | 🐛 1,547 | 🌐 Go | 📅 2026-11-03 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 35,411 | 🐛 761 | 🌐 Rust | 📅 2026-11-03 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,627 | 🐛 976 | 🌐 Rust | 📅 2026-10-30 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 23,574 | 🐛 15 | 🌐 C | 📅 2026-11-03 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,934 | 🐛 831 | 🌐 Go | 📅 2026-11-03 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,841 | 🐛 601 | 🌐 Rust | 📅 2026-11-04 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,265 | 🐛 113 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,159 | 🐛 254 | 🌐 Java | 📅 2026-11-03 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,025 | 🐛 196 | 🌐 Python | 📅 2026-09-03 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,737 | 🐛 150 | 🌐 Go | 📅 2026-11-02 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 44,195 | 🐛 3,738 | 🌐 Python | 📅 2026-11-04 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 28,654 | 🐛 2,208 | 🌐 Python | 📅 2026-11-03 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,849 | 🐛 25 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,948 | 🐛 1 | 📅 2026-09-30 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 11,042 | 🐛 124 | 🌐 Python | 📅 2026-11-03 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,787 | 🐛 524 | 🌐 Python | 📅 2026-11-03 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,338 | 🐛 530 | 🌐 Python | 📅 2026-11-03 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,934 | 🐛 256 | 🌐 Python | 📅 2026-11-02 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,311 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,245 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 160,343 | 🐛 1,248 | 🌐 Python | 📅 2026-11-03 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 96,243 | 🐛 9,822 | 🌐 Python | 📅 2026-11-03 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 33,031 | 🐛 1,086 | 🌐 Python | 📅 2026-11-03 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,922 | 🐛 217 | 🌐 Python | 📅 2026-11-03 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,330 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-04._
