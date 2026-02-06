# CLAUDE.md

This file provides guidance to AI coding agents (Claude Code, Cursor, Copilot, etc.) when working with code in this repository.

## Repository Overview

A collection of skills for Claude Code and other AI coding assistants for creating bold, minimal presentations. Skills are packaged instructions that extend Claude's capabilities with an opinionated presentation methodology.

## Skill Structure

```
skills/
  {skill-name}/
    SKILL.md              # Required: skill definition with YAML frontmatter
```

### SKILL.md Format

Each skill has YAML frontmatter with `name` and `description`, followed by markdown instructions:

- `name`: kebab-case skill name
- `description`: When to use this skill (trigger phrases and contexts)
- Body: Instructions, patterns, and examples

### Guidelines

- Keep SKILL.md under 500 lines — concise over comprehensive
- Use imperative/infinitive form in instructions
- Examples should be generic (no company-specific data)
- Each skill should be self-contained and independently useful
