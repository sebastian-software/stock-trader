# Testing

- Use **Vitest** for unit tests (hooks, utilities, logic).
- Use **Storybook `play()`** for **interaction tests** (e.g., opening a date picker).
- **Avoid `data-testid`**. Prefer **semantic selectors** and **a11y-first queries**:
  - `getByRole`, `getByLabelText`, `getByText`, etc., mirroring how users with assistive tech navigate.
- Add E2E tests with Playwright for critical flows.
