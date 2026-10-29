# Ecubate for Claude

The Ecubate plugin for claude.ai, Cowork and Claude Code: every Ecubate skill as a slash command, `/ecubate:<skill> <client>`.

This repo holds only pointers. Each skill here says one thing: load the real skill from the Ecubate connector (`https://mcp.ecubate.com/mcp`). The procedures, client context and account access live behind that connector, which only lets in @ecubate.com Google accounts on Ecubate's access list.

## Install (once)

1. In Claude, open **Customize > Plugins > Add > Add marketplace** and enter `Ecubate-agency/ecubate-mcp-skills`.
2. Install **ecubate**, open its **Connectors** tab and connect Ecubate with your @ecubate.com Google account.

Then type `/ecubate:` to see the skills. Setup steps and tips: https://mcp.ecubate.com

## Maintenance

Generated from Ecubate-agency/ecubate-skills with `servers/gateway/cloud-plugin.mjs`. Do not edit the skills here by hand; edit the real skill on the connector instead. Re-run the script only when a skill is added, removed or renamed.
