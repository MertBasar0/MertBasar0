# Hi, I'm Mert Başar 👋

.NET developer in Istanbul, focused on **agent runtime infrastructure**.

By day I build enterprise systems at **Metro İstanbul** (CRM, notification platforms, RabbitMQ/SignalR, Docker). The rest of the time I work on the plumbing that lets AI agents run as real, observable processes.

## 🔧 What I'm building

**[acp-net](https://github.com/MertBasar0/acp-net)** — ACP-compatible agent process runtime, diagnostics, and testing tools for .NET.
[![NuGet](https://img.shields.io/nuget/vpre/Acp.Net.Process?label=Acp.Net.Process)](https://www.nuget.org/packages/Acp.Net.Process)

The .NET ACP protocol SDKs model the protocol but leave process launch and platform interop to the consumer. Acp.Net is that layer: process lifecycle, WSL/native runtime bridging, environment shaping, preflight checks, transcript recording, and process-boundary testing with deterministic fake agents. Listed in the official [Agent Client Protocol community libraries](https://agentclientprotocol.com).

## 🦞 Open-source contributions

Contributor to [OpenClaw](https://github.com/openclaw/openclaw) — merged work includes:

- [openclaw#78086](https://github.com/openclaw/openclaw/pull/78086) — state-aware failover and lane suspension for agents
- [openclaw#80801](https://github.com/openclaw/openclaw/pull/80801) — auth: force re-login flag, remediation hints, session-scoped fallback skip cache
- [openclaw#75280](https://github.com/openclaw/openclaw/pull/75280) — durable delivery for main-session messages
- [agent-client-protocol#1428](https://github.com/agentclientprotocol/agent-client-protocol/pull/1428) — added Acp.Net to the official .NET community libraries

Plus open PRs around model fallback safety, subagent completion delivery, and auth billing cooldowns.

## ✍️ Writing

I write (in Turkish) about .NET internals and AI agent architecture on [Medium](https://medium.com/@mertbasar30):

- [Yapay Zekanın "Cam Duvarı" Aşması: Harness Konsepti](https://medium.com/@mertbasar30/yapay-zekan%C4%B1n-cam-duvar%C4%B1-a%C5%9Fmas%C4%B1-harness-konsepti-fc4142e329e0) — why agent harnesses, not chatbots, are the path to an agentic OS
- [Thread, Task ve Process Kavramları](https://medium.com/@mertbasar30/thread-task-ve-process-kavramlar%C4%B1-2c330291917f)
- [.Net Generic Host](https://medium.com/@mertbasar30/net-generic-host-f4e4b633cbca)
- [Azure OpenAI ile Sohbet Robotu Oluşturma](https://medium.com/@mertbasar30/azure-openai-client-k%C3%BCt%C3%BCphanesi-ile-sohbet-robotu-olu%C5%9Fturma-%C3%B6rne%C4%9Fi-gpt-4-azure-openai-version-2-40b55dd365a5)

## 📫 Links

[LinkedIn](https://www.linkedin.com/in/mert-basar-335b68100/) · [Medium](https://medium.com/@mertbasar30) · [Basar Labs](https://basarlabs.com.tr)
