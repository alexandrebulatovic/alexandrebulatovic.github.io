---
layout: post
title:  Minimal example for Apache Kafka real-time processing
categories: Maven Java ApacheKafka
slug: minimal-example-kafka
rank: 7
---

[Apache Kafka](https://en.wikipedia.org/wiki/Apache_Kafka) is a well-known messaging system which as key features comprises "real-time" processing (meaning very low latency) and high throughput. 

It is nonetheless a complex solution to master that needs fine-tuning in order to maximize the performance on a given technical need. We can think of [IoT](https://en.wikipedia.org/wiki/Internet_of_things) as an example of application, if for instance you want a real-time processing of data sent by the connected device.

This program is composed of two executable files, one is a Producer and one is a Consumer. The Producer side will send 100 messages to a topic in Apache Kafka and the Consumer will read the messages and display them in the output console. 

After 60 seconds of inactivity, the Consumer will shut down automatically.


**Skills :**
- using Apache Kafka
- create a Maven java project

*[Click here to see the source code and test the program...](https://github.com/alexandrebulatovic/kafka-minimal-example)*