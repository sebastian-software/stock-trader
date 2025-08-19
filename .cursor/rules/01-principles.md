# Principles

- **Prefer simple over clever.**
- **Prefer performance over code compactness.** During initial development: **simplicity over performance**.
- **Functional & declarative**; avoid **classes**.
- Prefer **presentational/pure** components (aka “dumb” components). Keep app-agnostic layouts where possible.
- **Descriptive names** with auxiliary verbs (`isLoading`, `hasError`, `canSubmit`).
- Avoid **inline render helpers**; extract into real components. Keep render closures lean (few variables).
- Prefer **named exports** over default exports.
- Avoid implicit global state.
- Avoid hidden I/O or side-effects.
