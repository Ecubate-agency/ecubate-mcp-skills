---
name: gmc-misrep-recovery
description: "Recover a Google Merchant Center account suspended for misrepresentation — diagnose the real trigger, run the full remediation audit, decide the right moment to request review, and choose between appeal and rebuild. Use this whenever the user mentions a GMC suspension, misrepresentation flag, \"misrep\", account disapproval, \"products disapproved due to policy violation\", a rejected GMC review, \"should I request a new review\", planning a resubmission, or deciding whether to appeal a suspended Merchant Center vs starting fresh with a new domain/GMC. Also trigger for Shopping ads suddenly stopped due to account suspension, and for post-reinstatement hardening. Do NOT use for a store that hasn't been suspended yet — use gmc-pre-launch-audit for that."
argument-hint: "<GMC account ID> [store domain]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `gmc-misrep-recovery` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
