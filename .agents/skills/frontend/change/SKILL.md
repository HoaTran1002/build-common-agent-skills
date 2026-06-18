---
name: frontend-change
description: Handle frontend engineering tasks such as UI changes, page updates, form behavior, state management, styling, accessibility, routing, and frontend bugs. Use when a task affects browser UI, frontend components, frontend tests, or client-side behavior.
---

# Frontend Change

## Workflow

1. Identify the frontend framework used in the repository.
2. Inspect existing component patterns before editing.
3. Prefer modifying existing components over creating new abstractions.
4. Preserve styling, state management, routing, and validation conventions.
5. Check accessibility and responsive behavior.
6. Run the narrowest relevant frontend test or typecheck.

## Framework references

Load only the relevant reference:

- React: `../references/react.md`
- Next.js: `../references/nextjs.md`
- Vue: `../references/vue.md`
- Angular: `../references/angular.md`
- Tailwind: `../references/tailwind.md`

Do not load all references by default.
