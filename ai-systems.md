# AI Systems

Self-hosted assistants, agent protocols, and memory.

Section page: [AI Systems: Self-Hosted Assistants, RAG, and Local Infrastructure](https://www.glukhov.org/ai-systems/)

[Index of all sections](README.md)

## Architecture

- [A2A Streaming and Async Tasks for Long-Running Agent Workflows](https://www.glukhov.org/ai-systems/architecture/a2a-streaming-async-task-lifecycle/) — How to design A2A protocol streaming, async tasks, push notifications, and long-running agent workflows with SSE, polling, HITL states, and production observability.
- [AI Assistant Architecture: LLM, Memory, Tools, Routing, Observability](https://www.glukhov.org/ai-systems/architecture/ai-assistant-architecture/) — A deep technical guide to AI assistant architecture: LLMs, memory, tools, routing, and observability, with real tradeoffs, failure modes, and design patterns.
- [Decision LLMs: When a Model Should Decide — and When It Shouldn't](https://www.glukhov.org/ai-systems/architecture/decision-llms-when-models-should-decide/) — LLMs answer well and decide badly. A decision rubric: five decision roles, routing to the smallest competent model, and verifiable decisions.
- [Multi-Agent Orchestration Patterns: A Practical Guide](https://www.glukhov.org/ai-systems/architecture/multi-agent-orchestration-patterns/) — Six proven multi-agent orchestration patterns for production AI systems: orchestrator-worker, sequential pipeline, fan-out, hierarchical, swarm, and mesh.
- [Polling Agents in AI Assistants: 11 Implementation Patterns](https://www.glukhov.org/ai-systems/architecture/polling-agents-ai-assistants-implementation-patterns/) — A practical guide to polling agent patterns in AI assistants — schedulers, queues, webhooks, durable workflows, state management, and tradeoffs for production systems.
- [What Is the A2A Protocol? Agent Cards and Tasks Explained](https://www.glukhov.org/ai-systems/architecture/a2a-protocol-explained/) — A practical guide to the A2A Protocol for AI agents, explaining Agent Cards, tasks, messages, parts, artifacts, discovery, and architecture tradeoffs.

## Comparisons

- [Google A2A Protocol in 2026: Adoption, Hype, and Reality](https://www.glukhov.org/ai-systems/comparisons/a2a-protocol-2026-adoption/) — Is Google's A2A protocol actually useful in 2026? A practical review of A2A adoption, MCP overlap, security concerns, and when to use agent-to-agent protocols in production.
- [OpenClaw vs Hermes Agent: Stars, Downloads & Usage 2026](https://www.glukhov.org/ai-systems/comparisons/openclaw-hermes-alternatives-popularity/) — Full data: 20 AI agent repos ranked by GitHub stars, OpenRouter daily tokens, npm/PyPI downloads, CVE history, ecosystem size, and Reddit sentiment.
- [Self-Hosted Deep Research Systems: 12 Tools Compared](https://www.glukhov.org/ai-systems/comparisons/deep-research-with-ai/) — Compare 12 self-hosted Deep Research systems: GPT Researcher, Onyx, Open WebUI, Khoj, Vane and more. Architectures, local LLM, RAG, licenses.

## OpenClaw

- [OpenClaw: Examining a Self-Hosted AI Assistant as a Real System](https://www.glukhov.org/ai-systems/openclaw/) — A case-study exploration of OpenClaw — a self-hosted AI assistant system that integrates local LLMs, retrieval, memory, routing, and observability into a cohesive local infrastructure.
- [Anthropic Closes Claude Loophole for Agent Tools](https://www.glukhov.org/ai-systems/openclaw/anthropic-claude-subscription-agent-tools/) — Anthropic blocks Claude subscriptions in agent tools like OpenClaw, forcing API usage. What changed, who is affected, and practical workarounds.
- [NemoClaw practical guide for secure OpenClaw operations in 2026](https://www.glukhov.org/ai-systems/openclaw/nemoclaw/) — NemoClaw runs OpenClaw inside OpenShell with policy driven network control, routed inference, and lifecycle tooling. This guide covers quickstart, operations, and troubleshooting.
- [OpenClaw Plugins — Ecosystem Guide and Practical Picks](https://www.glukhov.org/ai-systems/openclaw/plugins/) — Native OpenClaw plugins, workspace and global extension directories, CLI lifecycle and safety rails, plus mature picks.
- [OpenClaw Production Setup Patterns with Plugins and Skills](https://www.glukhov.org/ai-systems/openclaw/production-setup/) — Real world OpenClaw production setups combining plugins and skills by user type, with practical architecture patterns for reliability, workflows, and scale.
- [OpenClaw Quickstart: Install with Docker (Ollama GPU or Claude + CPU)](https://www.glukhov.org/ai-systems/openclaw/quickstart/) — Install OpenClaw in minutes with Docker. Run locally with Ollama (GPU) or use Claude Sonnet 4.6 (CPU-only). Includes setup, model config, testing, and troubleshooting.
- [OpenClaw Rise and Fall — Timeline and Real Reasons Behind the Collapse](https://www.glukhov.org/ai-systems/openclaw/openclaw-rise-and-fall-timeline/) — How OpenClaw grew to 247,000 GitHub stars in weeks and then collapsed when Anthropic blocked Claude subscription access. Full timeline and analysis of the real causes.
- [OpenClaw Skills Ecosystem and Practical Production Picks](https://www.glukhov.org/ai-systems/openclaw/skills/) — A practical guide to OpenClaw skills, ClawHub, install and removal flows, security tradeoffs, and the skills worth using in real work today.

## Hermes

- [Hermes AI Assistant - Install, Setup, Workflow, and Troubleshooting](https://www.glukhov.org/ai-systems/hermes/) — Self-hosted Hermes Agent install quickstart config workflow and troubleshooting, with provider setup, tool sandboxing, gateway tips, and diagnostics.
- [Hermes Agent CLI cheat sheet — commands, flags, and slash shortcuts](https://www.glukhov.org/ai-systems/hermes/hermes-agent-cli-cheatsheet/) — Quick reference for Hermes Agent CLI. Install path, hermes chat and -z one-shots, model, gateway, skills, memory, logs, profiles, and slash shortcuts.
- [Hermes Agent Memory System: How Persistent AI Memory Actually Works](https://www.glukhov.org/ai-systems/hermes/hermes-agent-memory-system/) — A deep technical guide to Hermes Agent's memory architecture — from bounded 2-file core memory to 8 pluggable external providers.
- [Hermes Agent Skill Authoring — SKILL.md Structure and Best Practices](https://www.glukhov.org/ai-systems/hermes/authoring-hermes-skill/) — Author Hermes skills with YAML frontmatter, progressive disclosure, conditional activation, secrets versus config, and index troubleshooting.
- [Hermes Agent: Headless Server + Remote Desktop Setup](https://www.glukhov.org/ai-systems/hermes/hermes-remote-backend-desktop/) — Run Hermes Agent on a headless server with remote desktop access. Covers hermes serve, gateway setup, systemd, and network security.
- [Hermes AI Assistant Skills for Real Production Setups](https://www.glukhov.org/ai-systems/hermes/production-setup/) — A profile-first guide to Hermes Agent configuration and skills for engineers, researchers, operators, and executive workflows in production.
- [Hermes Voice Control from Your Phone](https://www.glukhov.org/ai-systems/hermes/hermes-voice-control/) — Set up Hermes voice control on Telegram and Discord using local Whisper and free Edge TTS. Includes setup, tuning tips, examples, and troubleshooting.
- [Hindsight for Hermes Agent: Self-Hosted Memory with Local LLMs](https://www.glukhov.org/ai-systems/hermes/hindsight-for-hermes-local-llms/) — Deploy Hindsight for Hermes Agent with Docker and PostgreSQL. Wire local Qwen3 embeddings and reranking through Ollama or llama.cpp, with no cloud inference.
- [How to Migrate from OpenClaw to Hermes Agent Safely](https://www.glukhov.org/ai-systems/hermes/migrate-from-openclaw/) — Migrate OpenClaw to Hermes Agent with dry-run checks, precise memory and skill mapping, secret handling, channel cutover, rollback, and manual fixes.
- [Kanban in Hermes Agent for Self Hosted LLM Workflows](https://www.glukhov.org/ai-systems/hermes/kanban-in-hermes/) — Set up Hermes Kanban to safely schedule multi agent tasks on self hosted LLMs using a dispatcher daemon, rate limits and cron based batching.
- [Mnemosyne for Hermes Agent: Local Memory Quickstart](https://www.glukhov.org/ai-systems/hermes/mnemosyne-memory/) — Install Mnemosyne as a local Hermes memory provider, configure recall and retention, and inspect the SQLite store.

## Memory

- [Agent Memory Providers Compared — Honcho, Mem0, Hindsight, and Five More](https://www.glukhov.org/ai-systems/memory/agent-memory-providers/) — Compare eight agent memory backends for Hermes, OpenClaw, and other agents — Honcho, OpenViking, Mem0, Hindsight, Holographic, RetainDB, ByteRover, Supermemory — dependencies, self-hosting, and activation.
- [Choosing the Right LLM for Cognee: Local Ollama Setup](https://www.glukhov.org/ai-systems/memory/choosing-right-llm-for-cognee-on-ollama/) — Comparing qwen3:14b, gpt-oss20b, devstral 2 small, and others
- [Memory Systems in AI Assistants](https://www.glukhov.org/ai-systems/memory/memory-systems-in-ai-assistants/) — How to design short-term, long-term, and structured memory for AI assistants, with retrieval mechanics, tradeoffs, failure modes, and real patterns from OpenAI, LangGraph, Hermes, and OpenClaw.
- [Self-Hosting Cognee: LLM Performance Tests](https://www.glukhov.org/ai-systems/memory/selfhosting-cognee-quickstart-llms-comparison/) — Testing Cognee RAG framework with local LLMs - gpt-oss, qwen3, deepseek-r1, and others. Real-world results, configs, and performance insights.
- [Self-Reinforcing Memory Loops in AI Agents: Causes and Fixes](https://www.glukhov.org/ai-systems/memory/self-reinforcing-memory-loops/) — Agent memory can turn model inferences into future evidence. How those loops form, why they matter, and which write-path controls limit them.

## MCP

- [A2A vs MCP: Do AI Agents Really Need Both Protocols?](https://www.glukhov.org/ai-systems/mcp/a2a-vs-mcp-ai-agent-protocols/) — A practical comparison of A2A and MCP for AI agent systems, covering tools, agents, architecture patterns, overlap, security, and when to use both.
- [Agent Skills vs MCP Servers: Decision Framework](https://www.glukhov.org/ai-systems/mcp/agent-skills-vs-mcp-servers-decision-framework/) — Choose between Agent Skills and MCP servers using connectivity, credentials, context cost, security, and a practical thin-server pattern for AI agents.
- [Building MCP Servers in Python: WebSearch & Scrape](https://www.glukhov.org/ai-systems/mcp/mcp-server-in-python/) — A comprehensive guide to implementing Model Context Protocol (MCP) servers in Python with practical examples for web search and scraping capabilities, enabling seamless AI tool integration.
- [Model Context Protocol (MCP), and notes on implementing MCP server in Go](https://www.glukhov.org/ai-systems/mcp/mcp-server-in-go/) — The Model Context Protocol (MCP), how to implement an MCP server in Go, including message structure, protocol specifications, libraries and example implementation.
