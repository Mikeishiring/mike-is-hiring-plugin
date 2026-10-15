---
name: setup
description: Check the installed Mike is Hiring public MCP connection and help start a first job search. Use when setting up or troubleshooting this plugin.
---

# Set up Mike is Hiring

The package includes a public HTTPS MCP connection named `mike-is-hiring`. It needs no account, API key or local server.

Discover its tools and call `get_market_overview` once with the parameters required by its schema. If the call succeeds, report that public research is connected, then ask what role and location the user wants. Do not describe private candidate access as connected.

If the tools are missing, ask the user to enable Mike is Hiring in their installed plugins and start a new conversation. The install guide is https://jobs.mikeishiring.com/developers. Do not install a duplicate raw MCP server over an existing private connection.

If the tool returns an error, report it without claiming successful setup. Offer a retry or the website. Never request an API key for the public plugin.
