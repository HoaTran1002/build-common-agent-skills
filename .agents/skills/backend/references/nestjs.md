# NestJS Reference

Use this reference when the task affects NestJS modules, controllers, services, guards, interceptors, DTOs, or providers.

## Rules

- Keep controllers thin.
- Put business logic in services.
- Validate input using DTOs.
- Reuse existing guards and decorators.
- Do not bypass existing auth or permission patterns.
- Follow existing module boundaries.
- Keep database access in repository/service layer according to current project pattern.

## Before editing

Inspect:
- Existing module structure
- Controller route conventions
- DTO validation style
- Auth/permission pattern
- Error handling pattern
- Existing tests