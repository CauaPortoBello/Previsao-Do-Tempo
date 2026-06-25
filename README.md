# ☀️ API De Previsão Do Tempo

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

<p align="center">
  <strong>Aplicação web para consulta e monitoramento de dados climáticos em tempo real.</strong><br>
  <strong>Web application for querying and monitoring real-time weather data.</strong>
</p>

<p align="center">
  <a href="#-português-br">Português-BR</a> • 
  <a href="#-english">English</a>
</p>

---

# Português-BR

## 🔗 Demonstração Prática

O projeto está totalmente funcional e disponível para testes em ambiente de produção através do GitHub Pages.

💻 **Teste o projeto:** [Acessar Previsao Do Tempo](https://cauaportobello.github.io/Previsao-Do-Tempo/)

---

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

- **HTML5:** Estruturação semântica da interface gráfica.
- **CSS3:** Estilização moderna, estruturação de layout e total responsividade.
- **JavaScript (ES6+):** Lógica de consumo de API externa, manipulação dinâmica do DOM, tratamento de eventos e renderização dos dados na tela.

---

## 📈 Detalhes Técnicos da Arquitetura

O projeto segue os padrões da arquitetura em camadas do ecossistema Spring:

1. **`Controller`:** Camada de entrada que expõe os endpoints HTTP e gerencia as requisições do usuário.
2. **`Service`:** Concentra as regras de negócio, chamadas externas e tratamento das regras de validação.
3. **`Model/DTO`:** Classes de transporte de dados estritamente tipadas para garantir a integridade do JSON trafegado.

---

# English-US

## 🔗 Live Demo

The project is fully functional and available for testing in a production environment via GitHub Pages.

💻 **Try the project:** [Access Previsao Do Tempo](https://cauaportobello.github.io/Previsao-Do-Tempo/)

---

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

- **HTML5:** Semantic structuring of the graphical user interface.
- **CSS3:** Modern styling, layout structuring, and full responsiveness.
- **JavaScript (ES6+):** Logic for external API consumption, dynamic DOM manipulation, event handling, and data rendering on the screen.

---

## 📈 Technical Architecture Details

The project follows the standard layered architecture of the Spring ecosystem:

1. **`Controller`:** The entry layer that exposes HTTP endpoints and handles incoming user requests.
2. **`Service`:** Houses the core business logic, external API calls, and validation handling.
3. **`Model/DTO`:** Strictly typed data transfer objects to ensure the integrity of the transmitted JSON payload.
