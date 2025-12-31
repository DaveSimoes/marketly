# marketly
Trusted sellers. Happy buyers.

# ⚠️ Projeto E‑commerce + Marketplace — WIP / Work In Progress

> Português (PT-BR) abaixo — English version following.

---

PT-BR — Aviso WIP
-----------------
Status: **WIP — Em desenvolvimento** 🚧

Este repositório contém trabalho em progresso. Mudanças frequentes, funcionalidades incompletas e quebra de APIs podem ocorrer. Use por sua conta e risco e, se for testar localmente, **não use chaves/credenciais de produção**.

O que é este projeto
- Plataforma de e‑commerce com funcionalidades de marketplace (vendedores múltiplos).
- Objetivo inicial: MVP com catálogo, autenticação, carrinho e checkout.

O que já funciona (exemplo)
- Estrutura inicial do monorepo (apps/web, apps/api, packages)
- Autenticação básica (email/senha) — ambiente de desenvolvimento
- Conexão local a banco de dev (ex.: Postgres em Docker)

Em desenvolvimento / Prioridades atuais
- Integração com provedor de pagamentos (checkout)
- Painel do vendedor (cadastro e gestão de produtos)
- Testes automatizados e melhoria do CI
- Documentação e exemplos de deploy

Como rodar (exemplo rápido)
1. Clone:
   git clone git@github.com:SEU_USUARIO/SEU_REPO.git
2. Copie variáveis de exemplo:
   cp .env.example .env
   # Edite .env — NÃO coloque chaves de produção
3. Suba serviços locais (ex.: Docker Compose):
   docker compose up -d
4. Instale dependências (ex.: pnpm):
   pnpm install
5. Rodar local:
   pnpm --filter web dev
   pnpm --filter api dev

Contribuindo (Resumo)
- Leia CONTRIBUTING.md antes de abrir PRs.
- Use branches `feature/*`, `fix/*`.
- Faça commits pequenos e claros (conventional commits recomendados).
- Abra issues usando os templates em .github/ISSUE_TEMPLATE.

Segurança / Vulnerabilidades
- Não publique vulnerabilidades como issue pública.
- Se encontrar um problema de segurança, leia SECURITY.md (ou contate o mantenedor) para instruções de reporte.

Licença
- Este repositório está sob [LICENSE] — adicione a licença desejada (ex.: MIT).

Contato
- Mantenedor: SEU_NOME (github.com/SEU_USUARIO)
- Caso queira contribuir, veja CONTRIBUTING.md

---

EN — WIP notice
---------------

Status: **WIP — Work In Progress** 🚧

This repository contains work in progress. Frequent changes, incomplete features, and breaking API changes may occur. Use at your own risk and, if testing locally, **do not use production keys/credentials**.

What this project is
- An e‑commerce platform with marketplace features (multiple sellers).
- Initial goal: MVP with catalog, authentication, cart, and checkout.

What already works (example)
- Initial monorepo structure (apps/web, apps/api, packages)
- Basic authentication (email/password) — development environment
- Local development DB connection (e.g., Postgres via Docker)

In progress / Current priorities
- Payment provider integration (checkout)
- Vendor dashboard (product CRUD and management)
- Automated tests and CI improvements
- Documentation and deployment examples

Quick start (example)
1. Clone:
   git clone git@github.com:YOUR_USER/YOUR_REPO.git
2. Copy example env:
   cp .env.example .env
   # Edit .env — DO NOT use production keys
3. Start local services (e.g., Docker Compose):
   docker compose up -d
4. Install deps (e.g., pnpm):
   pnpm install
5. Run locally:
   pnpm --filter web dev
   pnpm --filter api dev

Contributing (Summary)
- Read CONTRIBUTING.md before opening PRs.
- Use `feature/*`, `fix/*` branches.
- Make small, focused commits (conventional commits recommended).
- Use issue templates in .github/ISSUE_TEMPLATE.

Security / Vulnerability reports
- Do not post security issues publicly.
- Follow instructions in SECURITY.md (or contact maintainer) to report vulnerabilities.

License
- This repo uses [LICENSE] — add your chosen license (e.g., MIT).

Contact
- Maintainer: YOUR_NAME (github.com/YOUR_USER)
- See CONTRIBUTING.md if you want to contribute

---

Nota final / Final note
- Mantenha este README atualizado com o progresso do projeto. Quando o projeto atingir um estado estável, remova o rótulo WIP e expanda a documentação (ex.: exemplos, screenshots, API reference).
- Keep this README up to date as the project progresses. When stable, remove the WIP label and expand docs (e.g., examples, screenshots, API reference).
