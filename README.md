# Spring Boot with Apache Kafka

# Apache Kafka 
    Is a Distributed publisher-subscriber messaging system, which can handle high volume of data
    It has high reliability, and be scaled easily
    It is fault tolerance because the messages are persisted in the disk before sending to consumer to prevent data loss
    It has high throughput, and it can perform 2 million writes per sec

# Prerequisites
    Install Apache Kafka and Start Zookeeper and Kafka Server(https://kafka.apache.org/quickstart)
    
# Use Cases
    Log Aggregator - Collect logs from different services - as a log streaming event (Zipkin stream server makes use of this) 
    Streaming of real time data (like Uber, etc.)
    Can be used in Event sourcing in Microservices. Multiple Microservices will be writing to kafka streams. And these streams will be responsible to write to database

# Kafka Elements
 - Kafka Cluster
 - Zookeeper
 - Topic
 - Partition
 - Partition Offset
 - Consumer Group
 - Leaders
 - Follower
 
 # Steps
 - start the Zookeeper
 - start the Kafka Server
 - run the producer project
 - run the consumer project
 
