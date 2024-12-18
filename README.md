# FórumHub 📝

FórumHub é uma API REST desenvolvida em Java usando o framework Spring Boot. Este projeto implementa um sistema de gerenciamento de tópicos de fórum com operações CRUD (Criar, Ler, Atualizar e Deletar) integradas com um banco de dados MySQL. O objetivo é fornecer uma solução eficiente e escalável para o gerenciamento de discussões em fóruns online.

---

## ⚙️ Funcionalidades

- **Criar Tópico**: Permite a criação de novos tópicos.
- **Listar Tópicos**: Retorna todos os tópicos cadastrados.
- **Consultar Tópico por ID**: Retorna os detalhes de um tópico específico.
- **Atualizar Tópico**: Permite a atualização das informações de um tópico existente.
- **Deletar Tópico**: Remove um tópico do sistema.
- **Autenticação e Autorização**: Restrição de acesso baseada em roles (em desenvolvimento).

---

## 🚀 Tecnologias Utilizadas

- **Java 23** 
- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **Hibernate**
- **Spring Security** (em desenvolvimento)
- **Insomnia** (para testes de API)

---

## 📂 Estrutura do Projeto

```plaintext
src
├── main
│   ├── java
│   │   └── com.alura.ForumHub
│   │       ├── controller
│   │       │   └── TopicoController.java
│   │       ├── model
│   │       │   └── Topico.java
│   │       ├── repository
│   │       │   └── TopicoRepository.java
│   │       └── service
│   │           └── TopicoService.java (opcional)
│   └── resources
│       ├── application.properties
│       └── data.sql (opcional)
└── test

