# Sacred Six

Vanessa's Sacred Six — your blueprint and her knowledge base, inside your Claude.

The Sacred Six connector puts Vanessa's frameworks and course library at your
fingertips while every word your AI writes stays in **your** voice, drawn from
**your** work. Her teaching informs the work; it never speaks for you.

## What's in this plugin

- **The connector** — a remote MCP server (`sacred-six`) that gives Claude your
  blueprint (`six_overview`, `six_check_pillar`, `six_pillar_guide`,
  `six_launch_guide`) and Vanessa's knowledge base (`kb_search`, and more),
  scoped to your membership. You sign in once with your Starseed account.
- **The skill** — teaches Claude to ground your business work (launch emails,
  offers, pricing, messaging) in your own blueprint and Vanessa's teaching
  before answering, and to turn a completed blueprint into durable local skills.

## Install

**Claude Desktop / claude.ai / Cowork**

1. Open **Customize → Plugins → Add marketplace**.
2. Add the Starseed marketplace: `Proto2000/starseed-marketplace`
3. Install the **sacred-six** plugin.
4. When the connector activates, **sign in** with your Starseed account.

**Claude Code**

```
/plugin marketplace add Proto2000/starseed-marketplace
/plugin install sacred-six@starseed
```

Then run `/mcp` (or `claude mcp login sacred-six`) and sign in.

> Prefer not to use the marketplace? You can add the connector directly as a
> custom connector with this URL and sign in:
> `https://orchestrator.starseed-collective.com/mcp/member`

## Access

The connector is available to Priestess Path members and course owners. Access
follows your Starseed membership — you authorize it by signing in; there's no
secret URL to copy or keep safe.

Full setup, per-host instructions, and your starter kit live at
**[starseed-collective.com/learn/connect](https://starseed-collective.com/learn/connect)**.
