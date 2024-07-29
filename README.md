# Task Manager

## Descrição do Projeto

O **Task Manager** é um sistema de gerenciamento de tarefas desenvolvido em Java utilizando o framework Spring Boot. Este projeto tem como objetivo fornecer uma aplicação web simples, onde os usuários podem criar, visualizar, atualizar e excluir tarefas. É um exemplo prático que demonstra como construir um CRUD (Create, Read, Update, Delete) utilizando tecnologias modernas e boas práticas de desenvolvimento.

## Funcionalidades

- **Criar Tarefas:** Permite ao usuário adicionar novas tarefas com título e descrição.
- **Visualizar Tarefas:** Exibe a lista de todas as tarefas existentes, mostrando detalhes como título e descrição.
- **Atualizar Tarefas:** Possibilita a edição de tarefas já existentes.
- **Excluir Tarefas:** Permite a remoção de tarefas da lista.
- **Interface Amigável:** Interface web simples e intuitiva, desenvolvida com HTML e Thymeleaf.

## Tecnologias Utilizadas

- **Java 17:** Linguagem de programação utilizada para desenvolver a aplicação.
- **Spring Boot:** Framework utilizado para simplificar o desenvolvimento de aplicações Java.
- **Maven:** Ferramenta de automação de compilação e gerenciamento de dependências.
- **Thymeleaf:** Template engine para a geração de páginas HTML dinâmicas.
- **H2 Database:** Banco de dados em memória utilizado para armazenamento temporário de dados.
- **JUnit:** Biblioteca para a realização de testes unitários.

## Estrutura do Projeto

task-manager/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ ├── com/
│ │ │ │ ├── example/
│ │ │ │ │ ├── taskmanager/
│ │ │ │ │ │ ├── TaskManagerApplication.java
│ │ │ │ │ │ ├── controller/
│ │ │ │ │ │ │ └── TaskController.java
│ │ │ │ │ │ ├── model/
│ │ │ │ │ │ │ └── Task.java
│ │ │ │ │ │ ├── repository/
│ │ │ │ │ │ │ └── TaskRepository.java
│ │ │ │ │ │ └── service/
│ │ │ │ │ │ └── TaskService.java
│ ├── resources/
│ │ ├── templates/
│ │ │ ├── index.html
│ │ │ ├── tasks.html
│ │ ├── application.properties
├── .gitignore
├── README.md
├── mvnw
├── mvnw.cmd
└── pom.xml
