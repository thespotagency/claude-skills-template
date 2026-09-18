# The Spot — Claude Code Design Skills

Reusable design skills for Claude Code. Copy `.claude/skills/` into any new project for instant premium-design behavior — no need to re-search or re-install per project.

## Quick use (any new project)

In the VS Code Claude Code panel, inside the new project's folder:

```
Copy the .claude/skills/ folder from
https://github.com/thespotagency/claude-skills-template
into this project.
```

## What's inside

| Skill | Status | What it does |
|---|---|---|
| `design-taste-frontend` | ✅ Installed (`.claude/skills/`) | Blocks generic/AI-looking UI when writing new frontend code — layout, typography, motion, spacing taste. |
| `redesign-existing-projects` | ✅ Installed (`.claude/skills/`) | Audit-first upgrade of an *existing* site/app to premium quality without breaking functionality. |
| `high-end-visual-design` | ✅ Installed (`.claude/skills/`) | "$150k agency" visual rules — fonts, shadows, card structure, motion — for a calm/expensive/premium feel. |
| `design-motion-principles` | ✅ Installed (`.claude/skills/`) | Motion/animation expert — build purposeful motion, or audit existing animations for AI-slop motion patterns. |

## Watchlist — found, not yet added (needs review before adding)

| Skill | Link | Why it's not a drop-in `.claude/skills/` folder |
|---|---|---|
| UI/UX Pro Max | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | Full CLI tool, not a single skill file — installs via `npx ui-ux-pro-max-cli init --ai claude` per project. 79 UI styles / 192 palettes / 74 font pairings. Strong for a brand-new project's design system from scratch; risk of clashing with an already-set brand (e.g. The Spot's own site). |
| Awesome Claude Design | https://github.com/VoltAgent/awesome-claude-design | Not a Claude Code skill — a collection of `DESIGN.md` files for the separate `claude.ai/design` web tool. Different workflow, browser-based. Useful as inspiration reference only. |
| TypeUI DESIGN.md Chrome Extension | https://github.com/bergside/design-md-chrome | Not a Claude Code skill — a Chrome extension that extracts design tokens from any live website into a DESIGN.md/SKILL.md. Useful for competitor/inspiration research, installed manually in Chrome (Developer Mode → Load unpacked). Un-official extension — grants broad site-read permission. |

Add a new skill here only after confirming it's a plain `.claude/skills/<name>/SKILL.md` (or that folder + `references/`) — that's the only format that copies cleanly into a new project with the one-liner above.
