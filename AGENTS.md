# AI Agent Instructions for True Connections

## Project Status

This repository powers the production website for:

https://coachingtrueconnections.com

Production branch:

master

Known-good production baseline tag:

production-baseline-2026-05-03

Known-good production baseline commit:

ad915a964bd2f43b9f0acffbf05ed4241211b6ed

## Critical Safety Rules

1. Do not push directly to `master`.
2. Do not delete, overwrite, retag, or force-update any Git tag matching `production-baseline-*`.
3. Do not modify, remove, or ignore `CNAME`.
4. Do not change the production domain.
5. Do not run destructive Git commands without explicit human approval.
6. Do not run commands containing `rm -rf`, `git reset --hard`, `git clean`, `git push --force`, or `chflags nouchg` without explicit human approval.
7. Do not edit files outside this repository unless explicitly instructed.
8. Do not access, delete, move, rename, overwrite, modify, compress, extract, or regenerate anything in `../backups`.
9. Work only on approved non-production branches.
10. Preserve coaching/consulting scope language. Do not imply therapy, diagnosis, or clinical mental health treatment.

## Required Workflow

Before editing files:

1. Inspect the repo.
2. Summarize the current structure.
3. Explain the proposed change.
4. List files expected to change.
5. Wait for explicit human approval.

After editing files:

1. Show a concise change summary.
2. Run available verification commands.
3. Show `git status`.
4. Do not commit unless explicitly instructed.
5. Do not push unless explicitly instructed.

## Project Type

This is a Jekyll GitHub Pages site using a remote theme.

Primary config file:

_config.yml

Primary content files include:

- index.md
- about-us.md
- coaching-services.md
- consulting-services.md
- how-it-works.md
- faq.md
- testimonials.md
- contact-us.md
