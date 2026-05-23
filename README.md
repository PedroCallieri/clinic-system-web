# 🏥 Clinic System

## 📌 Descrição

Sistema web de gerenciamento clínico que permite o controle de pacientes, médicos, prontuários e exames. Desenvolvido como projeto acadêmico em equipe durante o curso técnico de Desenvolvimento de Sistemas (SENAI Florianópolis).

---

## 🚀 Tecnologias

### Backend
- Node.js + TypeScript
- Prisma ORM
- PostgreSQL
- JWT (autenticação)
- Arquitetura em camadas: routes → controller → service → repository

### Frontend
- React
- Tailwind CSS

---

## ⚙️ Funcionalidades

- Autenticação de usuários com JWT
- Cadastro e listagem de pacientes e médicos
- Registro e visualização de prontuários
- Gerenciamento de exames
- Interface responsiva com Tailwind CSS

---

## 🏗️ Arquitetura do Backend

```
src/
├── routes/        # Definição das rotas da API
├── controllers/   # Recebe requisições e chama os serviços
├── services/      # Regras de negócio
├── repositories/  # Comunicação com o banco de dados (Prisma)
└── middlewares/   # Autenticação JWT e validações
```

---

## 👨‍💻 Minha contribuição

- Desenvolvimento do backend completo (rotas, controllers, services, repositories)
- Implementação da autenticação com JWT
- Modelagem do banco de dados com Prisma
- Integração backend ↔ frontend

---

## ▶️ Como rodar o projeto

### Pré-requisitos
- Node.js 18+
- PostgreSQL rodando localmente

### Backend
```bash
cd clinic_backend
npm install
npx prisma migrate dev
npm run dev
```

### Frontend
```bash
cd clinic_frontend
npm install
npm run dev
```

### Variáveis de ambiente (backend)

Crie um arquivo `.env` com:
```
DATABASE_URL="postgresql://usuario:senha@localhost:5432/clinic"
JWT_SECRET="sua_chave_secreta"
PORT=3333
```

---

## 👥 Time

Projeto desenvolvido com ajuda de Professores — SENAI Florianópolis, 3ª fase do CT de Desenvolvimento de Sistemas.
