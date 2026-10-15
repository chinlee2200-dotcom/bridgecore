# Bridgecore

**Plain words to app automations.** Say what should happen — *"when a Typeform is submitted, add a row to Google Sheets and send a Slack message"* — and get the concrete tool for each step, a ready-made recipe, an importable n8n workflow, or a preview of the exact API call. 3,597 capabilities from n8n, OpenAPI and MCP.

- **MCP server (Streamable HTTP, no sign-in):** `https://bridgecore-mcp.chinlee2200.workers.dev/`
- **Official MCP Registry:** `io.github.chinlee2200-dotcom/bridgecore`
- **Docs:** https://bridgecore.chinlee2200.workers.dev/for-agents.html · **Privacy:** https://bridgecore.chinlee2200.workers.dev/privacy.html · **Terms:** https://bridgecore.chinlee2200.workers.dev/terms.html
- **Run real calls:** [Apify Actor](https://apify.com/bridgecore/bridgecore-automation-planner)

## Tools (all read-only)
| Tool | What it does |
|---|---|
| `plan_automation` | Splits a need into steps and picks the exact tool per step; gaps are reported, never papered over. |
| `find_recipe` | Ready-made recipes plus matching public n8n templates. |
| `make_n8n_workflow` | An importable n8n workflow JSON with the blanks and accounts listed. |
| `do` | The exact HTTP/MCP request a task needs, as a preview. Nothing is sent from this server. |

## Install
- **Claude:** Settings → Connectors → Add custom connector → paste the server URL. Or install this repo as a plugin (`.claude-plugin/plugin.json`).
- **Gemini CLI:** `gemini extensions install https://github.com/chinlee2200-dotcom/bridgecore`
- **Cursor / VS Code / any MCP client:** add a remote server with the URL above.

## What this repo is
Connector manifests only (Claude plugin, Gemini CLI extension). The server is hosted; nothing to build or run here. Nothing you send is stored — the server keeps only a daily call count per tool.

## Support
Open an issue in this repository.

License: MIT
