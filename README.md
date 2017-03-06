Reactor Kafka
===================

[![Join the chat at https://gitter.im/reactor/reactor](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/reactor/reactor?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Maven](https://maven-badges.herokuapp.com/maven-central/io.projectreactor.kafka/reactor-kafka/badge.svg?style=plastic)](http://mvnrepository.com/artifact/io.projectreactor.kafka/reactor-kafka)
[![Bintray](https://api.bintray.com/packages/spring/jars/io.projectreactor.kafka/images/download.svg)](https://bintray.com/spring/jars/io.projectreactor.kafka/_latestVersion) 
[![Travis CI](https://img.shields.io/travis/reactor/reactor-kafka.svg)](https://travis-ci.org/reactor/reactor-kafka)
[![Coverage](https://img.shields.io/codecov/c/github/reactor/reactor-kafka.svg)](https://travis-ci.org/reactor/reactor-kafka)

You need to have [Gradle 2.0 or higher](http://www.gradle.org/installation) and [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html) installed.

### Bootstrap and download the wrapper ###
    cd reactor-kafka
    gradle wrapper

### Building Reactor Kafka jars ###
    ./gradlew jar

### Running unit tests ###
    ./gradlew test

### Building IDE project ###
    ./gradlew eclipse
    ./gradlew idea

### Sample producer and consumer ###

See [reactor-kafka-samples/src/main/java/reactor/kafka/samples/SampleProducer.java](reactor-kafka-samples/src/main/java/reactor/kafka/samples/SampleProducer.java) for sample reactive producer.
See [reactor-kafka-samples/src/main/java/reactor/kafka/samples/SampleConsumer.java](reactor-kafka-samples/src/main/java/reactor/kafka/samples/SampleConsumer.java) for sample reactive consumer.

#### Setup Kafka cluster and create topic: ####
1. Start Zookeeper and Kafka server
2. Create topic "demo-topic"

#### To run sample producer: ####
1. Update BOOTSTRAP_SERVERS and TOPIC in SampleProducer.java if required
2. Compile and run reactor.kafka.samples.SampleProducer (eg. from IDE as a Java application))

#### To run sample consumer: ####
1. Update BOOTSTRAP_SERVERS and TOPIC in SampleConsumer.java if required
2.  Run reactor.kafka.samples.SampleConsumer (eg. from IDE as a Java application))

### Community / Support ###

* [GitHub Issues](https://github.com/reactor/reactor-kafka/issues)

### License ###

Reactor Kafka is [Apache 2.0 licensed](http://www.apache.org/licenses/LICENSE-2.0.html).

