# Repository Instructions for Codex

## 1) Start With Context First
Before taking action, read context in this order:
1. `AGENTS.md`
2. `docs/product.md`
3. `docs/domain.md`
4. `docs/architecture.md`
5. `docs/constraints.md` and `docs/non-functional.md`
6. `docs/workflow.md` and `docs/scrum-rules.md`
7. Relevant backlog and template files under `docs/backlog/` and `docs/templates/`

If context is missing or stale, state assumptions clearly and propose doc updates.

## 2) What to Consult Before Acting
- For idea shaping: `docs/backlog/ideas.md`, `docs/templates/idea-template.md`
- For planning: `docs/backlog/epics.md`, `docs/backlog/user-stories.md`, `docs/backlog/release-plan.md`
- For implementation support: story + task + architecture + constraints
- For review support: acceptance criteria, non-functional requirements, PR template
- For docs support: `docs/documentation-rules.md`

## 3) Operating Modes

### Idea Shaping
- Clarify problem, user, value, and constraints.
- Convert raw idea into epic/story candidates.
- Flag uncertainty, dependencies, and risks.

### Planning
- Break epics into user stories and tasks.
- Keep slices vertical and testable.
- Highlight assumptions, ordering, and blockers.

### Implementation Support
- Prefer minimal, scoped changes tied to a single story/task.
- Avoid overengineering and speculative abstractions.
- Keep traceability to backlog IDs and acceptance criteria.

### Review Support
- Check correctness, scope alignment, risks, and test coverage impact.
- Surface regressions, missing edge cases, and unclear ownership.
- Provide actionable review feedback with suggested next steps.

### Documentation Support
- Update impacted docs after meaningful behavior/decision changes.
- Preserve human readability and concise structure.
- Keep examples generic unless explicitly project-specific.

## 4) Documentation Update Rule
Update docs when one of these changes:
- Product direction or priority
- Domain concepts/business rules
- Architecture/component boundaries
- Workflow or team operating rules
- Estimation/tracking conventions

At minimum, update the relevant file and add a short “Last Updated” note.

## 5) Human-Readable Output Rules
- Write for teammates first; tools second.
- Use clear headings, short sections, and checklists where helpful.
- Use explicit placeholders like `<project name>`, `<team rule>`, `<metric definition>`.
- Keep language practical and decision-oriented.

## 6) Avoid Overengineering
- Prefer the simplest solution that satisfies current acceptance criteria.
- Do not introduce unnecessary frameworks, abstractions, or process overhead.
- If proposing a bigger design, include a lightweight alternative.

## 7) Risk, Assumptions, and Missing Information
Always surface:
- Assumptions being made
- Known risks and impact
- Missing information that blocks confident decisions
- Suggested options with tradeoffs when non-obvious

## 8) Human Authority
- Humans own final decisions on scope, risk acceptance, architecture, and release.
- AI provides support, drafts, analysis, and implementation assistance.
- In conflicts between docs or unclear instructions, pause and ask for clarification.
