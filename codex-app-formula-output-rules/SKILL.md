---
name: codex-app-formula-output-rules
description: "Formula output rules for Codex App. Use when a reply will contain mathematical expressions, derivations, proofs, or symbol-heavy explanations in Codex App and you need stable rules for displayed equations, prose-vs-equation boundaries, equation numbering, and overflow-safe math layout."
---

# Codex App Formula Output Rules

Use this skill when writing math-heavy answers in Codex App.

This skill only governs formula output. It does not replace broader teaching,
memory, or workflow skills.

Read `references/common-principles.md` first.

Read `references/codex-app-rules.md` when the reply will contain displayed
equations, equation references, or dense notation.

Read `references/source-map.md` when you need to trace the published rule back
to the original local rule source.

## Quick Start

Apply this skill when the answer includes any of:

- derivations
- proofs
- symbol-heavy explanations
- numbered displayed equations
- comparisons between prose notation and displayed notation

## Workflow

### 1. Choose the right boundary

- Keep dense math out of prose.
- Put LaTeX only in standalone displayed equations.
- Keep prose in plain language or short Unicode symbols when clarity allows.

### 2. Format the displayed equations

- Use two-level numbering.
- Put numbers on the right.
- Use one shared number for one tightly coupled definition block.

### 3. Run the prose-math gate

- No raw LaTeX syntax in prose.
- No dense inline symbols that require subscripts, superscripts, or brace
  groups.

### 4. Run the structure gate

- Split long displayed equations before they overflow.
- Prefer short aligned lines for multi-relation or matrix-heavy expressions.

## Scope Boundaries

- Do not import unrelated style rules into this skill.
- Do not use this skill as a substitute for general teaching policy.
- Keep the public rule set stable, minimal, and environment-specific.
