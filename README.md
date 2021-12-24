## Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot

Curso da Digital Innovation One, no qual foram desenvolvidos e abordados os seguintes tópicos:
* Setup inicial deprojeto com o Spring Boot Initializr
* Criação de modelo de dados para o mapeamento de entidades em bancos de dados
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema).
* Relação de cada uma das operações acima com o padrão arquitetural REST, e a explicação de cada um dos conceitos REST envolvidos durante o desenvolvimento do projeto.
* Desenvolvimento de testes unitários para validação das funcionalidades
* Implantação do sistema na nuvem através do Heroku

Os pré-requisitos para a execução do projeto são:
* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.

Para executar o projeto no terminal, digite o seguinte comando:
Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```