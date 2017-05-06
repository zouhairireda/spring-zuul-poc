# spring-zuul-poc
Poc of spring zuul
- Module for rooting and filtering request to services (or microservices) using Netflix Zuul edge service library.
- Using spring cloud and spring-cloud-dependencies as a dependencyManagement
- Using spring-zuul-service-poc as a microservices for testing zuul proxy.
- Used as a reverse proxy to forward request to services (or microservices based on service registry - eureka or consul)

In this example, we disable ribbon eureka (ribbon.eureka.enabled=false) to perform a simple example of routing and filtering. In second part of example, we'll use ribbon to perform a client-side load balancing who will use Netflix Eureka for a service discovery.
