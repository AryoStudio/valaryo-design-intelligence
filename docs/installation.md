# Installation

## Skills CLI
After publishing:
```bash
npx skills add AryoStudio/valaryo-design-intelligence
```

## Codex user-level installation (Windows PowerShell)
```powershell
New-Item -ItemType Directory -Force "$HOME\.agents\skills" | Out-Null
git clone https://github.com/AryoStudio/valaryo-design-intelligence.git "$HOME\.agents\skills\valaryo-design-intelligence"
```

## Codex user-level installation (macOS/Linux)
```bash
mkdir -p "$HOME/.agents/skills"
git clone https://github.com/AryoStudio/valaryo-design-intelligence.git "$HOME/.agents/skills/valaryo-design-intelligence"
```

Other agents may use different skill discovery directories. Follow the agent's current documentation. Restart or reload the agent after installation.
