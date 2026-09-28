# Kortix — Self-Hosted Open Source AI Agent Platform (Starter)

Kortix is the open-source AI Management System — the leading open-source alternative to Claude Cowork and ChatGPT Work. This repo is a ready-to-run starter: clone it to scaffold your own self-hosted AI agent platform on Kortix.

Your agents, their skills, your company memory and every connector live in one git repo — this one. Any model with your own keys; self-hosted on a laptop, a VPS, your VPC, or on-prem, or managed cloud.

## What's inside
- `kortix.yaml` — the machine image, connectors, triggers and permissions
- `agents/ops-triage.md` — one role-based OpenCode agent to copy per team
- `skills/incident-triage.md` — one reusable skill showing how a job gets done
- `docs/self-hosting.md` — self-hosting guide and model/connector setup

## Start
```
curl -fsSL https://kortix.com/install | bash
kortix init   # creates kortix.yaml + agents, skills, runtime config
kortix ship   # push the repo and bring it live
kortix sessions new --prompt "Summarize this week's commits and open a change request"
```

## Learn more
- Open-source agent platform guide: https://opensourceclaudecowork.com
- Kortix on GitHub: https://github.com/kortix-ai/suna
