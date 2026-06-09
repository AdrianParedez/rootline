# Rootline Protocol

## Operating Contract

Rootline is a lightweight `AGENTS.md` protocol for route-aware agent work.

The agent must do four things:

1. Trace the instruction route before editing.
2. Work from the nearest applicable local guidance.
3. Control documentation drift when durable project facts change.
4. Leave a receipt that states what was read, changed, and verified.

Rootline is plain Markdown. It is not a runtime, package, validator, or hidden
state system. Keep public-facing project explanation in `README.md`.

## Route Brief

- Scope: this root file governs the whole project until child Rootline docs exist.
- Route: root `AGENTS.md` -> child `AGENTS.md` files on the path to the work.
- Local anchor: the nearest applicable Rootline doc, composed with every parent
  above it.
- Drift trigger: durable changes to structure, commands, ownership, workflows,
  constraints, quality bars, or agent-facing preferences.
- Receipt: every closeout must state the route read, docs updated, checks run,
  and known gaps.

## Route Protocol

- Identify the files or directories the task will touch.
- Read this root `AGENTS.md` first.
- For each target path, read every child `AGENTS.md` on the path from the project
  root to that target.
- Treat the `Route Map` as a guide, not proof. If it may be stale, verify the
  filesystem.
- If target paths use different child docs, apply the right route to each path.
- If route instructions conflict, follow the stricter applicable instruction and
  report the conflict in the receipt.
- If the route is missing or unclear in a way that changes the work, ask one
  precise question before editing.

## Local Anchors

- Root docs define project-wide rules, route policy, and the route map.
- Child docs define local rules for their directory tree.
- The nearest applicable Rootline doc owns local guidance for its scope.
- Local docs may refine parent guidance for their scope.
- Local docs must not weaken root safety rules or claim ownership outside their
  scope.
- Broad guidance belongs high in the tree. Concrete commands, files, and local
  gotchas belong near the work.

## Drift Control

- Update Rootline docs when a change creates, removes, or changes durable agent
  guidance.
- Prefer the nearest applicable local anchor. Update parent docs only when the
  broader route, map, or rule changes.
- Do not update Rootline docs for cosmetic edits, temporary notes, or one-off task
  history.
- Remove stale guidance instead of explaining that it is stale.
- Keep Rootline updates in the same change as the work that made them necessary.

## Receipt Protocol

Use this receipt shape when reporting completed work:

```text
Rootline receipt:
- Route read: <root doc and any child docs>
- Docs updated: <yes/no, paths>
- Checks run: <commands or inspection performed>
- Gaps: <checks not run, stale map entries, conflicts, or missing local docs>
```

Do not claim completion until the receipt is accurate.

## Writing Standard

- Write plain Markdown with stable headings and short bullets.
- Prefer exact paths, commands, and file names over broad advice.
- Prefer positive instructions with clear alternatives over bare prohibitions.
- Avoid pseudocode unless the repository contains the executable implementation.
- Avoid duplicated parent guidance, hype, filler, and task history.
- Do not invent user preferences in the starter contract.
- Keep examples brief and only where they prevent likely mistakes.

## Local Rootline Pattern

Create child `AGENTS.md` files only where a subtree has durable local guidance.

Use this shape:

- `# <Area> Rootline`
- `## Route Brief`
- `## Local Anchors`
- `## Commands`
- `## Verification`
- `## Receipt Protocol`
- `## Operator Profile`
- `## Route Map`

Omit sections that do not apply. Keep child docs short, concrete, and scoped to
the subtree they govern.

## Operator Profile

- No operator preferences are defined yet.
- After installing Rootline in a project, update this section with durable
  operator, team, or project preferences that affect agent behavior.
- Keep preferences scoped, stable, and non-conflicting with the operating
  contract.
- Do not record transient chat preferences or task-specific notes here.

## Route Map

- No child Rootline docs are defined yet.
