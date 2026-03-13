# Source Map

This file maps the published public rules to the original local rule sources.

| Published topic | Primary source | Notes |
|---|---|---|
| Codex App displayed-equation boundary | Private Codex App instruction set | Initial app-level rendering source |
| Prose-math gate and overflow gate | Private Codex App rendering summary | Current canonical refined version |
| Inline-code boundary for app prose | Private Codex App rendering summary | Prevents inline-code math leakage |
| Source-quote Unicode cleanup for OCR-style symbols | Private Codex App rendering summary | Reading-friendly quote rendering subset |
| Long-reply divider layout subset | Private Codex App rendering summary | Companion-only readability subset |
| CLI math override | Private CLI companion config | Environment-specific CLI surface |
| CLI notation and layout examples | Private CLI math fallback appendix | ASCII plus Unicode combining-char examples |

## Publishing policy

- This repository republishes the math-output subset.
- When local rules conflict in wording, prefer the more recent refined app
  rendering rule for Codex App.
- Keep the published set aligned with formula rendering, numbering, and layout.
- Do not publish private absolute paths, private file names, or private owner
  chain details in this public source map.
