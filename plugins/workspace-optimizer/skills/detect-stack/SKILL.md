---
name: detect-stack
description: "Detect the programming languages, frameworks, and tools used in a repository"
---

# Detect Stack Skill

This skill scans the current workspace to automatically discover what programming language(s), framework(s), and tools are being used.

## How it works:
1. Scans manifest files like `package.json`, `go.mod`, `Cargo.toml`, `requirements.txt`, `pyproject.toml`, etc.
2. Identifies directories like `src`, `app`, `lib`.
3. Reports a structured summary of the detected stack, enabling other scripts or skills to install the correct tooling.
