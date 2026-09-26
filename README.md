# Awesome Event Mesh Platform ⚡

[![Banner](./assets/banner.svg)](https://github.com/ishandutta2007/Awesome-Event-Mesh-Platform)

<p bottom="10px" align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Mesh-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Event-Mesh-Platform?style=flat-square" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Mesh-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Event-Mesh-Platform?style=flat-square" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Mesh-Platform/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Event-Mesh-Platform?style=flat-square" alt="Issues"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Mesh-Platform/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Event-Mesh-Platform?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🚀 Top Event Mesh Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Multi-Protocol Event Routing, Hybrid/Multi-Cloud Event Distribution, Event-Driven Integration & Dynamic Event Meshes*

**Last updated: September 2026**

---

### 📌 Overview & Architecture

This repository tracks notable **SaaS platforms** and **open-source projects** for **Event Mesh**. An event mesh is an architecture layer composed of interconnected event brokers that dynamically routes events across applications, multi-cloud deployments, edge locations, and data centers. It supports multiple protocols (AMQP, MQTT, CloudEvents, Kafka protocol, REST, WebSockets) to enable real-time, event-driven integration at enterprise scale.

**Examples** include Solace PubSub+, TIBCO FTL, IBM Event Streams, Red Hat AMQ Streams, Confluent Cloud, Azure Event Grid, Amazon EventBridge, Boomi Event Streams, and Ably.

---

## ☁️ SaaS/Hosted Platforms

> [!NOTE]
> **Market Insights & Industry Dynamics:**  
> The global Event Mesh and Event-Driven Architecture (EDA) software market is estimated at **$4.5 Billion to $5.2 Billion (2026)** with a compound annual growth rate (CAGR) of over **21%**. The sector is **moderately fragmented**: hyper-scaler cloud providers (AWS EventBridge, Azure Event Grid) dominate serverless cloud-native event buses, while enterprise multi-cloud event mesh capabilities are led by specialized vendors like Solace, Confluent, and IBM.

| Rank | SaaS Platform | Provider / Company | Size (Revenue / Valuation) 📊 | Starting Price 💵 | Free Tier / Trial Limits 🎁 | Key Features & Highlights 🌟 |
| :---: | :--- | :--- | :---: | :--- | :--- | :--- |
| 1 | **[Amazon EventBridge](https://aws.amazon.com/eventbridge/)** | Amazon Web Services (AWS) | ~$128.7B Annual AWS Revenue / ~$2.5T Parent Market Cap | $1.00 per 1M custom events published | 14 Million free invocations/month (Scheduler) + 1M free events/mo | Serverless event bus routing events across AWS services, SaaS apps, and custom webhooks. |
| 2 | **[Azure Event Grid](https://azure.microsoft.com/)** | Microsoft Azure | ~$101.9B Annual Azure Revenue / ~$3.6T Parent Market Cap | $0.60 per 1M operations (Basic Tier) | 100,000 operations free per month | Fully managed event routing service supporting pub/sub and MQTT brokering on Azure. |
| 3 | **[IBM Event Streams](https://www.ibm.com/)** | IBM Corporation | ~$65.0B Annual Revenue / ~$200B+ Market Cap | $1,500/month per instance base | 30-day free trial on IBM Cloud | Enterprise-grade Kafka event streaming with connectors, schema governance, and hybrid support. |
| 4 | **[Red Hat AMQ Streams](https://www.redhat.com/)** | Red Hat (IBM Subsidiary) | ~$6.5B Annual Revenue / Acquired for $34B | $2,500 per cluster/year (Subscription) | 60-day free Red Hat evaluation trial | Enterprise Apache Kafka deployed on Kubernetes/OpenShift with Strimzi operator governance. |
| 5 | **[TIBCO FTL](https://www.tibco.com/)** | Cloud Software Group (TIBCO) | ~$1.5B Annual Revenue / ~$3.94B Enterprise Value | $5,000 per production core/year | 30-day evaluation license | Low-latency, ultra-high performance messaging and event distribution engine for enterprise systems. |
| 6 | **[Confluent Cloud](https://www.confluent.io/)** | Confluent Inc. (Acquired by IBM) | ~$1.0B+ Annual Revenue / Acquired for $11B | $0.13/hour per Basic Kafka Cluster Unit (CKU) | $400 free credit valid for 30 days upon registration | Complete Kafka streaming platform with managed connectors, stream processing, and governance. |
| 7 | **[Boomi Event Streams](https://boomi.com/)** | Boomi LP | ~$500M Annual Revenue / ~$1.6B Valuation | $2,000/month starter add-on package | Free Starter tier included with Boomi Integration account | Cloud-native event streaming integrated directly into the Boomi iPaaS ecosystem. |
| 8 | **[Ably](https://ably.com/)** | Ably Real-time Ltd | ~$25M Annual Revenue / ~$200M Valuation | $29/month base (Standard Package) | Free Plan: 6M messages/mo, 200 channels, 200 connections | Serverless pub/sub, presence, and real-time event delivery infrastructure across edge networks. |
| 9 | **[Solace PubSub+](https://solace.com/)** | Solace Corporation | ~$100M Annual Revenue / $1.0B Valuation | $1,200/month managed cloud broker pack | Standard Edition: Free software broker up to 1,000 concurrent connections | Industry benchmark for dynamic event mesh, multi-protocol (MQTT, AMQP, JMS, REST, Kafka) routing. |

---

## 🔓 Open-Source GitHub Projects

Below is a curated selection of open-source event brokers, event mesh engines, and cloud-native building blocks.

> **Note on Star Count & Links:** Each repository star badge links directly to its official GitHub stargazers page.

| Rank | Repository | Stars ⭐️ | Language | Description & Primary Architectural Focus 🛠️ |
| :---: | :--- | :---: | :---: | :--- |
| 1 | **[Apache Kafka](https://github.com/apache/kafka)** | [![Stars](https://img.shields.io/github/stars/apache/kafka?style=social&color=white)](https://github.com/apache/kafka/stargazers) | Java / Scala | Distributed event streaming platform used as durable event backbone for event meshes. |
| 2 | **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)** | [![Stars](https://img.shields.io/github/stars/rabbitmq/rabbitmq-server?style=social&color=white)](https://github.com/rabbitmq/rabbitmq-server/stargazers) | Erlang | Widely adopted open-source message broker supporting AMQP, MQTT, and STOMP protocols. |
| 3 | **[NATS Server](https://github.com/nats-io/nats-server)** | [![Stars](https://img.shields.io/github/stars/nats-io/nats-server?style=social&color=white)](https://github.com/nats-io/nats-server/stargazers) | Go | Cloud-native, ultra-fast messaging system with JetStream persistence for edge and multi-cloud meshes. |
| 4 | **[Apache Pulsar](https://github.com/apache/pulsar)** | [![Stars](https://img.shields.io/github/stars/apache/pulsar?style=social&color=white)](https://github.com/apache/pulsar/stargazers) | Java | Multi-tenant, cloud-native messaging and streaming broker with separated compute/storage. |
| 5 | **[EMQX](https://github.com/emqx/emqx)** | [![Stars](https://img.shields.io/github/stars/emqx/emqx?style=social&color=white)](https://github.com/emqx/emqx/stargazers) | Erlang | Open-source enterprise MQTT broker for IoT, edge computing, and real-time event routing. |
| 6 | **[Knative Eventing](https://github.com/knative/eventing)** | [![Stars](https://img.shields.io/github/stars/knative/eventing?style=social&color=white)](https://github.com/knative/eventing/stargazers) | Go | Kubernetes-native eventing constructs enabling composable CloudEvents-based event routing. |
| 7 | **[Apache EventMesh](https://github.com/apache/eventmesh)** | [![Stars](https://img.shields.io/github/stars/apache/eventmesh?style=social&color=white)](https://github.com/apache/eventmesh/stargazers) | Java | Serverless event middleware designed specifically for distributed multi-protocol event routing. |
| 8 | **[CloudEvents Spec](https://github.com/cloudevents/spec)** | [![Stars](https://img.shields.io/github/stars/cloudevents/spec?style=social&color=white)](https://github.com/cloudevents/spec/stargazers) | Markdown / Tech | CNCF specification for describing event data in a common, vendor-neutral format. |
| 9 | **[Watermill](https://github.com/ThreeDotsLabs/watermill)** | [![Stars](https://img.shields.io/github/stars/ThreeDotsLabs/watermill?style=social&color=white)](https://github.com/ThreeDotsLabs/watermill/stargazers) | Go | Go library for efficiently building event-driven applications, pub/sub streams, and event meshes. |
| 10 | **[TriggerMesh](https://github.com/triggermesh/triggermesh)** | [![Stars](https://img.shields.io/github/stars/triggermesh/triggermesh?style=social&color=white)](https://github.com/triggermesh/triggermesh/stargazers) | Go | Cloud-native integration platform and AWS EventBridge alternative built on Kubernetes & CloudEvents. |
| 11 | **[Apache ActiveMQ Artemis](https://github.com/apache/activemq-artemis)** | [![Stars](https://img.shields.io/github/stars/apache/activemq-artemis?style=social&color=white)](https://github.com/apache/activemq-artemis/stargazers) | Java | High-performance non-blocking multi-protocol enterprise messaging broker (AMQP, JMS, MQTT). |

---

## 🛠️ How to Contribute 🤝

1. 🍴 Fork the repository.
2. 📝 Add or update entries in `README.md` following the tabular layout.
3. 🔍 Ensure descriptions are factual, links are active, and appropriate categories are selected.
4. 📤 Submit a Pull Request (PR) with a brief note explaining your changes.

---

## 📜 Disclaimer ⚠️

- This repository is a **community-curated list** — it is not exhaustive and does not constitute endorsement.
- Event mesh infrastructures are critical systems. Perform proper operational testing and security reviews before deploying in production environments.

---

## 💖 Support & Community ☕

Thank you for exploring **Awesome-Event-Mesh-Platform**! If you find this project helpful, please consider:
- ⭐️ **Starring** this repository to increase visibility.
- 🔄 **Forking** & contributing new event mesh platforms or tools.
- 📢 **Sharing** with your integration engineering colleagues and event-driven community.

☕ **Sponsor & Support:**  
If you'd like to support the ongoing maintenance of awesome developer resources, consider sponsoring via the button below:  
👉 **[Sponsor on GitHub](https://github.com/sponsors/ishandutta2007)** 💖

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Event-Mesh-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Event-Mesh-Platform&type=date&legend=top-left)

---

**Made for integration architects, event-driven platform teams, and open-source messaging advocates.** ⚡
