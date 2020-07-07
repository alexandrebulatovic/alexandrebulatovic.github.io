---
layout: post
title:  Dockerized Spring Batch importing data from Excel into an in-memory database
categories: Java SpringBatch SpringBoot SpringData Hibernate JPA HSQLDB
slug: dockerized-spring-batch
rank: 6
---

This personal project was made for in 2020 as a way to experiment with Spring Batch and Docker containerization.

It is a simple batch importing data from a CSV file "sample-data.csv" into an [in-memory database](https://en.wikipedia.org/wiki/HSQLDB).

The data comprises 1000 lines of generated data with [Mockaroo](https://www.mockaroo.com/) with an ID, a first name, a last name, an e-mail, a gender and an IP address. 

These data are imported into the database and logged in the console.

In order to run the program, you need [Docker](https://www.docker.com/products/docker-desktop).

**Skills :**
- using Spring Boot to bootstrap a simple app
- using Spring Batch framework
- using Spring Data JPA for database layer
- "containerize" a batch with Docker

*[Click here to see the source code and test the program...](https://github.com/alexandrebulatovic/dockerized-spring-batch)*