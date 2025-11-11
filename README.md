📚 SmartBiblio-global
📋 Project Overview

Welcome to the SmartBiblio project developed by the CodeCrafters team.
This project is designed to efficiently manage library resources using a microservices architecture.

It includes:

Catalog management

Stock management

Deliveries

E-commerce

Informative blogs

Event management

👨‍💻 CodeCrafters Team

We are a team specialized in full-stack development and distributed architectures:

Chihi Dorsaf → Catalog management

MedHedi Hamdi → Stock management

Hiba Louhibi → Delivery management

Walid Barhoumi → E-Commerce

Chiheb Lahbib → Blog

Ines Dahmani → Event management

🔧 Technology Stack

We use modern technologies to ensure performance, scalability, and security:

Development

Backend: Spring Boot (Java) with microservices architecture

Frontend: Angular

Database: MySQL, H2

DevOps & Security Tools

Microservices Management: Spring Cloud (Eureka, Gateway)

Authentication & Security: Keycloak

Containerization: Docker, Docker Compose

💼 Detailed Features
📚 Catalog Management

Add, update, and delete books

Classification by categories and authors

Advanced search by title, author, category

Manage book metadata (ISBN, summary, etc.)

📦 Stock Management

Real-time stock tracking

Automatic availability verification

🚚 Delivery Management

Order and delivery tracking

Status management (in progress, shipped, delivered, cancelled)

User notifications

🛒 E-Commerce (Online Purchase)

Book sales interface

Secure payments

Order history

📰 Blog (Microservice)

Create and publish articles

Manage comments and interactions

Trend tracking and analytics

🎉 Event Management

Create and manage library events

User registration for events

Participant tracking

Event notifications and reminders

📁 Project Structure
📁 Backend (Spring Boot - Microservices)
├── catalogue-service/
├── stock-service/
├── delivery-service/
├── ecommerce-service/
├── blog-service/
├── event-service/
├── gateway-service/  (Spring Cloud Gateway)
├── eureka-server/    (Service Discovery)
├── keycloak/         (Authentication & Security)

📁 Frontend (Angular)
├── src/app/
├── src/assets/
├── src/environments/

🔄 Microservices Relationships

Catalog ↔ Stock: Book availability verification

Catalog ↔ E-Commerce: Online book purchase

Stock ↔ Delivery: Shipment management

Blog ↔ E-Commerce: Articles linked to available books

Events ↔ Users: Registration and participant tracking

Eureka Server: Centralizes all microservices

Gateway: Single entry point for the frontend

Keycloak: Manages authentication and authorization

⚙️ Key Technical Points

Using Spring Cloud for microservices management

Centralized security with Keycloak

Inter-service communication via REST API and Event-Driven Architecture

Optimized queries with JPQL and native SQL

🚢 Deployment & CI/CD
Clone the project:
git clone https://github.com/CodeCrafters/SmartBiblio.git

Backend:
cd backend
mvn clean install
mvn spring-boot:run

Frontend:
cd frontend
npm install
ng serve

Using Docker:
docker-compose up -d

📜 License

This project is under the MIT license.