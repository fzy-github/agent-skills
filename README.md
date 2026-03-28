# fzy-skills

A collection of [Claude Code](https://claude.ai/code) skills (slash commands).

## Skills

| Skill | Description |
|-------|-------------|
| [joke-skill](joke-skill/) | Generate short, original jokes and joke-of-the-day responses |

## Structure

Each skill is a self-contained directory with:

- `SKILL.md` — Skill definition (YAML frontmatter + prompt)
- `agents/` — Optional agent integration configs

## Installation

Copy or symlink a skill directory into `~/.claude/skills/`:

```sh
cp -r joke-skill ~/.claude/skills/
```

## License

[MIT](LICENSE)
