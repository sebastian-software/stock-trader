# Routing & Project Structure

- Use the **Vite-enabled React Router** mode with **file-based routes**.
- **Routes are glue code** only; they delegate to **features** which implement functionality.
- **Feature folders** are **self-contained**. Avoid deep nesting. Prefer a **flat** structure when there are fewer than 10 files.
- Keep **one item per file**. Do **not** mix components and hooks/utils in the same file.
- **Co-locate** Storybook stories and Vitest tests in the **same folder** as the component.
- Prefer **routing over manual state**; use routes for **tabs** and **dialogs** as well.
- Implement **error boundaries** on **each route**.
