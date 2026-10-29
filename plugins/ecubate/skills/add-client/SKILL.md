---
name: add-client
description: "Onboard a client end to end — pull what Notion and Google Ads already know, then the business interview and the brand pass, in one session"
argument-hint: "<client-name>"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `add-client` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
