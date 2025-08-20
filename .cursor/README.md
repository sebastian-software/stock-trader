# Cursor Rules Conventions

This directory defines project rules that Cursor uses to guide edits, refactors, and answers. Files in `.cursor/rules/*.mdc` are loaded as a combined ruleset for style, architecture, and tooling.

## Layout

- Location: `.cursor/rules/`
- Entry point: `00-index.mdc` defines topic order (precedence)
- Topics: one file per topic (e.g., `05-react.mdc`, `14-data-fetching.mdc`)

## Authoring Rules (.mdc format)

- Use a single `# Heading` followed by imperative bullets only
- Start each bullet with a verb: Use/Prefer/Avoid/Ensure/Keep/Provide/Implement
- Keep bullets short, specific, and prescriptive
- Allow nested bullets for clarifications; avoid paragraphs and numbered lists
- Use inline code for filenames, flags, and APIs; keep links concise
- Avoid large code blocks; prefer linking or naming exact APIs instead

Example pattern:

# Topic Name

- Use <concise rule>
- Prefer <alternative> over <baseline> when <condition>
  - Provide <clarification> when needed

## Precedence and Conflicts

- Follow the order in `00-index.mdc` when rules conflict
- Keep rules consistent with higher-precedence topics; refine, do not contradict

## Adding or Editing Rules

- Add a new topic file using `NN-topic-name.mdc` where `NN` sets precedence
- Add the topic to `00-index.mdc` under "Topics (order of precedence)"
- Write bullets in imperative style; avoid prose
- Keep scope tight; split large topics instead of creating long files

## How Cursor Uses These Files

- Cursor reads `.mdc` files under `.cursor/rules/` and applies them as a combined ruleset
- The ruleset influences code style, structure, naming, testing, and tool choices during assistance
- Keep the set stable and predictable; noisy changes may cause inconsistent guidance

## Review Checklist (quick)

- Heading + imperative bullets only
- Verbs at start of bullets are consistent
- No paragraphs or numbered lists
- Topic added to `00-index.mdc` and order is correct
- Links and filenames use inline code formatting
