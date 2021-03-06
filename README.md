# Zero Downtime Tutorial

This is a tutorial walk-through how to setup health-checks on containers with examples using Docker Swarm or Kubernetes orchestrators.

This tutorial accompanies the Presentation [Zero Downtimes with Faulty Solutions](https://speakerdeck.com/spiddy/zero-downtimes-with-faulty-solutions).

## Target Audience

The target audience for this tutorial is someone planning to use Docker containers with either Docker Swarm or Kubernetes as orchestrator and wants to understand how to embed resilience to services using health checks.

## Labs

This tutorial assumes you have a working Docker and Kubernetes instance.

* [Prerequisites](./docs/01-prerequisites.md)
* [Build Coin Images](./docs/02-build-coin-images.md)
* [Deploy on Docker Swarm](./docs/03-deploy-on-docker-swarm.md)
* [Deploy on Kubernetes](./docs/04-deploy-on-kubernetes.md)
