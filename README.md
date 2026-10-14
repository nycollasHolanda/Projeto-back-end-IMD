# API de Blog e Gerenciamento de Usuários

Uma API RESTful completa desenvolvida em **Node.js** para o gerenciamento de postagens e usuários de um blog. O sistema conta com autenticação segura via tokens, upload de arquivos, validação de dados e uma interface de visualização acoplada.

Este projeto foi construído utilizando o padrão **MVC (Model-View-Controller)** e está documentado com a especificação OpenAPI (Swagger).

## Tecnologias Utilizadas

- **Linguagem & Ambiente:** JavaScript (ES6+) / Node.js
- **Framework Web:** Express.js
- **Banco de Dados:** SQLite (Desenvolvimento) / PostgreSQL (Produção)
- **ORM:** Sequelize (com Migrations e Seeders)
- **Autenticação:** JSON Web Token (JWT) e Bcrypt
- **Templates (Views):** EJS
- **Documentação:** Swagger / OpenAPI 3.0 (`api.yaml`)

## Funcionalidades

- **Usuários:** Cadastro, listagem, busca por ID e exclusão.
- **Autenticação:** Login com geração de Token JWT (Bearer Token).
- **Postagens:** Criação de publicações vinculadas a usuários autenticados.
- **Uploads:** Suporte a upload local de imagens de destaque.
- **Views:** Páginas HTML renderizadas pelo servidor para visualização das postagens.

---

## Como rodar o projeto localmente

Para rodar este projeto no seu computador, você precisará ter o [Git](https://git-scm.com/) e o [Node.js](https://nodejs.org/pt-br/) instalados.

**1. Clone o repositório**
```bash
git clone "https://github.com/SEU_USUARIO/Projeto-back-end-IMD.git"

cd Projeto-back-end-IMD