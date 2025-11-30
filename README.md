# Kafka NodeJS Example

## Introduction

This repository showcases a simple example of using Kafka with NodeJS. In this example the producer push a testing message onto the test_topic (in Kafka) while the consumer consumes the message and print it. This happens in a loop every 10s.

## Running the system

```
docker-compose up
```

This will start a Kafka broker, a Zookeeper instance, kafka ui, a producer and a consumer.

## Accessing Kafka UI

You can access the Kafka UI at: http://localhost:8082 where you can see all the persisted messages in the test_topic.

You can also see the logs of the producer and consumer in docker desktop.
