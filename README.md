# AI Agent Architecture in 2026

> MCP-First Strategy + Right Framework for the Right Context

A reference architecture for building enterprise AI agent systems in 2026. Framework-agnostic, MCP-standardised, built for regulated industries (FSI, healthcare, government).

## The Problem

Everyone is building AI agents. Most are coupling their business logic to a specific model and framework. When the model improves (it will) or the framework evolves (it will), they rebuild from scratch.

**The solution:** Invest in the layers that endure. Standardise on the layers that don't.

## The 6-Layer Architecture

```
┌──────────────────────────────────────────────────────────────────────┐
│  6. APPLICATIONS / AGENTS                                            │
│     Security · Licensing · Migration · Governance · CFO Agent        │
├──────────────────────────────────────────────────────────────────────┤
│  5. SKILLS / DOMAIN IP                              ★ INVEST HERE   │
│     Methodologies · Knowledge Vault · SOW Templates · Best Practices │
├──────────────────────────────────────────────────────────────────────┤
│  4. TOOLS / CAPABILITIES                                             │
│     CRM · SAP · ServiceNow · Email · Search · Reporting · APIs       │
├──────────────────────────────────────────────────────────────────────┤
│  3. MCP INTEROPERABILITY                            ★ STANDARDISE   │
│     Databases · APIs · SharePoint · ServiceNow · SAP · Custom        │
├──────────────────────────────────────────────────────────────────────┤
│  2. FOUNDATION MODELS                               ↕ REPLACEABLE   │
│     GPT · Claude · Gemini · Llama · DeepSeek                         │
├──────────────────────────────────────────────────────────────────────┤
│  1. COMPUTE / CLOUD                                 ↕ COMMODITY     │
│     Azure · AWS · Google Cloud · NVIDIA GPUs                         │
└──────────────────────────────────────────────────────────────────────┘
```

## Two Stacks, One Standard

This architecture applies differently depending on your context:

### AI Startup (Build for Portability)

- **Framework:** LangGraph or OpenAI Agents SDK (keep framework replaceable)
- **Knowledge:** Obsidian vault, personal notes, reusable skills
- **Tools:** GitHub, CRM APIs, email, search, Notion, Jira
- **Strategy:** Build MCP servers and Skills. Keep framework replaceable.

### Enterprise on Microsoft (Build for Scale)

- **Framework:** Microsoft Agent Framework (MAF) + Copilot Studio + Azure AI Foundry
- **Knowledge:** Architecture standards, SOW templates, compliance frameworks, SharePoint governance
- **Tools:** D365, ServiceNow, SharePoint, SAP, Azure, M365, reporting
- **Strategy:** Use MAF + Copilot Studio + Foundry. Invest in domain IP.

### What Converges

Both stacks standardise on **MCP** (Layer 3) and invest in **Skills / Domain IP** (Layer 5). The framework and model layers differ — and that's fine, because they're designed to be swapped.

## Investment Priority

| Priority | Layer | Durability | Action |
|---|---|---|---|
| 1 | Skills / Domain IP | Highest | Build methodologies, templates, knowledge bases |
| 2 | MCP Layer | High | Standardise all integrations on MCP |
| 3 | Tools / Capabilities | Medium | Build reusable tool interfaces |
| 4 | Framework | Low-Medium | Choose one, don't over-invest |
| 5 | Models | Low | Use the best available, stay portable |
| 6 | Compute / Cloud | Lowest | Commodity, choose by price and compliance |

## The Durable Layer

Layer 5 (Skills / Domain IP) is where long-term business value lives:

- **Architecture Standards** — How you design systems for your industry
- **SOW Templates** — Proven engagement structures
- **Compliance Frameworks** — APRA, EOS, regulatory knowledge
- **Methodologies** — Your way of working, codified
- **Knowledge Bases** — Institutional memory, searchable and agent-ready

These assets compound over time. They don't deprecate when GPT-5 ships or when LangGraph releases a breaking change.

## Knowledge Lifecycle

```
Create Knowledge          → Obsidian, personal research, notes
       ↓
Productise Knowledge      → Structure, package, version, make reusable
       ↓
Govern & Share            → Standards, permissions, enterprise lifecycle
       ↓
Execute Knowledge         → Agents and Copilot deliver outcomes
```

## The Rule

> Choose your framework. Standardise on MCP. Invest in Skills and Knowledge Assets.

Models change. Frameworks change. **Skills and IP endure.**

## Architecture Diagrams

See the `/diagrams` folder for high-resolution architecture visuals:

- `ai-agent-architecture-2026.png` — Full 6-layer overview
- `layer-4-6-deep-dive.png` — Detailed comparison of startup vs enterprise stacks

## Related Resources

- [Awesome Azure MCP](https://github.com/jeffreychu-au/awesome-azure-mcp) — Curated MCP resources for Azure
- [Supabase Keep-Alive Action](https://github.com/jeffreychu-au/supabase-keepalive-action) — Keep your Supabase projects alive
- [MCP Specification](https://spec.modelcontextprotocol.io/) — The protocol standard

## Author

[Jeffrey Chu](https://github.com/jeffreychu-au) — Sydney-based Cloud & AI Solution Architect. 12+ years in enterprise cloud, hybrid infrastructure, and digital transformation for regulated industries. Specialising in Azure, MCP, and agentic AI.

## Licence

MIT
