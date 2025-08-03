# 🤖 NLW Agents – Chat de Perguntas e Respostas

Este é um projeto Full-Stack desenvolvido durante a trilha NLW da Rocketseat. Ele permite que usuários façam perguntas em tempo real para salas de apresentação, com uma API robusta e uma interface moderna e responsiva.

---

## 📦 Tecnologias Utilizadas

### 💻 Front-end:
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)
- [React Router DOM](https://reactrouter.com/en/main)

### ⚙️ Back-end:
- [Fastify](https://www.fastify.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Zod](https://zod.dev/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

---

## 🗂️ Estrutura do Projeto

```
nlw-agents/
├── backend/     # API com Fastify, Zod, Drizzle e PostgreSQL
└── frontend/    # Interface web com React, Vite e Tailwind
```

---

## 🚀 Como Rodar o Projeto

### 🗃️ Backend

```bash
cd backend
npm install
docker run --name nlw-pg -e POSTGRES_PASSWORD=123456 -p 5432:5432 -d postgres
cp .env.example .env
npm run drizzle:push
npm run dev
```

### 💻 Frontend

```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

---

## 🌐 Funcionalidades

| Módulo     | Recurso                                       |
|------------|-----------------------------------------------|
| Web        | Visualizar salas e perguntas                  |
| Web        | Enviar novas perguntas para a sala            |
| API        | CRUD de salas e perguntas                     |
| API        | Validação de entrada com Zod                  |
| API        | Banco de dados PostgreSQL com Drizzle ORM     |

---

## 📸 Screenshots

> Adicione aqui imagens ou gifs demonstrando o funcionamento do sistema.
>
> Exemplo:
> ![Demo do Projeto](./screenshot.png)

---

## 🧑‍💻 Autor

**Gabriel Dadário**  
Desenvolvedor Full-Stack em formação

[🔗 LinkedIn](https://www.linkedin.com/in/seuusuario)  
[🐙 GitHub](https://github.com/seuusuario)

---

## 🏁 Próximos passos (sugestões)

- ✅ Adicionar autenticação por papel (admin, operador, cliente)
- ✅ Conectar a IA (Gemini API) para respostas automáticas
- ✅ Adicionar RAG com vetorização de documentos
- ✅ Integrar com WhatsApp/Telegram
- [ ] Implementar dashboard de métricas
- [ ] Treinamento contínuo da IA com base em feedbacks

---

## 📄 Licença

Este projeto está sob a licença MIT – sinta-se livre para usar, modificar e contribuir!
