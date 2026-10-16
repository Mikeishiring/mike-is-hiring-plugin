---
name: setup
description: Check the installed Mike is Hiring public MCP connection and help start a first job search. Use when setting up or troubleshooting this plugin.
---

# Set up Mike is Hiring

The package includes a public HTTPS MCP connection named `mike-is-hiring-public`. It needs no account, API key or local server.

Discover that connection's tools and call `get_market_overview` once with the parameters required by its schema. If the call succeeds, report that public research is connected, then ask what role and location the user wants. A separate `mike-is-hiring` candidate connection does not prove this plugin is connected; never use it as a fallback or read its private context for this setup.

If the public tools are missing, explain that the plugin is not connected. Have the user update the marketplace, reinstall the plugin, and restart Codex before trying a new conversation. The install guide is https://jobs.mikeishiring.com/developers. Do not replace an existing private connection or claim that loading the skill alone proves setup succeeded.

If the tool returns an error, report it without claiming successful setup. Offer a retry or the website. Never request an API key for the public plugin.
