# sleek-ev-docker-compose

This repository contains the `docker-compose` configuration for deploying the sleek-ev application stack.

## Prerequisites

1. [Docker](https://www.docker.com/products/docker-desktop)
2. [Docker Compose](https://docs.docker.com/compose/install/)

## Installation

Follow the steps below to deploy the sleek-ev application stack using `docker-compose`.

### 1. Clone the Repository

First, clone this repository to your local machine.

Using HTTPS:

```bash
git clone https://github.com/vijityannapon/sleek-ev-docker-compose.git
```

Or using SSH

```bash
git clone git@github.com:vijityannapon/sleek-ev-docker-compose.git
```

### 2. Navigate to the Repository

Change your directory to the cloned repository:

```bash
cd sleek-ev-docker-compose
```

### 3. Start the Application Stack

Use `docker-compose` to deploy the application:

```bash
docker-compose up --build
```

This command will pull the required images, build the Docker containers, and start the services defined in `docker-compose.yml`.

### 4. Access the Application

After successfully deploying the stack with `docker-compose`, you can access the application through your web browser or any API tools.

### 5. Stopping the Application Stack

To stop the services and containers started by `docker-compose`, run:

```bash
docker-compose down
```

### Feedback

If you encounter any issues or have feedback, please [open an issue](https://github.com/vijityannapon/sleek-ev-docker-compose/issues) on GitHub.
