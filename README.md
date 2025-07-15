# NLW Agents (Intermediário) - Backend

Este repositório faz parte do **Let me Ask**, projeto desenvolvido durante o evento "Next Level Week: Agents" da Rocketseat, realizado entre os dias 7 e 13 de julho de 2025.

## Especificações Técnicas

- **Servidor:** Node.js + Fastify
- **ORM:** Drizzle ORM
- **Banco de Dados:** PostgreSQL (com extensão pgvector)
- **Validação:** Zod
- **Migrações e Seeds:** Drizzle ORM + Drizzle Seed

## Tecnologias Utilizadas

- Node.js
- Fastify
- Drizzle ORM
- PostgreSQL
- Zod
- Drizzle Seed

## Como clonar e utilizar

```sh
git clone https://github.com/arthurcrodri/nlw-agents-intermediario-backend.git
cd nlw-agents-intermediario-backend
```

### 1. Instale as dependências

```sh
npm install
```

### 2. Configure o banco de dados PostgreSQL

Você pode subir o banco com Docker:

```sh
docker-compose up -d
```

### 3. Configure as variáveis de ambiente

Copie o arquivo `.env.example` para `.env` e ajuste se necessário.

### 4. Execute as migrações e seeds

```sh
npx drizzle-kit generate
npx drizzle-kit migrate
npm run db:seed
```

### 5. Inicie o servidor

```sh
npm run dev
```

O backend estará disponível em `http://localhost:3333`.

---

**Repositório Front-End:** [https://github.com/arthurcrodri/nlw-agents-intermediario-frontend](https://github.com/arthurcrodri/nlw-agents-intermediario-frontend)
**Repositório Back-End:** [https://github.com/arthurcrodri/nlw-agents-intermediario-backend](https://github.com/arthurcrodri/nlw-agents-intermediario-backend)