# Awesome Agent Security

A curated list of resources, models, and tools for securing AI agents.

## Contents

- [Security Models and Architecture](#security-models-and-architecture)
- [Security Skills and Review Frameworks](#security-skills-and-review-frameworks)
- [Security Guides and Practices](#security-guides-and-practices)
- [Sandboxing and Runtime Security](#sandboxing-and-runtime-security)
- [Monitoring and Red Teaming](#monitoring-and-red-teaming)

## Security Models and Architecture

- [The Agent Access Model](https://blog.cloudflare.com/the-agent-access-model/) — Cloudflare's reference architecture for task-scoped agent security, built around short-lived bound credentials, continuous mediation, least-privilege access, stateful trust reduction, and auditable activity.

## Security Skills and Review Frameworks

- [Skill Vetter](https://clawhub.ai/spclaudehome/skills/skill-vetter) — A security-first vetting protocol for reviewing AI agent skills before installation, covering source reputation, suspicious code patterns, permission scope, and risk classification.
- [SlowMist Agent Security](https://github.com/slowmist/slowmist-agent-security) — SlowMist's structured security review framework for agent skills, MCP servers, repositories, URLs, documents, on-chain addresses, products, and shared recommendations.

## Security Guides and Practices

- [OpenClaw Security Practice Guide](https://github.com/slowmist/openclaw-security-practice-guide) — An agent-facing zero-trust hardening guide for high-privilege OpenClaw deployments, with pre-action controls, runtime permission checks, nightly audits, recovery practices, and red-team validation.

## Sandboxing and Runtime Security

- [OpenShell](https://github.com/NVIDIA/OpenShell) — NVIDIA's open-source runtime for autonomous agents, providing sandboxed execution and declarative policies for filesystem, network, process, credential, and inference controls. ([Documentation](https://docs.nvidia.com/openshell/about/overview))
- [Claw Patrol](https://github.com/denoland/clawpatrol) — An agent security gateway that inspects network traffic and applies HCL rules to block or require approval for actions against services such as databases and Kubernetes.

## Monitoring and Red Teaming

- [ClawSec Monitor](https://github.com/chrisochrisochriso-cmyk/clawsec-monitor) — A transparent HTTP/HTTPS proxy for inspecting agent traffic and detecting secret leakage, sensitive-file access, command injection, reverse shells, and suspicious outbound connections.
- [Meridian Portal](https://github.com/chrisochrisochriso-cmyk/meridian-portal) — An AI agent security honeypot that uses canary tokens to test prompt injection, social engineering, false attestations, confabulation, and unsupported verification claims.

## Contributing

Contributions are welcome. Please submit resources that have a clear and substantive focus on AI agent security.
