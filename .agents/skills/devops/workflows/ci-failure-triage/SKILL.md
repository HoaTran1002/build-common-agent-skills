---
name: ci-failure-triage
description: Triage CI failures by reproducing locally, inspecting logs, and proposing minimal fixes.
---

# Ci Failure Triage

## Workflow

1. Clarify requirements, constraints, and acceptance criteria.
2. Inspect existing patterns and related code paths before editing.
3. Implement the smallest safe change that meets the goal.
4. Validate with the narrowest relevant checks (lint/typecheck/tests/build).
5. Summarize changes, risks, and follow-ups.
