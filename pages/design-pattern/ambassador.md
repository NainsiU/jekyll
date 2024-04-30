---
title: Ambassador 
permalink: /design-patterns/ambassador
layout: pagelayout
---

![Ambassador Pattern](./../../pictures/ambassador.png)

The Ambassador Pattern is a design pattern for microservices that allows communication between microservices while minimizing the complexity of that communication. It involves the use of a separate service, called the “ambassador,” that sits between the client and the microservices. The ambassador acts as a proxy for the microservices, handling communication and translating requests between the client and the microservices.

## Benefits

- **Multiple Languages and Technologies:**  
  It enables multiple languages and technologies for development teams.

- **Fast Time to Market:**  
  It creates a fast time to market (TTM) and low cost of development “wrapper” to convert legacy applications to increase their modern service benefits.

- **Offloads Common Client Connectivity Tasks:**  
  It offloads common client connectivity tasks such as monitoring, logging, routing, and security (such as TLS) in a language-agnostic way.

- **Easy Interactions Between Components:**  
  It provides conceptually easy interactions between components, typically consistent with interactions between all other services.

## Tangible Things to Do for Adoption

1. **Select Ambassador Technology:**  
   Choose the technology or framework that will serve as the ambassador. This could be an API Gateway, a reverse proxy like Nginx or Envoy, or a service mesh solution like Istio.

2. **Service Registration:**  
   Ensure that your microservices are registered with the ambassador service. This typically involves providing metadata and configuration for each microservice, such as routes and policies.

3. **Routing:**  
   Configure the ambassador to route incoming requests to the appropriate microservice based on routing rules. Set up routing based on path, domain, or other criteria as needed.
