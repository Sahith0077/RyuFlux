---
name: testing
description: Use this skill to create, maintain, and execute reliable tests for changes.
---

# testing

Purpose:
Create, maintain, and execute reliable tests for changes.

Instructions:
- Inspect the existing testing strategy first.
- Prefer the project's existing test framework.
- Add tests for new behavior.
- Update tests when behavior intentionally changes.
- Include normal cases, edge cases, and failure cases where appropriate.
- Run the smallest relevant test set first.
- Run the broader test suite when appropriate.
- Never claim a test passed unless it was actually executed.
- Report exact failures.
- Avoid brittle tests.
- Do not modify tests merely to make broken code pass unless the expected behavior legitimately changed.
