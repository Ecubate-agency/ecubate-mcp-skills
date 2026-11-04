---
name: quality-score-auditor
description: "Audit Quality Score on one client account — not as a number to raise, but as three components in a fixed order. Reports which of Ad Relevance, Expected CTR and Landing Page Experience is the binding constraint per ad group, brand and non-brand apart, ordered by money, down to the driver keywords, the URL each one lands on and the headlines the ad group actually serves, and routes each one to whoever can actually fix it. Use for \"quality score\", \"QS\", \"kwaliteitsscore\", \"quality score audit\", \"ad relevance\", \"advertentierelevantie\", \"expected CTR\", \"verwachte CTR\", \"landingspagina-ervaring\", \"landing page experience\", \"waarom is onze CPC zo hoog\", \"waarom staan we zo laag\", \"verkeerde landingspagina\", \"keyword final URL\". Diagnoses and routes; the one change it proposes itself is a keyword final URL re-route, after a live check of the page, and /ecubate:push-to-gads applies it."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `quality-score-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
