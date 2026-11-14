# Evidence and validation

## Match the test to the claim

| Claim | Suitable evidence | Limit |
| --- | --- | --- |
| Visible hierarchy and wrapping | Inspected screenshot of the named artifact, viewport and state | Does not prove interaction or offscreen states. |
| A control responds and recovers | Exercise pointer and keyboard paths, error and retry in the actual flow | A fixture or mocked response does not prove the production backend. |
| Changes survive navigation or reload | Perform each relevant operation and check the actual value | Local state is not proof of a server save. |
| Accessibility | Inspect semantics and keyboard behavior; run useful automated checks and, where possible, use the relevant assistive technology | Automated tools do not establish comprehensive accessibility. |
| Responsive and motion behavior | Inspect relevant widths, long content, enlargement and reduced-motion settings | Emulation does not prove native zoom, physical touch, haptics or software keyboard behavior. |
| Reference fidelity | Compare equivalent states at equivalent sizes; record deliberate departures | An image diff or sampled CSS cannot establish complete behavior or official tokens. |
| Release or deployment | Inspect the actual authorized destination and exercise the relevant flow | A local build, screenshot or staging test is not production verification. |

## Review and re-audit

1. Capture or inspect the initial state. Note artifact, route, date, viewport, state, source and limits. Avoid retaining private material in a public report.
2. For each major issue record location, observation, user consequence and correction. Distinguish observed evidence from interpretation and proposed changes.
3. If fixing, implement the agreed scope. Render again, inspect the changed state and its neighbors, and compare like with like. Recheck affected interactions and responsive states after changes. Iterate on material issues.
4. For each applicable dimension, record **pass**, **needs work**, or **unverified**, with a short observation: purpose and content; hierarchy and precision; behavior and recovery; continuity; accessibility; responsive layout; and evidence. A pass is scoped to what was actually checked. Do not turn untested dimensions into passes or average them into an overall score.
5. Report the remaining issues and test limits. Do not claim an independent review unless one occurred. Avoid prescribing deployment or new external actions unless requested and authorized.
