# ☀️ API De Previsão Do Tempo

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON" />
</p>

<p align="center">
  <strong>API RESTful para consulta e monitoramento de dados climáticos em tempo real.</strong><br>
  <strong>RESTful API for querying and monitoring real-time weather data.</strong>
</p>

<p align="center">
  <a href="#-português-br">Português-BR</a> • 
  <a href="#-english">English</a>
</p>

---

# Português-BR

## 💻 Sobre o Projeto

A **API de previsão do temp** é uma API RESTful back-end desenvolvida em **Java** com o ecossistema **Spring Boot**. O objetivo principal do projeto é centralizar, processar e expor dados de previsão do tempo de forma otimizada para o consumo de aplicações client-side (web ou mobile).

O sistema funciona como um microsserviço intermediário que se conecta a provedores globais de dados climáticos, aplicando regras de negócio, tratamento de exceções robusto e formatação de dados padronizada em JSON para garantir respostas rápidas e confiáveis.

---

## ✨ Funcionalidades

- 🌍 **Consulta por Localização:** Busca de condições climáticas atuais filtradas por cidade, coordenadas ou região.
- 📊 **Dados Detalhados:** Retorno completo incluindo temperatura, sensação térmica, umidade, velocidade do vento e condições textuais.
- 🔄 **Integração HTTP Dinâmica:** Consumo assíncrono e performático de APIs externas de clima.
- 🛠️ **Tratamento de Erros:** Respostas HTTP semânticas (404 Not Found, 400 Bad Request) com mensagens claras em caso de falhas na busca.
- 📦 **Estrutura DTO (Data Transfer Object):** Desacoplamento completo entre as entidades de integração externa e a resposta entregue ao cliente.

---

## 🛠️ Tecnologias Utilizadas

- **Java (JDK 17+)** – Linguagem base focada em tipagem forte e performance orientada a objetos.
- **Spring Boot** – Framework para agilizar o setup de aplicações prontas para produção.
- **Spring Web** – Módulo para criação de endpoints REST e controle de requisições HTTP.
- **Jackson/JSON** – Serialização e desserialização eficiente de payloads de dados.
- **Maven** – Gerenciador de dependências e automação de build do projeto.

---

## 📈 Detalhes Técnicos da Arquitetura

O projeto segue os padrões da arquitetura em camadas do ecossistema Spring:

1. **`Controller`:** Camada de entrada que expõe os endpoints HTTP e gerencia as requisições do usuário.
2. **`Service`:** Concentra as regras de negócio, chamadas externas e tratamento das regras de validação.
3. **`Model/DTO`:** Classes de transporte de dados estritamente tipadas para garantir a integridade do JSON trafegado.

---

# English-US

## 💻 About the Project

The **Weather Forecast API** is a back-end RESTful API developed in **Java** leveraging the **Spring Boot** ecosystem. The main objective of the project is to centralize, process, and expose weather forecast data optimized for client-side applications (web or mobile).

The system acts as an intermediary microservice that connects to global weather data providers, applying business rules, robust exception handling, and standardized JSON data formatting to ensure fast and reliable responses.

---

## ✨ Features

- 🌍 **Location-Based Query:** Fetch current weather conditions filtered by city, coordinates, or region.
- 📊 **Detailed Data:** Complete response including temperature, thermal sensation, humidity, wind speed, and textual conditions.
- 🔄 **Dynamic HTTP Integration:** Asynchronous and high-performance consumption of external weather APIs.
- 🛠️ **Error Handling:** Semantic HTTP responses (404 Not Found, 400 Bad Request) with clear error messages in case of lookup failures.
- 📦 **DTO (Data Transfer Object) Pattern:** Complete decoupling between external integration models and the final client response.

---

## 🛠️ Technologies Used

- **Java (JDK 17+)** – Base programming language focused on strong typing and object-oriented performance.
- **Spring Boot** – Framework to accelerate the setup of production-ready applications.
- **Spring Web** – Module for creating REST endpoints and managing HTTP requests.
- **Jackson/JSON** – Efficient serialization and deserialization of data payloads.
- **Maven** – Dependency management and project build automation.

---

## 📈 Technical Architecture Details

The project follows the standard layered architecture of the Spring ecosystem:

1. **`Controller`:** The entry layer that exposes HTTP endpoints and handles incoming user requests.
2. **`Service`:** Houses the core business logic, external API calls, and validation handling.
3. **`Model/DTO`:** Strictly typed data transfer objects to ensure the integrity of the transmitted JSON payload.
