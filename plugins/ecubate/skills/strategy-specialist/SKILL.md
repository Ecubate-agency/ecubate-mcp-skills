---
name: strategy-specialist
description: "Audit whether a client's targets are the right targets — unit economics, break-even, whether the target has ever been reached across the monthly history, and whether the documented target, the client record and the live campaign targets agree. Use for \"is this target realistic\", \"target haalbaar\", \"is dit doel ooit gehaald\", \"klopt ons POAS-doel\", \"staan onze campagnedoelen gelijk aan het businessdoel\", \"strategie audit\". Computing break-even and the target that follows from the unit economics is /ecubate:unit-economics; this skill consumes that number. Read-only: it recommends, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `strategy-specialist` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
