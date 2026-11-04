---
name: gtm-container-auditor
description: "Audit the Google Tag Manager container of one client — which container is actually live on the site, what fires from it, whether non-Google tags respect consent, whether its Google Ads conversion tags fire into anything that is used, and what is dead weight. Use for \"GTM audit\", \"container audit\", \"tag manager\", \"welke container staat live\", \"GTM opruimen\", \"consent in GTM\", \"Facebook pixel consent\", \"welke tags vuren er\", \"dubbele page_view\", \"custom template\", \"containerwildgroei\". Read-only in both directions: the GTM server cannot write, and this skill proposes nothing that a push can execute."
argument-hint: "<client> [domain]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `gtm-container-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
