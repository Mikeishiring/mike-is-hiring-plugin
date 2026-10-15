# Mike is Hiring for Codex

Public AI and crypto job search, company research, and salary evidence inside Codex.

## Install

With a current Codex CLI:

```sh
codex plugin marketplace add Mikeishiring/mike-is-hiring-plugin
codex plugin add mike-is-hiring@mike-is-hiring
```

Start a new Codex conversation after installation. Run the plugin's setup to check the public connection, or ask:

> Use Mike is Hiring to find AI engineering roles in London and link to the postings.

The bundled skill is named `mike-is-hiring`; select it from Codex's skill picker when you want to invoke it explicitly. The plugin includes the hosted public MCP connection. No account, API key, Node server or application repository is required.

If your CLI does not recognize `plugin`, update Codex from its official source. You can also add this marketplace and install Mike is Hiring from the desktop Plugins browser. A directory listing is a separate review process; this repository is the direct installation source.

## Scope

The public plugin reads jobs, company and market evidence. It does not read private candidate records, submit applications or send messages. Private search memory uses the separate [signed-in setup](https://jobs.mikeishiring.com/app/setup?restart=1&intent=connection&client=codex). Do not paste credentials into chat or overwrite an existing private MCP connection.

The ZIP in Releases is the portable plugin package. The repository includes the marketplace catalog used by the install commands. Report install problems through [support](https://jobs.mikeishiring.com/contact). [Privacy](https://jobs.mikeishiring.com/privacy).

## Update or remove

```sh
codex plugin marketplace upgrade mike-is-hiring
codex plugin add mike-is-hiring@mike-is-hiring
```

Use Codex's Plugins settings to disable or uninstall Mike is Hiring.
