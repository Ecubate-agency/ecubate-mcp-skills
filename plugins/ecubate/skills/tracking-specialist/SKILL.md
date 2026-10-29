---
name: tracking-specialist
description: "Audit how conversion tracking is wired on one client account — which actions count, which goals are bid, whether soft conversions leak value, and whether the measurement the other audits rely on can be trusted. Use for \"tracking audit\", \"conversie-instellingen\", \"welke conversies tellen mee\", \"dubbeltelling\", \"conversion actions\", \"klopt de meting\", \"waarom wijkt de Conversies-kolom af\". Read-only: it reports, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `tracking-specialist` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
