# Errors & Notifications

- Use **toasts** for successful transactions and ephemeral confirmations
- Use **dialogs** for failures with **retry** capability and clear remediation actions
- Implement **consistent UI patterns** for errors: inline field errors for validation, section alerts for recoverable issues, route-level boundaries for fatal errors
- Prefer **empty-first rendering**; add spinners only when background actions exceed acceptable latency
