---
name: setup-linters
description: "Configure appropriate linters and formatters based on the detected stack"
---

# Setup Linters Skill

This skill configures standard code styling, formatting, and linting tools based on the active stack.

## Guidelines:
1. Prefer well-known community standard tooling (Prettier for JS/TS, Black/Ruff for Python, gofmt for Go, rustfmt for Rust).
2. Create configuration files at the root of the repository without overwriting existing files.
3. Add helper commands or scripts to automate the running of linters in development.
