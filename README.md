# Basilica Skills

Agent skills for using Basilica from AI coding tools.

This public distribution is generated from `packages/skills/` in the
[Basilica development monorepo](https://github.com/one-covenant/basilica-backend).
Public issues and proposed patches remain welcome here; maintainers carry
accepted changes into the monorepo before regenerating the distribution.
The CLI installation URL remains unchanged.

## Install

Install the Basilica CLI, then install skills:

```bash
basilica skills install
```

## Repository Format

Each directory under `skills/` containing a `SKILL.md` file is an installable
skill:

```text
basilica-skills/
  README.md
  AGENTS.md
  skills/
    use-basilica/
      SKILL.md
```

Root files are repository metadata. The Basilica CLI installer ignores root
files and installs only curated directories under `skills/`.

## Skills

- `use-basilica`: route-first Basilica operations guide for the CLI and Python SDK.
