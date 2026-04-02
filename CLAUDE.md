# Testing

## Purpose

This is a development testing repository used to validate crucible's repo management and distribution mechanisms. It serves no runtime purpose for end users.

Use cases include testing:
- Primary branch migration
- Subproject update behavior (`crucible update`)
- Git workflow and CI integration
- Branch protection rulesets

## Language

None — this repo contains no application code.

## Key Files

| File | Purpose |
|------|---------|
| `.github/workflows/git-testing.yaml` | CI workflow for testing git repository introspection |
| `.github/workflows/run-crucible-tracking.yaml` | Standard crucible project tracking workflow |
