# Contributing to OpenCTO Skills

## Scope

This repository contains reusable skill packages for Codex/OpenClaw.

## Skill Structure

Each skill must follow:

- `<skill-id>/SKILL.md`
- `<skill-id>/references/*` (optional)

## Contribution Rules

1. Keep skills focused and production-oriented.
2. Do not include secrets, tokens, credentials, or private URLs.
3. Prefer deterministic commands and explicit safety guardrails.
4. Use DRY content: avoid repeating large duplicated sections.
5. Add/update `skills-manifest.json` for every new/changed skill.

## Validation Checklist

Before opening a PR:

1. Validate markdown formatting and links.
2. Run security scan on changed skills:
   - `uvx snyk-agent-scan@latest --skills <skill-path>/SKILL.md`
3. Ensure no proprietary or sensitive data is included.
4. Confirm install works by copying skill folder into a local skills directory.

## PR Guidelines

- One logical skill change per PR where possible.
- Include a short summary:
  - what changed
  - why it changed
  - how to use it
  - validation evidence
