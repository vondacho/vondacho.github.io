---
layout: post
title: Edgelab – Client relationships management
---

2021

## Why

Edge Laboratories wants to better control the access and consumption of the endpoints that make up its public API, so that fine-grained billing can be implemented.

## What

* To design and develop an API for the management of clients, and organizations with their users.
* To design and develop an API for the management of permissions.
* To design and develop a user interface.

### Requirements

* To be the source of truth for API keys and permissions of users of organizations.
* To automatize the manual process in place.

### Challenges

* To integrate token-based authentication with OIDC.
* To integrate with Edgelab API gateway as source of API-keys and permissions.

## Organization

Team of 2 software engineers (me) and 1 product owner

## Practices

### Software Development

* Specification by Example
* Behaviour-Driven Development (BDD)
* Acceptance-Test-Driven Development (ATDD)
* Continuous delivery

### Software Design

* REST API design
* Domain-Driven Design (DDD)
* Clean & Hexagonal architecture
* Micro-services architecture
* Reactive programming

## Technology

* Kotlin, Spring-Boot, Reactor
* Angular, Typescript
* OAuth, OIDC, Auth0
* PostgreSQL
* Jenkins CI, OpenSearch, Grafana, Logstash, Prometheus, Jaeger, Kong, Consul, Vault, Docker, Nomad
* Terraform, Amazon Cloud