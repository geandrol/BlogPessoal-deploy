# Blog Pessoal - Deploy

Este repositório contém um projeto de Blog Pessoal desenvolvido em Java com Spring Boot, permitindo a criação, edição e gerenciamento de postagens e temas.

## 📌 Menu de Navegação

[📌 Tecnologias Utilizadas](#-tecnologias-utilizadas) | [🚀 Funcionalidades](#-funcionalidades) | [📦 Instalação e Execução](#-instalação-e-execução) | [📂 Estrutura do Projeto](#-estrutura-do-projeto) | [🛠 Configuração do Banco de Dados](#-configuração-do-banco-de-dados) | [✉️ Contato](#-contato)

## 📌 Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Security
- JPA/Hibernate
- MySQL
- Swagger
- Render (para deploy)

## 🚀 Funcionalidades

- Cadastro e autenticação de usuários
- Criação, edição e exclusão de postagens
- Gerenciamento de temas para postagens
- Proteção de rotas com autenticação JWT
- Documentação com Swagger

## 📦 Instalação e Execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/geandrol/BlogPessoal-deploy.git
   ```
2. Importe o projeto para sua IDE preferida (Eclipse, IntelliJ, NetBeans, etc.).
3. Configure o banco de dados MySQL e atualize as credenciais no `application.properties`.
4. Execute o projeto com:
   ```sh
   mvn spring-boot:run
   ```

## 📂 Estrutura do Projeto

```
BlogPessoal-deploy/
│-- src/                   # Código-fonte do projeto
│-- resources/             # Arquivos de configuração e scripts SQL
│-- pom.xml                # Dependências do projeto
│-- README.md              # Documentação do projeto
```

## 🛠 Configuração do Banco de Dados

1. Crie um banco de dados no MySQL:
   ```sql
   CREATE DATABASE blog_pessoal;
   ```
2. Execute os scripts SQL presentes na pasta `resources` para criar as tabelas necessárias.
3. Atualize as configurações de conexão no `application.properties`, caso seja necessário.

## ✉️ Contato

Caso tenha dúvidas ou sugestões, entre em contato:
- GitHub: [geandrol](https://github.com/geandrol)
- Email: [SeuEmail@example.com](geandro_a@hotmail.com)


