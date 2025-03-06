# Distributed-Metadata-Scraper
 Developed a metadata scraper for async URL processing, improving data handling by 20% with JWT authentication.  Optimized  task queuing via RabbitMQ and Redis, ensuring PostgreSQL persistence. Containerized with Docker and tested via Postman.


# Distributed Metadata Scraper

## Overview
The **Distributed Metadata Scraper** is a high-performance, asynchronous URL metadata processing system designed for efficiency and scalability.

## 🚀 Technologies Used
- **Java**
- **Spring Boot**
- **PostgreSQL**
- **Redis**
- **JWT (JSON Web Tokens)**
- **RabbitMQ**
- **Docker**
- **Postman**

## 📌 Features
- **Asynchronous URL Processing**: Efficiently scrapes metadata from URLs with optimized task queuing.
- **JWT Authentication**: Ensures secure API access.
- **Task Queuing with RabbitMQ & Redis**: Enhances performance and reliability.
- **Persistent Data Storage**: Metadata is securely stored in **PostgreSQL**.
- **Docker Containerization**: Simplifies deployment and scaling.
- **API Testing with Postman**: Fully tested and verified endpoints.

## 🛠 Setup & Installation
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/akashavcoewala/URL-Metadata-Scraper.git
 cd URL-Metadata-Scraper
```

### 2️⃣ Run with Docker (Recommended)
```sh
 docker-compose up --build
```

### 3️⃣ Manual Setup
1. Install PostgreSQL, Redis, and RabbitMQ.
2. Configure database settings in `application.properties`.
3. Run the application:
```sh
 mvn spring-boot:run
```

## 📡 API Endpoints
| Method | Endpoint       | Description           |
|--------|--------------|----------------------|
| POST   | `/upload`     | Upload a URL         |
| GET    | `/status`     | Check URL status     |
| GET    | `/results`    | Fetch scraped data   |

## 🤝 Contributing
Pull requests are welcome! Please open an issue first to discuss changes.

## 📄 License
This project is licensed under the MIT License.

