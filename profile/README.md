<div align="center">
  <div>
    <a href="https://strandsagents.com">
      <img src="https://strandsagents.com/latest/assets/logo-github.svg" alt="Strands Agents" width="55px" height="105px">
    </a>
  </div>

  <h1>Strands Agents</h1>

  <h2>Build AI agents in just a few lines of code.</h2>

  <p>A model-driven, open source SDK for creating AI agents—from simple conversational assistants to complex autonomous workflows. Python and TypeScript. Apache 2.0.</p>

[![PyPI](https://img.shields.io/pypi/v/strands-agents)](https://pypi.org/project/strands-agents/)
[![npm](https://img.shields.io/npm/v/@strands-agents/sdk)](https://www.npmjs.com/package/@strands-agents/sdk)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Stars](https://img.shields.io/github/stars/strands-agents?style=social)](https://github.com/strands-agents)
[![Discord](https://img.shields.io/badge/Discord-Strands-5865F2?logo=discord&logoColor=white)](https://discord.gg/strands)

[Documentation](https://strandsagents.com/) · [Quick Start](https://strandsagents.com/docs/user-guide/quickstart/overview/) · [Samples](https://github.com/strands-agents/samples) · [Discussions](https://github.com/strands-agents/harness-sdk/discussions)

</div>

---

```python
from strands import Agent
from strands_tools import calculator

agent = Agent(tools=[calculator])
agent("What is the square root of 1764?")
```

```typescript
import { Agent } from "@strands-agents/sdk";

const agent = new Agent();
await agent.invoke("What is the square root of 1764?");
```

```bash
pip install strands-agents strands-agents-tools   # Python
npm install @strands-agents/sdk                    # TypeScript
```

---

### Why Strands?

- **Simple** — A minimal agent loop that just works. No boilerplate, no complex abstractions.
- **Model agnostic** — Amazon Bedrock, Anthropic, OpenAI, Gemini, Ollama, LiteLLM, llama.cpp, and [more](https://strandsagents.com/docs/user-guide/concepts/model-providers/). Swap providers in one line.
- **Multi-agent built in** — Coordinate agents with [Graph](https://strandsagents.com/docs/user-guide/concepts/multi-agent/graph/), [Swarm](https://strandsagents.com/docs/user-guide/concepts/multi-agent/swarm/), and [Workflow](https://strandsagents.com/docs/user-guide/concepts/multi-agent/workflow/) patterns — plus [A2A protocol](https://strandsagents.com/docs/user-guide/concepts/multi-agent/agent-to-agent/) for cross-framework interop.
- **Native MCP** — First-class Model Context Protocol support gives your agents access to thousands of tools.
- **Production ready** — [Deploy](https://strandsagents.com/docs/user-guide/deploy/operating-agents-in-production/) to AWS Lambda, Fargate, EKS, Bedrock AgentCore, Docker, Kubernetes, or Terraform with built-in OpenTelemetry observability.
- **Conversational & beyond** — Streaming, non-streaming, autonomous agents, structured output, and real-time bidirectional audio conversations.

### Community

Strands is built in the open and growing fast. The community contributes [model providers](https://strandsagents.com/docs/community/community-packages/) (Cohere, xAI, Fireworks AI, NVIDIA NIM, vLLM, MLX, SGLang), [session managers](https://strandsagents.com/docs/community/community-packages/) (Valkey/Redis, AgentCore Memory), [tools](https://strandsagents.com/docs/community/community-packages/) (Telegram, HubSpot, Deepgram), and [integrations](https://strandsagents.com/docs/community/integrations/ag-ui/) (AG-UI).

👉 [See all community packages](https://strandsagents.com/docs/community/community-packages/) · [Get your project featured](https://strandsagents.com/docs/community/get-featured/) · [Join the discussion](https://github.com/strands-agents/harness-sdk/discussions)

---

### SDKs

| | |
|---|---|
| **[harness-sdk/strands-py](https://github.com/strands-agents/harness-sdk/tree/main/strands-py)** | Python SDK — the core agent framework |
| **[harness-sdk/strands-ts](https://github.com/strands-agents/harness-sdk/tree/main/strands-ts)** | TypeScript SDK — agents in Node.js and the browser |
| **[evals](https://github.com/strands-agents/evals)** | SDK for testing and benchmarking your agents |

### Get Started

| | |
|---|---|
| **[samples](https://github.com/strands-agents/samples)** | Example agents and real-world use cases |
| **[docs](https://github.com/strands-agents/docs)** | Documentation source for [strandsagents.com](https://strandsagents.com) |
| **[mcp-server](https://github.com/strands-agents/mcp-server)** | Documentation server for building with Strands in your AI coding assistant |

### Go Deeper

| | |
|---|---|
| **[tools](https://github.com/strands-agents/tools)** | Pre-built tools: file I/O, HTTP, shell, code interpreter, and more |
| **[agent-sop](https://github.com/strands-agents/agent-sop)** | Structured prompting for reliable, multi-step agent behavior |

---

### Contributing

We welcome contributions of all kinds — bug reports, feature requests, docs improvements, and code. See our [contributing guide](https://github.com/strands-agents/harness-sdk/blob/main/CONTRIBUTING.md) to get started.

---

### Stay in touch with the team
Come meet the Strands team and other users on [**Discord**](https://discord.com/invite/strands)

---

<div align="center">

**[Website](https://strandsagents.com)** · **[Docs](https://strandsagents.com/docs/user-guide/quickstart/overview/)** · **[Samples](https://github.com/strands-agents/samples)** · **[Discussions](https://github.com/strands-agents/harness-sdk/discussions)**

All projects are Apache 2.0 licensed.

</div>
