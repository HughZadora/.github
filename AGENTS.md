# Agent Instructions

## Scope

This file applies only to the special account repository `HughZadora/.github`.

## Repository boundary

This repository exists to provide GitHub-native default community health files.
It is not a global engineering-policy repository.

- Do not treat it as a parent, canon, template, or source of truth for project
  architecture, tooling, CI, tests, formatting, deployment, or release policy.
- Do not add repository tiers, custom project metadata, cross-repository
  manifests, synchronized engineering files, or rollout machinery here.
- Do not place instructions here with the expectation that Agents in other
  repositories will inherit them.
- Repository-specific community files and instructions take precedence over
  account defaults.
- `HughZadora/repo-template` is a separate copy-on-create starter. It does not
  create ongoing inheritance either.

## Working rules

- Keep this repository limited to supported GitHub community defaults plus the
  minimal README and Agent guidance needed to maintain those defaults.
- Before adding a default, verify that GitHub supports it as an account-level
  community health file and that a shared default is actually appropriate.
- Keep defaults generic; engineering details belong in the target repository.
- Verify a reported problem before changing files and keep changes focused.
- Never commit secrets, credentials, or sensitive local configuration.

## Validation

Review changed community files for valid GitHub paths and syntax. For behavior
that depends on GitHub inheritance, verify it against current GitHub
Documentation rather than inventing a parallel validation system.
