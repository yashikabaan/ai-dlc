# AI-DLC Workflow

Last Updated: `<YYYY-MM-DD>`

## End-to-End Flow
1. Idea Intake
2. Backlog Shaping
3. Readiness Check
4. Implementation
5. Test and Verification
6. Review and PR
7. Learning Capture

## 1) Idea Intake
- Capture idea in `docs/backlog/ideas.md` using `docs/templates/idea-template.md`.
- Identify user value, problem, urgency, and unknowns.
- Decide: discard, park, or shape.

## 2) Backlog Shaping
- Convert qualified ideas into epics and user stories.
- Define acceptance criteria and dependencies.
- Record risks in `docs/backlog/risk-register.md`.

## 3) Readiness Check
- Story is clear, testable, and scoped for sprint execution.
- Dependencies are visible and owners identified.
- Required design/architecture decisions are documented.

## 4) Implementation
- Start from a linked story/task.
- Keep branch and commits focused.
- Update docs if behavior or decisions change.

## 5) Test and Verification
- Validate acceptance criteria.
- Run required checks.
- Document test evidence in PR summary.

## 6) Review and PR
- Open PR using `docs/templates/pr-template.md`.
- Review for correctness, risk, readability, and NFR impact.
- Human reviewer makes final merge decision.

## 7) Learning Capture
- Add daily and weekly updates.
- Capture defects, delays, and process improvements.
- Feed lessons into backlog/refinement.

## Collaborative and Solo Modes
- Collaborative mode: pair/mob on high-risk or high-ambiguity work.
- Solo mode: execute clear, low-risk tasks independently.
- Both modes must keep shared artifacts current.
