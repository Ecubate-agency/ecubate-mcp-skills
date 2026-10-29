---
name: offer-angles
description: "Turn what a client actually offers into the angles and headline phrases ad copy is written from, and write them to profile/offer-angles.md in the client folder: the 13 offer facts each with its source, six angles with counted headline phrases in the market's language, a scope per phrase, and the open questions for the client. Analysis, not an interview. Run it again when offers, prices, guarantees or proof change and it reports what moved before it rewrites the file. Use for \"offer angles\", \"angles uitwerken\", \"offer angles maken\", \"boodschappen voor de advertenties\", \"welke USPs mogen we claimen\", \"copy basis\", \"offer-angles first\", \"het aanbod is veranderd\", \"nieuwe garantie\", \"prijs is aangepast\", \"angles verversen\". Read-only on the account: it writes one file in the client workspace and never touches Google Ads."
argument-hint: "<client>"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `offer-angles` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
