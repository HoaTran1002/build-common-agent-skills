# Agent Instructions

## Shared skills

Reusable workflows live in `.agents/skills`.

Use these skills when relevant:

- `.agents/skills/pr-review/SKILL.md`
  Use for reviewing pull requests, code diffs, or changed files.

- `.agents/skills/debug-failing-test/SKILL.md`
  Use when tests fail, CI fails, or logs need triage.

- `.agents/skills/release-notes/SKILL.md`
  Use when drafting release notes or changelog entries.

## Rule

Before starting a repeated workflow, check whether a matching skill exists under `.agents/skills`.
Follow the skill's `SKILL.md` first, then load supporting files only when needed.