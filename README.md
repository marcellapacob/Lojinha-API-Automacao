## **Lojinha API Automação**

Esse é um repositório que contém a automação de alguns testes de API Rest de um software denominado Lojinha. Os sub-tópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.

## **Tecnologias Utilizadas**

- Java (https://www.oracle.com/pt/java/technologies/javase/jdk12-archive-downloads.html)
- JUnit (https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-migrationsupport/5.7.1)
- RestAssured (https://mvnrepository.com/artifact/io.rest-assured/rest-assured/4.4.0)
- Maven (https://maven.apache.org/)

## **Testes Automatizados**

Testes para validar as partições de equivalência relacionadas ao valor do produto na Lojinha, que estão vinculados diretamente a regra de negócio que diz que o valor do produto deve estar entre R$0,01 a R$7.000,00.

## **Notas Gerais**

1. Sempre utilizamos a anotação Before Each para capturar o token que será utilizado posteriormente nos métodos de teste.
2. Armazenamos os dados que são enviados para a API através do uso de classes POJO.
3. Criamos dados iniciais através do uso de classe Data Factory para facilitar a criação e controle dos mesmos.
4. Nesse projeto fazemos uso do JUnit 5, o que nos dá a possiilidade de usar a anotação DisplayName para dar descrições em Português para nossos testes.
