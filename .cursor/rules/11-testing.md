# Testing

- Use **Vitest** for unit tests (hooks, utilities, logic)
- Use **Storybook `play()`** for interaction tests (e.g., opening a date picker)
- Avoid `data-testid`; prefer **semantic selectors** and **a11y-first queries**:
  - `getByRole`, `getByLabelText`, `getByText`, etc., mirroring assistive-tech navigation
- Add E2E tests with **Playwright** for critical flows
- Use **Faker.js** for test/demo data; persist fixtures where helpful; add as dev dependency
