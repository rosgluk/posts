# LLM Architecture

Routing, guardrails, cost, and prompt design for systems that call models.

Section page: [LLM Architecture: System Design for Production AI](https://www.glukhov.org/llm-architecture/)

[Index of all sections](README.md)

## Model routing

- [Model Routing: Stop Using One Model for Everything](https://www.glukhov.org/llm-architecture/model-routing/model-routing-strategies/) — Routing tasks to the right model saves money and cuts latency. Capability-based, cost-aware, and latency-aware strategies with working Python code.
- [Multi-Model System Design: When One Model Isn't Enough](https://www.glukhov.org/llm-architecture/model-routing/multi-model-system-design/) — Architecture patterns for orchestrating multiple LLMs — sequential, parallel, hierarchical, and ensemble approaches with working Python code and tradeoff analysis.

## Guardrails

- [A2A and MCP Agent Security: Identity, Delegation, and Audit Trails](https://www.glukhov.org/llm-architecture/guardrails/a2a-mcp-agent-security/) — Secure A2A and MCP agent systems with identity, auth, delegation controls, gateways, registries, audit trails, and a production checklist for multi-agent deployments.
- [LLM Guardrails in Practice: What Actually Works](https://www.glukhov.org/llm-architecture/guardrails/llm-guardrails-in-practice/) — Input validation, output filtering, and safety mechanisms that protect your LLM system without breaking it. Patterns with real Python examples and compliance notes.

## Cost

- [Cost Optimization for LLM Systems: Where the Money Actually Goes](https://www.glukhov.org/llm-architecture/cost-optimization/cost-optimization-for-llm-systems/) — Token budgeting, fallback models, and caching strategies that cut LLM API bills. With real numbers, hardware break-even analysis, and working Python code.

## Prompts

- [Writing effective prompts for LLMs](https://www.glukhov.org/llm-architecture/prompt-engineering/writing-effective-llm-prompts/) — Several points to pay attention to when writing prompts for LLMs - to make them effective
