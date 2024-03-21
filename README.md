# <u>Data-pipeline</u>
## Introduction 
In this project, you will execute an End-To-End Data Pipeline on Real-Time Order Data using Kafka and ELK stack using Docker-Compose.

## Technology Used
Python3, Docker-compose, Apache Kafka and ELK Stack 

## Dependency

▪️ In **docker-compose** we have not used logstash, So we need to configure it on our system. 

▪️ In **Logstash** install __/usr/share/logstash/bin/logstash-plugin install logstash-integration-kafka__.



## Kafka Architecture

__Kafka__ is a distributed streaming platform that can handle real-time data feeds. It was initially developed by LinkedIn and later open-sourced by Apache Software Foundation. Kafka achieves its high-throughput and fault-tolerance by distributing the load over multiple servers.

### Key Components:

➣ ***Producer:*** Responsible for creating the data and sending it to the Kafka cluster. The producer is decoupled from the cluster and can send data at high speed.

➣ ***Consumer:*** Responsible for consuming the data produced by the producer. It connects to the Kafka cluster and subscribes to specific topics.

➣ ***Topic:*** It is a category or feed name to which the records are published. Topics are used to organize the data into categories.

➣ ***Broker:*** It is a Kafka server that receives the records from producers and serves them to consumers. A Kafka cluster can consist of multiple brokers.

➣ ***Zookeeper:*** It is a centralized service for maintaining configuration information and providing synchronization and coordination. In a Kafka cluster, Zookeeper helps in electing the cluster's controller and maintaining the broker and partition state.
