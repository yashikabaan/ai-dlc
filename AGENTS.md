# AI-DLC Operating Guide

## Purpose
This repository is a reusable AI-DLC template for small-team software delivery where humans and AI collaborate.

## Project Summary (Fill In)
- Project Name: `<project name>`
- Product Scope: `<short scope statement>`
- Business Goal: `<business goal>`
- Primary Users: `<target users>`
- Delivery Horizon: `<time horizon>`

## Core Working Rules
- Humans remain decision makers for scope, architecture, release, and risk acceptance.
- AI assists with analysis, drafting, implementation support, review support, and documentation upkeep.
- Git and GitHub are the control and traceability layer for all meaningful changes.
- Keep changes minimal, focused, and traceable to backlog artifacts.
- Prefer reusable, human-readable documentation over tool-specific outputs.

## Human Roles
- Product Owner (PO): prioritization and acceptance decisions.
- Designer: UX and interaction decisions.
- Engineers (Frontend/Backend): implementation and technical quality.
- Senior/Lead Engineer: architecture and technical risk decisions.
- Scrum/Coordinator: cadence, blockers, and flow coordination.

## AI Roles
- Product AI
- Planning AI
- Meeting AI
- Code Understanding AI
- Implementation AI
- Review AI
- Documentation AI
- Workflow AI

See `docs/ai-roles.md` for role boundaries and expected outputs.

## Standard Workflow
1. Idea intake (`docs/backlog/ideas.md` + `docs/templates/idea-template.md`)
2. Backlog shaping (`docs/backlog/epics.md`, `docs/backlog/user-stories.md`)
3. Readiness check (acceptance criteria, dependencies, risks)
4. Implementation (small branch, small PR, linked story/task)
5. Verification (tests/checks + review)
6. Merge and update documentation/context
7. Learning capture (weekly summary + retrospective inputs)

## Documentation Sources of Truth
- Product context: `docs/product.md`
- Domain context: `docs/domain.md`
- Technical direction: `docs/architecture.md`
- Constraints: `docs/constraints.md`
- Non-functional requirements: `docs/non-functional.md`
- Workflow rules: `docs/workflow.md`, `docs/scrum-rules.md`
- Tracking artifacts: `docs/backlog/*`

## Git / Branch / Commit / PR Rules
- Branch naming: `<type>/<ticket-or-topic>` (example: `feature/US-012-login-flow`)
- Commit style: concise and scoped (example: `feat(US-012): add login form validation`)
- One PR should map to one coherent change set.
- PR must reference related epic/story/task IDs.
- PR description should use `docs/templates/pr-template.md`.

## Review Rules
- Review for correctness, risk, readability, test impact, and rollback safety.
- Request changes when acceptance criteria are not met.
- Keep comments actionable and linked to requirement context.
- Human reviewer gives final approval for merge.

## AI Behavior Rules
- Read context files before proposing or implementing changes.
- Ask when requirements are unclear or conflicting.
- Make minimal diffs; avoid unrelated edits.
- Keep docs updated after meaningful decisions or behavior changes.
- Surface assumptions, risks, and missing information explicitly.
- Produce outputs that are human-readable first, AI-readable second.
