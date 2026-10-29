<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/header-dunkel.svg">
  <img alt="Awesome Agent OS" src=".github/assets/header-hell.svg" width="100%">
</picture>

<p align="center"><a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat2.svg"></a> <img alt="71 picks" src="https://img.shields.io/badge/picks-71-1B8DBE?style=flat-square"> <img alt="5.8M stars combined" src="https://img.shields.io/badge/stars_combined-5.8M-1B8DBE?style=flat-square"> <a href="https://github.com/Wellux/awesome-agent-os/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/Wellux/awesome-agent-os?style=flat-square&color=95969A"></a> <img alt="license CC0" src="https://img.shields.io/badge/license-CC0-95969A?style=flat-square"></p>

<h3 align="center">Your AI forgets you every morning. These repos fix that.</h3>

Hand-picked open-source building blocks for your own **personal AI operating system**: one brain, many agents, clear rules. Picked from 5,000+ starred repos and sorted by the job they do in the stack, not by hype.

## Start here

No time for 71 repos? These 4 cover the whole loop. Add the rest when you feel the gap.

| Role | Pick | Why |
|:--|:--|:--|
| **Builder** | [claude-code](https://github.com/anthropics/claude-code) `★ 150.6k` | writes and ships the code for everything else |
| **Companion** | [hermes-agent](https://github.com/NousResearch/hermes-agent) `★ 253.3k` | lives on your machine and answers on chat |
| **Hands** | [servers](https://github.com/modelcontextprotocol/servers) `★ 91.2k` | connects agents to files, apps and APIs |
| **Pipes** | [n8n](https://github.com/n8n-io/n8n) `★ 207.2k` | runs the routine so agents keep the thinking |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/map-dunkel.svg">
  <img alt="Map of the 11 categories" src=".github/assets/map-hell.svg" width="100%">
</picture>

## Contents

- [Agents that live with you](#agents-that-live-with-you) · 6
- [Coding agents](#coding-agents) · 6
- [Cockpits and control planes](#cockpits-and-control-planes) · 8
- [Skills and playbooks](#skills-and-playbooks) · 7
- [Tools and MCP](#tools-and-mcp) · 8
- [Memory and second brain](#memory-and-second-brain) · 8
- [Models and runtimes](#models-and-runtimes) · 6
- [Automation and pipelines](#automation-and-pipelines) · 6
- [Web, browser and data](#web-browser-and-data) · 6
- [Home, body and devices](#home-body-and-devices) · 5
- [Guardrails and security](#guardrails-and-security) · 5

## Agents that live with you

The always-on agents you talk to on chat, phone and desktop.

- **[hermes-agent](https://github.com/NousResearch/hermes-agent)** `★ 253.3k` · Self-improving personal agent with memory, skills and 20+ chat channels.
- **[openclaw](https://github.com/openclaw/openclaw)** `★ 391.8k` · The agent that really does things, on any OS and platform.
- **[nanobot](https://github.com/HKUDS/nanobot)** `★ 49k` · Ultra-light personal agent framework with web UI, memory and MCP.
- **[gbrain](https://github.com/garrytan/gbrain)** `★ 30.8k` · An opinionated brain for OpenClaw and Hermes agents.
- **[NemoClaw](https://github.com/NVIDIA/NemoClaw)** `★ 22.7k` · Run Hermes, OpenClaw and friends inside a secured sandbox.
- **[AstrBot](https://github.com/AstrBotDevs/AstrBot)** `★ 41.8k` · Agent assistant that plugs into many messengers and models.

<sub><a href="#contents">back to contents</a></sub>

## Coding agents

Agents that read, write and ship code with you.

- **[claude-code](https://github.com/anthropics/claude-code)** `★ 150.6k` · Anthropic's agentic coding tool in the terminal.
- **[codex](https://github.com/openai/codex)** `★ 129k` · OpenAI's coding agent that runs locally.
- **[opencode](https://github.com/anomalyco/opencode)** `★ 213.1k` · Open-source coding agent for the terminal, any model.
- **[cline](https://github.com/cline/cline)** `★ 70.3k` · Autonomous coding agent inside your editor.
- **[gemini-cli](https://github.com/google-gemini/gemini-cli)** `★ 107.3k` · Gemini as an agent in your terminal.
- **[pi](https://github.com/earendil-works/pi)** `★ 114.8k` · A minimal, hackable coding agent harness.

<sub><a href="#contents">back to contents</a></sub>

## Cockpits and control planes

Where you see what your agents do and step in.

- **[mission-control](https://github.com/builderz-labs/mission-control)** `★ 6.3k` · Mission control dashboard for agent fleets.
- **[orca](https://github.com/stablyai/orca)** `★ 91.2k` · Run a fleet of parallel coding agents with your own subscriptions.
- **[AionUi](https://github.com/iOfficeAI/AionUi)** `★ 33.5k` · 24/7 cowork app for Claude Code, Codex, OpenClaw, Hermes and more.
- **[cc-switch](https://github.com/farion1231/cc-switch)** `★ 143.7k` · Switch providers and configs across Claude Code, Codex and more.
- **[hermes-webui](https://github.com/nesquena/hermes-webui)** `★ 18.9k` · Use Hermes from the browser or your phone.
- **[claudecodeui](https://github.com/siteboon/claudecodeui)** `★ 14.1k` · Claude Code, Codex and others on mobile and web.
- **[claude-code-router](https://github.com/musistudio/claude-code-router)** `★ 37.7k` · Route agents across models and providers.
- **[paperclip](https://github.com/paperclipai/paperclip)** `★ 101.3k` · Orchestrate a whole company of agents with goals and budgets.

<sub><a href="#contents">back to contents</a></sub>

## Skills and playbooks

Teach agents how to do a job once, reuse it forever.

- **[skills](https://github.com/anthropics/skills)** `★ 180.8k` · The official Agent Skills repository.
- **[superpowers](https://github.com/obra/superpowers)** `★ 298.5k` · A battle-tested skill library and workflow for coding agents.
- **[agent-skills](https://github.com/addyosmani/agent-skills)** `★ 106k` · Production-grade engineering skills for coding agents.
- **[obsidian-skills](https://github.com/kepano/obsidian-skills)** `★ 49.5k` · Teach your agent Obsidian, Markdown, Bases and Canvas.
- **[skills](https://github.com/mattpocock/skills)** `★ 288.9k` · Practical skills for TypeScript-heavy work.
- **[awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)** `★ 77k` · A curated list of Claude skills.
- **[awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)** `★ 55.6k` · Commands, hooks and workflows for Claude Code.

<sub><a href="#contents">back to contents</a></sub>

## Tools and MCP

Give agents hands: apps, browsers, files and APIs.

- **[servers](https://github.com/modelcontextprotocol/servers)** `★ 91.2k` · Reference MCP servers.
- **[fastmcp](https://github.com/PrefectHQ/fastmcp)** `★ 28.1k` · The fast, Pythonic way to build MCP servers.
- **[github-mcp-server](https://github.com/github/github-mcp-server)** `★ 33.6k` · GitHub's official MCP server.
- **[playwright-mcp](https://github.com/microsoft/playwright-mcp)** `★ 38.1k` · Browser automation for agents over MCP.
- **[serena](https://github.com/oraios/serena)** `★ 30.2k` · Semantic code retrieval and editing as an MCP toolkit.
- **[composio](https://github.com/ComposioHQ/composio)** `★ 30.5k` · Hundreds of app integrations for agents.
- **[context7](https://github.com/upstash/context7)** `★ 63k` · Up-to-date library docs for coding agents.
- **[awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** `★ 96.3k` · The big list of MCP servers.

<sub><a href="#contents">back to contents</a></sub>

## Memory and second brain

So your agents stop asking the same questions.

- **[mem0](https://github.com/mem0ai/mem0)** `★ 67.1k` · Universal memory layer for AI agents.
- **[claude-mem](https://github.com/thedotmack/claude-mem)** `★ 100.3k` · Persistent memory across Claude Code sessions.
- **[khoj](https://github.com/khoj-ai/khoj)** · Self-hostable AI second brain.
- **[logseq](https://github.com/logseq/logseq)** `★ 45.2k` · Local-first knowledge graph and outliner.
- **[LightRAG](https://github.com/HKUDS/LightRAG)** `★ 40.1k` · Simple and fast graph-based retrieval.
- **[graphrag](https://github.com/microsoft/graphrag)** `★ 36.3k` · Graph-based RAG over your own documents.
- **[mempalace](https://github.com/MemPalace/mempalace)** `★ 59.5k` · Long-term memory palace for agents.
- **[qmd](https://github.com/tobi/qmd)** `★ 30.4k` · Local search engine for your Markdown notes.

<sub><a href="#contents">back to contents</a></sub>

## Models and runtimes

Run models locally or route between providers.

- **[ollama](https://github.com/ollama/ollama)** `★ 183k` · Run open models locally with one command.
- **[whisper.cpp](https://github.com/ggml-org/whisper.cpp)** `★ 54.3k` · Fast local speech-to-text.
- **[litellm](https://github.com/BerriAI/litellm)** `★ 61.1k` · One API for 100+ model providers, with budgets.
- **[vllm](https://github.com/vllm-project/vllm)** `★ 93.7k` · High-throughput model serving.
- **[LocalAI](https://github.com/mudler/LocalAI)** `★ 49.5k` · Drop-in local replacement for the OpenAI API.
- **[unsloth](https://github.com/unslothai/unsloth)** `★ 77.9k` · Fine-tune open models faster with less memory.

<sub><a href="#contents">back to contents</a></sub>

## Automation and pipelines

Deterministic workflows for the routine, agents for the thinking.

- **[n8n](https://github.com/n8n-io/n8n)** `★ 207.2k` · Workflow automation with native AI nodes, self-hostable.
- **[activepieces](https://github.com/activepieces/activepieces)** `★ 25k` · Open-source automation with MCP support.
- **[dify](https://github.com/langgenius/dify)** `★ 158.4k` · Build and run agentic workflows visually.
- **[langflow](https://github.com/langflow-ai/langflow)** `★ 155.6k` · Visual builder for agents and RAG flows.
- **[prefect](https://github.com/PrefectHQ/prefect)** `★ 24k` · Orchestrate data and AI pipelines in Python.
- **[self-hosted-ai-starter-kit](https://github.com/n8n-io/self-hosted-ai-starter-kit)** `★ 15.3k` · n8n, Ollama and Qdrant in one compose file.

<sub><a href="#contents">back to contents</a></sub>

## Web, browser and data

Let agents read the web like a person, politely.

- **[browser-use](https://github.com/browser-use/browser-use)** `★ 117.8k` · Make websites accessible for AI agents.
- **[firecrawl](https://github.com/firecrawl/firecrawl)** `★ 191k` · Turn websites into LLM-ready data.
- **[crawl4ai](https://github.com/unclecode/crawl4ai)** `★ 85.4k` · Open-source, LLM-friendly web crawler.
- **[Scrapling](https://github.com/D4Vinci/Scrapling)** `★ 87.2k` · Adaptive, undetectable-by-design web scraping in Python.
- **[skyvern](https://github.com/Skyvern-AI/skyvern)** `★ 23.2k` · Browser workflows driven by vision and LLMs.
- **[playwright](https://github.com/microsoft/playwright)** `★ 97.6k` · Reliable browser automation for every engine.

<sub><a href="#contents">back to contents</a></sub>

## Home, body and devices

Your OS does not end at the screen.

- **[core](https://github.com/home-assistant/core)** `★ 91.5k` · Local-first home automation.
- **[omi](https://github.com/BasedHardware/omi)** `★ 13.7k` · Open-source AI wearable that remembers your conversations.
- **[open-wearables](https://github.com/the-momentum/open-wearables)** `★ 2.6k` · Unified API for wearable health data.
- **[awesome-quantified-self](https://github.com/woop/awesome-quantified-self)** `★ 2.8k` · Tools to track and understand yourself.
- **[MentraOS](https://github.com/Mentra-Community/MentraOS)** `★ 2.4k` · Open OS for smart glasses.

<sub><a href="#contents">back to contents</a></sub>

## Guardrails and security

Autonomy needs a kill switch.

- **[personal-security-checklist](https://github.com/lissy93/personal-security-checklist)** `★ 22.5k` · Practical privacy and security checklist.
- **[CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries)** `★ 33.7k` · Concise security guidance for builders.
- **[trivy](https://github.com/aquasecurity/trivy)** `★ 38.4k` · Find vulnerabilities and secrets in code and containers.
- **[falco](https://github.com/falcosecurity/falco)** `★ 9.5k` · Runtime security that watches what processes do.
- **[headscale](https://github.com/juanfont/headscale)** `★ 44.6k` · Self-hosted control server for a private Tailscale network.

<sub><a href="#contents">back to contents</a></sub>

## How picks are made

1. Starred because it was useful, not because it trended.
2. Open source with a clear license. Check the license before you build on it.
3. One job per entry. If two do the same job, the simpler one wins.

Star counts as of 13 October 2026.

## Contribute

Know a repo that does one job better? Open an issue with the link and one sentence on the job it does. Picks that fit the rules above go in with credit.

## Why this list exists

It is the shopping list behind **myOS**, an open-source personal operating system for you and your agents. myOS opens on **1 January 2027**. Watch <a href="https://github.com/Wellux">Wellux</a> to see it land, and star this list if it saved you an afternoon.


---

<p align="center"><sub>Curated by <a href="https://github.com/Wellux">Marco Mengele · Wellux</a> · From leak to solution. One block at a time.</sub></p>
