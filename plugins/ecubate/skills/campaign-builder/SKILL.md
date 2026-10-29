---
name: campaign-builder
description: "Build new structure for one client account from the build queue — a new ad group with keywords, template RSA, routing negatives and extension check; a new Search campaign on the full Ecubate settings norm; a Display remarketing campaign with its audience, frequency caps and content-exclusion gate; or an ad-group merge. Consumes briefs from proposals/open/, plans the complete chain as ONE reviewable proposal, never pushes. Use for \"bouw de ad group\", \"nieuwe ad group\", \"nieuwe campagne\", \"display remarketing\", \"remarketing campagne bouwen\", \"campaign builder\", \"build queue\", \"bouwwerk\", \"ad groups samenvoegen\", \"merge ad groups\", \"verwerk de build briefjes\". Proposes only: /ecubate:push-to-gads is the only thing that changes an account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `campaign-builder` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
