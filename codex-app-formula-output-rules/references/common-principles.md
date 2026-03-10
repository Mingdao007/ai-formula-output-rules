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

## 5. Published rule set

- Formula rendering rules
- Environment-specific math formatting rules
- Prose-versus-equation boundary rules
- Equation numbering and layout rules

## 6. Language transfer

- The published examples come from a Chinese-first workflow.
- The formula rules themselves are mostly language-neutral.
- To transfer the rule set to English, keep the same displayed-equation
  boundary, numbering, and overflow rules, and localize only the prose layer.
- In particular, change equation-reference wording from forms such as
  `式 (1.3)` to forms such as `Eq. (1.3)` when writing in English.
