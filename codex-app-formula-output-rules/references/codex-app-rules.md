# Codex App Rules

## Rendering Boundary

- Only standalone displayed equations may use LaTeX.
- Prose, titles, bullets, table cells, recap lines, and other inline text
  should use plain language or short Unicode symbols instead.
- If an expression is formal enough to require LaTeX, move it into a displayed
  equation block.
- In prose, isolated symbol names may appear when necessary, but
  relation-bearing expressions may not.
- If a phrase would read as a formula rather than a name, move it into the next
  displayed equation block.

## Prose-Math Gate

- Do not leave raw LaTeX control words in prose.
- Do not leave LaTeX-style math syntax in prose, including backslashes,
  underscores, carets, or brace-group notation.
- If a symbol would require dense notation to render clearly, replace it in
  prose with a plain-language noun and keep the exact symbol in a nearby
  displayed equation.
- Keep inline symbols short and readable when they remain in prose, for
  example `ẋ`, `θ₀`, `ψ₀`, `φ`, `θ`, `ψ`.
- Do not leave inline equalities or other formula-shaped snippets in prose,
  even when the notation is visually simple.
- Sentences may introduce the role of the next formula in plain language, but
  the actual mathematical relation should appear only in the displayed equation
  block that follows.
- Keep recap lines, bullets, and other sentence-level summaries formula-free.
- If a recap needs an exact relation, place that relation in its own displayed
  equation block and keep the surrounding prose natural-language only.

## Inline Code Boundary

- Use inline code only for short atomic identifiers such as command names,
  environment variables, filenames, model names, API names, or one bare code
  symbol.
- Keep paper titles, method names, and ordinary technical terms in normal
  prose.
- Do not use inline code as a workaround for math rendering inside prose.
- If the content is mathematical enough to need special rendering, move it into
  the next displayed equation block instead.

## Default State-Space Naming

- For state-space definitions, use `x` as the default state variable name.
- Change the state symbol only when the user explicitly requests another
  notation or when the cited source fixes a different symbol.

## Equation Numbering

- Standalone equations use two-level numbering.
- The first number cycles in the `1`-`9` range across replies within the same
  topic.
- The second number is the local sequence within the current reply.
- When moving to the next numbered reply, advance the first number and restart
  the second number at `1`.
- Put equation numbers on the right, not on the left.
- In prose, refer to equation numbers as plain text.
- Use the local prose language for equation references, for example
  `式 (1.3)`, `Eq. (1.3)`, or `(1.3)`.
- When multiple displayed equations form one tightly coupled definition block,
  prefer one shared number.

## Structure Gate

- Do not wait for visible overflow. Split displayed equations proactively.
- If one displayed line has two or more relation symbols such as `=`,
  `\approx`, `\Longrightarrow`, `\to`, or `\iff`, split it into aligned lines.
- If one displayed line forms a long implication or transformation chain with
  four or more semantic blocks, split it into multiple aligned lines.
- If one displayed line contains a matrix or column vector plus extra operators
  or terms on both sides, break around the matrix or move it to its own line.
- If a displayed line reads like a sentence with symbols instead of one compact
  formula, split it before sending.

## Minimal Use Rule

- This public rule set is intentionally narrow.
- It governs formula rendering, numbering, and layout only.
- It is designed for math presentation in Codex App replies.
