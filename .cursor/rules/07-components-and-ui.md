# Components & UI

- Use **Web Components** from `https://webawesome.com/` for core components
- Prefer these over plain native elements when they provide better styling or integration
- Wrap customized Web Components in **React wrappers** (typed props, event mapping, controlled/uncontrolled behavior)
- Write **presentational/pure** components: no App Context dependencies; use only app-free hooks (no global state, no app logic/data)
- Provide **Storybook stories** for all presentational/pure components (each pure component must have a Story)
- Use **design tokens** with **Vanilla Extract** to keep theme styles out of implementation
