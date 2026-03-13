# AI Formula Output Rules

Portable formula-output rules for two environments:

- `Codex App`
- `Claude Code CLI`

This repository ships one installable `Codex App` skill and one copyable
`Claude Code CLI` rule excerpt. The public scope stays narrow: formula
rendering, prose-versus-equation boundaries, equation numbering, and
overflow-safe layout.

This repository is the rendering-rules half of the public stack. It pairs well
with a separate explanation skill such as
`codex-app-explain-skill`, which owns teaching-route selection.

## What Ships

- installable skill:
  [`codex-app-formula-output-rules`](./codex-app-formula-output-rules)
- copyable CLI file:
  [`claude-code-cli/CLAUDE.formula-rules.md`](./claude-code-cli/CLAUDE.formula-rules.md)
- supporting references for shared principles, `Codex App` math rules, and
  source tracing

## Install / Use

- `Codex App`: install the skill from this repo path
  `codex-app-formula-output-rules`
- `Claude Code CLI`: copy or merge
  `claude-code-cli/CLAUDE.formula-rules.md` into your local `CLAUDE.md`

## Coverage

- formula rendering rules
- prose-versus-equation rules
- equation numbering and layout rules
- reading-friendly Unicode cleanup for quoted OCR-style symbolic text
- long-reply divider guidance at clear structural transitions as a narrow
  rendering subset
- environment split between `Codex App` and `Claude Code CLI`
- language-agnostic math presentation rules with localized prose labels when
  needed

## Privacy Boundary

This public repository keeps the published rule set narrow and reusable.

- It excludes personal memory files, private workflow state, and local-only
  companion automation.
- It publishes no user-specific absolute paths inside the rule payloads.
- It keeps examples generic rather than tied to one course, institution, or
  identity.

## Companion Boundary

This repository is the rendering companion, not the teaching-route owner.

- It owns formula rendering, prose-versus-equation boundaries, numbering, and
  display-safe cleanup for quoted symbolic text.
- It does not own teaching-mode selection, prerequisite routing, or reading
  workflow orchestration.
- In sentence-by-sentence paper reading, the reading workflow and the decision
  to clean a quoted source belong to `codex-app-explain-skill`; this
  repository keeps the narrower symbol-cleanup subset for rendering
  consistency.
- In long explanations, this repository may publish the narrower divider-layout
  subset for major transitions, but it does not own the workflow decision for
  when a transition exists.

## Repository Layout

- `codex-app-formula-output-rules/`: installable `Codex App` skill
- `codex-app-formula-output-rules/references/`: published reference subset
- `claude-code-cli/`: minimal CLI excerpt for local `CLAUDE.md`

Chinese:

- [README.zh-CN.md](./README.zh-CN.md)
