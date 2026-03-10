# Claude Code CLI Formula Rules

This file is a minimal copyable excerpt for `Claude Code CLI`.

Merge it into your local `CLAUDE.md` as the formula-rules section.

## Formula Rendering

- Do not use `$$...$$` or `$...$` LaTeX blocks.
- This is a CLI environment. Raw LaTeX does not render well.
- Use ASCII math for ordinary expressions such as `x^2`, `lambda_i`,
  `A = U*T*U^T`, and `||x||`.
- For conjugate transpose, write `U*`, not `U^*`.

## Unicode Combining Characters

- Decorated variables may use Unicode combining characters:
  - hat: `x̂`
  - bar: `x̄`
  - dot: `ẋ`
  - double dot: `ẍ`
  - tilde: `x̃`

## CLI-Friendly Notation

- Vectors: `ω⃗`, `v⃗`, `F⃗`
- Unit vectors: `n̂`, `x̂`, `ŷ`, `ẑ`
- Time derivatives: `ω̇⃗`, `q̇`, `ẋ`
- Second derivatives: `q̈`, `ẍ`
- Measured values: `ω̃⃗`
- Estimated values: `ω⃗_est`

## Operators

- Norm: `‖v⃗‖`
- Dot product: `a⃗ · b⃗`
- Subscript: `ω⃗_b`, `R_12`
- Superscript: `R^T`
- PID gains: `Kp`, `Kd`, `Ki`

## Layout

- Spread formulas vertically when that improves readability.
- Break complex expressions into multiple lines.
- Use ASCII tables for variable definitions when helpful.
- Use simple ASCII layouts for vectors and matrices:

```text
v = [ 1 ]
    [ 0 ]
    [ 0 ]

M = [ a  b ]
    [ c  d ]
```
