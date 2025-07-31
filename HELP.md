# Desafio DIO: Microsserviços com Spring Boot & Spring Cloud

## 📌 Descrição
Projeto de catálogo de produtos e pedidos, utilizando arquitetura de microsserviços com Spring Boot, Spring Cloud, Eureka e API Gateway.

## 📂 Estrutura do Projeto
- `catalog-service`: gerenciamento de produtos
- `order-service`: simulação de pedidos
- `api-gateway`: ponto de entrada das requisições
- `service-discovery`: registro e descoberta dos serviços

## 🚀 Tecnologias
- Java 17
- Spring Boot
- Spring Cloud (Eureka, Gateway)
- Maven
- Lombok
- Docker (opcional)

## 🔄 Como Executar
```bash
# Executar via IDE ou Docker Compose
mvn clean install
docker-compose up --build
