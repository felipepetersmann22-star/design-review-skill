# Design Review

A general-purpose agent skill for reviewing and improving web and product interfaces. It combines content-first visual critique, practical interaction checks, anti-slop diagnosis and a scoped re-audit of the implemented result.

The method is grounded in a Design Language Atlas: start with the user's actual task and product identity, select relevant evidence, make deliberate visual decisions and verify the result. It does not require access to that private research collection. This repository contains a standalone synthesis rather than source captures or product-specific material.

## Use

Install the repository as a skill according to your agent's skill installation method. The repository root contains `SKILL.md` and its `references/` directory; keep them together. In Codex, for example, copy or clone the repository to `~/.codex/skills/design-review`, then restart or refresh skill discovery if needed. Review the files before installing any third-party skill.

Example requests:

- “Use the design-review skill to audit this dashboard. Give me prioritized findings with screenshots; do not change the code.”
- “Improve this checkout flow while keeping its visual identity, then test and re-audit the result at desktop and phone widths.”
- “Review this screenshot for hierarchy and generic design habits, and tell me what it cannot prove.”

## What to expect

The skill identifies the user's task and product context, reviews concrete evidence through several lenses, prioritizes actionable findings, and rechecks changes when implementation is in scope. It records what was observed, what remains an interpretation or proposal, and what was not tested. Distinctive design is encouraged; no particular visual style is automatically forbidden.

It cannot turn a screenshot into proof of behavior, a simulated device into a physical-device test, or an automated scan into a complete accessibility audit. Review quality depends on access to representative content, states, interaction tools and product context.

## Files

- `SKILL.md`: triggers and workflow.
- `references/review-lenses.md`: content, design, anti-slop, interaction, accessibility and responsive review.
- `references/validation.md`: evidence, re-audit and reporting.
- `references/examples.md`: fictional worked examples.

Licensed under the [MIT License](LICENSE).
