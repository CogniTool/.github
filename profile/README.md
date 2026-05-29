
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=CogniTool;AI-Native+Developer+Tools;MCP+Servers+%26+Agent+Infrastructure">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=15803D&center=true&vCenter=true&width=600&lines=CogniTool;AI-Native+Developer+Tools;MCP+Servers+%26+Agent+Infrastructure">
  <img alt="CogniTool" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=CogniTool;AI-Native+Developer+Tools;MCP+Servers+%26+Agent+Infrastructure">
</picture>

<p align="center">
  <a href="https://github.com/CogniTool"><img src="https://img.shields.io/badge/org-CogniTool-00cc66?style=flat-square&logo=github" alt="GitHub Org"></a>
  <a href="https://www.npmjs.com/org/cognitool"><img src="https://img.shields.io/badge/npm-@cognitool-cb3837?style=flat-square&logo=npm" alt="npm"></a>
  <img src="https://img.shields.io/badge/built%20for-AI%20agents-6e3df5?style=flat-square" alt="AI Agents">
  <img src="https://img.shields.io/badge/protocol-MCP-00b894?style=flat-square" alt="MCP">
</p>

---

## 🧠 What is CogniTool?

**CogniTool builds infrastructure for the AI agent era.** We create Model Context Protocol (MCP) servers that give AI agents — Claude, Cursor, Copilot, Gemini, and beyond — real capabilities: access to databases, financial data, GIS systems, and domain-specific knowledge.

Think of us as **"npm for AI agents"** — every repo is a plug-and-play toolset that makes AI agents useful in the real world.

---

## 🗺️ Our Stack

| Layer | What we build | Status |
|-------|---------------|--------|
| **Data Layer** | MCP servers connecting AI agents to real-world data | 🟢 Active |
| **Protocol Layer** | Reference implementations & standards for vertical domains | 🟡 Emerging |
| **Platform Layer** | Marketplace, registry, one-click install for AI agent tools | 🔮 Future |

---

## 📦 MCP Servers

### 🇻🇳 [Vietnam Finance MCP](https://github.com/CogniTool/vietnam-finance-mcp)
> Personal finance & accounting for Vietnamese users — 17 tools including tax calculation (PIT/VAT/insurance), VAT invoice generation, budgeting, financial reports, and currency conversion.
```
npx vietnam-finance-mcp
```

### 🗄️ [PostgreSQL Advanced MCP](https://github.com/CogniTool/postgres-advanced-mcp)
> Schema explorer, query analyzer, migration tools, and performance insights for PostgreSQL databases.
```
npx @cognitool/postgres-advanced-mcp
```

### 🗺️ [GIS Maps MCP](https://github.com/CogniTool/gis-maps-mcp)
> Geocoding, spatial analysis, PostGIS queries, map tiles, and Vietnam province/administrative boundary data.
```
npx @cognitool/gis-maps-mcp
```

---

## 🚀 Why CogniTool?

### The Problem
AI agents (Claude, Cursor, Copilot) are powerful **reasoning engines** — but they're **blind** to real-world data. They can't check your bank balance, query your database, or analyze your geography data. Every developer is building the same bridges over and over.

### Our Solution
**Pre-built, open-source MCP servers** that give AI agents immediate access to domain data. Install one command, and your AI agent goes from "helpful chatbot" to "actual assistant."

### The Vision
A world where every AI agent can access any data source through a standard protocol — and CogniTool is the library everyone reaches for first.

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────┐
│  AI Agents (Claude, Cursor, Copilot…)   │
└──────────────┬──────────────────────────┘
               │ Model Context Protocol
               │ (stdio / SSE / HTTP)
┌──────────────▼──────────────────────────┐
│  CogniTool MCP Servers                  │
│  ┌──────────┬──────────┬──────────────┐ │
│  │ Finance  │ Postgres │     GIS      │ │
│  │ (VN tax, │ (schema, │ (geocoding,  │ │
│  │  budget, │  query,  │  PostGIS,    │ │
│  │  invoice)│  migrate)│  map tiles)  │ │
│  └──────────┴──────────┴──────────────┘ │
└──────────────┬──────────────────────────┘
               │
┌──────────────▼──────────────────────────┐
│  Real-World Data & APIs                 │
│  (Banks, Databases, GeoServer, SBV…)    │
└─────────────────────────────────────────┘
```

---

## 📈 Roadmap

- [x] Core MCP servers (Finance, Postgres, GIS)
- [x] GitHub Org & Profile
- [ ] npm packages — one-command install
- [ ] MCP marketplace listings (smithery.ai, mcp.so, cursor.directory)
- [ ] SMS bank parser for Vietnam Finance MCP
- [ ] Tax XML export for Vietnam tax filing
- [ ] Streaming transport (SSE) for remote deployments
- [ ] Plugin system for community connectors
- [ ] CogniTool Registry — discover & install all tools in one place

---

## 🤝 Contributing

We build in the open. Every MCP server is open-source (MIT).

- 💡 **Add a bank SMS pattern** for Vietnam Finance MCP
- 🐛 **Report a bug** — agents should handle edge cases gracefully
- 🔧 **Fix a tool** — PRs welcome across all repos
- 🆕 **Propose a new MCP server** — what domain should AI agents access next?

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/phongnd93">Phong Nguyen</a> and AI agents 🤖</sub>
</p>
