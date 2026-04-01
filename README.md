# rails-rest-api

> Rails REST API: REST API with Ruby on Rails, Devise, PostgreSQL, and Sidekiq

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Ruby, Sinatra, PostgreSQL, Sequel

## 🏗️ Architecture
Three-tier architecture: Ruby, Sinatra backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rails-rest-api
cd rails-rest-api

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
