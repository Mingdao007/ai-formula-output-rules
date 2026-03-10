# Common Principles

These principles are shared by the public rule set for both environments in
this repository.

## 1. Readability first

- Formula output should be readable before it is elegant.
- Choose the rendering style that survives the target environment cleanly.

## 2. Separate the environments explicitly

- Codex App and Claude Code CLI do not share the same math renderer.
- Do not force one environment's rendering strategy onto the other.

## 3. Keep dense math out of prose

- If a symbol needs heavy subscripts, superscripts, brace groups, or operator
  names, do not leave it inline in prose.
- Move the exact expression into a displayed equation or a CLI-safe block.

## 4. Keep notation consistent

- Within one expression, use one notation style.
- Within one indexed family, keep indexing style consistent from start to
  finish.

## 5. Publish only the math rules

- This repository excludes general teaching structure, memory rules, page
  reference rules, agent workflow rules, and personal style preferences that do
  not directly affect formula output.
