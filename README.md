# OpenCTO Skills Pack

Repo-managed skill directory for Codex/OpenClaw.

This pack now includes:
- 15 business capability playbooks
- 1 engineering governance playbook: `cto-playbook`
- 1 specialty creative skill: `dj-playbook`

Total skill folders in this repo pack: `17`

## Business Capability Skills

| Capability | Skill ID | Repo Path |
|---|---|---|
| Leadership | `leadership-strategy-playbook` | `opencto/opencto-skills/leadership-strategy-playbook/` |
| Financial Management | `financial-management-playbook` | `opencto/opencto-skills/financial-management-playbook/` |
| Sales + Revenue Generation | `sales-playbook` | `opencto/opencto-skills/sales-playbook/` |
| Marketing + Brand | `marketing-brand-playbook` | `opencto/opencto-skills/marketing-brand-playbook/` |
| Product + Innovation | `product-innovation-playbook` | `opencto/opencto-skills/product-innovation-playbook/` |
| Operations + Execution | `operations-execution` | `opencto/opencto-skills/operations-execution/` |
| People + Culture | `people-culture-playbook` | `opencto/opencto-skills/people-culture-playbook/` |
| Technology + Data | `tech-data-playbook` | `opencto/opencto-skills/tech-data-playbook/` |
| Customer Experience | `customer-experience-playbook` | `opencto/opencto-skills/customer-experience-playbook/` |
| Legal + Compliance | `legal-compliance-playbook` | `opencto/opencto-skills/legal-compliance-playbook/` |
| Communication | `communication-playbook` | `opencto/opencto-skills/communication-playbook/` |
| Risk Management | `risk-management-playbook` | `opencto/opencto-skills/risk-management-playbook/` |
| Partnerships + Ecosystem | `partnerships-ecosystem` | `opencto/opencto-skills/partnerships-ecosystem/` |
| Adaptability + Learning | `adaptive-learning-playbook` | `opencto/opencto-skills/adaptive-learning-playbook/` |
| Sustainability & Social Responsibility | `sustainability-playbook` | `opencto/opencto-skills/sustainability-playbook/` |

## Additional Skills

| Type | Skill ID | Repo Path |
|---|---|---|
| Engineering Governance | `cto-playbook` | `opencto/opencto-skills/cto-playbook/` |
| Creative Performance | `dj-playbook` | `opencto/opencto-skills/dj-playbook/` |

## Skill Folder Standard

Each skill folder should contain:
- `SKILL.md`
- `references/...` for long-form material
- optional `README.md` for repo-level documentation
- optional `.gitignore`

The newer playbook skills added to this repo follow a normalized pattern:

```text
opencto/opencto-skills/<skill-id>/
├── SKILL.md
├── README.md
├── .gitignore
└── references/
    └── <playbook-file>.md
```

Legacy repo-managed skills may only include `SKILL.md` plus `references/`.

## Manifest

The pack index lives in:

- `opencto/opencto-skills/skills-manifest.json`

Each entry includes:
- skill id
- human-readable name
- skill path
- short description
- category
- safety scan command
- runtime compatibility

## Install to Codex/OpenClaw

Use the installer script:

```bash
./opencto/scripts/install-opencto-skill.sh \
  --skill <skill-id> \
  --dest ~/.codex/skills
```

For OpenClaw or another runtime path:

```bash
./opencto/scripts/install-opencto-skill.sh \
  --skill <skill-id> \
  --dest ~/.openclaw/skills
```

## Recommended Validation

Run a security scan before local installation or publishing:

```bash
uvx snyk-agent-scan@latest --skills opencto/opencto-skills/<skill-id>/SKILL.md
```

If the repo pack changes materially, also review:
- `opencto/opencto-skills/README.md`
- `opencto/opencto-skills/skills-manifest.json`

## Notes

- `Customer Experience` is the repo skill used to cover the customer/consumer experience capability.
- Several of these skills may already exist as standalone GitHub repos and `skills.sh` packages; this folder is the repo-managed source-of-truth pack inside OpenCTO.
