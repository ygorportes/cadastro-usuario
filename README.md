
# 📋 Cadastro de Usuário

Projeto simples feito com Spring Boot pra gerenciar usuários. Permite salvar, buscar, atualizar e deletar usuários com base no e-mail ou ID.

## 🔧 Tecnologias usadas

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Lombok

## 📬 Endpoints disponíveis

| Método | Endpoint         | Descrição                    |
| ------ | ---------------- | ---------------------------- |
| POST   | `/usuarios`      | Cria um novo usuário         |
| GET    | `/usuarios`      | Busca um usuário por e-mail  |
| PUT    | `/usuarios?id=1` | Atualiza um usuário pelo ID  |
| DELETE | `/usuarios`      | Deleta um usuário por e-mail |

## 🛠 Estrutura do projeto

- `controller/` → Camada de entrada (REST)

- `business/` → Regras de negócio

- `infrastructure/entity` → Entidades JPA

- `infrastructure/repository` → Repositórios JPA

