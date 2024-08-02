# Task Time Management

Este projeto é uma API para gerenciamento de tarefas e controle de tempo utilizando Java 1.8, JSF, Maven e Docker. A aplicação permite que os usuários iniciem e encerrem a contagem de tempo dedicado a uma tarefa específica, armazenando esses dados para posterior análise.

## Tecnologias Utilizadas

- **Java 1.8**: Linguagem de programação principal do projeto.
- **JSF (JavaServer Faces)**: Framework para construção da interface web e controle de fluxo.
- **Maven**: Ferramenta de automação de build e gerenciamento de dependências.
- **Docker**: Utilizado tanto para o ambiente de desenvolvimento quanto para o deploy em produção.
- **WildFly**: Servidor de aplicação para executar a aplicação JSF.
- **MySQL**: Banco de dados relacional utilizado para armazenar as tarefas e os registros de tempo.

## Funcionalidades

- **Gerenciamento de Tarefas**: Criação, visualização e atualização de tarefas.
- **Controle de Tempo**: Endpoints para iniciar e finalizar o tempo dedicado a uma tarefa.
- **Persistência de Dados**: Utiliza JPA para persistência dos dados em um banco de dados MySQL.
