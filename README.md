# The Spot — Claude Code Design Skills

Reusable design skills for Claude Code. Copy `.claude/skills/` into any new project for instant premium-design behavior — no need to re-search or re-install per project.

**Note:** the `.claude/skills/` folder itself always stays flat (one folder per skill, no category subfolders) — that's what Claude Code's skill loader and the one-line copy prompt below both require. Categories below are for this README's readability only.

## Quick use (any new project)

In the VS Code Claude Code panel, inside the new project's folder:

```
Copy the .claude/skills/ folder from
https://github.com/thespotagency/claude-skills-template
into this project.
```

## What's inside — by category

### 🎨 Visual Design & UI Taste
| Skill | Status | What it does |
|---|---|---|
| `design-taste-frontend` | ✅ Installed | Blocks generic/AI-looking UI when writing new frontend code — layout, typography, motion, spacing taste. |
| `high-end-visual-design` | ✅ Installed | "$150k agency" visual rules — fonts, shadows, card structure, motion — for a calm/expensive/premium feel. |

### 🎬 Motion & Animation
| Skill | Status | What it does |
|---|---|---|
| `design-motion-principles` | ✅ Installed | Motion/animation expert — build purposeful motion, or audit existing animations for AI-slop motion patterns. |

### 🔍 Audit & Redesign (Existing Projects)
| Skill | Status | What it does |
|---|---|---|
| `redesign-existing-projects` | ✅ Installed | Audit-first upgrade of an *existing* site/app to premium quality without breaking functionality. |

### 📋 Watchlist — found, not yet added (needs review before adding)
Not a drop-in `.claude/skills/` folder, so kept out of the flat skills folder above. Each is backed up as a full fork under `thespotagency` (all branches) in case the original ever disappears.

| Skill | Original | Backup fork | Why it's not a drop-in `.claude/skills/` folder |
|---|---|---|---|
| UI/UX Pro Max | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | https://github.com/thespotagency/ui-ux-pro-max-skill | Full CLI tool, not a single skill file — installs via `npx ui-ux-pro-max-cli init --ai claude` per project. 79 UI styles / 192 palettes / 74 font pairings. Strong for a brand-new project's design system from scratch; risk of clashing with an already-set brand (e.g. The Spot's own site). |
| Awesome Claude Design | https://github.com/VoltAgent/awesome-claude-design | https://github.com/thespotagency/awesome-claude-design | Not a Claude Code skill — a collection of `DESIGN.md` files for the separate `claude.ai/design` web tool. Different workflow, browser-based. Useful as inspiration reference only. |
| TypeUI DESIGN.md Chrome Extension | https://github.com/bergside/design-md-chrome | https://github.com/thespotagency/design-md-chrome | Not a Claude Code skill — a Chrome extension that extracts design tokens from any live website into a DESIGN.md/SKILL.md. Useful for competitor/inspiration research, installed manually in Chrome (Developer Mode → Load unpacked). Un-official extension — grants broad site-read permission. |

## Adding a new skill

1. Confirm it's a plain `.claude/skills/<name>/SKILL.md` (optionally + `references/` / `workflows/`) — that's the only format that copies cleanly into a new project with the one-liner above.
2. Drop it straight into `.claude/skills/<name>/` — flat, no category folder.
3. Add one row to the matching category table above (or a new category heading if it doesn't fit an existing one). If it doesn't qualify (CLI tool, browser extension, web-only workflow), add it to the Watchlist table instead with a one-line reason, and fork it (all branches) to `thespotagency` as a backup.
