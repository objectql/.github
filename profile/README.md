<h1 align="center">ObjectStack</h1>

<p align="center"><b>A complete business system in 16k tokens.</b></p>

AI agents write business apps as typed, validated metadata — objects, views,
flows, permissions — and the runtime derives the database, REST API, admin UI,
and MCP tools, enforcing permissions and audit on every call. That metadata is
your **business ontology**: an open, versioned definition of how your business
works — small enough for an agent to hold in context, reason about, and
refactor whole, and yours to keep.

## Two ways to build & ask

|  | **Build & ask with Claude Code** | **Build & ask online** |
|---|---|---|
| Where | In your repo, with your coding agent (Claude Code, Cursor, Copilot …) | In the browser — no toolchain, nothing to deploy |
| What | [**ObjectStack**](https://github.com/objectstack-ai/objectstack) — the open-source framework: protocol, kernel, CLI, SDK, and the production runtime | [**ObjectOS**](https://www.objectos.ai) — the commercial platform: AI Builder, governance, operations |
| Terms | Apache-2.0, self-host anywhere | Cloud (we operate it) or Enterprise (self-managed) |
| Start | `npm create objectstack@latest` | [objectos.ai](https://www.objectos.ai) |

## Repositories

| | Repo | What it is |
|---|---|---|
| 🏗️ | [objectstack](https://github.com/objectstack-ai/objectstack) | The open-source framework — protocol (`@objectstack/spec`), microkernel, CLI, SDK, and production runtime. Apache-2.0, no open-core asterisks. |
| ☁️ | [objectos](https://github.com/objectstack-ai/objectos) | Public home of the commercial platform — documentation ([docs.objectos.ai](https://docs.objectos.ai)), issue tracker, and trademark policy. |
| 🧩 | [objectui](https://github.com/objectstack-ai/objectui) | The Console / Studio UI layer. |
| 📇 | [hotcrm](https://github.com/objectstack-ai/hotcrm) | A full enterprise CRM in ~2,000 lines of typed metadata — the reference app. [Try it on StackBlitz](https://stackblitz.com/github/objectstack-ai/hotcrm) in ~30s, no install. |

## Try it in 60 seconds

```bash
npm create objectstack@latest my-app && cd my-app
npx os dev --ui   # → http://localhost:3000/_console/
```

Open the project in Claude Code (or any coding agent) and describe what the
business needs — the scaffold ships with the AI skills bundle and an
`AGENTS.md`, so the agent starts with the protocol's rules already loaded.
Prefer clicking to coding? Start online at [objectos.ai](https://www.objectos.ai).

---

<p align="center">
🌐 <a href="https://objectstack.ai">objectstack.ai</a> ·
📚 <a href="https://objectstack.ai/docs">Framework Docs</a> ·
🏢 <a href="https://docs.objectos.ai">ObjectOS Docs</a> ·
✍️ <a href="https://www.objectos.ai/en/blog/">Blog</a>
</p>
