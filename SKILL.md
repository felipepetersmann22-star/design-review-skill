---
name: design-review
description: Review and improve a web or product interface using its actual content, rendered states and interaction evidence. Use for a UI design audit, anti-slop critique, visual refinement, or implementation and re-audit of an existing screen or flow.
---

# Design review and improvement

Make the product easier to understand and use while preserving its intended character. A polished screenshot is not proof of a complete flow. Work within the user's requested scope: an audit reports findings; an authorized improvement implements and validates them. Do not assume permission to publish or modify unrelated product areas.

## 1. Establish the job and evidence

- Identify the audience, their main task and success, the primary action, actual content and data, constraints, platform, existing design system, and the requested output. Read the current brief and product guidance before proposing a new direction. Preserve explicit decisions and rejected directions.
- Inspect the actual artifact. For a running UI, render it and capture relevant narrow, intermediate and wide views, plus important states. Note viewport, date, route or artifact, state and tool. Inspect the frames themselves for loading failures, overlays and missing assets. For a screenshot or design file, record its crop and limits. If the browser, source or requested state is unavailable, assess only what can be seen and mark the other claims unverified. Do not infer keyboard behavior, data persistence or hidden content from a still frame.
- Capture and share only material the user is authorized to expose. Use fictional or redacted content for public examples when appropriate, and keep private customer data, account details and screenshots out of public artifacts.
- Where a reference is useful, choose one with a comparable job and density; add another for a named problem. Separate what is **observed**, **documented**, **interpreted**, and **proposed**. Scope measurements to the source and state. A public screen does not prove private behavior; sampled styling is not an official design token. Do not claim unsupported functionality or copy a reference's identity.
- State a compact design contract in the project's existing location when useful: user job, hierarchy, distinctive visual direction, key type/color/spacing roles, interaction and data commitments, relevant responsive states, and acceptance checks. For small reviews, a short working note is enough.

## 2. Audit through complementary perspectives

Use [the review lenses](references/review-lenses.md) to examine the job and content, composition and visual identity, anti-slop, interaction and continuity, accessibility, and responsive behavior. Apply them to the same real task, not as abstract checklists. If independent reviewers are available and warranted, reconcile their findings; otherwise use distinct lenses yourself and do not claim independent review.

Each actionable finding names **location and state → observed evidence → user consequence → concrete correction**, with its relative priority and any uncertainty. Separate a defect from a taste preference. Highlight what already works and should be retained; assess a visual treatment by its role and execution rather than banning its style. Prioritize broken tasks, misleading data, inaccessible interactions and lost work before hierarchy, composition, type, spacing, surfaces and decorative polish. Assess impact in context rather than assigning severity mechanically.

For detailed examples and edge cases, read [examples](references/examples.md). For reference-driven work compare equivalent viewports, content and states; record intentional differences.

## 3. Improve and validate

If implementation is requested or authorized, address the largest consequential problems first, using suitable existing components and the product's real operations. Define the relevant interaction as trigger, feedback, commit, cancel or reverse, and recovery. Preserve drafts and useful context according to the product's actual data contract. Do not silently turn a static mockup into a claim of live functionality.

Render the changed result again, inspect the actual frames at affected sizes and states, and exercise the requested flow. Test keyboard focus and operation, errors and recovery, long content, reflow and reduced motion as relevant. Check navigation, ordinary reload, saving and persistence separately when they matter. Revisit each original finding and record the evidence for its resolution, remaining defect or unverified status. Repair meaningful regressions and rerun checks affected by further changes.

Use [the evidence and validation guide](references/validation.md) for practical checks and reporting. Mark applicable dimensions **pass**, **needs work**, or **unverified**, with evidence and limitations. A screenshot, automated accessibility check, simulated device or successful build each proves only its own bounded result. Do not claim assistive technology, physical-device, authenticated, backend or deployed verification without testing it.

## 4. Deliver

Give the user the most consequential findings or completed changes first, with the evidence, practical corrections, verification performed and remaining gaps. Include screenshots or paths when useful and available, subject to the project's privacy constraints. For audit-only work, present a prioritized implementation plan without implying changes were made. For an improvement, report the post-fix re-audit rather than repeating only the original critique.
