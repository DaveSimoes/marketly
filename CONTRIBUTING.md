# CONTRIBUTING — Como contribuir / How to contribute

> PT‑BR abaixo — English version following.

---

PT-BR — Como contribuir (resumo)
--------------------------------
Obrigado por querer contribuir! Abaixo estão as diretrizes principais para colaborar de forma eficaz e organizada com este projeto WIP.

Antes de começar
- Leia o README.md (WIP) para entender o estado atual do projeto e o roadmap.
- Procure por issues abertas e por marcadores como `good first issue` ou `help wanted`.
- Se for uma mudança significativa, abra uma issue para discutir a proposta antes de desenvolver.

Branching / Fluxo de trabalho
- Base: crie suas branches a partir de `main`.
- Convenção de nomes:
  - feature/nome-curto (para novas funcionalidades)
  - fix/nome-curto (para correções)
  - chore/nome-curto (para tarefas de manutenção)
  - docs/nome-curto (para documentação)
- Mantenha branches pequenas e focadas.

Commits
- Use Conventional Commits para mensagens claras:
  - feat: adiciona endpoint de produtos
  - fix: corrige validação do checkout
  - chore: atualiza dependências
  - docs: atualiza README
- Mensagens devem ser curtas no título e detalhadas no corpo quando necessário.

Pull Requests (PR)
- Abra PRs contra `main`.
- No título e descrição do PR inclua:
  - Resumo do que foi alterado
  - Como testar localmente (passos)
  - Issues relacionadas (use `Closes #n` para fechar automaticamente)
- Checklist sugerido no PR:
  - [ ] Código segue as guidelines
  - [ ] Lint passou
  - [ ] Testes passaram / novos testes adicionados (se aplicável)
  - [ ] Documentação atualizada (se aplicável)

Revisão e merge
- Um ou mais revisores farão feedback. Responda aos comentários e atualize o PR.
- Recomendamos Squash and merge para manter o histórico limpo, a menos que o PR contenha commits com significado histórico.
- Não force‑push em branches compartilhadas sem coordenação.

Estilo de código e linters
- Siga as regras do projeto (ESLint / Prettier para JS/TS). Rode:
  - npm run lint
  - npm run format (se existir)
- Configure seu editor para aplicar formatação automática quando possível.

Testes
- Adicione testes para funcionalidades novas e correções críticas.
- Rode a suíte de testes localmente antes de abrir o PR:
  - npm test
- CI rodará testes e linter automaticamente (exija CI verde para merge).

Documentação
- Atualize README.md, docs/ ou exemplos sempre que sua mudança afetar o uso do projeto.
- Para alterações relevantes no comportamento público: adicione exemplos de uso e/ou snippets.

Segurança / Vulnerabilidades
- Não reporte vulnerabilidades publicamente. Siga as instruções em SECURITY.md.
- Se encontrar credenciais/segredos em commits, avise imediatamente os mantenedores e NÃO reponha esses dados em commits públicos.

Reescrever histórico / remoção de segredos
- Evite reescrever histórico em branches públicas. Se for necessário (ex.: remover segredo), coordene com os mantenedores. Reescrever histórico exige force push e re-clone por outros colaboradores.

Gerenciamento de dependências
- Atualize dependências com cuidado. Prefira PRs pequenos para atualizações de pacote e verifique breaking changes.
- Use ferramenta de dependabot/renovate quando disponível.

Templates e issues
- Use os templates de issue e PR fornecidos em .github/ para facilitar triagem.
- Ao abrir uma issue, forneça logs, passos para reproduzir e ambiente.

Comunicação e conduta
- Seja cordial e objetivo nas discussões.
- Siga o CODE_OF_CONDUCT (se existir). Respeite revisões e decisões dos mantenedores.

Traduções
- Se for traduzir docs, coloque arquivos em README.pt.md / README.en.md ou em docs/lang/.
- Mantenha traduções sincronizadas com o conteúdo principal.

Contato / Agradecimento
- Obrigado por contribuir! Adicione seu nome nos agradecimentos se desejar.
- Maintainer / Contato: YOUR_NAME (github.com/YOUR_USER)

---

EN — How to contribute (summary)
--------------------------------
Thanks for wanting to contribute! Below are the main guidelines to collaborate effectively with this WIP project.

Before you start
- Read README.md (WIP) to understand the current project state and roadmap.
- Look for open issues and labels like `good first issue` or `help wanted`.
- For substantial changes, open an issue to discuss the proposal before implementing.

Branching / Workflow
- Branch off from `main`.
- Naming convention:
  - feature/short-name (new features)
  - fix/short-name (bug fixes)
  - chore/short-name (maintenance)
  - docs/short-name (documentation)
- Keep branches small and focused.

Commits
- Use Conventional Commits:
  - feat: add product endpoint
  - fix: correct checkout validation
  - chore: update dependencies
  - docs: update README
- Keep the title concise and add a detailed body when needed.

Pull Requests (PR)
- Open PRs against `main`.
- Include in PR title/description:
  - Summary of changes
  - How to test locally (steps)
  - Related issues (use `Closes #n` to auto-close)
- Suggested PR checklist:
  - [ ] Code follows guidelines
  - [ ] Lint passed
  - [ ] Tests passed / new tests added (if applicable)
  - [ ] Documentation updated (if applicable)

Review and merge
- One or more reviewers will provide feedback. Address comments and update the PR.
- Prefer "Squash and merge" to keep history clean, unless commits are intentionally meaningful.
- Avoid force‑pushing to shared branches without coordination.

Code style & linters
- Follow the repo rules (ESLint / Prettier for JS/TS). Run:
  - npm run lint
  - npm run format (if available)
- Configure your editor to auto-format when possible.

Tests
- Add tests for new features and critical fixes.
- Run tests locally before opening the PR:
  - npm test
- CI will run tests and linter automatically (CI green is required for merge).

Documentation
- Update README.md, docs/, or examples when your change affects usage.
- For public behavior changes, add usage examples and/or code snippets.

Security / Vulnerability reporting
- Do not disclose vulnerabilities publicly. Follow SECURITY.md for reporting.
- If you find credentials/secrets in commits, notify maintainers immediately and DO NOT re-add those secrets in public commits.

History rewrite / secret removal
- Avoid rewriting history on public branches. If necessary (e.g., to remove secrets), coordinate with maintainers. History rewrite requires force push and collaborators to re-clone.

Dependency management
- Update dependencies carefully. Prefer small PRs for package updates and check for breaking changes.
- Use Dependabot / Renovate if available.

Templates & issues
- Use the .github issue/PR templates to help triage.
- When opening an issue, provide logs, reproduction steps, and environment details.

Communication & conduct
- Be polite and constructive in discussions.
- Follow the CODE_OF_CONDUCT (if present). Respect maintainers' decisions.

Translations
- For translated docs, place files like README.pt.md / README.en.md or under docs/lang/.
- Keep translations synchronized with the main content.

Contact / Thanks
- Thanks for contributing! Feel free to add your name in acknowledgments.
- Maintainer / Contact: YOUR_NAME (github.com/YOUR_USER)

---
