# Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja

* API REST para o gerenciamento de estoque;
* Desenvolver testes unitários para validar o sistema de gerenciamento de estoque;
* Criar testes unitários com JUnit e Mockito.
* Funcionalidades da API através da prática do TDD.

## Tópicos:

### Apresentação sobre testes:
    * a pirâmide dos tipos de testes;
    * importância de cada tipo de teste durante o ciclo de desenvolvimento.

### Desenvolvimento de testes unitários para validação de funcionalides básicas:
    * Criação;
    * Listagem;
    * Consulta por nome
    * Exclusão de cervejas.

### TDD: apresentação e exemplo prático em 2 funcionaliades importantes:
    * incremento no estoque
    * decremento no estoque.

### Foco nos testes unitários:
    Importância do desenvolvimento de testes como parte do ciclo de desenvolvimento de software.

### Principais frameworks para testes unitários em Java:
    * JUnit;
    * Mockito;
    * Hamcrest.

### Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run
```

### Para executar a suíte de testes, basta executar o seguinte comando:

```shell script
mvn clean test
```

### Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

### São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.

## Repositório referência:

https://github.com/rpeleias/beer_api_digital_innovation_one