# Accessibility

- Use **semantic HTML** elements
- Apply **ARIA roles** correctly
- Use `aria-label` and `aria-labelledby` for textless elements
- Maintain a correct **heading structure** (e.g., dialog titles are headings)
- Ensure **full keyboard navigation**: focus order, avoid focus traps, visible focus, ESC/Enter handling for dialogs
- Announce route changes via **live regions**
- Ensure color contrast meets **WCAG 2.1 AA**; prefer semantic tokens to maintain contrast. Where feasible, add automated checks (e.g., axe) in tests or Storybook
- Use **APCA** (or comparable) contrast checks aligned with **WCAG 3** guidance for forward-compatible contrast evaluation
