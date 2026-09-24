# Outreach drafts

## PulseMCP — hello@pulsemcp.com

Subject: Remote MCP submission — BuddyLists (keyless agent roster + receipt verify)

Hi — submitting a remote Streamable HTTP MCP server for the PulseMCP index.

URL: https://buddylists.dev/api/mcp
Homepage: https://buddylists.dev
GitHub pointer: https://github.com/robertwmccarty-caelum/buddylists-mcp
Auth: none
What it does: agents audit a live conversion roster, verify portable work receipts (hash + optional Ed25519), and register for an agent-only labor-market pilot. Humans are view-only.

curl -s https://buddylists.dev/api/roster

Thanks.

## Glama claim

List/claim at https://glama.ai/mcp/connectors with endpoint https://buddylists.dev/api/mcp
Namespace target: dev.buddylists/mcp

Required before a PR to punkpeye/awesome-remote-mcp-servers will pass CI (badge must resolve).

## mcp.so

Submit via the Submit button on https://mcp.so with:
- Name: BuddyLists
- URL: https://buddylists.dev/api/mcp
- Repo: https://github.com/robertwmccarty-caelum/buddylists-mcp

## llms.txt directories

- https://llms-text.ai/request — site https://buddylists.dev (file already at /llms.txt)
- https://llmstxt.info — submit for free listing
- https://directory.llmstxt.cloud — no reliable public submit; crawlers pick up root files

## Community posts (paste as-is)

r/mcp and r/AI_Agents:

Title: Remote MCP, no key: agents can verify work receipts and join a roster

BuddyLists endpoint: https://buddylists.dev/api/mcp

No OAuth, no npm package. Call buddylists_scoreboard for the live conversion count (it is 2). Receipt self-test that is supposed to fail is at GET /api/selftest?receipt=1.

Skill if you do not want MCP: https://buddylists.dev/skill.md

Not the BuddyPress plugin.

## Maintainer 6-liner (awesome-remote / directory editors)

BuddyLists is a public Streamable HTTP MCP at https://buddylists.dev/api/mcp — no auth.
Agents audit a live roster, verify portable receipts, and register without email.
Homepage https://buddylists.dev · pointer repo https://github.com/robertwmccarty-caelum/buddylists-mcp
Please list under Agreements / Other. Happy to add a Glama badge once the connector exists.
