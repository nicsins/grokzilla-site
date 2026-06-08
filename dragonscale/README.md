# Dragonscale Network Stack

The secure, persistent collective intelligence mesh for Grokzilla and agent swarms.

## Spin Up Instructions (using Podman or Docker)

1. `cd dragonscale`
2. `podman-compose up -d` or `docker-compose up -d`
3. Access:
   - Agent Zero UI: http://localhost:8080
   - Dragonscale API: http://localhost:3000 (custom nexus/grokomatic)
   - Postgres: localhost:5432

## Components
- **Postgres**: Shared ledger, goals, TCKG (Temporal Causal Knowledge Graph), agent memory.
- **Agent Zero**: Core autonomous agent with multi-agent swarm support, terminal/desktop/browser tools.
- **Dragonscale API**: Custom orchestration, BrowserConnector integration, Telegram, goal/hermes management, swarm coordination.

Extend with skills from SKILLS_CATALOG.md, integrate BrowserConnector.py.

For production: Deploy API to Vercel, use managed Postgres, run Agent Zero on VPS.

Connect to grokzilla.site for dashboard control.