## Repository Structure

````markdown
# Docker
Docker installation guides, practical Docker Compose examples, and containerized infrastructure deployments for Linux and DevOps environments.

## Contents
- [Installation](#installation)
- [Docker Compose](#docker-compose)
- [Networking](#networking)
- [Storage](#storage)
- [Examples](#examples)
- [Repository Structure](#repository-structure)

## Installation
Installation guides for Docker on different Linux distributions:
- RHEL
- Ubuntu
- Debian

## Docker Compose
Practical Docker Compose examples:
- ELK Stack
- Nginx
- MySQL

## Networking
Examples and notes about Docker networking:
- Bridge networks
- Overlay networks
- Container networking
- Port mapping

## Storage
Examples and notes about Docker storage:
- Volumes
- Bind mounts

## Examples
Practical containerized infrastructure examples.

## Repository Structure

docker/
├── README.md
│
├── installation/
│   ├── rhel/
│   │   └── README.md
│   ├── ubuntu/
│   │   └── README.md
│   └── debian/
│       └── README.md
│
├── compose/
│   ├── elk/
│   │   ├── docker-compose.yml
│   │   └── README.md
│   ├── nginx/
│   │   ├── docker-compose.yml
│   │   └── README.md
│   └── mysql/
│       ├── docker-compose.yml
│       └── README.md
│
├── networking/
│   ├── bridge/
│   ├── overlay/
│   └── README.md
│
├── storage/
│   ├── volumes/
│   ├── bind-mounts/
│   └── README.md
│
└── examples/
    ├── web-app/
    └── monitoring/






