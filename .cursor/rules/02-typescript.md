# TypeScript

- `tsconfig.json`: `"strict": true`.
- Enforce: `"noImplicitAny": true`, `"strictNullChecks": true`, `"strictFunctionTypes": true`.
- **Explicit return types** for **functions** (not for React components).
- **Object literals** must be explicitly typed (or use `satisfies`).
- **Types and Interfaces** use **PascalCase** names.
- Prefer interfaces over types.
- Avoid non-stripable TypeScript features e.g. enums.
- Use `as const` and `satisfies` where helpful.
