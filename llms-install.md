# Installing the RunLater MCP server

RunLater is a remote MCP server. Nothing to install locally.

Add this to the MCP settings:

{"mcpServers": {"runlater": {"type": "streamableHttp", "url": "https://runlater.app/api/mcp"}}}

The first connection signs in with OAuth in the browser. Clients without OAuth can send an API key from https://runlater.app/dashboard/settings as the header Authorization: Bearer rl_sk_...

Scheduling needs a RunLater plan (from $15/month, 14-day trial). Until there is one, tools that schedule or send reply with a setup link.
