# Graphite Skill for Claude Code

A Claude Code skill for managing branches and PRs using the [Graphite CLI](https://graphite.dev/) (`gt`).

## Installation

Copy the `skill/` directory to your Claude Code skills directory and rename it to `graphite`:

```bash
# Personal installation (available in all projects)
git clone https://github.com/matiacone/graphite-skill.git /tmp/graphite-skill
cp -r /tmp/graphite-skill/skill ~/.claude/skills/graphite

# Or project-specific installation
git clone https://github.com/matiacone/graphite-skill.git /tmp/graphite-skill
cp -r /tmp/graphite-skill/skill .claude/skills/graphite
```

## Prerequisites

- [Graphite CLI](https://graphite.dev/docs/installing-the-cli) installed and authenticated
- A repository initialized with Graphite (`gt init`)

## Usage

Once installed, invoke with `/graphite` or let Claude Code automatically use it for version control tasks.
