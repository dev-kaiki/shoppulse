# ShopPulse — Admin Dashboard (KPIs + Filters + Export)

[![CI](https://github.com/dev-kaiki/shoppulse/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/shoppulse/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Dashboard admin com KPIs, filtros, paginação e exportação (CSV/JSON). Feito pra demonstrar **UI + API escalável**.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> Os KPIs entram no roadmap abaixo.

---

## ✅ Roadmap (MVP do demo)
- [ ] CRUD: produtos
- [ ] CRUD: pedidos
- [ ] KPIs: receita, tickets, top produtos
- [ ] Filtros por data/categoria
- [ ] Export CSV
- [ ] UI com páginas e tabela

---

## ▶️ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d
