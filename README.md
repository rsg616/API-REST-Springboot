# API REST com Spring Boot

Este projeto é uma API REST simples desenvolvida em Java utilizando o framework Spring Boot.  
Ela permite realizar operações de CRUD (Create, Read, Update, Delete) para gerenciar usuários.

## 🚀 Tecnologias utilizadas

- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**
- **H2 Database (Banco em memória)**
- **Maven**
- **Lombok**

## 📦 Como executar o projeto

### Pré-requisitos

- Java 17 instalado
- Maven instalado (opcional se usar VS Code com extensões)
- IDE (IntelliJ IDEA, Eclipse, VS Code)

### Passos para rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/rsg616/API-REST-Springboot.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd API-REST-Springboot
   ```
3. Rode o projeto:
   ```bash
   mvn spring-boot:run
   ```

A aplicação estará disponível em:  
👉 `http://localhost:8080`

## 🛠️ Endpoints disponíveis

| Método | Endpoint | Descrição |
|:------|:---------|:----------|
| GET | `/api/hello` | Testa se a API está online |
| GET | `/api/usuarios` | Lista todos os usuários |
| POST | `/api/usuarios` | Cria um novo usuário |
| PUT | `/api/usuarios/{id}` | Atualiza um usuário existente |
| DELETE | `/api/usuarios/{id}` | Deleta um usuário |

---

## 🗄️ Acesso ao Banco de Dados H2

- Acesse: `http://localhost:8080/h2-console`
- JDBC URL: `jdbc:h2:mem:testdb`
- User: `sa`
- Senha: (deixe em branco)

---

## 📚 Estrutura do Projeto

```
minha-api
 ├── src/main/java/com/exemplo/minhaapi
 │    ├── controllers
 │    ├── models
 │    ├── repositories
 │    ├── services
 │    └── MinhaApiApplication.java
 ├── src/main/resources
 │    └── application.properties
 ├── pom.xml
```

---

## ✨ Autor

| Nome | GitHub |
|:-----|:-------|
| Seu Nome Aqui | [@rsg616](https://github.com/rsg616) |
