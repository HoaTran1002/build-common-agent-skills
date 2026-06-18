# Agent Instructions
# Project Stack

- Frontend: Next.js, React, Tailwind
- Backend: NestJS, Prisma, PostgreSQL
- Mobile: React Native
- CI/CD: GitHub Actions, Docker

Reusable workflows live in `.agents/skills`.

When doing frontend work, use `.agents/skills/frontend/change/SKILL.md`.
For React-specific work, also load `.agents/skills/frontend/references/react.md`.
For Next.js-specific work, also load `.agents/skills/frontend/references/nextjs.md`.

When doing backend work, use `.agents/skills/backend/change/SKILL.md`.
For NestJS-specific work, also load `.agents/skills/backend/references/nestjs.md`.
For Prisma-specific work, also load `.agents/skills/backend/references/prisma.md`.

## Shared skills

Reusable workflows live in `.agents/skills`.

Use these skills when relevant:

- `.agents/skills/quality/pr-review/SKILL.md`
  Use for reviewing pull requests, code diffs, or changed files.

- `.agents/skills/debug-failing-test/SKILL.md`
  Use when tests fail, CI fails, or logs need triage.

- `.agents/skills/quality/release-notes/SKILL.md`
  Use when drafting release notes or changelog entries.

## Rule

Before starting a repeated workflow, check whether a matching skill exists under `.agents/skills`.
Follow the skill's `SKILL.md` first, then load supporting files only when needed.
