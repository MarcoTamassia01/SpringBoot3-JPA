<h1 align="center">Projeto Web Services com Spring Boot e JPA / Hibernate</h1>

<p>Este é um projeto Java utilizando Spring Boot, JPA/Hibernate, e banco de dados H2 para demonstrar a implementação de um sistema de CRUD (Create, Retrieve, Update, Delete) com tratamento de exceções.</p>

## Objetivos
- [x] Implementar modelo de domínio
- [x] Estruturar camadas lógicas: resource, service, repository
- [x] Povoar o banco de dados
- [x] Implementar CRUD
- [x] Implementar tratamento de exceções

## Tecnologias Utilizadas

- Java
- Spring Boot3
- Spring Data JPA
- Hibernate
- H2 Database
- Maven
- Postman


           
          

  <img height = 100 hidht = 120 src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" /> <img height = 100 hidht = 120 src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original-wordmark.svg" />   <img height = 130 hidht = 120 src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original-wordmark.svg" />   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/maven/maven-original-wordmark.svg" /> <img height = 100 hidht = 120 src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tomcat/tomcat-original-wordmark.svg" />
                
## Estrutura do Dominio

<img src =https://r2.easyimg.io/9rn0xvian/capturar.png />


## Estrutura do Projeto
  * **Camada de Resource**: Responsável por expor os endpoints RESTful da aplicação. Nesta camada, são implementados os controllers que recebem as requisições HTTP e chamam os métodos apropriados na camada de serviço.
 
  * **Camada de Service**: Responsável pela lógica de negócio da aplicação. Aqui são implementados os serviços que realizam as operações específicas da aplicação, como cadastro, atualização, remoção e consulta de dados.

  * **Camada de Repository**: Responsável pela interação com o banco de dados. Nesta camada, são implementados os repositórios que utilizam o Spring Data JPA para realizar operações de CRUD no banco de dados..
 
  * **Camada de Entiteis**: Representam os objetos de domínio da aplicação e são mapeadas para tabelas no banco de dados. As entidades geralmente possuem anotações do JPA para configurar o mapeamento para o banco de dados..


## Uso
Para executar o projeto, você pode utilizar a IDE de sua preferência com suporte ao Spring Boot ou utilizar o Maven

## Créditos

Agradecimentos especiais ao Professor Nelio Alves por sua contribuição.

## Contato

Para mais informações, entre em contato em marco.a.s.tamassia@gmail.com.
