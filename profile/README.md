# Nullspace

[Website](https://ns.rocks) · [Docs](https://docs.ns.rocks) · [Quickstart](https://docs.ns.rocks/quickstarts/first-machine) · [Discord](https://discord.gg/nullspace)

Cloud infrastructure for production AI agents.

Give every agent its own machine with the CPU, memory, GPU, tools, and isolation
its work needs.

## Why Nullspace

- **Agent-native.** Run LangGraph, Claude Agent SDK, OpenAI Agents, CrewAI,
  coding agents, or a plain script without rewriting the agent around the
  infrastructure.
- **Isolated.** Today, each machine is a Firecracker microVM with its own
  filesystem, resource limits, network policy, and scoped secrets.
- **Stateful.** Create, execute, hibernate, resume, fork, and destroy machines
  through explicit lifecycle primitives. Availability varies by deployment.
- **Multi-runtime by design.** Firecracker is our starting point, not the
  boundary. Nullspace is designed to compose different virtualization
  technologies behind one machine model, matching each workload to the right
  isolation, performance, and hardware.
- **One interface.** Use the same platform through Python, TypeScript, the CLI,
  MCP, or plain HTTPS.

## Quickstarts

- [First machine](https://docs.ns.rocks/quickstarts/first-machine) — create a
  hosted machine and run code in under five minutes.
- [Bring your own agent](https://docs.ns.rocks/agents/bring-your-own-agent) —
  run an existing agent on the machine it needs.
- [Self-host Nullspace](https://docs.ns.rocks/quickstarts/self-hosted-single-host)
  — install the open-source runtime on one Ubuntu/KVM host.
- [Choose a client](https://docs.ns.rocks/reference/clients) — compare the
  Python and TypeScript SDKs, CLI, local MCP server, and HTTP API.

## Open source, by design

Agent execution is too foundational to be a proprietary black box. The runtime
that executes an agent — and defines what code, credentials, networks, and
machines it can access — should be inspectable, portable, and deployable on
infrastructure you control.

Our goal is for Nullspace to become **the open-source agent execution runtime**:
a shared, extensible layer that composes different virtualization technologies
behind one machine model, from a single host to production cloud.

The public API and protocol contracts, SDKs, CLI, console, documentation, and
single-host runtime are being prepared for release. Until then, start with the
[documentation](https://docs.ns.rocks).

## Stay close

[Join the private beta](https://ns.rocks) · [Discord](https://discord.gg/nullspace) · [Read the docs](https://docs.ns.rocks) · [Explore examples](https://docs.ns.rocks/examples) · [Work with us](https://ns.rocks/careers)

_Private beta._
