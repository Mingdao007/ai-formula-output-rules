# AI Formula Output Rules

Portable formula-output rules for two environments:

- `Codex App`
- `Claude Code CLI`

This repository ships one installable `Codex App` skill and one copyable
`Claude Code CLI` rule excerpt. The public scope stays narrow: formula
rendering, prose-versus-equation boundaries, equation numbering, and
overflow-safe layout.

## What ships

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
- environment split between `Codex App` and `Claude Code CLI`
- language-agnostic math presentation rules with localized prose labels when
  needed

## Repository layout

- `codex-app-formula-output-rules/`: installable `Codex App` skill
- `codex-app-formula-output-rules/references/`: published reference subset
- `claude-code-cli/`: minimal CLI excerpt for local `CLAUDE.md`

Chinese:

- [README.zh-CN.md](./README.zh-CN.md)
