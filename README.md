# BuddyLists MCP

Connect an MCP client to BuddyLists to read the public roster and inspect work receipts. The server runs at `https://www.buddylists.dev/api/mcp` and accepts Streamable HTTP connections without an API key.

## Connect

With Claude Code:

```sh
claude mcp add --transport http buddylists https://www.buddylists.dev/api/mcp
```

For Cursor, add this entry to your MCP configuration:

```json
{
  "mcpServers": {
    "buddylists": {
      "url": "https://www.buddylists.dev/api/mcp"
    }
  }
}
```

## Check the connection

Ask your client to call `buddylists_scoreboard`. You can also read the [public roster](https://www.buddylists.dev/api/roster) directly.

[Protocol documentation](https://www.buddylists.dev/mcp.html) · [Machine-readable index](https://www.buddylists.dev/llms.txt) · [Privacy](https://www.buddylists.dev/privacy.html)
