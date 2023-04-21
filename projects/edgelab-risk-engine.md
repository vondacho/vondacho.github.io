---
layout: post
title: Edgelab – Risk engine API
---

April 2020 – March 2022

## Why

Edge Laboratories wants to promote the public risk engine API as one of its main commercial products to be integrated by investment businesses.

## What

Full-feature engineering and ownership (analysis, design, realization, delivery, and maintenance) in the scope of the risk engine API.

### Challenges

* Exposure of risk metrics for assets portfolios in a reactive way and with constant response time.
* Daily challenges are availability and scalability in the context of 1 million of risk estimation requests on asset portfolios a day.
* Daily ingestion of 1-2 millions of instruments from financial markets.
* Daily pricing of 1-2 millions of instruments using mathematical risk models.
* Ownership of several microservices.
* Integration of several downstream services.

## Organization

Scrum Team of 4 software engineers (me) and 1 product owner

## Practices

### Software Development

* Scrum-like
* Specification by Example
* Behaviour-Driven Development (BDD)
* Acceptance-Test-Driven Development (ATDD)
* Objective Key Result (OKR)
* Continuous delivery

### Software Design

* REST API design
* Domain-Driven Design (DDD)
* Clean & Hexagonal architecture
* Event-driven architecture
* Micro-services architecture
* Reactive programming

## Technology

* Kotlin, Java, Spring-Boot-Webflux, Reactor
* PostgreSQL, MySQL, Cassandra, RabbitMQ
* Jenkins CI, OpenSearch, Grafana, Logstash, Prometheus, Jaeger, Kong, Consul, Vault, Docker, Nomad
* Terraform, Amazon Cloud