# Inkreo Backend

## Table of Contents

1. [👇🏾 Introduction](#-introduction)
2. [✍🏾 Getting Started](#-getting-started)
3. [✨ Features](#-features)
4. [⚙️ Technical Stack](#-technical-stack)
5. [🧑🏾‍💻 Contributing](#-contributing)
6. [🤝🏾 Code of Conduct](#-code-of-conduct)
7. [🗒️ License](#-license)

## 👇🏾 Introduction

The Inkreo backend is powered by Laravel and serves as the core API for the Inkreo document editing platform. It manages authentication, document storage, AI-powered editing, and database interactions.

## ✍🏾 Getting Started

To set up the backend locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-org/inkreo-backend.git
   ```
2. Navigate into the project directory:
   ```sh
   cd inkreo-backend
   ```
3. Install dependencies:
   ```sh
   composer install
   ```
4. Copy the environment file and update settings:
   ```sh
   cp .env.example .env
   ```
5. Generate the application key:
   ```sh
   php artisan key:generate
   ```
6. Configure database settings in `.env` (PostgreSQL, MySQL, or MariaDB supported).
7. Run migrations and seed data:
   ```sh
   php artisan migrate --seed
   ```
8. Start the development server:
   ```sh
   php artisan serve
   ```

## ✨ Features

- User authentication & role-based access
- Document management with cloud storage integration
- AI-powered document editing using the Gemini Model
- RESTful API for frontend communication
- Support for PostgreSQL, MySQL, and MariaDB

## ⚙️ Technical Stack

- **Framework**: Laravel (PHP)
- **Database**: PostgreSQL / MySQL / MariaDB
- **AI Model**: Gemini Model
- **Authentication**: Laravel Sanctum / Passport
- **Storage**: AWS S3 / Local Storage
- **Queue Management**: Laravel Queues & Redis

## 🧑🏾‍💻 Contributing

We welcome contributions! Please read our [Contribution Guidelines](./CONTRIBUTING.md) before submitting any pull requests.

## 🤝🏾 Code of Conduct

Please follow our [Code of Conduct](./CODE_OF_CONDUCT.md) to ensure a positive community experience.

## 🗒️ License

Inkreo Backend is licensed under the [MIT License](./LICENSE).

