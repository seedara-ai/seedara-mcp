# Seedara MCP server

AI video, image and audio generation inside your AI agent. Connect Seedara to Claude, ChatGPT, Cursor, VS Code or any MCP client and ask for images, video, music and voice right in the conversation. The agent picks the model, tells you the price before it runs and brings back the result.

- **150+ models**: Kling, Veo, Seedance, Runway, Hailuo (video) · Nano Banana, GPT Image, FLUX, Seedream (images) · Suno, ElevenLabs (music and voice)
- **One URL for every agent**, sign-in with OAuth, no API keys
- **The price before every run**; a failed run refunds the credits

```
Server URL: https://seedara.ai/api/mcp
Transport:  Streamable HTTP
Auth:       OAuth (sign in to Seedara and press "Allow")
```

## Connect

Step-by-step instructions for Claude, ChatGPT, Claude Code, Cursor, VS Code, Windsurf / Devin, Codex, Antigravity / Gemini CLI and other clients: **https://seedara.ai/mcp**

Example — Claude (claude.ai or the Claude app):

1. Open **Customize → Connectors**.
2. Press **+ → Add custom connector**, name it `Seedara`, paste `https://seedara.ai/api/mcp` and press **Add**.
3. Press **Connect** next to Seedara, sign in and press **Allow**.
4. In a chat press **+ → Connectors** and turn Seedara on.

Most other clients only need the server URL: add a remote (HTTP) MCP server with `https://seedara.ai/api/mcp` and sign in when asked.

## Tools

| Tool | What it does |
|---|---|
| `generate` | Start a generation: images arrive right in the chat |
| `get_generation` | Status and result of a long run — video, music |
| `list_models` | Image, video and audio models with prices |
| `get_model` | A model's settings: formats, duration, quality |
| `get_price` | The exact price before the run |
| `get_balance` | How many credits are left |
| `list_generations` | Your latest work with links |
| `upload_file` | Your own photo, video or recording — by link or as a file |
| `list_elements` | Your characters, locations, products and voices — the same hero in every shot |

The tools are the same ones the website runs on: moderation, limits and prices are identical.

## Example prompts

- "Make a 5-second vertical video of a cat surfing at sunset with Kling, and tell me the price first."
- "Generate four product shots of this sneaker on a white background." (attach a photo)
- "Write a 30-second upbeat jingle about coffee with Suno."
- "Which video models support 1080p and audio? Compare their prices."

## Pricing

Free to start with 100 credits on sign-up. Plans from $19 a month: https://seedara.ai/pricing

## Links

- Website: https://seedara.ai
- MCP docs: https://seedara.ai/mcp
- Official MCP Registry: `ai.seedara/mcp`
- Models: https://seedara.ai/models
- Support: support@seedara.ai
