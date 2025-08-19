# Security & Secrets

- Use environment variables via **`.env` files**; do not commit secrets. Add `*.env*` to `.gitignore`
- Load env at runtime/build using a vetted library; validate via **Zod** and fail fast on missing/invalid vars
- Store local development secrets in `.env.local`; keep `.env.example` up to date with keys and safe defaults
- Avoid leaking secrets in logs, stack traces, or error messages
