### Sarah Vogel

I build the integration layer between the tools small businesses already use — CRMs, accounting, mailboxes, industry portals — and the automation on top of it. Three of those tools are public, with demos you can click through without an account.

| | |
|---|---|
| **[birdie-platform](https://github.com/GodSmasher/birdie-platform)** | The transparency layer for solar installers: connector SDK, utility-registration automation with a human in the loop, EN/DE demo. [Live demo →](https://birdie-platform-nine.vercel.app/demo) |
| **[botworks](https://github.com/GodSmasher/botworks)** | A modular AI bot platform: 13 bots on one runtime with queue, retries and offline answers, multi-tenant admin panel. [Live demo →](https://botworks-psi.vercel.app/dashboard) |
| **[commission-engine](https://github.com/GodSmasher/commission-engine)** | Sales commissions done properly: tiers, team pools, own-lead bonuses, clawbacks and monthly statements as a tested engine, plus a role-based demo app. [Live demo →](https://commission-engine-beta.vercel.app) |

All three run locally with two commands and no credentials; all are tested and built in CI on every push.

### Side-research: MCP security

**[patchbay-audit](https://github.com/GodSmasher/patchbay-audit)** — passive security scanner for Model Context Protocol servers, the interface LLM agents use for tools and data. 25+ checks across OAuth 2.1 metadata, transport-security headers, tool-description poisoning (zero-width + bidi Unicode) and manifest drift. SARIF 2.1.0 output integrates into GitHub Code Scanning. Cross-referenced against 802 public MCP CVEs with OWASP MCP Top 10 mapping.

Live index: [patchbay-mcp.dev](https://patchbay-mcp.dev)

### Open-source contributions

**[getnao/nao](https://github.com/getnao/nao)** (YC) — 4 merged PRs, [view all](https://github.com/getnao/nao/pulls?q=is%3Apr+author%3AGodSmasher+is%3Amerged):

- **[#1783](https://github.com/getnao/nao/pull/1783)** — set `forceReasoning` on OpenAI so gateway-prefixed model ids (orq.ai, Nebius, etc.) keep reasoning options
- **[#1775](https://github.com/getnao/nao/pull/1775)** — skip empty-summary parts so a failed compaction cannot permanently break a chat
- **[#1773](https://github.com/getnao/nao/pull/1773)** — render empty table cells as `-` so Slack accepts the message
- **[#1761](https://github.com/getnao/nao/pull/1761)** — upload files written by the agent into the Slack thread

Plus 5 more under review covering MCP shared-story resolution, display_chart/story rendering, SQL result caps, tool-name sanitization and compaction reasoning strips.

**[openstatusHQ/openstatus](https://github.com/openstatusHQ/openstatus)**:

- **[#2898](https://github.com/openstatusHQ/openstatus/pull/2898)** — detect Microsoft Teams webhook URLs (Workflows, Power Automate, legacy Office connector) and send Adaptive Cards instead of raw JSON

### Available

**Freelance integration and automation work from January 2026**, remote, EN/DE.

:email: vogels671@gmail.com · [LinkedIn](https://www.linkedin.com/in/sarah-vogel-39b95a352/) · [Portfolio](https://godsmasher.github.io/my-portfolio/)
