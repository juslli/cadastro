# 🚀 API REST - Cadastro de Pessoas

API desenvolvida com **Java + Spring Boot**, com operações completas de CRUD, validação de dados, tratamento de erros e integração com banco de dados MySQL.

---

## 🧠 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Swagger (OpenAPI)
- Maven

---

## ⚙️ Funcionalidades

- Criar pessoa
- Listar todas as pessoas
- Buscar pessoa por ID
- Atualizar dados de pessoa
- Deletar pessoa
- Validação de campos (nome e email)
- Tratamento de erros de validação

---

## 🔗 Endpoints da API

| Método | Endpoint | Descrição |
|--------|----------|----------|
| POST   | /pessoas | Criar nova pessoa |
| GET    | /pessoas | Listar todas |
| GET    | /pessoas/{id} | Buscar por ID |
| PUT    | /pessoas/{id} | Atualizar pessoa |
| DELETE | /pessoas/{id} | Deletar pessoa |

---

## 🧪 Testes da API

A API pode ser testada diretamente pelo Swagger:

```text
http://localhost:8080/swagger-ui.html