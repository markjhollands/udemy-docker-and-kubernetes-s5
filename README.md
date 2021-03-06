# docker-compose-simple-project
Learning: Simple project with basic use of **docker-compose** to control Docker containers.

This project formed part of an online course on how to use Docker.

## Overview

This section introduced Docker Compose as a mechanism to create and manage a multi container application. In this instance we have a bespoke Node.js Express.js application, which stores data in a redis instance.

## Running project using Docker Compose

To run Docker Compose run the following command:

```bash
docker-compose up
```

To quit, issue CTRL-C in the command line.

### Running in background

More than likely you will want to run the containers in the background. To run the application in the background run:

```bash
docker-compose up -d
```

You will then need to stop the containers by issuing another command.

### Stopping the containers

To stop the running containers that are running in the background, run:

```bash
docker-compose down
```
