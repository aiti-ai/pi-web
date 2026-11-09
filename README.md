# pi-web

[中文文档](https://github.com/aiti-ai/pi-web/blob/main/docs/README.zh-CN.md) | [日本語](https://github.com/aiti-ai/pi-web/blob/main/docs/README.ja.md) | [Русский](https://github.com/aiti-ai/pi-web/blob/main/docs/README.ru.md)

**AITI Web** (`@aiti-ai/pi-web`) is a browser workbench for the [pi coding agent](https://github.com/earendil-works/pi) — and the base of the [aiti](https://aiti.pw/) tooling ecosystem: page-injected debugging tools, an MCP bridge for AI agents, and a large library of bundled extensions.

This repository is a placeholder. The workbench itself — the `@aiti-ai/pi-web` distribution (an upstream [pi-web](https://github.com/agegr/pi-web) fork that ships 63+ bundled extensions), its documentation, and the whole aiti ecosystem (extensions, pi packages, tooling) — lives in the **[aiti-ai/aiti-ai](https://github.com/aiti-ai/aiti-ai)** monorepo:

- Workbench (install, docs, source): <https://github.com/aiti-ai/aiti-ai>
- TUI bridge: [@aiti-ai/pi-web-bridge](https://github.com/aiti-ai/aiti-ai/tree/main/pi-plugins/pi-web-bridge) — bridge a pi TUI session to the workbench with `/web` (live view + bidirectional IO)
- Site: <https://aiti.pw>

### Public repositories under aiti-ai

- **[aiti-ai](https://github.com/aiti-ai/aiti-ai)** — the monorepo: the AITI Web distribution (63+ bundled extensions), pi packages, and tooling (fork of upstream pi-web)
- **[aiti-aigrdpwasm](https://github.com/aiti-ai/aiti-aigrdpwasm)** — Web-based RDP client (Go WASM); fork of [nakagami/grdpwasm](https://github.com/nakagami/grdpwasm) with xrdp/GDS/CredSSP fixes — npm package `@aiti-ai/grdpwasm`
- **[pi-subagents](https://github.com/aiti-ai/pi-subagents)** — upstream fork of the pi extension for async subagent delegation (truncation, artifacts, session sharing)
- **[pi-models-respect](https://github.com/aiti-ai/pi-models-respect)** — pi package: keep only the models you explicitly configured (legacy name, superseded by `@aiti-ai/pi-models-combo`)

## License

MIT
