# Docker-Compose
A standard docker compose file which spins up the scale-able starter.

## What's in this file?
This compose file spins up the following wb3-spring project services within a single overlay network.  Each of these services are exposed for external consumption using port mapping.

### WB3-Spring Projects
* [Config-Server](https://github.com/wb3-spring/Config-Server) | Port 3000 | [![CircleCI](https://circleci.com/gh/BillBensing/pluralsight-docker-ci/tree/master.svg?style=svg)](https://circleci.com/gh/BillBensing/pluralsight-docker-ci/tree/master) Spring Cloud Configuration Server
* [Microservice-Discovery](https://github.com/wb3-spring/Microservice-Discovery) | Port 3002 | [![CircleCI](https://circleci.com/gh/wb3-spring/Microservice-Discovery/tree/master.svg?style=svg)](https://circleci.com/gh/wb3-spring/Microservice-Discovery/tree/master) Spring Cloud Eureka Service Discovery Server
* [Edge-Server](https://github.com/wb3-spring/Edge-Server) | Port 3003 | [![CircleCI](https://circleci.com/gh/wb3-spring/Edge-Server/tree/master.svg?style=svg)](https://circleci.com/gh/wb3-spring/Edge-Server/tree/master) Spring Cloud Zuul API Gateway
* [Trace-Server](https://github.com/wb3-spring/Trace-Server) | Port 3004 | [![CircleCI](https://circleci.com/gh/wb3-spring/Trace-Server/tree/master.svg?style=svg)](https://circleci.com/gh/wb3-spring/Trace-Server/tree/master) Spring Cloud Zipkin Call Tracing Server

## Other Implemented Services
* [Service-Discovery](https://hub.docker.com/_/consul/) | Port 3001 | Consul Service Discovery
