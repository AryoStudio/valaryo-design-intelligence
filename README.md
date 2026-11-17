# VALARYO Design Intelligence

**Created by RyouzZz** · **Brand: VALARYO** · **Version: 0.1.0**  
**Free to use · No password · No mandatory login**

A professional adaptive UI/UX skill for AI coding agents. It helps plan, design, implement, review, and improve digital interfaces with context-driven art direction, responsive behavior, usability, accessibility, maintainable frontend code, and honest visual QA.

## Install with Skills CLI

After publishing this repository:

```bash
npx skills add <GITHUB_OWNER>/valaryo-design-intelligence
```

Replace `<GITHUB_OWNER>` with the GitHub account or organization that owns the repository. Choose the agent and installation scope when prompted.

## Manual install for Codex

Windows PowerShell:

```powershell
New-Item -ItemType Directory -Force "$HOME\.agents\skills" | Out-Null
git clone https://github.com/<GITHUB_OWNER>/valaryo-design-intelligence.git "$HOME\.agents\skills\valaryo-design-intelligence"
```

macOS/Linux:

```bash
mkdir -p "$HOME/.agents/skills"
git clone https://github.com/<GITHUB_OWNER>/valaryo-design-intelligence.git "$HOME/.agents/skills/valaryo-design-intelligence"
```

Other agents use different discovery paths. Follow the current installation guide for your agent. Restart/reload the agent after installation.

## First prompt

```text
Use VALARYO Design Intelligence. Inspect this project first, understand its current design system and UX, then identify the five highest-impact improvements. Do not edit files until you explain the plan.
```

## Repository contents

- `SKILL.md`: main skill instructions.
- `references/`: specialist design guidance.
- `docs/`: installation, architecture, protection, privacy, and release guidance.
- `LICENSE` and `NOTICE.md`: ownership and usage terms.

## Protection note

This public repository contains readable files. Copyright and the proprietary license set legal restrictions, but cannot technically prevent copying of public files. Keep confidential algorithms, private prompts, credentials, and server configuration out of this repository.

The planned private VALARYO Core, MCP server, and API are **not included or active** in version 0.1.0. This release works as a local Agent Skill using the public instructions and the capabilities of the AI agent.

## Ownership

VALARYO Design Intelligence is created by **RyouzZz**. Do not remove attribution, claim authorship, rebrand, sell, or redistribute the skill package except as permitted by `LICENSE` or with written permission.
