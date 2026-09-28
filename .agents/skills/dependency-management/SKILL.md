---
name: dependency-management
description: Use this skill to safely manage project dependencies and versions.
---

# dependency-management

Purpose:
Safely manage project dependencies and versions.

Instructions:
- Inspect the existing dependency manager first.
- Respect the project's current version strategy.
- Do not add a dependency when the standard library or an existing dependency is sufficient.
- Before adding a package, explain why it is needed.
- Prefer well-maintained and appropriate packages.
- Avoid unnecessary dependency duplication.
- Update lockfiles/manifests correctly.
- Check compatibility with the current runtime.
- Avoid arbitrary version upgrades.
- Identify potential breaking changes before major upgrades.
- Verify the application after dependency changes.
