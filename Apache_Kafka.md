# Apache Kafka Overview

## Apache Kafka 

A distributed data streaming platform that enables applications to process, publish, and consume data streams in real time. Kafka is a publish-and-subscribe messaging system that can handle data from multiple sources and deliver it to multiple consumers.

## Example

In a Zomato-like application, Kafka can be used to manage location-based data updates. For example:

1. User location updates are published to a Kafka topic.
2. Services consume these updates to refresh nearby restaurant recommendations in real-time.

## Structure

- **Producers**: Applications or services that send data to Kafka.
- **Topics**: Logical channels where data is categorized.
- **Consumers**: Applications or services that receive data from Kafka topics.
- **Brokers**: Servers that store and replicate data across the Kafka cluster.
- **ZooKeepers**: Manages and coordinates Kafka brokers, handling metadata and leader election.
   
<br>   

![Kafka Architecture](https://www.tutorialspoint.com/apache_kafka/images/cluster_architecture.jpg)

## References

- [Kafka Documentation](https://kafka.apache.org/documentation/)
- [Kafka Guide](https://www.tutorialspoint.com/apache_kafka/apache_kafka_introduction.htm)
- [Introduction to Apache Kafka](https://youtu.be/s-dWdUM4g0s?si=_flbBezxdxzXjSlX)
- [Apache Kafka Tutorial](https://youtu.be/xGwzuz8F9k0?si=8BCbsGhoxl58K-EK)


