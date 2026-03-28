# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

A collection of Claude Code skills (slash commands). Each skill is a self-contained directory that gets installed into `~/.claude/skills/` and becomes available as a `/skill-name` command in Claude Code.

## Skill Structure

Each skill directory contains:

- **`SKILL.md`** — The skill definition. YAML frontmatter (`name`, `description`) controls discovery and matching. The markdown body is the prompt that Claude follows when the skill is invoked.
- **`agents/`** (optional) — YAML configs for agent integrations (e.g., `openai.yaml` for scheduled/remote agent triggers).

## Writing a New Skill

1. Create a directory named `<skill-name>/` at the repo root.
2. Add a `SKILL.md` with frontmatter (`name` and `description` are required) and the skill prompt in markdown.
3. The `description` field is used for matching — write it so Claude knows *when* to invoke the skill.
4. Keep prompts action-oriented: define the workflow, constraints, and output format. Avoid generic filler.
