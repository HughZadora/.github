# Agent Instructions

## Scope

This file applies only to this account-level `.github` repository.

## Purpose

Maintain GitHub-native community health defaults shared across repositories, such as contribution,
issue, pull-request, security, and support guidance.

## Working rules

- Keep this repository narrow and GitHub-native.
- Do not use it as a global engineering canon, repository schema, bootstrap framework, or shared
  validation implementation.
- Do not add project-wide architecture, toolchain, lifecycle, package-manager, language, or release
  rules here; those belong to the relevant project.
- Preserve repository-specific ownership: project manifests, lockfiles, tests, CI, and local
  instructions remain authoritative for implementation facts.
- Keep changes focused on account-level community health behavior.
- Never commit secrets, credentials, or sensitive local configuration.

## Validation

There is no dedicated build or repository-wide validation command. Validate only the GitHub community
files changed by the task using their native syntax and GitHub behavior; do not introduce a toolchain
solely to manufacture a generic gate for this repository.
