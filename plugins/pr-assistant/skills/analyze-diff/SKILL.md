---
name: analyze-diff
description: "Analyze the current Git diff to identify key changes and affected modules"
---

# Analyze Diff Skill

This skill analyzes the current active Git branch's differences against the main/target branch.

## How it works:
1. Inspects changed files, added lines, and removed lines.
2. Identifies public API changes, refactoring, and dependency updates.
3. Groups modifications by package or functional area.
4. Highlights potential risk areas (e.g., deleted security checks, modified SQL queries, complex algorithmic changes).
