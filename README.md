# Código Fonte

https://github.com/YspaceBR/Tech-Recycle

Tech-Recycle/
├── assets/ # Arquivos estáticos (CSS, imagens)
├── controllers/ # Lógica das rotas e controladores
├── models/ # Acesso ao banco de dados (usuário, etc.)
├── routes/ # Arquivos de rotas organizadas
├── tests/ # Testes de unidade com Jest
├── views/
│ ├── layouts/
│ ├── public/
│ └── auth/
├── .env
├── index.js # Arquivo principal da aplicação
├── package.json
└── README.md

# 🌱 Tech-Recycle

Sistema web para incentivar o descarte correto de resíduos, com cadastro e login de usuários, funcionalidades de mapa e informações de reciclagem.

## 📦 Tecnologias

- Node.js
- Express
- MySQL
- Handlebars
- bcrypt (hash de senha)
- express-session
- Jest (testes)

## 🚀 Como rodar localmente

1. Clone o repositório
2. Instale as dependências: `npm install`
3. Configure o `.env` com os dados do MySQL
4. Inicie com `npm start`

## 🧪 Testes

- Para rodar os testes: `npm test`

## ✅ Requisitos Atendidos

- Cadastro e login de usuários
- Senha com hash
- Sessão segura
