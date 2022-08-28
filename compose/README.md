# Example Docker Compose Configurations

This folder contains some example configurations for Momentum using Docker Compose.

## Prerequisites

To run any of the examples, you need `docker`.

## Usage

To install and run any of the examples, you will need to download the corresponding `docker-compose.yml` file. Then simply run the following command in the folder containing the aforementioned file:

```bash
docker compose up -d
```

## Update

To pull the latest updates for the docker images, run:

```bash
docker compose pull
```

To apply the updates to the containers, run:

```bash
docker compose up -d
```