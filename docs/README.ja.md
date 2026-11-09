# pi-web

[English](https://github.com/aiti-ai/pi-web/blob/main/README.md) | [中文文档](https://github.com/aiti-ai/pi-web/blob/main/docs/README.zh-CN.md) | [Русский](https://github.com/aiti-ai/pi-web/blob/main/docs/README.ru.md)

**AITI Web**（`@aiti-ai/pi-web`）は、[pi コーディングエージェント](https://github.com/earendil-works/pi) 向けのブラウザーワークベンチで、[aiti](https://aiti.pw/) ツールエコシステムの基盤です：ページインジェクション型 AI デバッグツール、AI エージェント向け MCP ブリッジ、そして大規模なバンドル拡張機能ライブラリ。

このリポジトリはプレースホルダーです。ワークベンチ本体——`@aiti-ai/pi-web` ディストリビューション（上流 [pi-web](https://github.com/agegr/pi-web) のフォークで、63 以上のバンドル拡張機能を同梱）、そのドキュメント、aiti エコシステム全体（拡張機能・pi パッケージ・ツール群）——はすべて **[aiti-ai/aiti-ai](https://github.com/aiti-ai/aiti-ai)** モノレポにあります：

- ワークベンチ（インストール・ドキュメント・ソース）：<https://github.com/aiti-ai/aiti-ai>
- TUI ブリッジ：[@aiti-ai/pi-web-bridge](https://github.com/aiti-ai/aiti-ai/tree/main/pi-plugins/pi-web-bridge)——`/web` で pi TUI セッションをワークベンチにブリッジ（ライブ表示 + 双方向 IO）
- サイト：<https://aiti.pw>

### aiti-ai 配下の公開リポジトリ

- **[aiti-ai](https://github.com/aiti-ai/aiti-ai)** —— モノレポ本体：AITI Web ディストリビューション（63 以上のバンドル拡張機能）、pi パッケージ、ツール群（上流 pi-web のフォーク）
- **[aiti-aigrdpwasm](https://github.com/aiti-ai/aiti-aigrdpwasm)** —— Web 版 RDP クライアント（Go WASM）；[nakagami/grdpwasm](https://github.com/nakagami/grdpwasm) のフォークで、xrdp/GDS/CredSSP の修正を含む——npm パッケージ `@aiti-ai/grdpwasm`
- **[pi-subagents](https://github.com/aiti-ai/pi-subagents)** —— 非同期サブエージェント委譲用 pi 拡張の上流フォーク（トランケーション・アーティファクト・セッション共有）
- **[pi-models-respect](https://github.com/aiti-ai/pi-models-respect)** —— pi パッケージ：明示的に設定したモデルだけを表示（旧名称、`@aiti-ai/pi-models-combo` に統合）

## License

MIT
