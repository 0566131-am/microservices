# 🧩 Microservices Project

A collection of Spring Boot microservices demonstrating service discovery, API gateway, and REST APIs.

## 📦 Services

| Service | Description |
|---|---|
| `api-gateway` | Routes requests to appropriate microservices |
| `compound-interest-microservice` | Calculates compound interest via REST API |
| `microservices-eureka` | Eureka Service Registry for service discovery |
| `learning-jdbc/departmentAPI` | Department management REST API using JDBC |

## 🚀 Tech Stack

- **Java** - Spring Boot
- **Spring Cloud** - Eureka, API Gateway
- **Maven** - Build tool
- **JDBC** - Database connectivity

## ▶️ How to Run

Start services in this order:

1. **Eureka Server** (service registry first)
```bash
cd microservices-eureka
./mvnw spring-boot:run
```

2. **Microservices** (any order)
```bash
cd compound-interest-microservice
./mvnw spring-boot:run
```

3. **API Gateway** (last)
```bash
cd api-gateway
./mvnw spring-boot:run
```

## 📬 Contact

- **GitHub**: [0566131-am](https://github.com/0566131-am)
