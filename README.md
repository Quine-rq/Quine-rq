<div align="center">

# Hi, I'm Quine

**Building agents that follow through.**

Agent engineering · Reusable skills · Evidence-driven evaluation

[Projects](https://github.com/Quine-rq?tab=repositories) · [Functional Acceptance](https://github.com/Quine-rq/functional-acceptance) · [Contributions](https://github.com/pulls?q=is%3Apr+author%3AQuine-rq) · [VERIO](https://myverio.com)

</div>

---

I build tools and workflows that help coding agents carry a task through to a verifiable user result. My current work focuses on **agent skills, functional acceptance, and failure recovery**.

I'm also the Founder & Lead Engineer of **[VERIO（星眸）](https://myverio.com)**, building across mobile apps, real-time services, AI, and connected hardware.

我关注 Agent 如何把事情真正做完：理解目标、执行任务、验证结果，并在失败后恢复。

## Featured project

### [Functional Acceptance](https://github.com/Quine-rq/functional-acceptance)

**The feature is built. Does it work for the user?**

A skill for coding agents to verify features through real user flows, collect evidence, and leave repeatable checks.

- **User outcomes:** check the promised result against explicit expectations.
- **Visible evidence:** distinguish **PASS**, **FAIL**, and **UNVERIFIED**.
- **Repeatable journeys:** examples cover CSV export, SQLite workflows, and a browser/server/database flow.
- **Honest evaluation:** retain missed checks and failed attempts alongside successful runs.

*Early development. Broader agent compatibility and reliable full-flow coverage are still being evaluated.*

[Read the project →](https://github.com/Quine-rq/functional-acceptance#readme) · [中文介绍 →](https://github.com/Quine-rq/functional-acceptance/blob/main/README.zh-CN.md)

## Agent ecosystem contributions

Recent pull requests to **[Hermes Desktop](https://github.com/fathah/hermes-desktop)**, a desktop companion for Hermes Agent:

| Area | Proposed improvement |
| :--- | :--- |
| Model identity | [Preserve distinct endpoints when adding models over SSH](https://github.com/fathah/hermes-desktop/pull/945) |
| Remote context | [Honor the active remote model's context length](https://github.com/fathah/hermes-desktop/pull/946) |
| Session lifecycle | [Reflect native archive and restore state in local session lists](https://github.com/fathah/hermes-desktop/pull/947) |
| Configuration | [Preserve Windows CRLF platform settings](https://github.com/fathah/hermes-desktop/pull/943) |

These are submitted contributions; each PR links to its current review and merge status.

## How I build

**Define the outcome → Trace the real flow → Exercise failure paths → Verify with evidence**

I treat recovery, concurrency, weak networks, and state consistency as part of the feature. A successful command is one observation; the user's result is the acceptance criterion.

**Working stack:** Python · TypeScript · Flutter / Dart · Java / Spring Boot · SQLite · WebSocket · BLE

---

Interested in agent skills or reproducible acceptance cases? [Open a discussion through an issue](https://github.com/Quine-rq/functional-acceptance/issues).
