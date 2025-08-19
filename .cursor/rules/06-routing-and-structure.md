# Routing & Project Structure

- Use the **Vite-enabled React Router** with **file-based routes**
- Keep routes as **glue code**; delegate to **features** which implement functionality
- Keep **feature folders** self-contained; avoid deep nesting; prefer a **flat** structure when fewer than 10 files
- Keep **one item per file**; do not mix components and hooks/utilities in the same file
- **Co-locate** Storybook stories and Vitest tests with their component
- Prefer **routing over manual state**; use routes for **tabs** and **dialogs**
- Implement **error boundaries** on **each route**
