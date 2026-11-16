# Config examples

Ready-to-copy configs for the Seedara MCP server (`https://seedara.ai/api/mcp`, Streamable HTTP, OAuth). Every client opens a Seedara window on first use: sign in and press **Allow**. No API keys.

| Client | File | Where it goes |
|---|---|---|
| Claude (claude.ai, Claude app) | [claude/README.md](claude/README.md) | Customize → Connectors → Add custom connector |
| ChatGPT | [chatgpt/README.md](chatgpt/README.md) | Settings → Developer mode, then Plugins → Create MCP App |
| Claude Code | [claude-code/install.sh](claude-code/install.sh) | Run in a terminal |
| Cursor | [cursor/mcp.json](cursor/mcp.json) | `~/.cursor/mcp.json` or `.cursor/mcp.json` in a project |
| VS Code | [vscode/.mcp.json](vscode/.mcp.json) | `.mcp.json` at the project root |
| Windsurf / Devin | [windsurf-devin/mcp_config.json](windsurf-devin/mcp_config.json) | `~/.config/devin/mcp_config.json`, on Windows `%APPDATA%\devin\mcp_config.json` |
| Codex | [codex/install.sh](codex/install.sh), [codex/config.toml](codex/config.toml) | Terminal, or `~/.codex/config.toml` |
| Antigravity | [antigravity/mcp_config.json](antigravity/mcp_config.json) | `~/.gemini/config/mcp_config.json` |
| Gemini CLI | [gemini-cli/install.sh](gemini-cli/install.sh) | Run in a terminal, then `/mcp auth seedara` |
| Clients with local servers only | [mcp-remote/mcp.json](mcp-remote/mcp.json) | Your client's MCP config; `mcp-remote` opens the sign-in window |

If a file already has other servers, add the `seedara` entry next to them instead of replacing the file.

Step-by-step instructions for every client: [README](../README.md#connect-your-agent) and [seedara.ai/mcp](https://seedara.ai/mcp).
