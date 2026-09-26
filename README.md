# Awesome-Event-Mesh-Platform

## Top Event Mesh Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Multi-Protocol Event Routing, Hybrid/Multi-Cloud Event Distribution, Event-Driven Integration & Dynamic Event Meshes*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Event Mesh**. An event mesh is a layer of interconnected event brokers that dynamically routes events across applications, clouds, data centers, and edge environments—supporting multiple protocols and enabling real-time, event-driven architectures at enterprise scale.



**Examples** include Solace PubSub+, TIBCO FTL, IBM Event Streams, Red Hat AMQ Streams, Confluent, Azure Event Grid, Amazon EventBridge, TriggerMesh, Boomi Event Streams, and Ably (the category leaders).



**Open-source emphasis**: True multi-protocol, multi-environment event mesh platforms are largely commercial (Solace is the reference design). Strong open foundations exist in **Apache EventMesh**, **TriggerMesh**, **Apache Kafka**, **Apache Pulsar**, **NATS**, and related cloud-native eventing projects. This section expands those options and remains realistic about the commercial gap for full mesh federation and multi-protocol brokers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Solace PubSub+](https://solace.com/)**  

  Leading event mesh and event broker platform—multi-protocol (MQTT, AMQP, JMS, REST, Kafka, WebSockets), hybrid/multi-cloud routing, high performance, and dynamic event mesh capabilities for large enterprises.



- **[TIBCO FTL](https://www.tibco.com/)**  

  High-performance messaging and event distribution technology from TIBCO for low-latency, real-time event-driven systems.



- **[IBM Event Streams](https://www.ibm.com/)**  

  Enterprise event streaming platform based on Apache Kafka, with IBM’s operational tooling, connectors, and hybrid-cloud support.



- **[Red Hat AMQ Streams](https://www.redhat.com/)**  

  Kafka-based event streaming on OpenShift/Kubernetes, part of Red Hat’s application and integration portfolio.



- **[Confluent](https://www.confluent.io/)**  

  Complete event streaming platform built on Apache Kafka—managed and self-managed options with governance, connectors, and stream processing that can form the backbone of event-driven meshes.



- **[Azure Event Grid](https://azure.microsoft.com/)**  

  Fully managed event routing service on Azure for reactive, event-driven architectures across Azure and external services.



- **[Amazon EventBridge](https://aws.amazon.com/eventbridge/)**  

  Serverless event bus that routes events between AWS services, SaaS applications, and custom applications with content-based filtering.



- **[TriggerMesh](https://www.triggermesh.com/)**  

  Cloud-native integration and eventing platform (with open-source roots) that unifies event sources and targets, often positioned as an EventBridge-style experience.



- **[Boomi Event Streams](https://boomi.com/)**  

  Event streaming and integration capabilities within the Boomi iPaaS for connecting applications and data in real time.



- **[Ably and additional real-time / event platforms](https://ably.com/)**  

  Managed real-time messaging and event distribution services used for pub/sub, presence, and multi-channel event delivery.



## Open-Source GitHub Projects

- **[Apache EventMesh](https://github.com/apache/eventmesh)**  

  Open-source serverless event middleware designed for distributed event-driven applications—CloudEvents-native, multi-runtime support, and positioned as next-generation event mesh infrastructure.



- **[TriggerMesh](https://github.com/triggermesh/triggermesh)**  

  Open-source cloud-native integration platform and AWS EventBridge alternative—Kubernetes-native event sources, targets, filtering, transformation, and routing via CloudEvents.



- **[Apache Kafka](https://github.com/apache/kafka)**  

  Foundational open-source event streaming platform frequently used as the durable backbone of custom event meshes and hybrid event-driven architectures.



- **[Apache Pulsar](https://github.com/apache/pulsar)**  

  Open-source messaging and streaming platform with multi-tenancy, geo-replication, and separated compute/storage—well-suited as a mesh building block.



- **[NATS / NATS JetStream](https://github.com/nats-io/nats-server)**  

  Lightweight, high-performance open-source messaging system with JetStream for persistence and streaming; popular in cloud-native and edge event meshes.



- **[Knative Eventing](https://github.com/knative/eventing)**  

  Open-source Kubernetes-native eventing building blocks for sources, brokers, triggers, and CloudEvents-based routing.



- **[CloudEvents specification and SDKs](https://github.com/cloudevents)**  

  Vendor-neutral open specification and libraries that enable portable event formats across mesh and broker technologies.



- **[RabbitMQ and AMQP open brokers](https://github.com/rabbitmq/rabbitmq-server)**  

  Mature open message broker still widely used for traditional messaging patterns within broader event-driven systems.



- **[Apache ActiveMQ / Artemis](https://github.com/apache/activemq)**  

  Open-source multi-protocol message brokers that support JMS, AMQP, MQTT, and related enterprise messaging use cases.



- **[Documentation and event-mesh open playbooks](https://github.com/)**  

  Guides for composing Kafka, Pulsar, NATS, EventMesh, and Knative into hybrid event-routing architectures.



### Additional Strong Open-Source Options

- Building a practical event mesh with **Apache EventMesh** or **TriggerMesh** on Kubernetes for CloudEvents-based routing.

- Using **Kafka** or **Pulsar** as the durable core and layering protocol bridges (MQTT, AMQP, REST) for multi-protocol access.

- Combining **NATS** for low-latency edge/cloud messaging with heavier streaming platforms for long-term retention.

- Accepting that full multi-protocol federation, dynamic topic routing across hybrid environments, enterprise-grade HA, and managed mesh operations still favor commercial platforms (especially Solace PubSub+, plus Confluent, IBM Event Streams, cloud event buses, etc.).

- Focusing open-source efforts on standards (CloudEvents), portability, and cost control for platform engineering teams.



**Frameworks for building custom systems**: Choose a core broker (Kafka/Pulsar/NATS/EventMesh) → adopt CloudEvents for portability → deploy protocol bridges or gateways → federate across clusters/regions → add filtering, transformation, and observability. Suitable for cloud-native and hybrid architectures with strong engineering ownership. Large enterprises often adopt Solace or managed Kafka/Pulsar platforms for production event meshes.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Event mesh and event-driven systems are critical infrastructure. Misconfiguration can cause lost events, ordering issues, or cascading failures. Open-source stacks require skilled operations and careful capacity planning. This list is not architectural or operational advice.



---

**Made for integration architects, event-driven platform teams, and open-source messaging advocates.**

Let's keep events flowing across boundaries—reliably, portably, and as open as practical.
