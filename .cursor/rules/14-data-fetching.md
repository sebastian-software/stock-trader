# Data Fetching

- Prefer **React-native mechanisms**: **Suspense**, route loaders/actions, and router-driven fetching where possible
- Use a data library when needed (e.g., SWR or TanStack Query) but favor router/Suspense first; adopt only if it provides clear value
- Ensure **type safety** for fetched data: use **TypeScript generics**, **schema validation (Zod / zod-mini)**, or `satisfies` to assert shapes
- Render **empty states** rather than skeleton placeholders; show real components with empty data; reserve loading indicators for long-latency or background actions
- Centralize fetch utilities (headers, base URL, retries, timeouts); avoid duplicating fetch logic in components
- Handle errors with boundaries and typed error shapes; prefer retry/backoff where safe
