# Docker-Compose
A standard docker compose file which spins up the scale-able starter.

## What's in this file?
This compose file spins up the following wb3-spring project services within a single overlay network.

* [Config-Server](https://github.com/wb3-spring/Config-Server) | Spring Cloud Configuration Server
* [Service-Discovery](https://hub.docker.com/_/consul/) | Consul Service Discovery
* [Microservice-Discovery](https://github.com/wb3-spring/Microservice-Discovery) | Spring Cloud Eureka Service Discovery Server
* [Edge-Server](https://github.com/wb3-spring/Edge-Server) | Spring Cloud Zuul API Gateway
* [Trace-Server](https://github.com/wb3-spring/Trace-Server) | Spring Cloud Zipkin Call Tracing Server
