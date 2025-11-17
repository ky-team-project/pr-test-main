# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository overview

- Project name: `pr-test-main` (from `README.md`).
- As of now, the repository only contains `README.md` and no detectable source directories or language/tooling configuration files.

## Tooling and commands

- There are currently **no project-specific build, lint, or test commands** defined (no `package.json`, `pyproject.toml`, `go.mod`, `Cargo.toml`, `Makefile`, etc. were found).
- Before running any build or test commands, check for newly added tooling:
  - Look for files like `package.json`, `pyproject.toml`, `requirements.txt`, `go.mod`, `Cargo.toml`, `pom.xml`, `build.gradle`, `Makefile`, or language-specific configs.
  - If such files exist, prefer the documented scripts/commands (for example, `npm test`, `pytest`, `go test ./...`, etc.) and update this `WARP.md` with concrete commands.

## Architecture notes

- No application code or structured directories (e.g., `src/`, `app/`, `backend/`, `frontend/`) are present yet.
- When code is added, future updates to this file should summarize the high-level architecture (major modules/services, primary entrypoints, and how they interact) rather than listing every file.
