# .agents/skills/task-intake/SKILL.md

---

name: task-intake
description: Classify a new engineering task before implementation. Use this skill whenever a user gives a new coding, debugging, infrastructure, mobile, frontend, backend, fullstack, refactoring, testing, or release-related task. Determine the task type, impacted areas, risk level, required context, and which follow-up skills should be used.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task Intake

When receiving a new engineering task, do not start editing immediately.

First classify the task.

## 1. Identify task type

Classify the task into one or more categories:

* `frontend-change`
* `backend-change`
* `mobile-change`
* `devops-change`
* `fullstack-change`
* `bug-fix`
* `refactor`
* `test-verification`
* `release-notes`
* `investigation-only`

A task may belong to multiple categories.

Examples:

* "Fix button not working on login page" → `frontend-change`, `bug-fix`
* "Add API for user profile" → `backend-change`
* "Update mobile onboarding screen" → `mobile-change`
* "Fix Docker build in CI" → `devops-change`, `bug-fix`
* "Add checkout flow with UI, API, DB migration" → `fullstack-change`, `frontend-change`, `backend-change`

## 2. Determine impacted areas

Identify likely impacted areas:

* UI
* API
* database
* auth
* permissions
* mobile app
* CI/CD
* infrastructure
* tests
* documentation
* release notes

## 3. Choose follow-up skills

Use the most specific matching skill:

* For UI work, use `.agents/skills/frontend-change/SKILL.md`
* For API, service, database, or server work, use `.agents/skills/backend-change/SKILL.md`
* For iOS, Android, React Native, Flutter, or mobile UX work, use `.agents/skills/mobile-change/SKILL.md`
* For CI/CD, Docker, Kubernetes, deployment, cloud, or environment work, use `.agents/skills/devops-change/SKILL.md`
* For tasks spanning UI, API, database, and deployment, use `.agents/skills/fullstack-change/SKILL.md`
* For failing behavior or regression, use `.agents/skills/bug-fix/SKILL.md`
* Before finishing, use `.agents/skills/test-verification/SKILL.md`
* Before merge or handoff, use `.agents/skills/pr-review/SKILL.md`

## 4. Produce a short execution plan

Before implementation, produce:

* Task type
* Impacted areas
* Files or folders to inspect first
* Main risks
* Skills to use
* Verification approach

Keep the plan short.
Do not over-plan simple tasks.
