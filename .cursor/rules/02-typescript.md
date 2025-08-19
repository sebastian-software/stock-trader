# TypeScript

- Enable `"strict": true` in `tsconfig.json`
- Enforce `"noImplicitAny": true`, `"strictNullChecks": true`, `"strictFunctionTypes": true`
- Define **explicit return types** for functions (not required for React components)
- Provide **explicit types** for object literals or use `satisfies`
- Use **PascalCase** for types and interfaces
- Prefer **interfaces** over `type`
- Avoid non-stripable features (e.g., enums); use `as const` objects instead
- Use `as const` and `satisfies` to narrow and validate types
