# Account GitHub Defaults

This is the special public `.github` repository for the HughZadora account.
Its only cross-repository role is to provide GitHub-native default community
health files when a repository does not define its own equivalent.

## Scope

The reusable defaults live under `.github/` and cover supported GitHub community
files such as:

- contribution guidance;
- issue templates;
- the pull request template;
- security reporting guidance;
- support guidance;
- the code of conduct.

A repository-specific file takes precedence over these defaults.

## Boundary

This repository is **not** an engineering-policy repository and is not a parent
of the account's other repositories. It does not define or synchronize:

- application or infrastructure architecture;
- languages, frameworks, runtimes, or package managers;
- repository tiers or custom project metadata;
- formatting, linting, testing, build, deployment, or release rules;
- Agent instructions for another repository;
- cross-repository file contents.

`HughZadora/repo-template` is a separate copy-on-create starter for new
repositories. A project created from that template becomes autonomous
immediately. Neither this repository nor the template creates ongoing
inheritance between repositories.

For engineering work, always follow the target repository's own README,
`AGENTS.md`, configuration, tests, and workflows.
