# Bytebank - Cypress E2E Tests

<p align="right"><a href="#-descrição">Leia em Português</a></p>

![Project Screenshot](/src/assets/bytebank-cypress-e2e-screenshot-0.png)

A project dedicated to End-to-End (E2E) testing for the Bytebank application, developed with **Cypress** and **JavaScript** to ensure the integrity of user flows and functionalities.

## 📝 Description

This repository contains a comprehensive suite of automated end-to-end tests for the Bytebank web application. Using Cypress, the tests simulate real user interactions to validate critical journeys, from initial registration and login to performing financial transactions and navigating the platform. The main goal is to guarantee the application's quality, stability, and reliability before deploying new features.

## ✨ Key Features

- Validation of login and registration forms.
- Simulation of a complete user journey: login, transaction, and logout.
- Tests for navigating between different pages of the application.
- Responsiveness testing for mobile devices, including burger menu interactions.
- Validation of success and error messages in user-facing forms.

## 🛠️ Technologies Used

![Cypress](https://img.shields.io/badge/Cypress-%23E5E5E5?logo=cypress&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## 🚀 Getting Started

To run the tests locally, follow these steps:

1.  **Clone the repository**

    ```bash
    git clone https://github.com/Buenohy/bytebank-cypress-e2e.git
    ```

2.  **Navigate to the project directory**

    ```bash
    cd bytebank-cypress-e2e
    ```

3.  **Install dependencies**

    ```bash
    npm install
    ```

4.  **Start the local server**

    You need to start both the API and the application in separate terminals.

    _Start the API:_

    ```bash
    npm run api
    ```

    _Start the application:_

    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.

5.  **Run the Cypress tests**

    Open the Cypress Test Runner to execute the tests interactively.

    ```bash
    npx cypress open
    ```

## 👨‍💻 Author

- **Gabriel Bueno Hygino**

## ⚖️ License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for more details.

---

# Bytebank - Testes E2E com Cypress

<p align="right"><a href="#-description">Read in English</a></p>

![Screenshot do Projeto](/src/assets/bytebank-cypress-e2e-screenshot-0.png)

Um projeto dedicado a testes End-to-End (E2E) para a aplicação Bytebank, desenvolvido com **Cypress** e **JavaScript** para garantir a integridade dos fluxos e funcionalidades do usuário.

## 📝 Descrição

Este repositório contém uma suíte completa de testes automatizados end-to-end para a aplicação web Bytebank. Utilizando Cypress, os testes simulam interações de usuários reais para validar jornadas críticas, desde o cadastro e login inicial até a realização de transações financeiras e a navegação pela plataforma. O objetivo principal é garantir a qualidade, estabilidade e confiabilidade da aplicação antes de implantar novas funcionalidades.

## ✨ Principais Funcionalidades

- Validação dos formulários de login e cadastro.
- Simulação de uma jornada de usuário completa: login, transação e logout.
- Testes para navegação entre diferentes páginas da aplicação.
- Teste de responsividade para dispositivos móveis, incluindo interações com o menu hambúrguer.
- Validação de mensagens de sucesso e erro nos formulários da aplicação.

## 🛠️ Tecnologias Utilizadas

![Cypress](https://img.shields.io/badge/Cypress-%23E5E5E5?logo=cypress&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## 🚀 Como Executar

Para executar os testes localmente, siga os passos abaixo:

1.  **Clone o repositório**

    ```bash
    git clone https://github.com/Buenohy/bytebank-cypress-e2e.git
    ```

2.  **Navegue até o diretório do projeto**

    ```bash
    cd bytebank-cypress-e2e
    ```

3.  **Instale as dependências**

    ```bash
    npm install
    ```

4.  **Inicie o servidor local**

    Você precisa iniciar tanto a API quanto a aplicação em terminais separados.

    _Inicie a API:_

    ```bash
    npm run api
    ```

    _Inicie a aplicação:_

    ```bash
    npm start
    ```

    A aplicação estará disponível em `http://localhost:3000`.

5.  **Execute os testes do Cypress**

    Abra o Cypress Test Runner para executar os testes de forma interativa.

    ```bash
    npx cypress open
    ```

## 👨‍💻 Autor

- **Gabriel Bueno Hygino**

## ⚖️ Licença

Este projeto está licenciado sob a Licença ISC. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
