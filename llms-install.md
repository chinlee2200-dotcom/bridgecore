# Installing Bridgecore (for AI agents such as Cline)

Bridgecore is a **remote** MCP server. Nothing to clone, build or install, and no API key.

Add this entry to the MCP settings file (for Cline: `cline_mcp_settings.json`):

```json
{
  "mcpServers": {
    "bridgecore": {
      "type": "streamableHttp",
      "url": "https://bridgecore-mcp.chinlee2200.workers.dev/"
    }
  }
}
```

Then check it works by calling `plan_automation` with
`{"need": "when a typeform is submitted add a row to google sheets and send a slack message"}` —
the answer lists three steps (Typeform trigger, Google Sheets append, Slack send).

All four tools are read-only. `do` only previews the exact API request; it never sends anything.
