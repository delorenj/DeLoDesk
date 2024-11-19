# DeLoDesk

A Docker-based desktop environment management system.

## Overview

DeLoDesk is a containerized desktop environment solution that allows for easy setup and management of development environments using Docker.

## Features

- Docker-based environment configuration
- Database initialization support
- Environment variable management
- Persistent storage management through Docker volumes

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:
```bash
git clone https://github.com/delorenj/DeLoDesk.git
```

2. Configure your environment variables:
```bash
cp .env.example .env
```

3. Start the services:
```bash
docker-compose up -d
```

## Project Structure

- `docker-compose.yml` - Main Docker Compose configuration
- `initdb.sql` - Database initialization script
- `config/` - Configuration files
- `drive/` - Drive storage directory
- `record/` - Record keeping directory

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
