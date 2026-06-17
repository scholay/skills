# Scholay Skills

Open academic AI skills maintained by Scholay.

Scholay is building an AI-native academic workspace for literature discovery, evidence management, peer review, LaTeX writing, and research workflows.

Website: <https://www.scholay.com>

## Repository Layout

```text
corpus-building/
evidence-review/
literature-discovery/
research-writing/
source-intake/
```

## Included Skill Families

- **Literature Discovery**: build a search matrix, expand seed literature, and maintain an intake queue.
- **Source Intake**: classify raw research materials before processing.
- **Corpus Building**: convert source objects into addressable evidence cards.
- **Evidence Review**: promote extracted evidence toward citation readiness.
- **Research Writing**: draft from verified evidence while preserving citation integrity.

## What Is Intentionally Not Included

This repository is a clean public export. It does not include Scholay application source code, agent-facing skills, private deployment configuration, product infrastructure, credentials, internal databases, or private project history.

## Publishing Boundary

Use the private `scholar` repository as the internal source of truth when the application needs to reference skills from its `main` branch. Use this repository only for the reviewed public skill export.

The `.gitignore` in this repository is allowlist-based: by default, files are ignored unless they are root public docs or files under the reviewed public skill directories. This releases the public skill folders directly at the repository root while preventing accidental upload of private application code, agent-facing skills, environment files, generated assets, screenshots, design files, or runtime data.

If a future public skill needs non-Markdown assets or scripts, place them inside its reviewed public skill directory.

## Status

This repository is an early public skills release. More Scholay open-source materials will be published progressively.

If these skills are useful to your research workflow, please star the repository.
