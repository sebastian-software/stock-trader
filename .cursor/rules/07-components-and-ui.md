# Components & UI

- Use **Web Components from https://webawesome.com/** for **core components**.
- Prefer these over plain web-native elements when they provide better styling or integration capabilities.
- **Wrap all customized Web Components** in **React wrappers** (typed props, event mapping, controlled/uncontrolled behavior).
- Write **presentational/pure** components: No App Context dependencies and only use **app-free hooks** (no global state, no app logic/data).
- Provide **Storybook stories** for **all** presentational/pure components.
- Use design tokens with Vanilla Extract to keep specific theme-styles out of implementation.
