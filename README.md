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

* [Supabase](https://github.com/supabase/supabase) ⭐ 114,031 | 🐛 1,166 | 🌐 TypeScript | 📅 2026-10-26 - An open source Firebase alternative
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,593 | 🐛 0 | 🌐 C | 📅 2026-10-26 - Advanced object-relational database management system
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,479 | 🐛 129 | 🌐 C++ | 📅 2026-10-26 - One of the most popular open Source Databases
* [SQlite](https://github.com/sqlite/sqlite) ⭐ 10,821 | 🐛 26 | 🌐 C | 📅 2026-10-26 - Most popular embedded database engine
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,453 | 🐛 575 | 🌐 C++ | 📅 2026-10-26 - A popular MySQL server fork

### Distributed SQL DBMS

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,682 | 🐛 7,457 | 🌐 Go | 📅 2026-10-26 - A cloud-native, distributed, MySQL-Compatible database
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,585 | 🐛 8,228 | 🌐 Go | 📅 2026-10-21 - A cloud-native distributed SQL database
* [Neon](https://github.com/neondatabase/neon) ⭐ 23,262 | 🐛 578 | 🌐 Rust | 📅 2026-08-31 - A serverless open-source alternative to AWS Aurora Postgres
* [ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,815 | 🐛 258 | 🌐 Java | 📅 2026-10-26 - A Distributed SQL transaction & query engine
* [Citus](https://github.com/citusdata/citus) ⭐ 12,827 | 🐛 465 | 🌐 C | 📅 2026-10-26 - A popular distributed PostgreSQL as an extension
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,630 | 🐛 8,688 | 🌐 C | 📅 2026-10-26 - A cloud-native distributed SQL database
* [OceanBase](https://github.com/oceanbase/oceanbase) ⭐ 10,353 | 🐛 609 | 🌐 C++ | 📅 2026-10-23 - A scalable distributed relational database
* [CrateDB](https://github.com/crate/crate) ⭐ 4,447 | 🐛 321 | 🌐 Java | 📅 2026-10-26 - A distributed and scalable PostgreSQL-compatible SQL database

### Cache Store

* [Redis](https://github.com/redis/redis) ⭐ 77,127 | 🐛 3,077 | 🌐 C | 📅 2026-10-26 - A popular key-value based cache store
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,824 | 🐛 276 | 🌐 C++ | 📅 2026-10-26 - A modern cache store compatible with Redis and Memcached APIs
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,300 | 🐛 121 | 🌐 C | 📅 2026-09-11 - A high performance multithreadedkey-value cache store

### In-memory SQL Database

* [ReadySet](https://github.com/readysettech/readyset) ⭐ 5,296 | 🐛 121 | 🌐 Rust | 📅 2026-10-26 - A MySQL and Postgres wire-compatible caching layer
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,088 | 🐛 921 | 🌐 Java | 📅 2026-10-26 - A distributed, ACID-compliant in-memory DBMS
* [VoltDB](https://github.com/voltdb/) - A distributed, horizontally-scalable, ACID-compliant database

### Document Store

* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,661 | 🐛 38 | 🌐 C++ | 📅 2026-10-26 - A cross-platform, document-oriented NoSQL database
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,008 | 🐛 1,349 | 🌐 C++ | 📅 2026-10-26 | ⚠️ Inactive | - A distributed document-oriented database for real-time applications
* [LowDB](https://github.com/typicode/lowdb) ⭐ 22,584 | 🐛 17 | 🌐 JavaScript | 📅 2026-03-27 | ⚠️ Inactive | - A simple and fast JSON database
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,107 | 🐛 449 | 🌐 Go | 📅 2026-06-05 - A truly Open Source MongoDB alternative!
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,990 | 🐛 372 | 🌐 Erlang | 📅 2026-10-26 - A Scalable document-oriented NoSQL database
* [RavenDB](https://github.com/ravendb/ravendb) ⭐ 4,012 | 🐛 70 | 🌐 C# | 📅 2026-10-26 - An ACID NoSQL document database
* [Couchbase](https://github.com/couchbase) - A modern cloud-native NoSQL distributed database

### NoSQL Multi-model

* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 33,237 | 🐛 448 | 🌐 Rust | 📅 2026-10-19 - A scalable, distributed, collaborative, document-graph database
* [ArrangoDB](https://github.com/arangodb/arangodb) ⭐ 14,287 | 🐛 819 | 🌐 C++ | 📅 2026-10-26 - A Multi-model database with flexible data models for documents, graphs, and key-values
* [EdgeDB](https://github.com/edgedb/edgedb) ⭐ 14,176 | 🐛 948 | 🌐 Python | 📅 2025-12-24 - A graph-relational database with declarative schema
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,996 | 🐛 385 | 🌐 Java | 📅 2026-10-26 - A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models

### Graph Database

* [Dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,812 | 🐛 101 | 🌐 Go | 📅 2026-10-26 - A horizontally scalable and distributed GraphQL database with a graph backend
* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,363 | 🐛 235 | 🌐 Java | 📅 2026-10-23 - A high performance leading graph database
* [Cayley](https://github.com/cayleygraph/cayley) ⭐ 15,065 | 🐛 93 | 🌐 Go | 📅 2026-08-27 | ⚠️ Inactive | - Inspired by the graph database behind Google's Knowledge Graph
* [NebulaGraph](https://github.com/vesoft-inc/nebula) ⭐ 12,452 | 🐛 694 | 🌐 C++ | 📅 2026-09-08 - A distributed, horizontal scalability, fast open-source graph database
* [FalkorDB](https://github.com/FalkorDB/falkordb) ⭐ 10,495 | 🐛 856 | 🌐 Rust | 📅 2026-10-26 - A graph database that uses GraphBLAS under the hood, tailored for LLMs
* [JunasGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,866 | 🐛 580 | 🌐 Java | 📅 2026-10-25 - A highly scalable distributed graph database
* [Apache Age](https://github.com/apache/age) ⭐ 4,916 | 🐛 260 | 🌐 C | 📅 2026-10-13 - A graph database as an extension to PostgreSQL
* [HugeGraph](https://github.com/apache/incubator-hugegraph) ⭐ 3,195 | 🐛 378 | 🌐 Java | 📅 2026-10-26 - A fast-speed and highly-scalable graph database

### Distributed Key-value Store

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,429 | 🐛 400 | 🌐 Go | 📅 2026-10-26 - A distributed reliable key-value store written in Go
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 27,527 | 🐛 963 | 🌐 C | 📅 2026-10-26 - A distributed key-value datastore forked from Redis
* [TiKV](https://github.com/tikv/tikv) ⭐ 16,928 | 🐛 2,000 | 🌐 Rust | 📅 2026-10-26 - A distributed transactional key-value database, originally created to complement TiDB
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,818 | 🐛 794 | 🌐 C++ | 📅 2026-10-26 - A distributed, transactional key-value store from Apple
* [Immudb](https://github.com/codenotary/immudb) ⭐ 9,044 | 🐛 116 | 🌐 Go | 📅 2026-10-21 - A database with built-in cryptographic proof and verification
* [Apache Kvrocks](https://github.com/apache/kvrocks) ⭐ 4,481 | 🐛 279 | 🌐 C++ | 📅 2026-10-26 - A distributed key-value database that uses RocksDB as storage engine
* [Riak](https://github.com/basho/riak) ⭐ 4,028 | 🐛 150 | 🌐 Shell | 📅 2026-08-14 | ⚠️ Inactive | - A decentralized key-value datastore from Basho Technologies

### Wide-column Key-value Store

* [Scylla](https://github.com/scylladb/scylladb) ⭐ 15,809 | 🐛 3,029 | 🌐 C++ | 📅 2026-10-26 - LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,119 | 🐛 548 | 🌐 Java | 📅 2026-10-26 - A highly-scalable LSM-Tree based partitioned row store
* [Apache Hbase](https://github.com/apache/hbase) ⭐ 5,571 | 🐛 420 | 🌐 Java | 📅 2026-10-26 - A distributed wide column-oriented store modeled after Google' Bigtable
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,182 | 🐛 353 | 🌐 Java | 📅 2026-10-26 - A distributed key-value store with scalable data storage and retrieval, on top of Hadoop

### Embedded Key-value Store

* [LevelDB](https://github.com/google/leveldb) ⭐ 39,512 | 🐛 427 | 🌐 C++ | 📅 2026-10-08 | ⚠️ Inactive | - A fast key-value storage library written at Google
* [RocksDB](https://github.com/facebook/rocksdb) ⭐ 32,227 | 🐛 1,792 | 🌐 C++ | 📅 2026-10-26 - An embeddable, persistent key-value store developed by Meta (Facebook)
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,790 | 🐛 80 | 🌐 Go | 📅 2026-10-20 - An embeddable, fast key-value database written in pure Go
* [MyRocks](https://github.com/facebook/mysql-5.6) ⚠️ Archived - A RocksDB storage engine for MySQL

### Search Engine

* [Elastic Search](https://github.com/elastic/elasticsearch) ⭐ 78,398 | 🐛 6,200 | 🌐 Java | 📅 2026-10-26 - A distributed, RESTful search engine optimized for speed
* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,682 | 🐛 320 | 🌐 Rust | 📅 2026-10-26 - A fast search API with great integration support
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,910 | 🐛 3,297 | 🌐 Java | 📅 2026-10-26 - A community-driven, open source fork of Elasticsearch and Kibana
* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,744 | 🐛 853 | 🌐 Rust | 📅 2026-10-26 - A fast cloud-native search engine for observability data
* [ParadeDB](https://github.com/paradedb/paradedb) ⭐ 9,453 | 🐛 242 | 🌐 Rust | 📅 2026-10-26 - A search engine built on Postgres
* [Sphinx](https://github.com/sphinxsearch/sphinx) ⭐ 1,826 | 🐛 20 | 🌐 C++ | 📅 2023-12-19 | ⚠️ Inactive | - A fulltext search engine with high speed of indexation
* [Apache Solr](https://github.com/apache/solr) ⭐ 1,691 | 🐛 271 | 🌐 Java | 📅 2026-10-26 - A fast distributed search database built on Apache Lucene

### Streaming Database

* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,389 | 🐛 1,793 | 🌐 Rust | 📅 2026-10-26 - A scalable Postgres for stream processing, analytics, and management
* [Materialize](https://github.com/MaterializeInc/materialize) ⭐ 6,388 | 🐛 860 | 🌐 Rust | 📅 2026-10-26 - A real-time data warehouse purpose-built for operational workloads
* [EventStoreDB](https://github.com/EventStore/EventStore) ⭐ 5,875 | 🐛 146 | 🌐 C# | 📅 2026-10-24 - An event-native database designed for event sourcing and event-driven architectures
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,275 | 🐛 75 | 🌐 C++ | 📅 2026-10-12 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Fluss](https://github.com/alibaba/fluss) ⭐ 2,230 | 🐛 1,136 | 🌐 Java | 📅 2026-10-26 - A streaming storage serving as the real-time data layer for Lakehouse architectures
* [KsqlDB](https://github.com/confluentinc/ksql) ⭐ 316 | 🐛 1,328 | 🌐 Java | 📅 2026-10-26 - A database for building stream processing applications on top of Apache Kafka

### Time-Series Database

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,786 | 🐛 2,180 | 🌐 Rust | 📅 2026-10-26 - A scalable datastore for metrics, events, and real-time analytics
* [TDEngine](https://github.com/taosdata/TDengine) ⭐ 25,172 | 🐛 446 | 🌐 C | 📅 2026-10-26 - A high-performance, cloud native time-series database optimized for Internet of Things (IoT)
* [TimeScaleDB](https://github.com/timescale/timescaledb) ⭐ 23,764 | 🐛 443 | 🌐 C | 📅 2026-10-26 - A fast ingest time-series SQL database packaged as a PostgreSQL extension
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,477 | 🐛 1,307 | 🌐 Java | 📅 2026-10-26 - A time-series database for fast ingest and SQL queries
* [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,767 | 🐛 336 | 🌐 Rust | 📅 2026-10-26 - A cloud-native, unified time series database for metrics, logs and events
* [Apache IoTDB](https://github.com/apache/iotdb) ⭐ 6,424 | 🐛 763 | 🌐 Java | 📅 2026-10-26 - An Internet of Things database with seamless integration with the Hadoop and Spark ecology
* [Netflix Atlas](https://github.com/Netflix/atlas) ⭐ 3,578 | 🐛 10 | 🌐 Scala | 📅 2026-10-23 - An n-memory dimensional time series database developed and open sourced by Netflix
* [HoraeDB](https://github.com/apache/horaedb) ⚠️ Archived - A distributed, cloud native time-series database
* [KairosDB](https://github.com/kairosdb/kairosdb) ⭐ 1,760 | 🐛 141 | 🌐 Java | 📅 2026-03-05 | ⚠️ Inactive | - A scalable time series database written in Java

### Columnar OLAP Database

* [Databend](https://github.com/datafuselabs/databend) ⭐ 9,482 | 🐛 430 | 🌐 Rust | 📅 2026-10-26 - An lastic, workload-aware cloud-native data warehouse built in Rust
* [Hydra](https://github.com/hydradatabase/hydra) ⭐ 3,042 | 🐛 33 | 🌐 C | 📅 2025-02-10 | ⚠️ Inactive | - A column-oriented Postgres extension
* [ByConity](https://github.com/ByConity/ByConity) ⚠️ Archived - A cloud-native data warehouse forked from ClickHouse
* [Apache Kudu](https://github.com/apache/kudu) ⭐ 1,915 | 🐛 10 | 🌐 C++ | 📅 2026-10-26 -  A column-oriented data store for the Apache Hadoop ecosystem
* [MonetDB](https://github.com/MonetDB/MonetDB) ⭐ 485 | 🐛 105 | 🌐 C | 📅 2026-10-26 - A high-performance columnar database originally developed by the CWI database research group
* [Greeenplum](https://github.com/greenplum-db/gpdb-archive) ⚠️ Archived | ⛔️ Archived | -  A column-oriented massively parallel PostgreSQL for analytics

### Real-time OLAP Engine

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 50,615 | 🐛 8,457 | 🌐 C++ | 📅 2026-10-26 - A real-time column-oriented database originally developed at Yandex
* [Apache Doris](https://github.com/apache/doris) ⭐ 16,144 | 🐛 1,351 | 🌐 Java | 📅 2026-10-26 - A high-performance and real-time analytical database based on MPP architecture
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,095 | 🐛 774 | 🌐 Java | 📅 2026-10-26 - A high performance real-time OLAP engine developed and open sourced by Metamarkets
* [StarRocks](https://github.com/StarRocks/StarRocks) ⭐ 12,208 | 🐛 1,596 | 🌐 Java | 📅 2026-10-26 -  A sub-second OLAP database supporting multi-dimensional analytics (Linux Foundation project)
* [Apache Pinot](https://github.com/apache/pinot) ⭐ 6,169 | 🐛 1,295 | 🌐 Java | 📅 2026-10-26 - A a real-time distributed OLAP datastore open sourced by LinkedIn
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,783 | 🐛 78 | 🌐 Java | 📅 2026-10-19 - A distributed OLAP engine designed to provide multi-dimensional analysis on Hadoop

### In-process OLAP Engine

* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 42,596 | 🐛 1,055 | 🌐 C++ | 📅 2026-10-26 - An in-process SQL OLAP Database Management System
* [Apache DataFusion](https://github.com/apache/datafusion) ⭐ 9,535 | 🐛 2,475 | 🌐 Rust | 📅 2026-10-26 - An extensible query engine with SQL and Dataframe APIs
* [SlateDB](https://github.com/slatedb/slatedb) ⭐ 3,593 | 🐛 216 | 🌐 Rust | 📅 2026-10-26 - A cloud-native embedded storage engine built on object storage
* [chdb](https://github.com/chdb-io/chdb) ⭐ 2,920 | 🐛 46 | 🌐 Python | 📅 2026-10-13 - An in-process OLAP SQL Engine powered by ClickHouse
* [GlareDB](https://github.com/GlareDB/glaredb) ⭐ 1,024 | 🐛 130 | 🌐 Rust | 📅 2025-11-14 - A SQL database for running analytics across distributed data

### OLAP Extensions

* [pg\_duckdb](https://github.com/duckdb/pg_duckdb) ⭐ 3,275 | 🐛 146 | 🌐 C++ | 📅 2026-07-17 - A Postgres extension that embeds DuckDB's analytics engine
* [pg\_mooncake](https://github.com/Mooncake-Labs/pg_mooncake) ⭐ 2,011 | 🐛 15 | 🌐 Rust | 📅 2026-03-31 - A columnar storage extension for Postres based on DuckDB
* [pg\_parquet](https://github.com/CrunchyData/pg_parquet) ⭐ 693 | 🐛 11 | 🌐 Rust | 📅 2026-10-26 - A Postgres extension for reading and writing data lake Parquet files
* [pg\_analytics](https://github.com/paradedb/pg_analytics) ⚠️ Archived - A DuckDB-powered analytics extension for Postgres

## DATA LAKE PLATFORM

### Distributed File System

* [Apache Hadoop HDFS](https://github.com/apache/hadoop) ⭐ 15,699 | 🐛 272 | 🌐 Java | 📅 2026-10-26 - A highly scalable distributed block-based file system
* [JuiceFS](https://github.com/juicedata/juicefs) ⭐ 14,580 | 🐛 251 | 🌐 Go | 📅 2026-10-26 - A distributed POSIX file system built on top of Redis and S3
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,264 | 🐛 309 | 🌐 C | 📅 2026-10-24 | ⚠️ Inactive | - A scalable distributed storage that can scale to several petabytes
* [Lustre](https://github.com/lustre) - A distributed parallel file system purpose-built to provide global POSIX-compliant namespace

### Distributed Object Store

* [Minio](https://github.com/minio/minio) ⚠️ Archived - A high performance object storage being API compatible with Amazon S3
* [Ceph](https://github.com/ceph/ceph) ⭐ 17,170 | 🐛 1,828 | 🌐 C++ | 📅 2026-10-26 - A distributed object, block, and file storage platform
* [Apache Ozone](https://github.com/apache/ozone) ⭐ 1,320 | 🐛 150 | 🌐 Java | 📅 2026-10-26 - A scalable, redundant, and distributed object store for Apache Hadoop
* [Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage) - A S3-compatible distributed object storage designed for self-hosting at a small-to-medium scale

### Serialisation Framework

* [Arrow Feather](https://github.com/apache/arrow) ⭐ 17,232 | 🐛 2,305 | 🌐 C++ | 📅 2026-10-26 - A portable file format for storing Arrow tables or data frames
* [Lance](https://github.com/lancedb/lance) ⭐ 7,216 | 🐛 1,109 | 🌐 Rust | 📅 2026-10-26 - A modern columnar data format for ML and LLMs implemented in Rust
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,308 | 🐛 268 | 🌐 Java | 📅 2026-10-26 - An efficient and fast row-based binary serialisation framework
* [Vortex](https://github.com/spiraldb/vortex) ⭐ 3,284 | 🐛 426 | 🌐 Rust | 📅 2026-10-26 - A highly extensible and fast columnar file format
* [Apache Parquet](https://github.com/apache/parquet-format) ⭐ 2,630 | 🐛 88 | 🌐 Thrift | 📅 2026-10-26 - An efficient columnar binary storage format that supports nested data
* [Apache ORC](https://github.com/apache/orc) ⭐ 770 | 🐛 21 | 🌐 Java | 📅 2026-10-26 - A self-describing type-aware columnar file format designed for Hadoop

### Open Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,371 | 🐛 942 | 🌐 Java | 📅 2026-10-26 -  A high-performance table format for large analytic tables developed at Netflix
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,056 | 🐛 992 | 🌐 Scala | 📅 2026-10-26 - A storage framework for building Lakehouse architecture developed by Databricks
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,343 | 🐛 3,043 | 🌐 Java | 📅 2026-10-26 - An open table format desined to support incremental data ingestion on cloud and Hadoop
* [Apache Paimon](https://github.com/apache/incubator-paimon) ⭐ 3,433 | 🐛 791 | 🌐 Java | 📅 2026-10-26 - An Apache inclubating project to support streaming high-speed data ingestion
* [OpenHouse](https://github.com/linkedin/openhouse) ⭐ 402 | 🐛 100 | 🌐 Java | 📅 2026-10-26 - A declarative catalog with data services for open Data Lakehouse formats

### Native Open Table Format Library

* [Delta-rs](https://github.com/delta-io/delta-rs) ⭐ 3,350 | 🐛 167 | 🌐 Rust | 📅 2026-10-26 - A native Rust library for Delta Lake, with bindings into Python
* [PyIceberg](https://github.com/apache/iceberg-python) ⭐ 1,160 | 🐛 257 | 🌐 Python | 📅 2026-10-26 - A native Python library for interacting with Iceberg table format
* [Hudi-rs](https://github.com/apache/hudi-rs) ⭐ 280 | 🐛 87 | 🌐 Rust | 📅 2026-10-24- A native Rust library for Apache Hudi, with bindings into Python

### Universal Lakehouse

* [Apache XTable](https://github.com/apache/incubator-xtable) ⭐ 1,311 | 🐛 176 | 🌐 Java | 📅 2026-10-26 - A unified framework supporting interoperability across multiple open-source table formats
* [Apache Amoro](https://github.com/apache/amoro) ⭐ 1,199 | 🐛 63 | 🌐 Java | 📅 2026-10-26 - A Lakehouse management system built on open data lake formats

## DATA INTEGRATION

### Data Integration Platform

* [Airbyte](https://github.com/airbytehq/airbyte) ⭐ 22,272 | 🐛 2,674 | 🌐 Python | 📅 2026-10-26 - A data integration platform for ETL / ELT data pipelines with wide range of connectors
* [Apache SeaTunnel](https://github.com/apache/seatunnel) ⭐ 9,763 | 🐛 835 | 🌐 Java | 📅 2026-10-26 - A high-performance, distributed data integration tool supporting vairous ingestion patterns
* [Apache Camel](https://github.com/apache/camel) ⭐ 6,380 | 🐛 58 | 🌐 Java | 📅 2026-10-26 - An embeddable integration framework supporting many enterprise integration patterns
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,277 | 🐛 55 | 🌐 Java | 📅 2026-10-26 - A reliable, scalable low-code data integration platform with good enterprise support
* [dlt](https://github.com/dlt-hub/dlt) ⭐ 6,017 | 🐛 473 | 🌐 Python | 📅 2026-10-26 - A lightweight data integration library for Python-first data platforms
* [Meltano](https://github.com/meltano/meltano) ⭐ 2,670 | 🐛 149 | 🌐 Python | 📅 2026-10-26 - A declarative code-first data integration engine
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 143 | 🌐 Java | 📅 2026-10-15 - A distributed data integration framework built by LinkedIn supporting both streaming and batch data
* [Apache Inlong](https://github.com/apache/Inlong) ⭐ 1,507 | 🐛 25 | 🌐 Java | 📅 2026-09-16 - An integration framework for supporting massive data, originally built at Tencent
* [Estuary Flow](https://github.com/estuary/flow) ⭐ 985 | 🐛 243 | 🌐 Rust | 📅 2026-10-26 - A real-time ETL and data pipeline platform for quick data integration

### CDC Tool

* [Kafka Connect](https://github.com/apache/kafka) ⭐ 34,134 | 🐛 668 | 🌐 Java | 📅 2026-10-26 - A streaming data integration framework and runtime on top of Apache Kafka supporting CDC
* [Debezium](https://github.com/debezium/debezium) ⭐ 13,276 | 🐛 128 | 🌐 Java | 📅 2026-10-26 - A change data capture framework supporting variety of databases
* [Redpanda Conenct](https://github.com/redpanda-data/connect) ⭐ 8,790 | 🐛 378 | 🌐 Go | 📅 2026-10-26 - A data streaming and integration framework on top of Redpanda
* [Flink CDC](https://github.com/apache/flink-cdc) ⭐ 6,488 | 🐛 95 | 🌐 Java | 📅 2026-10-26 - CDC Connectors for Apache Flink engine supporting different databases
* [RudderStack](https://github.com/rudderlabs/rudder-server) ⭐ 4,506 | 🐛 42 | 🌐 Go | 📅 2026-10-26 - A headless Customer Data Platform to build data pipelines, open alternative to Segment
* [PeerDB](https://github.com/PeerDB-io/peerdb) ⭐ 3,310 | 🐛 217 | 🌐 Go | 📅 2026-10-26 - A CDC tool to replicate data from Postgres to data warehouses, queues and other storage
* [Dozer](https://github.com/getdozer/dozer) ⭐ 1,578 | 🐛 187 | 🌐 Rust | 📅 2024-06-18 - A real-time CDC based data integration tool between various sources and sinks
* [Brooklin](https://github.com/linkedin/brooklin) ⭐ 972 | 🐛 37 | 🌐 Java | 📅 2026-08-19 | ⚠️ Inactive | - A distributed platform for streaming data between various heterogeneous source and destination systems
* [Artie Transfer](https://github.com/artie-labs/transfer) - A real-time CDC replication solution between OLTP and OLAP databases

### Data Migration

* [DBmate](https://github.com/amacneil/dbmate) ⭐ 7,492 | 🐛 34 | 🌐 Go | 📅 2026-10-18 - A lightweight, framework-agnostic database migration tool.
* [Ingestr](https://github.com/bruin-data/ingestr) ⭐ 4,030 | 🐛 33 | 🌐 Go | 📅 2026-10-26 - A CLI tool to copy data between any databases with a single command
* [Sling](https://github.com/slingdata-io/sling-cli) ⭐ 917 | 🐛 23 | 🌐 Go | 📅 2026-10-22 - A CLI tool to transfer data from a source to target storage/database

### Log & Event Collection

* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,991 | 🐛 32 | 🌐 Go | 📅 2026-10-22 - A zero-ETL solution for getting data directly from APIs and services
* [Snowplow](https://github.com/snowplow/snowplow) ⭐ 7,046 | 🐛 59 | 🌐 Scala | 📅 2026-10-19 | ⚠️ Inactive | - A cloud-native engine for collecting behavioral data and load into various cloud storage systems
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,543 | 🐛 169 | 🌐 Go | 📅 2026-10-26 - An ETL tool for syncing data from cloud APIs to variety of supported destinations
* [Jitsu](https://github.com/jitsucom/jitsu) ⭐ 5,117 | 🐛 58 | 🌐 TypeScript | 📅 2026-10-26 - A fully-scriptable data ingestion engine for collecting event data
* [Apache Flume](https://github.com/apache/flume) ⭐ 2,573 | 🐛 84 | 🌐 Java | 📅 2026-10-05 | ⚠️ Inactive | - A scalable distributed log aggregation service
* [EventMesh](https://github.com/apache/eventmesh) ⭐ 1,758 | 🐛 257 | 🌐 Java | 📅 2026-10-21 - A serverless event middlewar for collecting and loading event data into various targets

### Event Hub

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 34,134 | 🐛 668 | 🌐 Java | 📅 2026-10-26 - A highly scalable distributed event store and streaming platform
* [NSQ](https://github.com/nsqio/nsq) ⭐ 25,772 | 🐛 82 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform designed to operate at scale
* [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,644 | 🐛 922 | 🌐 Java | 📅 2026-10-26 - A a cloud native messaging and streaming platform
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,355 | 🐛 477 | 🌐 Java | 📅 2026-10-26 - A scalable distributed pub-sub messaging system
* [Redpanda](https://github.com/redpanda-data/redpanda) ⭐ 12,643 | 🐛 516 | 🌐 C++ | 📅 2026-10-08 - A high performance Kafka API compatible streaming data platform
* [AutoMQ](https://github.com/AutoMQ/automq) ⭐ 10,922 | 🐛 70 | 🌐 Java | 📅 2026-10-26 - A a cloud-first alternative to Kafka using S3 as the main storage layer
* [Memphis](https://github.com/memphisdev/memphis) ⭐ 3,444 | 🐛 110 | 🌐 Go | 📅 2026-03-02 | ⚠️ Inactive | - A scalable data streaming platform for building event-driven applications

### Reverse ETL

* [Multiwoven](https://github.com/Multiwoven/multiwoven) ⭐ 1,683 | 🐛 204 | 🌐 Ruby | 📅 2026-10-24 - A Reverse ETL open source alternative to Hightouch and RudderStack

## DATA PROCESSING AND COMPUTATION

### Unified Processing

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,331 | 🐛 702 | 🌐 Scala | 📅 2026-10-26 - A unified analytics engine for large-scale data processing
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,696 | 🐛 3,887 | 🌐 Java | 📅 2026-10-26 - A unified programming model supporting execution on popular distributed processing backends
* [Dinky](https://github.com/DataLinkDC/dinky) ⭐ 3,775 | 🐛 31 | 🌐 Java | 📅 2026-10-22 - A unified streaming & batch computation platform based on Apache Flink
* [Feldora](https://github.com/feldera/feldera) ⭐ 2,138 | 🐛 609 | 🌐 Rust | 📅 2026-10-26 - A unified incremental computation engine

### Batch processing

* [Hadoop MapReduce](https://github.com/apache/hadoop) ⭐ 15,699 | 🐛 272 | 🌐 Java | 📅 2026-10-26 - A  highly scalable distributed batch processing framework from Apache Hadoop project
* [Apache Tez](https://github.com/apache/tez) ⭐ 522 | 🐛 79 | 🌐 Java | 📅 2026-10-08 - A distributed data processing pipeline built for Apache Hive and Hadoop

### Stream Processing

* [Apache Flink](https://github.com/apache/flink) ⭐ 26,426 | 🐛 413 | 🌐 Java | 📅 2026-10-26 - A scalable high throughput stream processing framework
* [Akka](https://github.com/akka/akka) ⭐ 13,281 | 🐛 901 | 🌐 Scala | 📅 2026-10-16 - A highly concurrent, distributed, message-driven processing system based on Actor Model
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,698 | 🐛 34 | 🌐 Java | 📅 2026-10-26 - A distributed realtime computation system based on  Actor Model framework
* [FastStream](https://github.com/airtai/faststream) ⭐ 5,384 | 🐛 90 | 🌐 Python | 📅 2026-10-26 - A Python framework for interacting with event streams such as Apache Kafka
* [Fluvio](https://github.com/infinyon/fluvio) ⭐ 5,261 | 🐛 140 | 🌐 Rust | 📅 2026-10-13 - A lean distributed stream processing system written in Rust and web assembly
* [Arroyo](https://github.com/ArroyoSystems/arroyo) ⭐ 5,068 | 🐛 131 | 🌐 Rust | 📅 2026-10-26 - A distributed stream processing engine written in Rust
* [Timeplus Proton](https://github.com/timeplus-io/proton) ⭐ 2,275 | 🐛 75 | 🌐 C++ | 📅 2026-10-12 - A streaming SQL engine, fast and lightweight, powered by ClickHouse
* [Bento](https://github.com/warpstreamlabs/bento) ⭐ 2,173 | 🐛 157 | 🌐 Go | 📅 2026-10-26 - A stream processing engine from WarpStream Labs (forked from Benthos)
* [Bytewax](https://github.com/bytewax/bytewax) ⭐ 2,060 | 🐛 75 | 🌐 Python | 📅 2026-10-25 - A Python stream processing framework with a Rust distributed processing engine
* [Apache Samza](https://github.com/apache/samza) ⭐ 844 | 🐛 45 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Kafka and Hadoop, originally developed by LinkedIn

### Python Processing Framework

* [PySpark](https://github.com/apache/spark) ⭐ 44,331 | 🐛 702 | 🌐 Scala | 📅 2026-10-26 - An interface for Apache Spark in Python
* [Polars](https://github.com/pola-rs/polars) ⭐ 40,209 | 🐛 2,945 | 🌐 Rust | 📅 2026-10-26 - A multithreaded Dataframe with vectorized query engine, written in Rust
* [Apache Arrow](https://github.com/apache/arrow) ⭐ 17,232 | 🐛 2,305 | 🌐 C++ | 📅 2026-10-26 - An efficient in-memory data format
* [cuDF](https://github.com/rapidsai/cudf) ⭐ 9,781 | 🐛 1,455 | 🌐 C++ | 📅 2026-10-26 -  A GPU-accelerated pandas API dataFrame library
* [Vaex](https://github.com/vaexio/vaex) ⭐ 8,516 | 🐛 558 | 🌐 Python | 📅 2026-04-01 - A high performance Python library for  big tabular datasets.
* [Ibis](https://github.com/ibis-project/ibis) ⭐ 6,682 | 🐛 547 | 🌐 Python | 📅 2026-10-26 - A portable Python dataframe library supporting many engine backends
* [Daft](https://github.com/Eventual-Inc/Daft) ⭐ 5,814 | 🐛 438 | 🌐 Rust | 📅 2026-10-26 - A distributed query engine for large-scale data processing using Python or SQL
* [SQLFrame](https://github.com/eakmanrq/sqlframe) ⭐ 541 | 🐛 7 | 🌐 Python | 📅 2026-10-26 - A Spark DataFrame API compatible library for data transformation

### Python Workflow Scaling

* [RAY](https://github.com/ray-project/ray) ⭐ 44,128 | 🐛 3,638 | 🌐 Python | 📅 2026-10-26 - A unified framework with distributed runtime for scaling Python applications
* [Dask](https://github.com/dask/dask) ⭐ 13,939 | 🐛 1,406 | 🌐 Python | 📅 2026-09-29 - A flexible parallel computing library with task scheduling
* [Modin](https://github.com/modin-project/modin) ⭐ 10,392 | 🐛 724 | 🌐 Python | 📅 2026-02-10 - A library for scaling Pandas workflows to multi-threded execution
* [Pandaral·lel](https://github.com/nalepae/pandarallel) ⭐ 3,796 | 🐛 99 | 🌐 Python | 📅 2024-07-09 | ⚠️ Inactive | - A library to parallelize Pandas operations on all available CPUs

### SQL Toolkit

* [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,266 | 🐛 213 | 🌐 Python | 📅 2026-10-26 - A Python SQL toolkit and Object Relational Mapper
* [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 9,725 | 🐛 4 | 🌐 Python | 📅 2026-10-26 - A Python SQL parser and transpiler

## WORKFLOW MANAGEMENT & DATAOPS

### Workflow Orchestration

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,284 | 🐛 1,938 | 🌐 Python | 📅 2026-10-26 - A plaform for creating and scheduling workflows as directed acyclic graphs (DAGs) of tasks
* [Kestra](https://github.com/kestra-io/kestra) ⭐ 30,020 | 🐛 844 | 🌐 Java | 📅 2026-10-26 - A declarative language-agnostic worfklow orchestration and scheduling platform
* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 24,081 | 🐛 897 | 🌐 Python | 📅 2026-10-26 - A Python based workflow orchestration tool
* [Temporal](https://github.com/temporalio/temporal) ⭐ 24,001 | 🐛 1,081 | 🌐 Go | 📅 2026-10-26 - A resilient workflow management system, originated as a fork of Uber's Cadence
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,784 | 🐛 194 | 🌐 Python | 📅 2026-10-14 - A python library for building complex pipelines of batch jobs
* [Windmill](https://github.com/windmill-labs/windmill) ⭐ 18,278 | 🐛 877 | 🌐 Rust | 📅 2026-10-26 - A fast workflow engine, and open-source alternative to Airplane and Retool
* [Argo](https://github.com/argoproj/argo-workflows) ⭐ 17,055 | 🐛 1,356 | 🌐 Go | 📅 2026-10-26 - A container-native workflow engine for orchestrating parallel jobs on Kubernetes
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,331 | 🐛 2,613 | 🌐 Python | 📅 2026-10-26 - A cloud-native data pipeline orchestrator written in Python
* [Apache DolpinScheduler](https://github.com/apache/dolphinscheduler) ⭐ 14,537 | 🐛 115 | 🌐 Java | 📅 2026-10-24 - A low-code high performance workflow orchestration platform
* [Cadence](https://github.com/uber/cadence) ⭐ 9,522 | 🐛 211 | 🌐 Go | 📅 2026-10-26 - A distributed, scalable available orchestration supporting different language client libraries
* [Mage.ai](https://github.com/mage-ai/mage-ai) ⭐ 8,837 | 🐛 636 | 🌐 Python | 📅 2026-10-23 - A platform for integrating, cheduling and managing data pipelines
* [Flyte](https://github.com/flyteorg/flyte) ⭐ 7,766 | 🐛 203 | 🌐 Go | 📅 2026-10-26 - A scalable and flexible workflow orchestration platform for both data and ML workloads
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,511 | 🐛 802 | 🌐 Java | 📅 2024-07-03 | ⚠️ Inactive | - A batch workflow job scheduler created at LinkedIn to run Hadoop jobs
* [Maestro](https://github.com/Netflix/maestro) ⭐ 3,846 | 🐛 39 | 🌐 Java | 📅 2026-10-23 - A general-purpose workflow orchestrator developed by Netflix

### Job Scheduling

* [Celery](https://github.com/celery/celery) ⭐ 29,076 | 🐛 741 | 🌐 Python | 📅 2026-10-26 - A distributed Task Queue system for Python
* [ApScheduler](https://github.com/agronholm/apscheduler/) ⭐ 7,672 | 🐛 82 | 🌐 Python | 📅 2026-10-26 - An advanced task scheduler and task queue system for Python
* [DKron](https://github.com/distribworks/dkron) ⭐ 4,740 | 🐛 47 | 🌐 Go | 📅 2026-10-26 - A distributed, fault tolerant job scheduling system

### Data Quality

* [Pydantic](https://github.com/pydantic/pydantic) ⭐ 29,205 | 🐛 589 | 🌐 Python | 📅 2026-10-26 - A data validation library using Python type hints
* [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐ 11,904 | 🐛 57 | 🌐 Python | 📅 2026-10-22 - A data validation and profiling tool written in Python
* [Pandera](https://github.com/unionai-oss/pandera) ⭐ 4,499 | 🐛 458 | 🌐 Python | 📅 2026-10-26 - A light-weight, flexible, and expressive statistical data testing library
* [Deeque](https://github.com/awslabs/deequ) ⭐ 3,656 | 🐛 62 | 🌐 Scala | 📅 2026-10-20 - A library based on Apache Spark for measuring data quality in large datasets
* [Data-diff](https://github.com/datafold/data-diff) ⚠️ Archived | ⛔️ Archived | - A tool for comparing tables within or across databases
* [Soda](https://github.com/sodadata/soda-core) ⭐ 2,453 | 🐛 208 | 🌐 Python | 📅 2026-10-26 - A CLI tool and Python library for data quality testing

### Data Versioning

* [Dolt](https://github.com/dolthub/dolt) ⭐ 24,744 | 🐛 604 | 🌐 Go | 📅 2026-10-26 - A Git for data tool
* [DVC](https://github.com/iterative/dvc) ⭐ 15,942 | 🐛 227 | 🌐 Python | 📅 2026-10-26 - A data version control tool for data and ML experiments
* [Git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,565 | 🐛 499 | 🌐 Go | 📅 2026-10-23 - A Git extension for versioning large files
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,570 | 🐛 455 | 🌐 Go | 📅 2026-10-21 - A data version control for data stored in data lakes
* [Datachain](https://github.com/iterative/datachain) ⭐ 2,829 | 🐛 137 | 🌐 Python | 📅 2026-10-26 - A Python-based framework for versioning for unstructured Data
* [Project Nessie](https://github.com/projectnessie/nessie) ⭐ 1,524 | 🐛 165 | 🌐 Java | 📅 2026-10-26 - A transactional Catalog for Data Lakes with Git-like semantics

### Data Modeling

* [dbt](https://github.com/dbt-labs/dbt-core) ⭐ 14,087 | 🐛 1,823 | 🌐 Rust | 📅 2026-10-26 - A data modeling and transformation tool for data pipelines
* [SQLMesh](https://github.com/TobikoData/sqlmesh) ⭐ 3,332 | 🐛 297 | 🌐 Python | 📅 2026-10-26 - A data transformation and modeling framework that is backwards compatible with dbt

### Pipeline Observability

* [Elementry](https://github.com/elementary-data/elementary) ⭐ 2,428 | 🐛 24 | 🌐 HTML | 📅 2026-10-22 - A dbt-native data observability solution to monitor data pipelines

## DATA INFRASTRUCTURE

### Resource Scheduling

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 128,721 | 🐛 3,253 | 🌐 Go | 📅 2026-10-26 - A production-grade container scheduling and management tool
* [Apache Yarn](https://github.com/apache/hadoop) ⭐ 15,699 | 🐛 272 | 🌐 Java | 📅 2026-10-26 - The default Resource Scheduler for Apache Hadoop clusters
* [Apache Mesos](https://github.com/apache/mesos) ⭐ 5,366 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - A resource scheduling and cluster resource abstraction framework developed by Ph.D. students at UC Berkeley
* [Apache YuniKorn](https://github.com/apache/yunikorn-core) ⭐ 1,037 | 🐛 27 | 🌐 Go | 📅 2026-10-16 - A light-weight, universal resource scheduler for container orchestrator systems
* [Docker](https://github.com/docker) - The popular OS-level virtualization and containerization software

### Cluster Administration

* [Apache Ambari](https://github.com/apache/ambari) ⭐ 2,312 | 🐛 125 | 🌐 Java | 📅 2026-10-26 - A tool for provisioning, managing, and monitoring of Apache Hadoop clusters
* [Apache Helix](https://github.com/apache/helix) ⭐ 505 | 🐛 41 | 🌐 Java | 📅 2026-10-20 - A generic cluster management framework developed at LinkedIn

### Security

* [Apache Ranger](https://github.com/apache/ranger) ⭐ 1,084 | 🐛 132 | 🌐 Java | 📅 2026-10-26 - A security and governance platform for Hadoop and other popular services
* [Kerberos](https://github.com/krb5/krb5) ⭐ 607 | 🐛 52 | 🌐 C | 📅 2026-09-05 - A popular enterprise network authentication protocol
* [Apache Knox](https://github.com/apache/knox) ⭐ 220 | 🐛 9 | 🌐 Java | 📅 2026-10-26 - A gateway and SSO service for managing access to Hadoop clusters

### Metrics Store

* [Influxdb](https://github.com/influxdata/influxdb) ⭐ 31,786 | 🐛 2,180 | 🌐 Rust | 📅 2026-10-26 - A scalable datastore for metrics and events
* [Mimir](https://github.com/grafana/mimir) ⭐ 5,262 | 🐛 909 | 🌐 Go | 📅 2026-10-26 - A scalable long-term metrics storage for Prometheus, developed by Grafana Labs
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) ⭐ 5,066 | 🐛 541 | 🌐 Java | 📅 2024-12-12 - A distributed, scalable Time Series Database written on top of Apache Hbase
* [M3](https://github.com/m3db/m3) ⭐ 4,909 | 🐛 171 | 🌐 Go | 📅 2026-10-20 - A distributed TSDB and metrics storage and aggregator

### Observability Framework

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,792 | 🐛 1,020 | 🌐 Go | 📅 2026-10-26 - A popular metric collection and management tool
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,911 | 🐛 788 | 🌐 Go | 📅 2026-10-26 - An scalable monitoring solution with a time series database
* [Zabbix](https://github.com/zabbix/zabbix) ⭐ 6,512 | 🐛 109 | 🌐 Go Template | 📅 2026-10-23 - A real-time infrastructure and application monitoring service
* [ELK](https://www.elastic.co/elastic-stack) - A poular observability stack comprsing of Elasticsearch, Kibana, Beats, and Logstash
* [Graphite](https://github.com/graphite-project) - An established infrastructure monitoring and observability system
* [OpenTelemetry](https://github.com/open-telemetry) - A collection of APIs, SDKs, and tools for managing and monitoring metrics

### Monitoring Dashboard

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,529 | 🐛 3,310 | 🌐 TypeScript | 📅 2026-10-26 - A popular open and composable observability and data visualization platform
* [Kibana](https://github.com/elastic/kibana) ⭐ 21,338 | 🐛 14,829 | 🌐 TypeScript | 📅 2026-10-26 - The visualistion and search dashboard for Elasticsearch
* [Redpanda Console](https://github.com/redpanda-data/console) ⭐ 4,345 | 🐛 155 | 🌐 TypeScript | 📅 2026-10-24 - A UI for monitoring and managing Apache Kafka and Redpanda workloads

### Log & Metrics Pipeline

* [Vector](https://github.com/vectordotdev/vector) ⭐ 22,771 | 🐛 2,529 | 🌐 Rust | 📅 2026-10-26 - A  high-performance, end-to-end (agent & aggregator) observability data pipeline
* [StatsD](https://github.com/statsd/statsd) ⭐ 18,078 | 🐛 93 | 🌐 JavaScript | 📅 2025-05-20 | ⚠️ Inactive | - A network daemon for collection, aggregation and routing of metrics
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,884 | 🐛 462 | 🌐 Go | 📅 2026-10-26 - A plugin-driven server agent for collecting & reporting metrics developed by Influxdata
* [Logstash](https://github.com/elastic/logstash) ⭐ 14,970 | 🐛 2,265 | 🌐 Java | 📅 2026-10-26 - A server-side log and metric transport and processor, as part of the ELK stack
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,612 | 🐛 120 | 🌐 Ruby | 📅 2026-10-26 - A metric collection, buffering and router service
* [Fluent Bit](https://github.com/fluent/fluent-bit) ⭐ 8,170 | 🐛 818 | 🌐 C | 📅 2026-10-26 - A fast log processor and forwarder, and part of the Fluentd ecosystem

### Cost Management

* [OpenCost](https://github.com/opencost/opencost) ⭐ 6,795 | 🐛 358 | 🌐 Go | 📅 2026-10-26 - Cost monitoring for Kubernetes workloads and cloud costs

## METADATA MANAGEMENT

### Metadata Platform

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,587 | 🐛 915 | 🌐 TypeScript | 📅 2026-10-26 - A unified platform for discovery and governance, using a central metadata repository
* [DataHub](https://github.com/datahub-project/datahub) ⭐ 12,894 | 🐛 1,390 | 🌐 Python | 📅 2026-10-26 - A metadata platform for the modern data stack developed at Netflix
* [ckan](https://github.com/ckan/ckan) ⭐ 5,147 | 🐛 867 | 🌐 Python | 📅 2026-10-26 - A data management system  for cataloging, managing and accessing data
* [Amundsen](https://github.com/amundsen-io/amundsen) ⚠️ Archived - A data discovery and metadata engine developed by Lyft engineers
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,300 | 🐛 257 | 🌐 Java | 📅 2026-10-26 - A metadata service for the collection, aggregation, and visualization of metadata
* [Apache Atlas](https://github.com/apache/atlas) ⭐ 2,157 | 🐛 170 | 🌐 Java | 📅 2026-10-26 - A data observability platform for Apache Hadoop ecosystem
* [ODD Platform](https://github.com/opendatadiscovery/odd-platform) ⭐ 1,438 | 🐛 150 | 🌐 Java | 📅 2026-10-19 - A data discovery and observability platform

### Open Standards

* [Open Metadata](https://github.com/open-metadata/OpenMetadata) ⭐ 15,587 | 🐛 915 | 🌐 TypeScript | 📅 2026-10-26 - A unified metadata platform providing open stadards for managing metadata
* [Open Lineage](https://github.com/OpenLineage/OpenLineage) ⭐ 2,726 | 🐛 413 | 🌐 Java | 📅 2026-10-25 - An open standard for lineage metadata collection
* [Egeria](https://github.com/odpi/egeria) ⭐ 925 | 🐛 29 | 🌐 Java | 📅 2026-10-26 - Open metadata and governance standards to facilitate metadata exchange

### Schema & Catalog Service

* [Hive Metastore](https://github.com/apache/hive) ⭐ 6,037 | 🐛 130 | 🌐 Java | 📅 2026-10-26 - A popular schema management and metastore service as part of the Apache hive project
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) ⭐ 3,563 | 🐛 462 | 🌐 Java | 📅 2026-10-26 - A Universal catalog for Data Lakehouse formats and other data/AI assets
* [Apache Gravitino](https://github.com/apache/gravitino) ⭐ 3,332 | 🐛 1,234 | 🌐 Java | 📅 2026-10-26 - A geo-distributed and federated open data catalog
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry) ⭐ 2,470 | 🐛 381 | 🌐 Java | 📅 2026-10-26 - A schema registry for Kafka, developed by Confluent
* [Apache Polaris](https://github.com/apache/polaris) ⭐ 2,098 | 🐛 415 | 🌐 Java | 📅 2026-10-26 - An interoperable, open source catalog for Apache Iceberg
* [Lakekeeper](https://github.com/lakekeeper/lakekeeper) ⭐ 1,490 | 🐛 114 | 🌐 Rust | 📅 2026-10-26 - A Rust native Apache Iceberg REST Catalog

## ANALYTICS & VISUALISATION

### BI & Dashboard

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,322 | 🐛 608 | 🌐 Python | 📅 2026-10-26 - A poular open source data visualization and data exploration platform
* [Metabase](https://github.com/metabase/metabase) ⭐ 49,858 | 🐛 4,579 | 🌐 Clojure | 📅 2026-10-26 - A simple data visualisation and exploration dashboard
* [Redash](https://github.com/getredash/redash) ⭐ 28,849 | 🐛 817 | 🌐 Python | 📅 2026-10-26 - A tool to explore, query, visualize, and share data with many data source connectors
* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,200 | 🐛 1,106 | 🌐 TypeScript | 📅 2026-10-26 - A self-service BI to turn dbt project into a full-stack BI platform

## BI as Code (Web App)

* [Streamlit](https://github.com/streamlit/streamlit) ⭐ 46,143 | 🐛 1,191 | 🌐 Python | 📅 2026-10-26 - A python tool to package and share data as web apps
* [dash](https://github.com/plotly/dash) ⭐ 24,471 | 🐛 432 | 🌐 Python | 📅 2026-10-26 - A Python framework for building ML & data science web apps
* [Evidence](https://github.com/evidence-dev/evidence) ⭐ 7,059 | 🐛 17 | 🌐 TypeScript | 📅 2026-10-23 - A tool to build interactive data visualizations in pure SQL and markdown
* [Mercury](https://github.com/mljar/mercury) ⭐ 4,359 | 🐛 4 | 🌐 Python | 📅 2026-10-26 - A tool to convert Jupyter Notebooks to web apps
* [Vizro](https://github.com/mckinsey/vizro) ⭐ 3,811 | 🐛 3 | 🌐 Python | 📅 2026-10-26 - A toolkit for creating modular data visualization applications
* [Quary](https://github.com/quarylabs/quary) ⭐ 2,385 | 🐛 43 | 🌐 Rust | 📅 2026-10-26 - A code-based BI solution

### Query & Collaboration

* [IPython](https://github.com/ipython/ipython) ⭐ 16,796 | 🐛 1,287 | 🌐 Python | 📅 2026-10-23 - An enhanced interactive Python shell for data analysis
* [Jupyter](https://github.com/jupyter/notebook) ⭐ 13,460 | 🐛 1,893 | 🌐 Jupyter Notebook | 📅 2026-10-20 - A popular interactive web-based notebook application
* [Datasette](https://github.com/simonw/datasette) ⭐ 11,524 | 🐛 708 | 🌐 Python | 📅 2026-10-23 - A tool for exploring and publishing data
* [Apache Zeppelin](https://github.com/apache/zeppelin) ⭐ 6,667 | 🐛 63 | 🌐 Java | 📅 2026-10-26 - A web-base Notebook for interactive data analytics and collaboration for Hadoop
* [Querybook](https://github.com/pinterest/querybook) ⭐ 2,300 | 🐛 241 | 🌐 TypeScript | 📅 2026-09-16 - A simple query and notebook UI developed by Pinterest
* [Hue](https://github.com/cloudera/hue) ⭐ 1,406 | 🐛 9 | 🌐 JavaScript | 📅 2026-10-26 - A query and data exploration tool with Hadoop ecosystem support, developed by Cloudera

### MPP Query Engine

* [Presto](https://github.com/prestodb/presto) ⭐ 16,763 | 🐛 3,020 | 🌐 Java | 📅 2026-10-26 - A distributed SQL query engine for big data
* [Trino](https://github.com/trinodb/trino) ⭐ 13,369 | 🐛 2,732 | 🌐 Java | 📅 2026-10-26 - The former PrestoSQL distributed SQL query engine
* [Apache Hive](https://github.com/apache/hive) ⭐ 6,037 | 🐛 130 | 🌐 Java | 📅 2026-10-26 - A data warehousing and MPP engine on top of Hadoop
* [DataFusion Ballista](https://github.com/apache/datafusion-ballista) ⭐ 2,157 | 🐛 181 | 🌐 Rust | 📅 2026-10-26 - A distributed query execution engine based on Apache DataFusion
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,027 | 🐛 128 | 🌐 Java | 📅 2026-10-25 - A distributed MPP query engine against NoSQL and Hadoop data storage systems
* [Apache Implala](https://github.com/apache/impala) ⭐ 1,292 | 🐛 8 | 🌐 C++ | 📅 2026-10-26 - A MPP engine mainly for Hadoop clusters, developed by Cloudera

### Semantic & Middleware Layer

* [Cube](https://github.com/cube-js/cube) ⭐ 21,080 | 🐛 1,156 | 🌐 Rust | 📅 2026-10-26 - A semantic layer for building data applications supporting popular databse engines
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,255 | 🐛 1,048 | 🌐 Java | 📅 2026-09-01 - A data orchestration and virtual distributed storage system
* [Apache OpenDAL](https://github.com/apache/opendal) ⭐ 5,427 | 🐛 361 | 🌐 Rust | 📅 2026-10-23 - An open data access Llyer that enables seamless interaction with diverse storage services
* [Apache Linkis](https://github.com/apache/linkis) ⭐ 3,415 | 🐛 186 | 🌐 Java | 📅 2026-10-22 - A computation middleware to facilitate connection and orchestration between applications and data engines
* [Apache Gluten](https://github.com/apache/incubator-gluten) ⭐ 1,610 | 🐛 1,093 | 🌐 Scala | 📅 2026-10-26 - A middle layer for offloading JVM-based SQL engines execution to native engines

### Data Sharing

* [delta-sharing](https://github.com/delta-io/delta-sharing) ⭐ 960 | 🐛 152 | 🌐 Scala | 📅 2026-10-26 - An open protocol for secure real-time exchange of large datasets

## ML/AI PLATFORM

### Vector Storage

* [milvus](https://github.com/milvus-io/milvus) ⭐ 46,488 | 🐛 1,470 | 🌐 Go | 📅 2026-10-26 -  A cloud-native vector database, storage for AI applications
* [qdrant](https://github.com/qdrant/qdrant) ⭐ 35,265 | 🐛 803 | 🌐 Rust | 📅 2026-10-26 - A high-performance, scalable Vector database for AI
* [chroma](https://github.com/chroma-core/chroma) ⭐ 29,589 | 🐛 979 | 🌐 Rust | 📅 2026-10-26 - An AI-native embedding database for building LLM apps
* [pgvector](https://github.com/pgvector/pgvector) ⭐ 23,487 | 🐛 15 | 🌐 C | 📅 2026-10-26 - A vector similarity search as a Postgres extension
* [weaviate](https://github.com/weaviate/weaviate) ⭐ 16,920 | 🐛 812 | 🌐 Go | 📅 2026-10-26 - A scalable, cloud-native supporting storage of both objects and vectors
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,782 | 🐛 677 | 🌐 Rust | 📅 2026-10-26 - A serverless vector database for AI applications written in Rust
* [deeplake](https://github.com/activeloopai/deeplake) ⭐ 9,260 | 🐛 131 | 🌐 C++ | 📅 2026-05-21 -  A storage format optimized AI database for deep-learning applications
* [Vespa](https://github.com/vespa-engine/vespa) ⭐ 7,149 | 🐛 266 | 🌐 Java | 📅 2026-10-26 - A storage to organize vectors, tensors, text and structured data
* [marqo](https://github.com/marqo-ai/marqo) ⭐ 5,030 | 🐛 196 | 🌐 Python | 📅 2026-09-03 - An end-to-end vector search engine for both text and images
* [vald](https://github.com/vdaas/vald) ⭐ 1,734 | 🐛 151 | 🌐 Go | 📅 2026-10-23 - A scalable distributed approximate nearest neighbor (ANN) dense vector search engine

### MLOps

* [RAY](https://github.com/ray-project/ray) ⭐ 44,128 | 🐛 3,638 | 🌐 Python | 📅 2026-10-26 - A unified framework for scaling AI and Python applications
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 28,546 | 🐛 2,227 | 🌐 Python | 📅 2026-10-26 - A a platform to streamline machine learning development and lifecycle management
* [Jina](https://github.com/jina-ai/jina) ⭐ 21,854 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - A tool to build multimodal AI applications with cloud-native stack
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,928 | 🐛 1 | 📅 2026-09-30 - A cloud-native platform for ML operations - pipelines, training and deployment
* [NNI](https://github.com/microsoft/nni) ⚠️ Archived | ⛔️ Archived | - An autoML toolkit for automate machine learning lifecycle, from Microsoft
* [Kedro](https://github.com/kedro-org/kedro) ⭐ 11,035 | 🐛 128 | 🌐 Python | 📅 2026-10-26 - A toolbox and framework for building production-ready data science and ML workflows
* [SkyPilot](https://github.com/skypilot-org/skypilot) ⭐ 10,752 | 🐛 513 | 🌐 Python | 📅 2026-10-26 - A framework for running LLMs, AI, and batch jobs on any cloud
* [Metaflow](https://github.com/Netflix/metaflow) ⭐ 10,318 | 🐛 532 | 🌐 Python | 📅 2026-10-26 - A tool to build and manage ML/AI, and data science projects, developed at Netflix
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,920 | 🐛 245 | 🌐 Python | 📅 2026-10-23 - A framework for building reliable and scalable AI applications
* [Pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,314 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - A calable ML and Data Science data processing workflow management platform
* [Determined AI](https://github.com/determined-ai/determined) ⭐ 3,244 | 🐛 108 | 🌐 Go | 📅 2025-03-20 - An ML platform that simplifies distributed training, tuning and experiment tracking

### LLMOps

* [Dify](https://github.com/langgenius/dify) ⭐ 159,627 | 🐛 1,202 | 🌐 Python | 📅 2026-10-26 - LLM development platform nwith AI workflow, RAG pipeline and model management
* [vLLM](https://github.com/vllm-project/vllm) ⭐ 95,621 | 🐛 9,496 | 🌐 Python | 📅 2026-10-26 - A high-throughput and memory-efficient inference and serving engine for LLMs
* [Cognee](https://github.com/topoteretes/cognee) ⭐ 32,783 | 🐛 1,063 | 🌐 Python | 📅 2026-10-26 - LLM Memory Engine for implementing LLM Workflows
* [Haystack](https://github.com/deepset-ai/haystack) ⭐ 26,849 | 🐛 188 | 🌐 Python | 📅 2026-10-26 - AI orchestration framework to build customizable, production-ready LLM applications
* [Superduper](https://github.com/superduper-io/superduper) ⭐ 5,327 | 🐛 36 | 🌐 Python | 📅 2025-09-01 - a Python based framework for building AI-data workflows and applications

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-26._
