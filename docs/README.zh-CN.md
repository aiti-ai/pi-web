# pi-web

[English](https://github.com/aiti-ai/pi-web/blob/main/README.md) | [日本語](https://github.com/aiti-ai/pi-web/blob/main/docs/README.ja.md) | [Русский](https://github.com/aiti-ai/pi-web/blob/main/docs/README.ru.md)

**AITI Web**（`@aiti-ai/pi-web`）是 [pi 编程智能体](https://github.com/earendil-works/pi)的浏览器工作台，也是 [aiti](https://aiti.pw/) 工具生态的基座：页面注入式 AI 调试工具、面向 AI agent 的 MCP 桥，以及庞大的内置扩展库。

本仓库为占位说明页。工作台本体——`@aiti-ai/pi-web` 发行版（上游 [pi-web](https://github.com/agegr/pi-web) 的 fork，内置 63+ 个扩展随包分发）、其文档以及整个 aiti 生态（扩展、pi 包、工具链）——全部在 **[aiti-ai/aiti-ai](https://github.com/aiti-ai/aiti-ai)** monorepo 中：

- 工作台（安装、文档、源码）：<https://github.com/aiti-ai/aiti-ai>
- TUI 桥：[@aiti-ai/pi-web-bridge](https://github.com/aiti-ai/aiti-ai/tree/main/pi-plugins/pi-web-bridge)——用 `/web` 把 pi TUI 会话桥接到工作台（实时查看 + 双向 IO）
- 官网：<https://aiti.pw>

### aiti-ai 下的公开仓库

- **[aiti-ai](https://github.com/aiti-ai/aiti-ai)** —— monorepo 主仓：AITI Web 发行版（63+ 内置扩展）、pi 包与工具链（上游 pi-web 的 fork）
- **[aiti-aigrdpwasm](https://github.com/aiti-ai/aiti-aigrdpwasm)** —— Web 版 RDP 客户端（Go WASM）；[nakagami/grdpwasm](https://github.com/nakagami/grdpwasm) 的 fork，含 xrdp/GDS/CredSSP 修复——npm 包 `@aiti-ai/grdpwasm`
- **[pi-subagents](https://github.com/aiti-ai/pi-subagents)** —— pi 异步子代理扩展的上游 fork（截断、工件、会话共享）
- **[pi-models-respect](https://github.com/aiti-ai/pi-models-respect)** —— pi 包：只保留你显式配置的模型（旧名，已被 `@aiti-ai/pi-models-combo` 取代）

## License

MIT
