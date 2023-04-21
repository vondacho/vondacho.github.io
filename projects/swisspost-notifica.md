---
layout: post
title: SwissPost - Consignment Notification Service
---

2016

## Why

PostLogistics wants its clients to be kept informed of their shipment status and have the option of controlling how they receive it.

## What

To design and develop an online e-mail/SMS/Push notification service, which notifies Swiss Post registered users about the status of their parcel inside the logistic chain of the Swiss Post.

### Challenges

* 1 million events a day, each event having to be handled in less than 1 second
* Complex business logic that manages several workflows and sending decision logic, depending on the product
* Availability, scalability, idempotency, ordering
* Compatibility between internet browsers on both desktop and mobile platforms (Android, iPhone)

## My roles

* Software developer
* Technical leader substitute

## Organization

* Scrum Team of 3 software engineers (me as technical leader substitute), 1 project manager, 1 business analyst

## Technology

* Java, Spring, Hibernate, Camel, Activiti, Drools
* JSP, Angular, Typescript
* SOAP
* Tomcat, Oracle
* Jenkins, SonarQube, Splunk

## Links

* [Official product](https://www.post.ch/en/business/a-z-of-subjects/practical-tips-recipient-customers/recipient-services-letters/notification-services)

![En cours d'acheminement]({{ '/public/images/nca1.png' | absolute_url }})
![Invitation à retirer]({{ '/public/images/nca2.png' | absolute_url }})
![Prêt à être retiré]({{ '/public/images/nca3.png' | absolute_url }})
![A été distribué]({{ '/public/images/nca4.png' | absolute_url }})
