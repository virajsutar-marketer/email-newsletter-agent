# Email & Newsletter Agent

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](SKILL.md)

A detailed, tool-agnostic AI agent skill for **email and newsletter marketing** — human voice discipline, honest urgency/FOMO psychology, hero design patterns, newsletter content strategy, automation/drip sequences, deliverability audits, MJML/email-safe technical build discipline, and list segmentation. Written so any AI agent can execute correctly for any brand/industry with no prior context.

## Install as a Claude Code Skill

```bash
git clone https://github.com/virajsutar-marketer/email-newsletter-agent.git ~/.claude/skills/email-newsletter
```

Restart Claude Code. The skill is discovered automatically via `SKILL.md`.

## Contents

| File | What it's for |
|---|---|
| [`SKILL.md`](./SKILL.md) | The Claude Code Skill manifest — what triggers this skill and the process to follow. |
| [`EMAIL-NEWSLETTER-PLAYBOOK.md`](./EMAIL-NEWSLETTER-PLAYBOOK.md) | The full operating manual: voice discipline, honest urgency/FOMO, hero section design patterns, newsletter content strategy, automation/drip sequence design, deliverability audit (SPF/DKIM/DMARC, sender reputation, list hygiene), MJML/email-safe HTML build discipline, and list segmentation logic. |
| [`CHECKLISTS.md`](./CHECKLISTS.md) | Condensed pre-send and technical-build checklists. |

## How to use this repo as an AI agent skill

1. Read `EMAIL-NEWSLETTER-PLAYBOOK.md` before drafting any campaign or newsletter edition.
2. Never fabricate an urgency claim (fake scarcity, fake countdowns, invented deadlines) — see Section 2's honest-urgency line.
3. Never send an email without visually verifying it renders correctly at true email width and mobile — see the technical checklist.
4. Segment every send by real reader relationship (prospect / customer / advocate) — never blast one undifferentiated message to a whole list.

## Scope and limitations

This repo is strategy and craft, not an ESP integration — it won't send an email, check a real DNS record, or pull real bounce/complaint data for you. Pair it with your email service provider's tools/APIs; this repo is what decides what to say, how to structure it, and what to check technically before you hit send.

## Contributing

Living document — add new email/newsletter patterns or gotchas in generalized form (no client names, no literal brand hex codes) under the most relevant section.

## License

MIT — see [`LICENSE`](./LICENSE).
