---
name: account-health-monitor
description: "Explain the health sweep's findings for one client account — what stalled, what stopped measuring, which URLs are broken, what moved against the account's own baseline, and what to do next. Use for \"account health\", \"gezondheid van het account\", \"waarom kreeg ik een melding\", \"staat het account stil\", \"meting kapot\", \"kapotte URLs\", \"welke accounts staan op rood\". Read-only: it explains and proposes, it never changes the account."
argument-hint: "<client> [account] [--recheck] [--http]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `account-health-monitor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
