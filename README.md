<h1 align="center">Controle de Gastos - Spring Boot + HTMX</h1>

<p align="center">
  <strong>Uma aplicação web Full Stack para gerenciamento financeiro, construída com o poder do Spring Boot e a simplicidade do HTMX.</strong>
</p>

<p align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-17-orange?logo=java">
  <img alt="Spring" src="https://img.shields.io/badge/Spring_Boot-3.x-brightgreen?logo=spring">
  <img alt="Status" src="https://img.shields.io/badge/status-finalizado-blue">
  <a href="LICENSE"><img alt="Licença" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-tecnologias-utilizadas">Tecnologias</a> •
 <a href="#-como-começar">Como Começar</a> •
 <a href="#-autor">Autor</a>
</p>

---

## 💻 Sobre o Projeto

Este projeto foi desenvolvido como parte da avaliação da disciplina de "Projeto de Aplicação Full Stack". A meta era criar uma solução completa (backend e frontend) para o controle de despesas, que fosse ao mesmo tempo robusta e de fácil utilização.

O resultado é um sistema onde o backend, construído com **Spring Boot**, gerencia toda a lógica de negócio e a persistência dos dados, enquanto o frontend, renderizado com **Thymeleaf** e aprimorado com **HTMX**, oferece uma experiência de usuário ágil e moderna, sem a necessidade de um framework JavaScript complexo.

---

## ✨ Funcionalidades

O sistema oferece as seguintes funcionalidades essenciais para o controle financeiro:

* **`CRUD de Despesas`**: Ciclo completo de operações para gerenciar os gastos.
    * **(C)reate**: Adicionar novas despesas com descrição, valor, data e categoria.
    * **(R)ead**: Listar todas as despesas cadastradas de forma clara.
    * **(U)pdate**: Editar os detalhes de qualquer despesa existente.
    * **(D)elete**: Remover despesas que não são mais necessárias.
* **`Interface Reativa`**: Graças ao HTMX, as ações do usuário resultam em atualizações parciais da página, tornando a navegação mais rápida e fluida.
* **`Persistência Confiável`**: Os dados são armazenados em um banco de dados PostgreSQL, garantindo segurança e consistência.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com um ecossistema de tecnologias modernas e eficientes, focadas em produtividade e performance.

| Categoria | Tecnologia/Ferramenta |
|-----------|-----------------------|
| **Backend** | `Java 17`, `Spring Boot`, `Spring Web`, `Spring Data JPA` |
| **Frontend**| `Thymeleaf`, `HTMX`, `HTML5`, `CSS3 (Bootstrap)` |
| **Banco de Dados**| `PostgreSQL` (Produção), `H2` (Desenvolvimento) |
| **Build/Gerenciamento** | `Apache Maven` |
| **Deploy** | `Render.com` |

---

## 🚀 Como Começar

Para executar este projeto em seu ambiente local, siga os passos detalhados abaixo.

### **Pré-requisitos:**

* **Java Development Kit (JDK)** - `Versão 17 ou superior`
* **Apache Maven** - `Versão 3.8 ou superior`
* **Git** para clonar o repositório
* Um SGBD **PostgreSQL** instalado e em execução (opcional, pode usar H2)

### **Guia de Instalação:**

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Configure o Banco de Dados:**
    * Abra o arquivo `src/main/resources/application.properties`.
    * Atualize as propriedades `spring.datasource.url`, `spring.datasource.username`, e `spring.datasource.password` com as credenciais do seu banco PostgreSQL. Se preferir, mantenha o H2 (banco em memória) para testes.

3.  **Execute a Aplicação:**
    * Utilize o Maven Wrapper para iniciar o servidor.
    ```bash
    # No Windows
    ./mvnw spring-boot:run
    
    # No Linux ou macOS
    ./mvnw spring-boot:run
    ```
    * A aplicação estará disponível em `http://localhost:8080`.

### **Deploy na Nuvem com Render:**

* Crie um **Web Service** no [Render](https://render.com) e conecte seu repositório.
* **Build Command**: `./mvnw clean install`
* **Start Command**: `java -jar target/nome-do-seu-jar.jar`
* Não se esqueça de criar um banco de dados **PostgreSQL** no Render e configurar a variável de ambiente `SPRING_DATASOURCE_URL` no seu Web Service.

---

## 👨‍💻 Autor

Desenvolvido por **Giovanni dos Santos Zago**.

<div>
  <a href="https://github.com/seu-usuario" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/seu-linkedin/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>
🛍️ Corra e garanta já o seu!
📍 Av. 7 de Setembro, 694 - Paraguaçu Paulista
⏰ Atendimento até as 18:00H
