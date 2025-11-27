# Order Service

Order Service is a Spring Boot microservice responsible for managing customer orders.  
It integrates with **Product Service** to fetch product details and registers itself with **Eureka Server** for service discovery.  
Requests are routed through the **API Gateway**.

---

## 🚀 Features
- Create and manage orders
- Fetch product details via REST call to Product Service
- Register with Eureka for service discovery
- Exposed through API Gateway routes (`/orders/**`)

---

## 🛠️ Tech Stack
- **Java 17**
- **Spring Boot 3.x**
- **Spring WebFlux**
- **Spring Data JPA / R2DBC** (depending on your persistence choice)
- **MySQL** (for order database)
- **Spring Cloud Netflix Eureka Client
