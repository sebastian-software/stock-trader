# CI/CD

- Keep workflows minimal; prefer invoking **npm scripts** (pnpm run ...) for typecheck, lint, test, build, storybook
- Cache pnpm store; pin Node and pnpm via `package.json` and enforce with setup steps
- Include basic jobs: typecheck, lint, unit tests, Storybook build; add e2e on main/critical PRs
- Integrate **CSpell** for spell checks in Markdown and docs
