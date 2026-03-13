# Source Map

This file maps the published public rules to the original local rule sources.

| Published topic | Primary source | Notes |
|---|---|---|
| Codex App displayed-equation boundary | `/Users/andyl/AGENTS.md` | Initial App rule source |
| Prose-math gate and overflow gate | `/Users/andyl/AGENTS.md` | Hard pre-send gate |
| Refined App math rules | `/Users/andyl/.codex/context/output-rule-summary.md` | Current canonical refined version |
| Inline-code boundary for App prose | `/Users/andyl/.codex/context/output-rule-summary.md` | Prevents inline-code math leakage |
| Source-quote Unicode cleanup for OCR-style symbols | `/Users/andyl/.codex/context/output-rule-summary.md` | Reading-friendly quote rendering in paper reading |
| CLI math override | `/Users/andyl/CLAUDE.md` | Environment-specific CLI override |
| CLI notation and layout examples | `/Users/andyl/.shared_ai_skills/math-formatting.md` | ASCII + Unicode combining chars |

## Publishing policy

- This repository republishes the math-output subset.
- When local rules conflict in wording, prefer the more recent refined math
  rule from `output-rule-summary.md` for Codex App.
- Keep the published set aligned with formula rendering, numbering, and layout.
