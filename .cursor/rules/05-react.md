# React

- Use the **latest React** and **React Router** for application development.
- Use the **React Compiler** and **omit manual memoization** where the compiler already optimizes. Use `useMemo`/`useCallback` only for measured wins (expensive calcs, stable refs).
- Prefer **presentational/pure** components; move app-specific logic into dedicated hooks or higher-level containers.
- Consistent Suspense-based data fetching pattern.
