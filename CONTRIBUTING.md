# Contributing to Rootline

Rootline is a small Markdown protocol. Contributions should make future agent
work easier to route, verify, or maintain.

## Contribution Rules

- Keep `AGENTS.md` universal and copyable.
- Keep public explanation in `README.md`.
- Keep release notes in `CHANGELOG.md`.
- Do not commit internal reports or local analysis artifacts.
- Prefer concise, durable guidance over task history.
- Do not add runtime dependencies unless Rootline stops being Markdown-only.

## Change Checklist

- Read the relevant Rootline route before editing.
- Keep terminology consistent with the protocol primitives.
- Update `README.md` when public behavior or install guidance changes.
- Update `CHANGELOG.md` when release-facing behavior changes.
- Leave a Rootline receipt in the final response.

## Release Checklist

- Confirm the `LICENSE` file is present.
- Confirm the README version matches `CHANGELOG.md`.
- Confirm compatibility links still point to current tool documentation.
- Confirm no child `AGENTS.md` files exist without a `Route Map` entry.
