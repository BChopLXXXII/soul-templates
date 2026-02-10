# soul-templates

personality templates for [OpenClaw](https://github.com/openclaw/openclaw) agents. pick one. customize it. ship it.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-compatible-blue)](https://openclaw.ai)

## what's a SOUL.md?

every OpenClaw agent reads a `SOUL.md` file when it wakes up. this file defines who the agent *is* — personality, boundaries, how it talks, what it cares about.

these also work with [Claude Code](https://claude.ai/claude-code), ChatGPT, and any AI tool that supports system-level personality files.

think of it as your agent's DNA.

## the templates

| template | vibe | best for |
| ---------- | ------ | ---------- |
| [01-chill-assistant](./templates/01-chill-assistant.md) | low-key, minimal, just helps | daily driver, general use |
| [02-adhd-brain](./templates/02-adhd-brain.md) | structured, patient, no shame | task management, staying on track |
| [03-sarcastic-dev](./templates/03-sarcastic-dev.md) | dry humor, ships anyway | devs who don't take themselves seriously |
| [04-strict-executor](./templates/04-strict-executor.md) | no opinions, just does the thing | power users who know what they want |
| [05-creative-partner](./templates/05-creative-partner.md) | opinionated, pushes back | writing, projects, creative work |
| [06-patient-teacher](./templates/06-patient-teacher.md) | explains simply, never condescends | learning new things |
| [07-midnight-companion](./templates/07-midnight-companion.md) | present, thoughtful, no rush | late night conversations |
| [08-hype-person](./templates/08-hype-person.md) | celebrates everything | when you need energy |

## quick start

```bash
# clone the repo
git clone https://github.com/BChopLXXXII/soul-templates.git

# copy a template to your openclaw workspace
cp soul-templates/templates/01-chill-assistant.md ~/.openclaw/workspace/SOUL.md

# restart your agent or start a new session
```

or just copy the raw file content directly from github. whatever works.

## customize

these are starting points, not rules. mix and match. add your own sections. remove what doesn't fit.

the best SOUL.md is the one that makes *your* agent feel right.

## license

MIT. do whatever you want with these.

## about

made by [@BChopLXXXII](https://x.com/BChopLXXXII)

built for vibe coders who just want their AI to feel less... corporate.

ship it. 🚀

---

if this helped, [star the repo](https://github.com/BChopLXXXII/soul-templates) — it helps others find it.
