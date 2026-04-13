# oh-my-skills

Curated skill collections for AI coding agents. Ready-to-use with [aweskill](https://github.com/mugpeng/aweskill).

## Quick Start

```bash
# Install aweskill
npm install -g aweskill

# Init the local store
aweskill store init

# Option 1: Restore full backup from GitHub Release
aweskill store restore skills-2026-04-13.tar.gz

# Option 2: Import individual skills from a cloned repo
aweskill skill import ./skills/paper-workflow

# Import a bundle
aweskill bundle template import Nature-Paper-Skills
aweskill agent add bundle Nature-Paper-Skills
```

## Contents

### Skills (260)

Located in `skills/`. Each skill is a directory with a `SKILL.md` file.

### Bundles

Located in `bundles/`:

| Bundle | Description |
|--------|-------------|
| `Nature-Paper-Skills` | Nature portfolio paper writing workflow |
| `K-Dense-AI-scientific-skills` | Comprehensive scientific computing skills |
| `Superpowers` | Claude Code superpower skills |
| `global` | Essential utility skills |

## Releases

Full skill backups are published as [GitHub Releases](https://github.com/mugpeng/oh-my-skills/releases). Download and restore with:

```bash
aweskill store restore /path/to/skills-backup.tar.gz
```

## License

Individual skills may have their own licenses. See each skill's `SKILL.md` for details.
