[![Build Status](https://travis-ci.org/weaveworks/weaveDemo.svg?branch=master)](https://travis-ci.org/weaveworks/weaveDemo)

# Sock Shop : A Microservice Reference Application

The application is the user-facing part of an online shop that sells socks. It is intended to aid the demonstration and testing of microservice and cloud native technologies.

It is built using [Spring Boot](http://projects.spring.io/spring-boot/), [Go kit](http://gokit.io) and [Node.js](https://nodejs.org/) and is packaged in Docker containers.

## Deployment Platforms

The application is designed to be deployed to multiple platforms.

- [Docker](./docker-single/) (single host, e.g. Docker For Mac)
- [Docker Swarm](./docker-swarm/)
- [Kubernetes](./kubernetes/)
- [Mesos (CNI)](./mesos-cni/)
- [Amazon ECS](./aws-ecs/)

### Screenshot

![Sock Shop frontend](./docs/images/sockshop-frontend.png)

### Visualizing the application in Scope

Use [Weave Scope](http://weave.works/products/weave-scope/) or [Weave Cloud](http://cloud.weave.works/) to visualize the application once it's running in the selected [target platform](./deploy/).

![Sock Shop in Weave Scope](./docs/images/sockshop-scope.png)

