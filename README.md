# user-management

User management system.

This project was created solely for educational purposes as a part of the JavaScript class.

## Development

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)

### Setup

1. Clone the repository.
2. Copy and paste `.env.example` to `.env` and fill it. NODE_ENV should be set to `development`.
3. Start the containers with `docker compose up`.

### Warning

You should only clone this repository, not the other two. This repository contains the `docker-compose.yml` file, which is used to start the containers.

If you ever add packages, you have to **delete** the containers and rebuild them with `docker compose up --build`. Otherwise, the `node_modules` folder won't change inside the containers.

### Default ports

- Front-end: 3000
- Back-end: 4000
- PostgreSQL: 5432
