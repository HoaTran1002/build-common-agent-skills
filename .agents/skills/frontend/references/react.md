# React Reference

Use this reference when the task affects React components, hooks, forms, state, effects, or React tests.

## Rules

- Prefer functional components.
- Keep side effects inside `useEffect`.
- Do not duplicate derived state unless necessary.
- Avoid unnecessary global state.
- Keep component logic close to the component unless reused.
- Follow existing form validation patterns.
- Preserve controlled/uncontrolled input conventions already used in the file.

## Before editing

Check:
- Existing component structure
- State management style
- Form library, if any
- Test style
- Styling convention

## Common risks

- Stale closure in hooks
- Missing dependency in `useEffect`
- Double submit
- Broken loading state
- Unhandled error state
- Accessibility regression