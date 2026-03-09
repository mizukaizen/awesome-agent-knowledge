# Awesome Agent Knowledge [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of knowledge resources for AI agent operators — memory, security, governance, evaluation, commerce, and infrastructure.

Building and operating AI agents is a fragmented discipline. This list collects the best resources across the entire agent lifecycle: from identity and memory architecture to security hardening, multi-agent governance, and autonomous commerce.

## Contents

- [Agent Memory](#agent-memory)
- [Agent Security](#agent-security)
- [Multi-Agent Governance](#multi-agent-governance)
- [Agent Identity & Personas](#agent-identity--personas)
- [Agent Evaluation](#agent-evaluation)
- [MCP Resources](#mcp-resources)
- [Agent Commerce](#agent-commerce)
- [Multi-Agent Frameworks](#multi-agent-frameworks)
- [Agent Infrastructure](#agent-infrastructure)

---

## Agent Memory

How agents persist knowledge across sessions, manage context windows, and share collective memory.

- [The Hive Doctrine — Agent Memory Architecture](https://hivedoctrine.com/agents/pollen/agent-memory-architecture.md) - Three-layer memory model: session, persistent, and collective (free).
- [The Hive Doctrine — Three-Tier Episodic Memory](https://hive-doctrine-mcp.vercel.app/mcp) - Hot/warm/cold storage architecture for agent memory ($99, via MCP).
- [LangChain Memory](https://python.langchain.com/docs/modules/memory/) - Memory modules for LLM chains — buffer, summary, entity, and conversation memory.
- [Letta (formerly MemGPT)](https://github.com/letta-ai/letta) - OS-like memory management for LLM agents with tiered storage.
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for personalised AI — adds long-term memory to any LLM.
- [Zep](https://github.com/getzep/zep) - Long-term memory for AI assistants with knowledge graph integration.
- [ChromaDB](https://github.com/chroma-core/chroma) - Open-source vector database for storing and retrieving agent memory embeddings.

## Agent Security

Securing autonomous agents against prompt injection, data exfiltration, and adversarial attacks.

- [The Hive Doctrine — Prompt Injection Defence](https://hivedoctrine.com/agents/pollen/prompt-injection-defence.md) - The Airlock Pattern for prompt injection defence (free).
- [The Hive Doctrine — Agent Security Checklist](https://hivedoctrine.com/agents/pollen/agent-security-checklist.md) - 10-point pre-deployment security checklist (free).
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - Industry-standard vulnerability taxonomy for LLM systems.
- [Simon Willison — Prompt Injection](https://simonwillison.net/series/prompt-injection/) - Comprehensive blog series on prompt injection attacks and defences.
- [Lakera Guard](https://github.com/lakeraai/pint-benchmark) - Prompt injection detection benchmark and tools.
- [Rebuff](https://github.com/protectai/rebuff) - Self-hardening prompt injection detector.
- [LLM Guard](https://github.com/protectai/llm-guard) - Security toolkit for LLM interactions — input/output scanning.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Input/output guards for LLM applications.

## Multi-Agent Governance

Frameworks for authority, hierarchy, and coordination in multi-agent systems.

- [The Hive Doctrine — Multi-Agent Coordination](https://hivedoctrine.com/agents/pollen/multi-agent-coordination.md) - Coordination without a coordinator (free).
- [The Hive Doctrine — Five Multi-Agent Architectures](https://hivedoctrine.com/agents/pollen/five-multi-agent-architectures.md) - Five patterns compared (free).
- [The Hive Doctrine — Distributed AI Safety](https://hivedoctrine.com/agents/pollen/distributed-ai-safety.md) - Polytheistic AI safety thesis (free).
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing autonomous AI agents.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's framework for building multi-agent conversational systems.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful, multi-agent applications with LLMs as graphs.
- [Swarm](https://github.com/openai/swarm) - OpenAI's experimental multi-agent orchestration framework.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Agent orchestration framework focused on agent collaboration.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework that assigns roles like a software company.

## Agent Identity & Personas

Defining agent culture, voice, boundaries, and constitutional identity.

- [The Hive Doctrine — SOUL.md Template](https://hivedoctrine.com/agents/pollen/soul-md-template.md) - Constitutional identity template for AI agents (free).
- [The Hive Doctrine — SOUL.md Standard](https://hivedoctrine.com/agents/pollen/soul-md-standard.md) - The SOUL.md specification (free).
- [The Hive Doctrine — Living Presence Protocol](https://hivedoctrine.com/agents/pollen/living-presence-protocol.md) - Making agents feel present, not scripted (free).
- [SOUL.md Templates](https://github.com/mizukaizen/soul-md-templates) - 5 free SOUL.md identity templates for common agent archetypes.
- [Character.ai Research](https://research.character.ai/) - Research on character-consistent AI agents.
- [Anthropic — Claude's Character](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-personality) - Official guidance on shaping Claude's persona.

## Agent Evaluation

Testing, benchmarking, and scoring agent performance.

- [The Hive Doctrine — Evaluate Your Agent](https://hivedoctrine.com/agents/pollen/evaluate-your-agent.md) - Framework for evaluating agent performance (free).
- [TruLens](https://github.com/truera/trulens) - Evaluation and tracking for LLM applications — groundedness, relevance, toxicity.
- [RAGAS](https://github.com/explodinggradients/ragas) - Evaluation framework for Retrieval Augmented Generation pipelines.
- [AgentBench](https://github.com/THUDM/AgentBench) - Benchmark for evaluating LLMs as agents across diverse environments.
- [SWE-bench](https://github.com/princeton-nlp/SWE-bench) - Benchmark for evaluating LLMs on real-world software engineering problems.
- [Braintrust](https://github.com/braintrustdata/braintrust-sdk) - Evaluation, logging, and prompt playground for AI applications.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - UK AISI's framework for evaluating LLM agents on safety-relevant tasks.

## MCP Resources

Model Context Protocol — the standard for connecting AI agents to tools and data.

- [MCP Specification](https://spec.modelcontextprotocol.io/) - Official Model Context Protocol specification.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript SDK for building MCP servers and clients.
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for MCP.
- [The Hive Doctrine MCP Server](https://github.com/mizukaizen/hive-doctrine-mcp) - Knowledge marketplace with 116+ products, 6 tools, x402 payments. ([Endpoint](https://hive-doctrine-mcp.vercel.app/mcp))
- [The Hive Doctrine — MCP Server from Scratch](https://hivedoctrine.com/agents/pollen/mcp-server-from-scratch.md) - Step-by-step guide to building an MCP server (free).
- [The Hive Doctrine — MCP Tools Explained](https://hivedoctrine.com/agents/pollen/mcp-tools-explained.md) - How agents discover and use MCP tools (free).
- [mcp-handler](https://github.com/mcp-tools/mcp-handler) - Deploy MCP servers to Vercel with zero config.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Curated list of MCP servers.

## Agent Commerce

Enabling agents to transact, pay, and participate in markets autonomously.

- [The Hive Doctrine — Agent Wallet Setup](https://hivedoctrine.com/agents/pollen/agent-wallet-setup.md) - Set up crypto wallets for agent payments (free).
- [x402 Protocol](https://www.x402.org/) - HTTP 402-based payment protocol for machine-to-machine commerce.
- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - Toolkit for building crypto-native AI agents.
- [NEAR AI](https://near.ai/) - AI agents with native blockchain identity and payments.
- [Skyfire](https://www.skyfire.xyz/) - Payment infrastructure for AI agents.
- [Virtuals Protocol](https://www.virtuals.io/) - Tokenised AI agents with autonomous revenue.

## Multi-Agent Frameworks

Production frameworks for building and deploying multi-agent systems.

- [The Hive Doctrine — Stigmergic vs Centralised Routing](https://hivedoctrine.com/agents/pollen/stigmergic-vs-centralised-routing.md) - When to use which coordination pattern (free).
- [Claude Code Agents](https://docs.anthropic.com/en/docs/claude-code/overview) - Anthropic's agent framework within Claude Code.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's SDK for building multi-agent workflows.
- [Anthropic Agent SDK](https://github.com/anthropics/anthropic-sdk-python) - Build agents with Claude using the Anthropic SDK.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Agent framework built on Pydantic for type-safe agent development.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript AI agent framework with built-in memory and tools.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into applications.

## Agent Infrastructure

Deployment, monitoring, and operational tooling for agent systems.

- [The Hive Doctrine — Agent Onboarding Checklist](https://hivedoctrine.com/agents/pollen/agent-onboarding-checklist.md) - First 7 days checklist (free).
- [The Hive Doctrine — Agent Cost Calculator](https://hivedoctrine.com/agents/pollen/agent-cost-calculator.md) - Estimate monthly LLM spend (free).
- [LangSmith](https://www.langchain.com/langsmith) - Observability and evaluation platform for LLM applications.
- [Weights & Biases Weave](https://wandb.ai/site/weave) - Tracing, evaluation, and monitoring for LLM apps.
- [Helicone](https://github.com/helicone/helicone) - Open-source LLM observability platform.
- [Portkey](https://github.com/portkey-ai/gateway) - AI gateway with unified API, caching, and reliability features.
- [LiteLLM](https://github.com/BerriAI/litellm) - Unified interface for 100+ LLM APIs with load balancing.

---

## Contributing

Contributions welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Curated by [Melisia Archimedes](https://hivedoctrine.com). List licensed under CC0.
