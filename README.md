
# Awesome Kafka [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **amazing things related to Apache Kafka** – tools, libraries, frameworks, learning resources, and more.

Apache Kafka is the **de-facto standard for real-time data streaming**, powering event-driven systems, pipelines, and microservices at scale.
This repo collects the **best resources in the Kafka ecosystem**.

---

## 📚 Contents

- [Awesome Kafka ](#awesome-kafka-)
  - [📚 Contents](#-contents)
  - [📖 Learning Resources](#-learning-resources)
  - [💻 Clients \& SDKs](#-clients--sdks)
    - [Official](#official)
    - [Python](#python)
    - [Node.js / JavaScript / TypeScript](#nodejs--javascript--typescript)
    - [Go](#go)
    - [C / C++](#c--c)
    - [Rust](#rust)
    - [.NET / C#](#net--c)
    - [Scala](#scala)
    - [PHP](#php)
    - [Ruby](#ruby)
    - [Erlang / Elixir](#erlang--elixir)
    - [Haskell](#haskell)
    - [Julia](#julia)
  - [🛠 Kafka Management Tools](#-kafka-management-tools)
  - [🔌 Kafka Connectors](#-kafka-connectors)
  - [📦 Schema \& Data Formats](#-schema--data-formats)
  - [📊 Monitoring \& Observability](#-monitoring--observability)
  - [🔒 Security](#-security)
  - [📚 Books \& Talks](#-books--talks)
  - [🌍 Community \& Blogs](#-community--blogs)
  - [🤝 Contributing](#-contributing)
  - [📜 License](#-license)

---

## 📖 Learning Resources

* [Apache Kafka Official Docs](https://kafka.apache.org/documentation/)
* [Confluent Kafka Tutorials](https://developer.confluent.io/learn-kafka/)
* [Kafka in a Nutshell (LinkedIn Engineering Blog)](https://engineering.linkedin.com/kafka)
* [Kafka Internals (GitHub Guide)](https://github.com/jpzk/missing-kafka-docs)
* [Kafka Streams 101](https://kafka.apache.org/documentation/streams/)

---

## 💻 Clients & SDKs

### Official

* [kafka-clients (Java)](https://mvnrepository.com/artifact/org.apache.kafka/kafka-clients) – Official Java client

### Python

* [confluent-kafka-python](https://github.com/confluentinc/confluent-kafka-python) – Confluent-maintained Python client (librdkafka based)
* [pykafka](https://github.com/Parsely/pykafka) – Pure Python client (no longer actively maintained but widely used)

### Node.js / JavaScript / TypeScript

* [kafkajs](https://github.com/tulios/kafkajs) – Modern Node.js client with TypeScript support
* [node-rdkafka](https://github.com/Blizzard/node-rdkafka) – Node.js bindings for librdkafka

### Go

* [Sarama](https://github.com/Shopify/sarama) – Go client for Kafka
* [confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) – Go bindings for librdkafka

### C / C++

* [librdkafka](https://github.com/edenhill/librdkafka) – C/C++ client, used by many other language bindings

### Rust

* [rust-rdkafka](https://github.com/fede1024/rust-rdkafka) – Rust wrapper for librdkafka
* [kafka-rust](https://github.com/kafka-rust/kafka-rust) – Pure Rust client (less active than rust-rdkafka)

### .NET / C\#

* [Confluent.Kafka](https://github.com/confluentinc/confluent-kafka-dotnet) – .NET client for Apache Kafka

### Scala

* [Alpakka Kafka (Reactive Kafka)](https://github.com/akka/alpakka-kafka) – Kafka connector for Akka Streams

### PHP

* [php-rdkafka](https://github.com/arnaud-lb/php-rdkafka) – PHP bindings for librdkafka

### Ruby

* [ruby-kafka](https://github.com/zendesk/ruby-kafka) – Kafka client for Ruby
* [racecar](https://github.com/zendesk/racecar) – Framework for Kafka-based Ruby apps

### Erlang / Elixir

* [brod](https://github.com/klarna/brod) – Erlang Kafka client
* [kafka\_ex](https://github.com/kafkaex/kafka_ex) – Elixir Kafka client

### Haskell

* [haskakafka](https://github.com/haskell-works/hw-kafka-client) – Haskell client using librdkafka

### Julia

* [Kafka.jl](https://github.com/JuliaData/Kafka.jl) – Julia client for Kafka

---

## 🛠 Kafka Management Tools

* [KLogic](https://klogic.io) – AI Powered Kafka observability & monitoring platform
* [Conduktor](https://www.conduktor.io/) – Kafka UI & monitoring suite
* [Kpow](https://kpow.io/) – Kafka observability for ops & devs
* [Lenses.io](https://lenses.io/) – Kafka monitoring & data explorer
* [Kafka Tool](http://www.kafkatool.com/) – GUI for Kafka cluster management
* [AKHQ](https://github.com/tchiotludo/akhq) – Kafka UI for topics, consumers, brokers

---

## 🔌 Kafka Connectors

* [Kafka Connect Hub](https://www.confluent.io/hub/) – Official marketplace
* [Debezium](https://debezium.io/) – Change Data Capture (CDC) for MySQL, PostgreSQL, MongoDB, etc.
* [Stream Reactor](https://github.com/lensesio/stream-reactor) – Connectors for Cassandra, Elastic, InfluxDB, and more
* [Redpanda Connect](https://redpanda.com/connectors) – Alternative connector ecosystem

---

## 📦 Schema & Data Formats

* [Confluent Schema Registry](https://docs.confluent.io/platform/current/schema-registry/index.html)
* [Apicurio Registry](https://www.apicur.io/registry/) – Schema registry alternative
* [Avro](https://avro.apache.org/) – Popular Kafka serialization format
* [Protobuf](https://developers.google.com/protocol-buffers) – Compact binary format
* [JSON Schema](https://json-schema.org/) – Human-readable schema definition

---

## 📊 Monitoring & Observability

* [KLogic](https://klogic.io) – Kafka dashboards, logs, and metrics
* [Burrow](https://github.com/linkedin/Burrow) – Consumer lag checking tool
* [Cruise Control](https://github.com/linkedin/cruise-control) – Kafka cluster balancing
* [Prometheus JMX Exporter](https://github.com/prometheus/jmx_exporter) – Expose Kafka metrics
* [Datadog Kafka Integration](https://docs.datadoghq.com/integrations/kafka/)
* [New Relic Kafka Monitoring](https://docs.newrelic.com/docs/infrastructure/host-integrations/host-integrations-list/kafka/kafka-config/)
* [Atatus Kafka Monitoring](https://www.atatus.com/)

---

## 🔒 Security

* [Kafka Security Docs](https://kafka.apache.org/documentation/#security)
* [Kafka SSL Setup Guide](https://docs.confluent.io/platform/current/kafka/encryption.html)
* [RBAC in Kafka](https://docs.confluent.io/platform/current/security/rbac/index.html)
* [OAuth & SASL Integration](https://docs.confluent.io/platform/current/security/authentication/sasl/oauthbearer/overview.html)

---

## 📚 Books & Talks

* [Kafka: The Definitive Guide](https://www.confluent.io/resources/ebook/kafka-the-definitive-guide/) by Neha Narkhede, Gwen Shapira, Todd Palino
* [Designing Event-Driven Systems](https://www.oreilly.com/library/view/designing-event-driven-systems/9781492038252/) by Ben Stopford
* [Kafka Summit Talks](https://www.kafka-summit.org/)
* [YouTube: Confluent Kafka Tutorials](https://www.youtube.com/c/Confluent)

---

## 🌍 Community & Blogs

* [Apache Kafka Blog](https://kafka.apache.org/blog)
* [Confluent Blog](https://www.confluent.io/blog/)
* [Redpanda Blog](https://redpanda.com/blog)
* [Strimzi Blog](https://strimzi.io/blog/)
* [KLogic Blog](https://klogic.io/blog/)
* [Kafka Users Mailing List](https://kafka.apache.org/contact)

---

## 🤝 Contributing

Contributions welcome! Please check the [contributing guidelines](./CONTRIBUTING.md).

---

## 📜 License

[![License: Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](./LICENSE)

---
