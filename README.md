# Web Services API Rest

## Modelo de domínio
![Diagrama de Classes](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/f2ab73f9-0388-4081-a7eb-e5b2ac6f8b4a)

> Trata-se de um projeto Web services com Spring Boot com intuito de simular compras online!

## Diagrama de objetos
![Diagrama de Objetos](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/6e316ae9-c045-43a2-a11a-a40a9f3e5035)

## Camadas lógicas
![Camadas Lógicas](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/61f916b5-7289-43f0-8bd2-4e97d9f89cfb)

### Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você precisa compreender a linguagem Java, conceitos de POO (Encapsulamento, herança e polimorfismo)
* Você precisa compreender alguns projetos do ecossistema Spring
* Você precisa compreender o que é API Rest

### Tecnologias empregadas
- [x] Java
- [x] Spring Boot
- [x] Apache Tomcat
- [x] Maven
- [x] Banco de dados H2
- [x] Object Relational Mapping (ORM)
- [x] Postman

## Estrutura [Banco de Dados H2](https://en.wikipedia.org/wiki/H2_(DBMS))

Banco de dados totalmente contruído com ORM
<center> 
    <b>Banco de dados em memória</b>
</center>

![Banco de Dados](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/063402fd-8d45-4769-805c-b6e432ab8346)



### Imagens APIs Rest no [Postman](https://en.wikipedia.org/wiki/Postman_(software))
#### Post
> Método genérico para qualquer requisição que envia dados ao servidor.
![Post](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/33b8bf5a-5594-4da1-97be-abb4388fa2d0)


#### Get
> Método genérico para qualquer requisição que busca dados do servidor.
![Get](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/e3160577-2c95-4672-9ecd-e2a5ceab9f5d)


#### Put
> Método específico para atualização de dados no servidor.
![Put](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/7589e742-790b-4e6c-a9d9-5ea677266522)


#### Delete
> Método específico para remoção de dados no servidor.
![Delete](https://github.com/brunincodes/workshop-springboot3-jpa/assets/142227838/4c58d498-a6a9-4f66-8618-30447747d478)


## Resumo aplicação

A aplicação destina-se a elaborar as entidades do negócio com vários tipos de relacionamentos de "um para muitos", "muitos para um" e vice-versa, usando o modelo divididos em camadas lógicas que funciona no servidor, usando-se a camada Resource (controladores REST - Representational State Transfer, que são as interfaces da aplicação com o "Back End", os quais irão receber as requisições e vão responder de acordo com o comportamento do sistema), a camada de Serviços e a camada de Acesso a dados, bem como, essa pilha de camadas comunicam-se com as camadas de Entidades.
<br/>
Configurando o banco de dados relacional para testes e povoando o banco de dados, administramos o "CRUD" que são as operações de cadastro completo da entidade para criar, recuperar, atualizar e deletar, assim como, gerenciar os erros preventivos com o tratamento de exceções.
Logo, com a implementação do modelo de domínio, instanciou-se os objetos e criou-se a base de dados relacional, registrando-se automaticamente.
<br/>
Para o panorama do projeto, utilizou-se as ferramentas como o Spring Boot, o framework usado para criar a apliação, o Apache Tomcat, o conteúdo Web para usar a aplicação, o Maven, como gerenciador de dependências, o banco de dados H2 para testes, o Postman, para testar as requisições. Por fim desenvolveu-se toda a aplicação e testou-se, gerando-se o ambiente de produção no banco de dados relacional, com o Postgrees.

## Como executar o projeto: 
Para instalar o projeto, siga estas etapas:

```
<git clone git@github.com:brunincodes/workshop-springboot3-jpa.git >
```
#### Próximo passo
* Importe o projeto na IDE _**Spring Tools Suite**_, e execute a classe 
``
CourseApplication.java
`` dentro da pasta `src/main/java/com/educandoweb` | [Acessar pasta](src/main/java/com/).

# Agradecimentos:

Professor: Nélio Alves. <br />
https://devsuperior.com.br/cursos <br />
https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br
