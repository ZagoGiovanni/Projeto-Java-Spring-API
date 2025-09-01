<h1 align="center">Lista de Tarefas - API REST</h1>
<p align="center">API RESTful para um sistema de gerenciamento de tarefas (To-Do List), desenvolvida com Spring Boot.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-blue?style=for-the-badge&logo=java" alt="Java 21">
  <img src="https://img.shields.io/badge/Spring_Boot-3-success?style=for-the-badge&logo=spring" alt="Spring Boot 3">
  <img src="https://img.shields.io/badge/Maven-4-red?style=for-the-badge&logo=apache-maven" alt="Maven">
  <img src="https://img.shields.io/badge/PostgreSQL-16-blue?style=for-the-badge&logo=postgresql" alt="PostgreSQL">
</p>

<details>
  <summary><strong>📝 Sobre o Projeto</strong></summary>
  <br>
  Esta API foi criada para servir como o backend da aplicação "Lista de Tarefas". Ela gerencia todas as operações de CRUD (Criar, Ler, Atualizar e Deletar) para as tarefas, utilizando uma arquitetura RESTful.

  O projeto foi desenvolvido seguindo o tutorial "Projeto Aplicação Full Stack" do professor Ricardo Tec.
</details>

## 🏛️ Arquitetura da Solução

Este projeto corresponde à API (Backend) da aplicação "Lista de Tarefas". A solução completa é modularizada em três repositórios independentes para garantir a separação de responsabilidades.

* **Backend (Este Repositório):** API RESTful desenvolvida com Spring Boot que serve como o núcleo da aplicação.
* **Frontend (Web):** Interface web desenvolvida com Angular.
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-Web`
* **Desktop:** Aplicação de desktop (a ser desenvolvida).
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-Desktop`

## 💻 Tecnologias Utilizadas

* **Linguagem:** Java 21
* **Framework:** Spring Boot 3
* **Banco de Dados:**
    * H2 (Ambiente de Desenvolvimento)
    * PostgreSQL (Ambiente de Produção)
* **Gerenciamento de Dependências:** Maven
* **Mapeamento Objeto-Relacional:** Spring Data JPA / Hibernate

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/ZagoGiovanni/Projeto-Java-Spring-API.git]
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd lista-tarefas-api
    ```

3.  **Configure o banco de dados** no arquivo `src/main/resources/application.properties`.

4.  **Execute a aplicação:**
    ```bash
    mvn spring-boot:run
    ```

5.  A API estará disponível em `http://localhost:8080`.

## Endpoints Principais

* `GET /api/tarefas` - Lista todas as tarefas.
* `POST /api/tarefas` - Cria uma nova tarefa.
* `PUT /api/tarefas/{id}` - Atualiza uma tarefa existente.
* `DELETE /api/tarefas/{id}` - Remove uma tarefa.

## Autor

**Giovanni dos Santos Zago**

- LinkedIn: `https://www.linkedin.com/in/giovanni-zago-058891290/`
- GitHub: `https://github.com/ZagoGiovanni`
