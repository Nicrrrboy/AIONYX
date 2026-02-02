# CLAUDE.md — AIONYX

This file provides guidance for AI assistants (including Claude) working in this repository.

## Project Overview

AIONYX is a newly initialized repository owned by **Nicrrrboy**. The project is in its earliest stage and does not yet contain application code, build tooling, or dependency manifests. This document will evolve alongside the codebase.

## Repository Structure

```
AIONYX/
├── CLAUDE.md          # AI assistant guidance (this file)
├── AIONYX TEST        # Initial test file
└── .git/              # Git metadata
```

## Current State

- **Status**: Bootstrapped — no source code, frameworks, or tooling configured yet.
- **Primary branch**: `main`
- **Remote**: GitHub (Nicrrrboy/AIONYX)

## Development Conventions

The following conventions should be adopted as code is added to the project.

### Git Workflow

- The default branch is `main`.
- Feature work should be done on dedicated branches.
- Write clear, concise commit messages that describe *why* the change was made.
- Do not force-push to `main`.

### Code Quality

- When tooling (linters, formatters, type checkers) is added, always run them before committing.
- Prefer small, focused commits over large monolithic ones.
- Do not commit secrets, credentials, or `.env` files.

### Testing

- When a test framework is introduced, ensure new functionality includes corresponding tests.
- Tests should pass before merging to `main`.

### Documentation

- Update this `CLAUDE.md` whenever significant project structure, tooling, or conventions change.
- Keep a `README.md` for human-oriented project documentation once the project scope is defined.

## Instructions for AI Assistants

1. **Read before modifying.** Always read a file before proposing changes to it.
2. **Stay minimal.** Only make changes that are directly requested or clearly necessary. Do not add features, refactoring, or "improvements" beyond what is asked.
3. **Respect existing patterns.** When the codebase establishes a convention, follow it rather than introducing alternatives.
4. **No secrets.** Never commit API keys, tokens, passwords, or other sensitive values.
5. **Update this file.** If you add frameworks, tooling, or significant structure, update this document to reflect the new state.
6. **Verify your work.** Run any available linters, type checkers, and tests before considering a task complete.
