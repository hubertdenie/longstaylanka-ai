# Long Stay Lanka for Claude Code

A Claude Code plugin marketplace with one plugin, `longstaylanka`. It adds the Long Stay Lanka MCP server (`https://longstaylanka.com/mcp`), so Claude can search private homes on Sri Lanka's south coast for stays of a week or longer, read a home's public details and list the areas. It is free, read only and needs no account.

## Install

```
claude plugin marketplace add OWNER/longstaylanka-ai
claude plugin install longstaylanka@longstaylanka-ai
```

Replace `OWNER` with the account that holds this repository. Or add the server on its own:

```
claude mcp add --transport http --scope user longstaylanka https://longstaylanka.com/mcp
```

## What the tools do

- Search homes: up to 10 homes that match, in the site's own order, with homes that match the traveller's description moved up, and a link to each.
- Home details: one home's public details by its reference code.
- List areas: the areas with homes now, and those coming soon.
- How it works: what is free, what a plan unlocks and what the prices mean.
- Send feedback: a short note about the answers or the catalogue.

No tool shows a home's name, contact details, exact location, photos or availability, and none can unlock, buy or sign in. Prices are indicative targets, not confirmed by the owner.

## Privacy

What the server receives and keeps is listed at https://longstaylanka.com/ai and in the privacy notice at https://longstaylanka.com/privacy.

Long Stay Lanka is independent. We are not affiliated with or endorsed by Anthropic.

<!-- This folder is copied as-is to the public repository longstaylanka-ai (Default D9). Its source of truth is integrations/claude-plugin/ in the Long Stay Lanka repository. -->
