# AgentLab — engineering environment by DC ESCRYPT

AgentLab is an engineering environment for building and operating AI-agent systems: agent orchestration, human-in-the-loop approvals, MCP integrations, backend services, and the infrastructure that keeps them running.

## Public components

- **[Raposa Aval](https://github.com/agentlabbusiness/raposa-mcp)** — human approval for AI agents: a named person approves or rejects, silence is not consent, hash-chained audit log. `pip install raposa` (SDK: [raposa-sdk](https://github.com/agentlabbusiness/raposa-sdk)), n8n integration: [n8n-nodes-raposa](https://github.com/agentlabbusiness/n8n-nodes-raposa). Listed as an n8n community node.
- **[Intesta](https://github.com/agentlabbusiness/intesta-mcp)** — MCP server for the Intesta trust registry: check a domain's A0–A4 trust level and verified facts before an agent acts. Refuse, don't guess.

## Engineering focus

- AI agents and LLM infrastructure: orchestration, model routing, evaluation gates
- MCP servers and agent tooling (Python, TypeScript)
- Backend services and API platforms
- Cybersecurity, automation and monitoring: hardened agent runtimes, fail2ban, audit trails, launchd/systemd watchdogs
- Developer tooling: homegrown dashboards, intake/task tracking, deploy pipelines

## Work model

Most projects are developed in private repositories. The contribution graph below shows real activity, including anonymized private contributions — no code or repository names are exposed.