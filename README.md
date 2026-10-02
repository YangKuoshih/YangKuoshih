# Kuoshih (Tony) Yang

**AI Solutions Architect** — enterprise data and AI platforms, and AI enablement.

I turn manual, ad-hoc work into reusable systems other teams adopt. Twenty years in
enterprise data management; the last two building GenAI at a Federal Reserve trading and markets organization —
a production Retrieval-Augmented Generation platform on AWS Bedrock, proofs of
concept for three AI agents, and an internal AI enablement program with 100+ users.

📍 New York, NY · open to relocating to Fremont, CA · open to AI solutions architecture and enterprise AI roles

---

## How I build

I direct coding agents against specs I own — **Claude Code, Codex, Cursor, Kiro,
Antigravity**. The architecture decisions are mine; the keystrokes usually aren't.
Everything below was built that way, and I can defend every design call in it.

---

## Selected work

| Project | What it is |
|---|---|
| **[security-audit](https://github.com/YangKuoshih/security-audit)** | AI security scanner — 60 detection rules (46 GitLeaks-informed secret patterns, 14 OWASP Top 10 checks) plus 15 dangerous-file checks, with LLM-based false-positive filtering. SARIF output for GitHub code scanning. Apache-2.0. |
| **[smart-chef-pantry-concierge](https://github.com/YangKuoshih/buildwithgemini-smart-chef-pantry-concierge)** | Multi-agent culinary concierge on Google ADK — Gemini 2.5 Flash, Vertex AI Agent Runtime, A2A protocol, A2UI components, RAG over a recipe corpus, deployed to Cloud Run. |
| **[MarketSounding](https://github.com/YangKuoshih/MarketSounding)** | Multi-agent market intelligence platform. Enter a macro event — FOMC decision, tariff shock — and five primary-dealer AI agents debate it in real time. |
| **[fathom](https://github.com/YangKuoshih/fathom)** | Autonomous web research agent. Searches, extracts, and synthesizes sourced reports with full traceability and version history. |
| **[Launch-Neo4j-With-Terraform-and-Portainer](https://github.com/YangKuoshih/Launch-Neo4j-With-Terraform-and-Portainer)** | Neo4j Enterprise on AWS via Terraform and Docker, with Portainer and Caddy. A reproducible graph-database sandbox. |
| **[treasury-yield-summarizer](https://github.com/YangKuoshih/treasury-yield-summarizer)** | Treasury yield-curve dashboard with AI-generated market commentary. Next.js, React, shadcn/ui. |

### Also built (private)

- **BeeQuill** — local-first AI meeting notes. LangGraph retrieval agent with confidence
  scoring and query expansion, plus a custom int8-quantized vector store that cut
  embedding storage 4× at sub-100ms retrieval.
  Eight LLM backends behind one adapter, an MCP server, 62 test suites.
- **[Table Tennis SB](https://apps.apple.com/app/id6751131004)** — iOS match
  tracking for competitive junior players. Live on the App Store: four languages,
  in-app purchases, 750+ commits over 16 months. Built it because my son competes on
  the US National Juniors team.
- **Whiskey Sensei** — gamified prompt-engineering platform on AWS Bedrock with API
  Gateway, Cognito, and DynamoDB, provisioned through eight Terraform modules.

---

## Stack

**AI** Agentic orchestration · RAG · AWS Bedrock · Google ADK · LangChain · LangGraph · MCP · vector databases
**Cloud** AWS · Terraform · Databricks · Vertex AI · Cloud Run · Firestore
**Data** Starburst · Neo4j · Collibra · semantic layer · metadata & lineage
**Languages** Python · SQL · TypeScript · React

---

[LinkedIn](https://www.linkedin.com/in/kuoshih-yang)
