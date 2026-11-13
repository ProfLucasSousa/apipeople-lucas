# API People

API REST de cadastro de pessoas desenvolvida como projeto da Digital Innovation One (DIO). O projeto demonstra um CRUD com Spring Boot, Spring Data JPA, banco H2, DTOs, validação, MapStruct e testes.

## Tecnologias

- Java 11
- Spring Boot 2.2
- Spring Web e Spring Data JPA
- H2 Database
- Lombok e MapStruct
- Maven Wrapper

## Estrutura

O código do projeto está na pasta `apipeople-lucas-main/`.

## Como executar

```bash
cd apipeople-lucas-main
./mvnw spring-boot:run
```

No Windows:

```powershell
cd apipeople-lucas-main
.\mvnw.cmd spring-boot:run
```

A aplicação usa, por padrão, a porta `8080`.

## Endpoints

Base: `http://localhost:8080/api/v1/people`

| Método | Rota | Ação |
| --- | --- | --- |
| `POST` | `/api/v1/people` | Cadastra uma pessoa |
| `GET` | `/api/v1/people` | Lista as pessoas |
| `GET` | `/api/v1/people/{id}` | Consulta uma pessoa |
| `PUT` | `/api/v1/people/{id}` | Atualiza uma pessoa |
| `DELETE` | `/api/v1/people/{id}` | Remove uma pessoa |

## Testes

```bash
cd apipeople-lucas-main
./mvnw test
```

Há um README original dentro da pasta do projeto; este arquivo na raiz documenta a execução e facilita localizar o código.
