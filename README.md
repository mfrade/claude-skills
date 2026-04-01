# claude-skills

A personal collection of skills for [Claude Code](https://claude.ai/code) — some created from scratch, some curated from the community.

Skills are Markdown files that Claude loads from `/mnt/skills/` to shape its behaviour in specific domains without manual prompting each session.

## Skills

| Skill | Description |
|-------|-------------|
| [pt-pt](pt-pt/) | Forces all Portuguese responses to follow European Portuguese (PT-PT), avoiding Brazilian Portuguese constructions and vocabulary. |

## Usage

Copy any skill's `SKILL.md` to your Claude skills directory:

```
/mnt/skills/user/<skill-name>/SKILL.md
```

Claude will detect and load it automatically.

## Structure

Each skill lives in its own folder:

```
<skill-name>/
├── SKILL.md    # The skill itself — loaded by Claude
└── README.md   # Documentation and examples
```

## License

MIT
