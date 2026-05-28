# Claude Marketing Workflow Kit

A demo portfolio repo for Junior Claude AI Systems Builder roles.

This repo shows you understand:
- **Claude Projects / Workspaces** – structured folders with context
- **Claude Skills** – reusable prompt + code packages using progressive disclosure
- **Claude Cowork** – agents that run multi-step tasks
- **Integrations** – Gmail, Google Drive, Notion, Canva via MCP connectors
- **SOPs** – simple documentation teams can follow

## What's inside

### 1. projects/
- `marketing-campaign-project/` – Project instructions stored as .md (not embedded), with brand voice, goals, and sample data.

### 2. skills/
- `social-calendar-skill/` – skill.json + instructions.md + template.csv
- `lead-qualifier-skill/` – reusable skill to score inbound leads
- `report-builder-skill/` – turns spreadsheets into PowerPoint using Claude's code execution

Each skill follows Anthropic's Skills format: name, description, then files loaded only when needed.

### 3. agents/
- `inbox-triage-agent.md` – simple agent that reads Gmail, drafts replies, logs to Notion

### 4. integrations/
- `mcp-notion-gmail.yaml` – example connector config

### 5. sops/
- `SOP-Build-Claude-Project.md` – step-by-step for non-technical teammates

## How this maps to the job post
- Build Claude Projects → see /projects
- Create reusable Skills → see /skills
- Build simple AI agents → see /agents
- Connect workflows → see /integrations
- Document everything → see /sops

Use this as a template, replace with real screenshots and Loom videos when you apply.
