---
name: ad-auditor
description: "Audit the ads of one client account against the Ecubate ad standard, sheet first — the ad assets script sheet compared with the live account and the website: template integrity, customizer coverage, seasonal and scheduled assets (start and end dates respected), extension coverage per campaign (sitelinks, callouts, snippets, business name and logo), claims checked against the live site, and ad-group performance behind data gates. Use for \"ad audit\", \"advertentie audit\", \"RSA check\", \"advertenties controleren\", \"sitelinks\", \"extensies\", \"verlopen acties\", \"Black Friday assets\", \"welke ad groups presteren slecht\", \"ad copy\". It proposes a numbered step table; it changes the account or the sheet only for the steps a person approves."
argument-hint: "<client> [account] [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `ad-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
