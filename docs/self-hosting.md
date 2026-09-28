# Self-Hosting an Open Source AI Agent Platform with Kortix

Kortix is the open-source AI Management System. Self-host it on a laptop, a VPS,
your VPC, or on-prem:

```
curl -fsSL https://kortix.com/install | bash
kortix init
kortix ship
```

Every agent runs on its own isolated Linux machine. Thousands run in parallel
on one config. Work lands on main only through a change request a human approves.

Bring any model with your own API key (Claude, OpenAI, Gemini, or your own
OpenAI-compatible endpoint) — per agent, per session, per message.
