# Changelog

## 2026-07-09 — Spectre v0.1.0

- Initial Spectre foundation established
- Created ~/.spectre/ directory structure
- Wrote AGENTS.md with core principles and task lifecycle
- Created 8 config files: workstation, coding, architecture, security, git, testing, deployment, style
- Created 8 playbooks: create-service, create-api, debug, review, refactor, documentation, release, incident
- Created 8 knowledge files: modelink, fastapi, nextjs, postgres, redis, ollama, podman, linux
- Created 7 scripts: bootstrap, lint, test, security, update, backup, cleanup
- Created 3 memory files: decisions, architecture, changelog
- Created template stubs for microservice, frontend, api, docker, kubernetes, github
- Created README.md

## 2026-07-09 — Spectre v0.2.0

- Production-hardened all scripts (error traps, exit codes, expanded security patterns, parameterized targets)
- Replaced hardcoded secrets in docker-compose.yml with env var interpolation
- Fixed Dockerfile multi-stage to copy source code
- Updated Node.js Dockerfile for Next.js v15 standalone output
- Added concurrency, caching, and conditional build to CI workflow
- Added deploy workflow with environment targeting
- Added HPA, PDB, and NetworkPolicy to Kubernetes templates
- Added feature request issue template
- Added references and external_directory permissions to OpenCode config
- Added .gitignore and initialized git repository
