<h1 align="center">ObjectStack</h1>
<p align="center"><b>A complete business system in 16k tokens.</b></p>

AI agents write business apps as typed, validated metadata — objects, views,
flows, permissions — and our runtime turns it into the database, REST API,
admin UI, and MCP tools, with permissions and audit enforced on every call.
That metadata is your **business ontology**: an open, versioned definition
you own, small enough for an agent to hold in context and refactor whole.

## Where to start

| | Repo | What it is |
|---|---|---|
| 🏗️ | [**objectstack**](https://github.com/objectstack-ai/objectstack) | The open-source framework — protocol, kernel, CLI, SDK, and production runtime. Apache-2.0, no open-core asterisks. |
| ☁️ | [**objectos**](https://github.com/objectstack-ai/objectos) | The commercial runtime environment (Cloud & Self-Managed) — AI Builder, governance, operations. Docs & issues live here. |
| 🧩 | [**objectui**](https://github.com/objectstack-ai/objectui) | The Console / Studio UI layer. |
| 📇 | [**hotcrm**](https://github.com/objectstack-ai/hotcrm) | A full enterprise CRM in ~2,000 lines of metadata — the reference app. |

## Try it in 60 seconds

​```bash
npm create objectstack@latest my-app && cd my-app
npx os dev --ui   # → http://localhost:3000/_console/
​```

Point your coding agent (Claude Code, Cursor, Copilot …) at the project and
describe what the business needs — the scaffold ships with the AI skills
bundle and an AGENTS.md, so the agent starts with the rules already loaded.

🌐 [objectstack.ai](https://objectstack.ai) · 📚 [Docs](https://objectstack.ai/docs) · 🏢 [ObjectOS](https://www.objectos.ai) · ✍️ [Blog](https://www.objectos.ai/en/blog/)
