# Native PHP JWT API

Este projeto é uma API RESTful desenvolvida em PHP nativo, com autenticação baseada em JWT (JSON Web Tokens), tendo como objetivo principal aprimorar habilidades em PHP sem o uso de frameworks.

## 🎯 Objetivo
Demonstrar como criar uma API segura e modular utilizando PHP puro, JWT para autenticação de usuários, e conexão com banco de dados via MySQL. O foco está na simplicidade e no entendimento aprofundado das bases do PHP.

---
## 🚀 Funcionalidades
1. CRUD de Usuários: Gerencie dados de usuários autenticados.
2. Autenticação JWT:
 * Registro de usuários com hash de senhas.
 * Login com geração de tokens JWT.
 * Validação de tokens para rotas protegidas.
3. Endereços RESTful:
4. Rotas organizadas e acessíveis via HTTP (GET, POST, PUT, DELETE).
5. Banco de Dados Postgresql.
   
--- 
## 🛡️ Configuração de Ambiente

1. Clone este repositório:

```
git clone https://github.com/sandoelio/nativephp-jwt-api.git
```
2. Configure o banco de dados:
3. Instale as dependências via Composer:
```
composer install
```
ou
```
composer update
```
---
## Endpoints Principais
* **Registro:** POST /api/register
* **Login:** POST /api/login
* **Obter Dados do Usuário:** GET /api/user (Token necessário)
* **Atualizar Usuário:** PUT /api/user/{id}
* **Deletar Usuário:** DELETE /api/user/{id}

  ---
  
## 📌 Objetivo do Projeto
Este projeto tem como foco:

* Estimular o aprendizado e a prática com PHP nativo.
* Demonstrar a criação de uma API RESTful do zero.
* Explorar o uso de JWT para autenticação em APIs.
  
## 📧 Contato
* Autor: Sandoelio Silva
* Email: sandoelio@hotmail.com
* LinkedIn: [Sandoelio Silva](https://www.linkedin.com/in/sandoelio-silva/)

