# Agent Instructions

## Scope

This file applies to the entire repository.

- Name: .github
- Purpose: Account-level community health files for every repository
- Tier: meta

## Working rules

- Read `README.md` and `STANDARD.md` before making non-trivial changes.
- Follow the repository standard and existing tooling before adding
  dependencies or custom infrastructure.
- Verify a reported problem before fixing it, and prefer the smallest systemic
  fix that addresses the root cause.
- Keep changes focused on the requested outcome and avoid unrelated refactoring.
- Never commit secrets, credentials, or sensitive local configuration.
- Never edit a shared file locally; change the canon and roll it out.

## Validation

Run `./scripts/repository-check` before claiming completion.
