# Desafio Final
O desafio final do projeto Impulsionar da [South System](https://www.linkedin.com/company/south-system/mycompany/)!

## Objetivo
O objetivo central do projeto era desenvolver um app capaz de manter usuários, assembleias e suas respectivas pautas, assim como ser possível realizar uma votação dentro de cada pauta. 

## Detalhes do projeto
- O prazo para o desenvolvimento do aplicativo foi de 6 à 27 de fevereiro;
- Foi a primeira experiência da equipe em desenvolver uma aplicação completa (backend, frontend e QA) em equipe;

 ### Observações pontuais sobre o repositório
 A entrega final da aplicação não foi completa. O ocorrido foi que a equipe toda não foi capaz de aplicar todas as funcionalidades esperadas na entrega, portanto o repositório consta com duas branches (além da [main](https://github.com/Artur-Bertoni/final-challenge) claro), a [develop](https://github.com/Artur-Bertoni/final-challenge/tree/develop), com a aplicação funcionando em sua integridade e revisada por QA e a [develop-with-security](https://github.com/Artur-Bertoni/final-challenge/tree/develop-with-security), que como consta no nome se trata da mesma aplicação com a diferença de possuir [autenticação e autorização](https://github.com/Artur-Bertoni/final-challenge/tree/develop-with-security/easy-vote-api/src/main/java/com/easyvoteapi/config/security) implementadas, com a diferença de não ter passado por testes automatizados e/ou manuais por parte da QA.
 
 ## Equipe
 ### Backend
 - [Artur Bertoni dos Santos](https://www.linkedin.com/in/artur-bertoni-dos-santos/);
 - [Jhean Ferreira Alves](https://www.linkedin.com/in/jhean-alves-b05296239/);
 - [Pedro Chaparro Stregue](https://www.linkedin.com/in/pedro-chaparro-2a28161b5/);
 ### Frontend
 - [Leonardo Masera Torres](https://www.linkedin.com/in/leonardo-torres-2b5245248/);
 - [Lucas Galarraga Burch](https://www.linkedin.com/in/lucas-galarraga-burch-32a0a018b/);
 ### QA
 - [Lyene de Souza Benvenutti](https://www.linkedin.com/in/lyene-de-souza-benvenutti/).
 
 ## [Dependências utilizadas](https://github.com/Artur-Bertoni/final-challenge/blob/develop-with-security/easy-vote-api/pom.xml) (backend)
 - [Spring Boot](https://spring.io/projects/spring-boot) (org.springframework.boot) -> utilizando os artefatos [spring-boot-starter-web](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-web), [spring-boot-starter-data-jpa](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-data-jpa), [spring-boot-starter-security](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-security), [spring-boot-starter-validation](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation) e [spring-boot-starter-amqp](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-amqp);
 - [Spring OAuth](https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html) (org.springframework.security.oauth.boot) -> utilizando o artefato [spring-security-oauth2-autoconfigure](https://mvnrepository.com/artifact/org.springframework.security.oauth.boot/spring-security-oauth2-autoconfigure);
- [Flyway](https://flywaydb.org) (org.flywaydb) -> utilizando o artefato [flyway-core](https://mvnrepository.com/artifact/org.flywaydb/flyway-core);
- [PostgreSQL](https://www.postgresql.org) (org.postgresql) -> utilizando o artefato [postgresql](https://mvnrepository.com/artifact/org.postgresql/postgresql);
- [Lombok](https://projectlombok.org) (org.projectlombok) -> utilizando o artefato [lombok](https://mvnrepository.com/artifact/org.projectlombok/lombok);
- [ModelMapper](https://modelmapper.org) (org.modelmapper) -> utilizando o artefato [modelmapper](https://mvnrepository.com/artifact/org.modelmapper/modelmapper);
- [Mapstruct](https://mapstruct.org) (org.mapstruct) -> utilizando os artefatos [mapstruct-processor](https://mvnrepository.com/artifact/org.mapstruct/mapstruct-processor) e [mapstruct](https://mvnrepository.com/artifact/org.mapstruct/mapstruct);
- [Javafx Validation](https://mvnrepository.com/artifact/javax.validation) (javax.validation) -> utilizando o artefato [validation-api](https://mvnrepository.com/artifact/javax.validation/validation-api);
- [Open API](https://springdoc.org) (org.springdoc) -> utilizando o artefato [springdoc-openapi-ui](https://mvnrepository.com/artifact/org.springdoc/springdoc-openapi-ui);
#### Testes
- [Spring Boot](https://spring.io/projects/spring-boot) (org.springframework.boot) -> utilizando o artefato [spring-boot-starter-test](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-test);
- [Spring Security](https://docs.spring.io/spring-security/reference/index.html) (org.springframework.security) -> utilizando o artefato [spring-security-test](https://mvnrepository.com/artifact/org.springframework.security/spring-security-test);
- [Spring AMQP](https://docs.spring.io/spring-amqp/reference/html/) (org.springframework.amqp) -> utilizando o artefato [spring-rabbit-test](https://mvnrepository.com/artifact/org.springframework.amqp/spring-rabbit-test);
- [JavaFaker](https://github.com/DiUS/java-faker) (com.github.javafaker) -> utilizando o artefato [javafaker](https://mvnrepository.com/artifact/com.github.javafaker/javafaker).
- [H2](https://www.h2database.com/html/main.html) (com.h2database) -> utilizando o artefato [h2](https://mvnrepository.com/artifact/com.h2database/h2);
