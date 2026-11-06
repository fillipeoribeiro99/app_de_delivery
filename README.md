# 🌱 Eco Tech Entregas | Aplicação Web de Delivery

## 📌 Sobre o projeto

O **Eco Tech Entregas** é um projeto de aplicação web de delivery, desenvolvido com foco em tecnologia, organização de pedidos e experiência do usuário.

A aplicação integra um frontend desenvolvido com **HTML, CSS e JavaScript** a um backend construído com **Java e Spring Boot**, utilizando **MySQL** para armazenamento de dados.

O projeto foi desenvolvido para colocar em prática conhecimentos de desenvolvimento web, integração entre sistemas, APIs REST e persistência de dados.

---

## 🚀 Funcionalidades

- Cadastro de usuários.
- Login de usuários.
- Interface web para navegação e compras.
- Adição de produtos ao carrinho.
- Armazenamento do carrinho no banco de dados por usuário.
- Consulta dos itens adicionados ao carrinho.
- Remoção dos itens do carrinho.
- Integração entre frontend, backend e banco de dados.

---

## 🛠️ Tecnologias utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- API REST

### Banco de dados
- MySQL

### Ferramentas
- Git
- GitHub
- Maven
- Visual Studio Code

---

## 🔗 Endpoints da API

### Usuários

| Método | Endpoint | Descrição |
|---|---|---|
| POST | `/api/users/register` | Cadastrar usuário |
| POST | `/api/users/login` | Realizar login |
| GET | `/api/users` | Listar usuários |

### Carrinho de compras

| Método | Endpoint | Descrição |
|---|---|---|
| POST | `/api/cart/add/{email}` | Adicionar item ao carrinho |
| GET | `/api/cart/{email}` | Consultar itens do carrinho |
| DELETE | `/api/cart/{email}` | Limpar carrinho |

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/fillipeoribeiro99/app_de_delivery.git
```

### 2. Criar o banco de dados

No MySQL, execute:

```sql
CREATE DATABASE ecotech;
```

### 3. Configurar a conexão

No arquivo `src/main/resources/application.properties`, configure a conexão com o MySQL.

Recomenda-se utilizar variáveis de ambiente para as credenciais, evitando publicar senhas no GitHub.

### 4. Executar a aplicação

No terminal, dentro da pasta do projeto:

```bash
mvn spring-boot:run
```

### 5. Acessar o sistema

Abra o navegador:

```text
http://localhost:8080/index.html
```

---

## 🎯 Objetivo do projeto

O Eco Tech Entregas foi desenvolvido para aprimorar conhecimentos em desenvolvimento de aplicações web, programação Java, integração de APIs e gerenciamento de dados.

O projeto também explora conceitos de experiência do usuário e organização de funcionalidades em uma aplicação de delivery.

---

## 📂 Repositório

**Código-fonte:**  
https://github.com/fillipeoribeiro99/app_de_delivery

---

## 👨‍💻 Desenvolvedor

**Desenvolvido por Fillipe de Oliveira Ribeiro.**

Bacharel em Sistemas de Informação, com interesse em Desenvolvimento Web, Análise de Dados, Business Intelligence e Tecnologia.

**LinkedIn:**  
https://www.linkedin.com/in/filliperibeiro/

**GitHub:**  
https://github.com/fillipeoribeiro99

---

⭐ *Projeto desenvolvido para fins de aprendizado, prática e demonstração de conhecimentos técnicos.*
