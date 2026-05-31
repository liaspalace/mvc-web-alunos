# MVC Web - Cadastro de Alunos

# Giulia Meninel Mattedi

## Arquitetura

O projeto foi desenvolvido utilizando o padrão MVC (Model-View-Controller).

### Model

Responsável pela representação dos dados da aplicação.

* Aluno.java

### Controller

Responsável por receber as requisições HTTP e controlar o fluxo da aplicação.

* AlunoController.java

### View

Responsável pela interface com o usuário utilizando Thymeleaf.

* alunos-form.html
* alunos-lista.html

## Tecnologias Utilizadas

* Java
* Spring Boot
* Thymeleaf
* Maven

## Como Executar

1. Clone o repositório.
2. Acesse a pasta do projeto.
3. Execute:

```
.\mvnw.cmd spring-boot:run
```

4. Abra o navegador:

```
http://localhost:8080/alunos
```

## Estrutura MVC

```
src/main/java/com/exemplo/mvc
├── controller
├── model
└── MvcApplication.java

src/main/resources/templates
├── alunos-form.html
└── alunos-lista.html
```
