# Hi, I'm Mert Başar 👋

.NET developer in Istanbul, focused on **AI agent runtime infrastructure**: the process, delivery, recovery and protocol plumbing that lets agents run as real, observable software.

By day I build enterprise systems at **Metro İstanbul** (CRM, notification platforms, RabbitMQ/SignalR, Docker). Outside of that I build open-source agent infrastructure under [Basar Labs](https://basarlabs.com.tr).

## 🔧 What I'm building

**[acp-net](https://github.com/MertBasar0/acp-net)**: ACP-compatible agent process runtime, diagnostics and testing tools for .NET. Stable on NuGet.
[![NuGet](https://img.shields.io/nuget/v/Acp.Net.Process?label=Acp.Net.Process)](https://www.nuget.org/packages/Acp.Net.Process)

The .NET ACP SDKs model the protocol; Acp.Net is the process layer underneath: lifecycle, WSL/native bridging, environment shaping, preflight checks, transcript recording, and process-boundary tests with deterministic fake agents. Listed in the official [Agent Client Protocol community libraries](https://agentclientprotocol.com).

**[ceviz](https://github.com/MertBasar0/ceviz)**: Apple Watch + iPhone control surface for a self-hosted OpenClaw agent. Speak a job on your wrist, read the summary, continue on your phone. Local-first; open beta on [TestFlight](https://testflight.apple.com/join/nEdn2Np2) · [overview](https://basarlabs.com.tr/ceviz/)

**[ceviz-pusula](https://github.com/MertBasar0/ceviz-pusula)**: optional model-routing plugin for Ceviz. It stays on the agent's default model and escalates only after conversational misses.

## 🦞 Open source

**[OpenClaw](https://github.com/openclaw/openclaw)**: 25+ merged PRs across agent failover, auth and credential handling, subagent completion delivery, restart recovery and platform services. Credited in the release notes of [2026.9.7](https://docs.openclaw.ai/releases/2026.9.7), 2026.9.9, 2026.10.1, 2026.10.5, 2026.10.7 and 2026.10.8. Selected:

- [#157658](https://github.com/openclaw/openclaw/pull/157658): ACP runs are no longer cancelled after an in-process Gateway restart
- [#151121](https://github.com/openclaw/openclaw/pull/151121): `doctor` repairs tool policies that set both `allow` and `alsoAllow` (crash-loop fix)
- [#158954](https://github.com/openclaw/openclaw/pull/158954): the macOS app no longer restarts a slow-starting Gateway in a loop after reboot
- [#153340](https://github.com/openclaw/openclaw/pull/153340): opt-in Decision-model filtering that omits tools on conversational turns while preserving required tools (co-developed with the maintainers)
- [#175886](https://github.com/openclaw/openclaw/pull/175886) / [#176567](https://github.com/openclaw/openclaw/pull/176567): realtime voice and GPT-Live Talk honor the managed proxy on egress-restricted hosts (Node and Bun)
- [#149000](https://github.com/openclaw/openclaw/pull/149000): Codex threads settled in `systemError` resume on a fresh client
- [#163817](https://github.com/openclaw/openclaw/pull/163817) / [#163756](https://github.com/openclaw/openclaw/pull/163756): session titles on single-slot model servers; Discord thread subagent results no longer marked failed
- [#131220](https://github.com/openclaw/openclaw/pull/131220) / [#129754](https://github.com/openclaw/openclaw/pull/129754): credential-source provenance across model attempts; pending subagent completions survive restart
- [#92011](https://github.com/openclaw/openclaw/pull/92011) · [#78086](https://github.com/openclaw/openclaw/pull/78086) · [#80801](https://github.com/openclaw/openclaw/pull/80801) · [#75280](https://github.com/openclaw/openclaw/pull/75280): fallback re-execution guard (P1 incident fix), state-aware failover, forced re-login and fallback skip cache, durable main-session delivery
- Co-authored: [#147456](https://github.com/openclaw/openclaw/pull/147456), [#109541](https://github.com/openclaw/openclaw/pull/109541), [#166425](https://github.com/openclaw/openclaw/pull/166425), [#180288](https://github.com/openclaw/openclaw/pull/180288), [#180541](https://github.com/openclaw/openclaw/pull/180541), [#180576](https://github.com/openclaw/openclaw/pull/180576)
- [Full list →](https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3AMertBasar0+is%3Amerged)

**Agent protocols**

- [a2a-dotnet](https://github.com/a2aproject/a2a-dotnet) (official A2A .NET SDK): registry-backed extension negotiation ([#548](https://github.com/a2aproject/a2a-dotnet/pull/548)) with follow-up helpers and docs ([#562](https://github.com/a2aproject/a2a-dotnet/pull/562), [#563](https://github.com/a2aproject/a2a-dotnet/pull/563), [#564](https://github.com/a2aproject/a2a-dotnet/pull/564), [#567](https://github.com/a2aproject/a2a-dotnet/pull/567)); fix for a valid null result that threw on delete ([#433](https://github.com/a2aproject/a2a-dotnet/pull/433)); service-discovery client docs ([#535](https://github.com/a2aproject/a2a-dotnet/pull/535))
- [a2a-itk#44](https://github.com/a2aproject/a2a-itk/pull/44): added the .NET SDK to the A2A Integration Testing Kit matrix and dashboard
- [agent-client-protocol#1428](https://github.com/agentclientprotocol/agent-client-protocol/pull/1428): Acp.Net in the official .NET community libraries
- [openclaw/ocm](https://github.com/openclaw/ocm): [#110](https://github.com/openclaw/ocm/pull/110), [#131](https://github.com/openclaw/ocm/pull/131)

## ✍️ Writing

On [Medium](https://medium.com/@mertbasar30), in English and Turkish:

- [The Model Isn't the Breakthrough. The Architecture Might Be.](https://medium.com/@mertbasar30/the-model-isnt-the-breakthrough-the-architecture-might-be-03a98ec1935b)
- [Can a Decision Model Safely Remove Tools from an AI Agent?](https://medium.com/@mertbasar30/can-a-decision-model-safely-remove-tools-from-an-ai-agent-ff6803e22619)
- [ACP Is Not One Protocol: A Chronological Guide to Four Different ACPs](https://medium.com/@mertbasar30/acp-is-not-one-protocol-a-chronological-guide-to-four-different-acps-and-where-acp-net-fits-41952bfef80e)
- [Same Seed, Matching Initial State: Is the Velocity the Model Sees Correct?](https://medium.com/@mertbasar30/same-seed-matching-initial-state-is-the-velocity-the-model-sees-correct-157f4defbb34)
- 🇹🇷 [Harness Konsepti](https://medium.com/@mertbasar30/yapay-zekan%C4%B1n-cam-duvar%C4%B1-a%C5%9Fmas%C4%B1-harness-konsepti-fc4142e329e0) · [Thread, Task ve Process](https://medium.com/@mertbasar30/thread-task-ve-process-kavramlar%C4%B1-2c330291917f) · [.NET Generic Host](https://medium.com/@mertbasar30/net-generic-host-f4e4b633cbca)

## 📫 Links

[LinkedIn](https://www.linkedin.com/in/mert-ba%C5%9Far-335b68100/) · [Medium](https://medium.com/@mertbasar30) · [Basar Labs](https://basarlabs.com.tr)
