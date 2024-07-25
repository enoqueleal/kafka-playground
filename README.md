# Kafka playground

This repository is for my notes about Kafka.

The stack:

* Zookeeper
* Kafka
* AKHQ

## Commands

```sh
# list topics
$ kafka-topics --bootstrap-server localhost:9092 --list
```

```sh
# create a topic
kafka-topics --bootstrap-server localhost:9092 --create --topic meu_topico --partitions 3 --replication-factor 1
```

```sh
# delete a topic
kafka-topics --bootstrap-server localhost:9092 --delete --topic meu_topico
```
## Setup

To start zookeeper, kafka and akhq, run this command:

```sh
$ docker-compose up
```

To stop zookeeper, kafka and akhq, run this command:

```sh
$ docker-compose down
```
