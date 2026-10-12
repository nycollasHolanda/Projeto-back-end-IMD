# API de Gerenciamento de Blog e Usuários

Uma API RESTful desenvolvida em Node.js para gerenciamento de postagens e usuários, com suporte a autenticação via token JWT, upload de imagens e renderização de views no servidor.

O projeto foi construído utilizando a arquitetura MVC (Model-View-Controller) e conta com documentação baseada na especificação OpenAPI (Swagger).

## 🚀 Tecnologias Utilizadas

- **Backend:** Node.js, Express
- **Banco de Dados:** SQLite (Desenvolvimento) e PostgreSQL (Produção)
- **ORM:** Sequelize
- **Autenticação:** JSON Web Token (JWT)
- **Views:** EJS (Embedded JavaScript templating)
- **Documentação:** Swagger (`api.yaml`)

## ⚙️ Funcionalidades

- CRUD completo de Usuários e Posts.
- Autenticação e proteção de rotas (Middlewares).
- Upload local de imagens de destaque para os posts.
- Validação de schemas nos dados de entrada.
- Views integradas para navegação visual e consumo dos dados.

## 🛠️ Como Executar Localmente

1. Instale as dependências:
   ```bash
   npm install