# Awesome Integration

A curated list of awesome integration patterns, software and resources. Inspired by awesome-... stuff.

- [Awesome Integration](#awesome-integration)
  - [API Management](#api-management) 
  - [API Gateway](#api-gateway)
  - [API Testing](#api-testing)
  - [Business Rules Engine (BRE)](#business-rules-engine)
  - [BPM](#bpm)
  - [Data Mapping Solution](#data-mapping-solution) 
  - [ESB](#esb)
  - [ETL](#etl)
  - [Integration Frameworks](#integration-frameworks)
  - [iPaaS](#ipaas)
  - [Managed File Transfer](#managed-file-transfer)
  - [Master Data Management](#master-data-management)
  - [Messanging](#messanging)
    - [Messaging as a Service](#messaging-as-a-service)
  - [Self-service integration](#self-service-integration)
- [Specifications](#specifications)
  - [API Specification](#api-specification) 
  - [Connectors](#connectors)
  - [Data formats](#data-formats)
  - [Enterprise Integration Patterns](#enterprise-integration-patterns) 
  - [Integration styles](#integration-styles)
  - [Protocols](#protocols)
  - [Standards](#standards)
- [Resources](#resources)
    - [Books](#books)
    - [Websites](#websites)
- [Contributing](#contributing)

---

## API Management
*API Management solutions.*

- [Anypoint API Manager](https://www.mulesoft.com/platform/api/manager) - Combines API management and integration capabilities in a single platform from Mulesoft.
- [Apigee](https://cloud.google.com/apigee) - API Management solution from Google.
- [Amplify API Management Platform](https://www.axway.com/en/products/amplify-api-management-platform) - An open platform for API management from Axway.
- [IBM API Connect](https://www.ibm.com/cloud/api-connect) - A complete, intuitive and scalable API platform that lets you create, expose, manage and monetize APIs across clouds.
- [Kong Enterprise](https://konghq.com/products/kong-enterprise) - The service connectivity platform.
- [Red Hat 3scale API Management](https://www.redhat.com/en/technologies/jboss-middleware/3scale) - Cloud-native development made simpler and more flexible.
- [TIBCO Cloud Mashery](https://www.tibco.com/products/api-management) - The cloud-native API platform you can deploy anywhere, and manage APIs from everywhere.
- [WSO2 API Manager](https://wso2.com/api-manager/) - Fully open-source API management platform.

## API Gateway
*API Gateways.*
* [Kong API Gateway](https://github.com/Kong/kong) - Cloud-native, platform-agnostic, scalable API Gateway distinguished for its high performance and extensibility via plugins.
* [Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway) -  API Gateway built on top of the Spring Ecosystem, including: Spring 5, Spring Boot 2 and Project Reactor.

## API Testing

* [curl](https://github.com/curl/curl)
* [HTTPie](https://httpie.io)
* [Insomnia](https://insomnia.rest/products/insomnia)
* [Karate](https://github.com/intuit/karate)
* [Postman](https://www.postman.com/product/api-client/)
* [SoapUI](https://www.soapui.org/tools/soapui)

## Business Rules Engine

* [Drools](https://www.drools.org)
* [NxBRE](https://github.com/ddossot/NxBRE/wiki)
* [OpenL Tablets](http://openl-tablets.org/)

## BPM

* [Appian BPM Suite](https://appian.com/platform/complete-automation/business-process-management-bpm.html) - Platform combines low-code development with process management to
allow both IT and citizen developers to construct process-centric and case-centric applications.

## Data Mapping Solution

* [AltasMap](https://www.atlasmap.io/)

## ESB

* [IBM App Connect](https://www.ibm.com/cloud/app-connect) - Connect applications together, regardless of the message formats or protocols that they support. Formerly known as IBM Integration Bus.

## ETL
- [Apache NiFi](https://nifi.apache.org/) - Apache NiFi is an integrated data logistics platform for automating the movement of data between disparate systems.

## Integration Frameworks
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Ballerina](https://ballerina.io/) - An open-source programming language that makes it easier to use, combine, and create network services.
- [Spring Integration](https://spring.io/projects/spring-integration) - Extends the Spring programming model to support the well-known Enterprise Integration Patterns.

## iPaaS

- [Jitterbit Harmony](https://www.jitterbit.com/platform/ipaas)

## Managed File Transfer

* [Oracle Managed File Transfer](https://www.oracle.com/middleware/technologies/mft/managed-file-transfer.html) - Enables secure file exchange and management.
* [IBM Sterling Secure File Transfer](https://www.ibm.com/products/secure-file-transfer) - Move over 1 million files per day with a fast and scalable file transfer platform.
* [Axway Managed File Transfer](https://www.axway.com/en/products/managed-file-transfer)

## Master Data Management

- [Informatica Multidomain MDM](https://www.informatica.com/products/master-data-management/multidomain-mdm.html)

## Messanging

- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
- [Apache RocketMQ](https://rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
- [Eclipse Mosquitto](https://mosquitto.org/) - An lightweight open source message broker that implements the MQTT protocol.
- [IBM MQ](https://www.ibm.com/products/mq) - Enterprise-grade messaging capabilities that skillfully and safely move information between applications.
- [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
- [RabbitMQ](https://www.rabbitmq.com) - An open-source message-broker that originally implemented the Advanced Message Queuing Protocol (AMQP).
- [Red Hat AMQ](https://www.redhat.com/en/technologies/jboss-middleware/amq) - Red Hat AMQ-based on open source communities like Apache ActiveMQ and Apache Kafka.
- [TIBCO Enterprise Message Service](https://www.tibco.com/products/tibco-enterprise-message-service) - TIBCO EMS is standards-based Java™ Message Service (JMS) implementation allows any application that supports JMS, whether home grown or third-party, to quickly and easily exchange messages.  

### Messaging as a Service

- [Amazon MQ](https://aws.amazon.com/amazon-mq) - Fully managed message broker service for Apache ActiveMQ and RabbitMQ.
- [Amazon MSK](https://aws.amazon.com/msk) -  Amazon Managed Streaming for Apache Kafka.
- [Amazon SQS](https://aws.amazon.com/sqs) - Amazon Simple Queue Service.
- [Amazon SNS](https://aws.amazon.com/sns) - Amazon Simple Notification Service. Pub/sub functionality provides topics for high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications.
- [Alibaba Cloud Message Queue for Apache Kafka](https://www.alibabacloud.com/product/kafka)
- [Alibaba Cloud Message Queue for RabbitMQ](https://www.alibabacloud.com/product/rabbitmq)
- [Alibaba Cloud Message Service](https://www.alibabacloud.com/product/message-service)
- [AlibabaMQ for Apache RocketMQ](https://www.alibabacloud.com/product/mq)
- [Anypoint MQ](https://www.mulesoft.com/platform/anypoint-mq-message-queue)
- [Azure Service Bus](https://azure.microsoft.com/en-us/services/service-bus/)
- [CloudAMQP](https://www.cloudamqp.com/) - RabbitMQ as a Service.
- [Google Cloud Pub/Sub](https://cloud.google.com/pubsub) - Messaging and ingestion for event-driven systems and streaming analytics.
- [IronMQ](https://www.iron.io/mq) - Elastic message queue created specifically with the cloud in mind.
- [Solace PubSub+ Cloud](https://solace.com/products/platform/cloud/)
- [Yandex Message Queue](https://cloud.yandex.com/en/services/message-queue) - Compatibility with the Amazon SQS HTTP API.
- [Yandex Managed Service for Apache Kafka](https://cloud.yandex.com/en/services/managed-kafka)

## Self-Service Integration

- [Oracle Self-Service Integration](https://docs.oracle.com/en/cloud/paas/self-service-integration-cloud/index.html) - Automates tasks between cloud applications.

# Specifications
## API Specification
* [AsyncAPI](https://www.asyncapi.com/docs/specifications/v2.0.0)
* [GraphQL](https://github.com/graphql/graphql-spec)
* [OpenAPI (ex.Swagger)](https://spec.openapis.org/oas/v3.1.0)
* [RAML](https://github.com/raml-org/raml-spec/blob/master/versions/raml-10/raml-10.md/)
* [WSDL](http://www.w3.org/TR/wsdl20)
## Connectors
* [JCA]
* [Kafka Connect]
## Data formats
* [Apache Avro]
* [JSON]
* [XML]
## Enterprise Integration Patterns
## Integration styles
* [File Transfer](https://www.enterpriseintegrationpatterns.com/patterns/messaging/FileTransferIntegration.html)
* [Messaging](https://www.enterpriseintegrationpatterns.com/patterns/messaging/Messaging.html)
* [Remote Procedure Invocation](https://www.enterpriseintegrationpatterns.com/patterns/messaging/EncapsulatedSynchronousIntegration.html)
* [Shared Database](https://www.enterpriseintegrationpatterns.com/patterns/messaging/SharedDataBaseIntegration.html)
## Protocols
* [AMQP]
* [HTTP]
* [MQTT]
## Standards
* [BPEL]
* [WS-Security]
# Resources
## Books
## Websites
# Contributing
