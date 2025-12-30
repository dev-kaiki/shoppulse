<div align="center">

# shoppulse

<a href="https://dev-kaiki-shoppulse.vercel.app"><img src="https://img.shields.io/badge/LIVE%20DEMO-Vercel-111?style=for-the-badge&logo=vercel&logoColor=white"></a>
<a href="https://dev-kaiki-shoppulse-api.onrender.com/docs"><img src="https://img.shields.io/badge/SWAGGER-API%20Docs-111?style=for-the-badge&logo=swagger&logoColor=white"></a>
<a href="https://github.com/dev-kaiki/shoppulse"><img src="https://img.shields.io/badge/REPO-GitHub-111?style=for-the-badge&logo=github&logoColor=white"></a>

</div>

## Quick Links
- Live: https://dev-kaiki-shoppulse.vercel.app
- Swagger: https://dev-kaiki-shoppulse-api.onrender.com/docs

## Deploy (1-click)
- Deploy API (Render): https://render.com/deploy?repo=https://github.com/dev-kaiki/shoppulse
- Deploy Web (Vercel): https://vercel.com/new/clone?repository-url=https://github.com/dev-kaiki/shoppulse

---

# ShopPulse â€” Admin Dashboard (KPIs + Filters + Export)

[![CI](https://github.com/dev-kaiki/shoppulse/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/shoppulse/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Dashboard admin com KPIs, filtros, paginaÃ§Ã£o e exportaÃ§Ã£o (CSV/JSON). Feito pra demonstrar **UI + API escalÃ¡vel**.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> Os KPIs entram no roadmap abaixo.

---

## âœ… Roadmap (MVP do demo)
- [ ] CRUD: produtos
- [ ] CRUD: pedidos
- [ ] KPIs: receita, tickets, top produtos
- [ ] Filtros por data/categoria
- [ ] Export CSV
- [ ] UI com pÃ¡ginas e tabela

---

## â–¶ï¸ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d

