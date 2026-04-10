# Contacts-and-Suppliers-Management-System

## Video demonstration
🇧🇷 Portuguese: https://youtu.be/-xd3Hu5IC0I
🇺🇸 Technical walkthrough (English): https://youtu.be/m6poyrLvpsk

## English

## About the project
This project was built with Java and Spring Boot, applying concepts of secure development, data persistence, and entity modeling.

## Objectives
This project simulates a contact and supplier management system used in corporate environments, featuring user authentication and role-based access control.

## Features

- **User registration and authentication.**
- **Access control with Spring Security.**
- **Save, read, update and delete operations for contacts.**
- **Save, read, update and delete operations for suppliers.**
- **Category organization.**
- **Entity relationships.**
- **Object-Oriented Programming.**

## Technologies used

- **Java.**
- **Spring Boot.**
- **Spring Security.**
- **Maven.**
- **Hibernate (JPA).**
- **Thymeleaf.**

## Architecture

- **Controller: Handles HTTP requests.**
- **Service: Business logic layer.**
- **Repository: Data access layer (JPA/Hibernate).**
- **Model: Entity definitions and domain representation.**
- **Security: Authentication, authorization, security configuration, password encryption and login handling.**

## Security

- **User authentication with Spring Security.**
- **Protected endpoints.**
- **Access control.**
- **Password encryption.**
- **Authentication and authorization.**

## Usage examples
The application also exposes REST endpoints used internally by the interface.
Authentication example:
POST /login
{
  "email": "user@email.com",
  "password": "123456"
}

POST /contacts
{
  "name": "John Senna",
  "mobileNumber": "999999999",
  "email": "john@email.com",
  "address": "Y Street",
  "category": "Friend"
}

POST /suppliers
{
  "name": "Company S.A.",
  "mobileNumber": "999999000",
  "email": "company@companySA.com",
  "address": "X Street",
  "category": "Supplier"
  "companyRegistrationNumber": "24134123444"
  "headquarter": "Brazil"
}

## Project differentiators

- **Authentication and authorization system with Spring Security.**
- **Well-defined layered architecture (Controller, Service, Repository, Models, Security).**
- **Entity modeling with relationships between users, contacts, and suppliers.**
- **Application of development best practices.**

## Author
Developed by Matheus Freire Pessoa.


## Português

## Sobre o projeto
Este projeto foi desenvolvido com Java e Spring Boot, aplicando conceitos de desenvolvimento seguro, persistência de dados e modelagem de entidades.

## Objetivos
Este projeto simula um sistema de gerenciamento de contatos e fornecedores utilizado em ambientes corporativos, com autenticação de usuários e controle de acesso baseado em funções (roles).

## Funcionalidades

- **Registro e autenticação de usuários.**
- **Controle de acesso com Spring Security.**
- **Operações de criar, ler, atualizar e deletar para contatos.**
- **Operações de criar, ler, atualizar e deletar para fornecedores.**
- **Organização por categorias.**
- **Relacionamentos entre entidades.**
- **Programação orientada a objetos.**

## Tecnologias utilizadas

- **Java.**
- **Spring Boot.**
- **Spring Security.**
- **Maven.**
- **Hibernate (JPA).**
- **Thymeleaf.**

## Arquitetura

- **Controller: Responsável por lidar com requisições HTTP.**
- **Service: Camada de lógica de negócio.**
- **Repository: Camada de acesso a dados (JPA/Hibernate).**
- **Model: Definições de entidades e representação do domínio.**
- **Security: Autenticação, autorização, configuração de segurança, criptografia de senhas e gerenciamento de login.**

## Segurança

- **Autenticação de usuários com Spring Security.**
- **Endpoints protegidos.**
- **Controle de acesso.**
- **Criptografia de senhas.**
- **Autenticação e autorização.**

## Exemplos de uso
A aplicação também expõe endpoints REST utilizados internamente pela interface.
Exemplo de autenticação:
POST /login
{
  "email": "user@email.com",
  "password": "123456"
}

POST /contacts
{
  "name": "John Senna",
  "mobileNumber": "999999999",
  "email": "john@email.com",
  "address": "Y Street",
  "category": "Friend"
}

POST /suppliers
{
  "name": "Company S.A.",
  "mobileNumber": "999999000",
  "email": "company@companySA.com",
  "address": "X Street",
  "category": "Supplier"
  "companyRegistrationNumber": "24134123444"
  "headquarter": "Brazil"
}

## Diferenciais do projeto

- **Sistema de autenticação e autorização com Spring Security.**
- **Arquitetura em camadas bem definida (Controller, Service, Repository, Models, Security).**
- **Modelagem de entidades com relacionamentos entre usuários, contatos e fornecedores.**
- **Aplicação de boas práticas de desenvolvimento.**

## Autor
Desenvolvido por Matheus Freire Pessoa.
