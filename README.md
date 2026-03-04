# OpenCTO Skills

Skills pack for Codex/OpenClaw.

## Included Skills

- `cto-playbook`: CTO and engineering execution standards
- `dj-playbook`: DJ performance and creator workflow standards

## Repository Layout

- `skills-manifest.json`
- `cto-playbook/SKILL.md`
- `cto-playbook/references/full-playbook.md`
- `dj-playbook/SKILL.md`
- `dj-playbook/references/full-playbook.md`

## Install (Codex/OpenClaw)

Clone and copy the skill you want into your runtime skill directory.

```bash
git clone https://github.com/Hey-Salad/opencto-skills.git
mkdir -p ~/.codex/skills
cp -R opencto-skills/cto-playbook ~/.codex/skills/
cp -R opencto-skills/dj-playbook ~/.codex/skills/
```

Restart Codex/OpenClaw after installing.

## Security Scan (Recommended)

```bash
uvx snyk-agent-scan@latest --skills cto-playbook/SKILL.md
uvx snyk-agent-scan@latest --skills dj-playbook/SKILL.md
```
