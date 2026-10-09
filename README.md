# Hi, I'm Faron 👋

I build **AI agents and automation** that take real work off small teams: bots that write, analyse, track pipelines and remember what the team decided. I care about the unglamorous parts that make them usable: safe defaults, human approval where it matters, cost-aware model use, and tests.

## Featured projects

### 🤖 [The New Hire](https://github.com/illegalfish14/the-new-hire)
**An AI operations teammate that lives in your team chat.** Six Claude-powered agents (analyst, writer, social drafter, pipeline tracker, digest, long-term memory) wired to Notion, GitHub and Gmail/Outlook. A single JSON profile adapts it to any business.
`Node.js` `Claude API` `tool use` `discord.js` `Notion API` `OAuth` `node-cron`

- Agent loop with parallel tool calls, refusal handling and prompt caching
- Schema-aware Notion layer: works with any database layout, no code changes
- Human-in-the-loop approvals (✅ / 🔄 / ❌) that expire rather than auto-approve
- Email safety boundary: sends only to the team, everything else becomes a draft
- 30 tests against a scripted fake client, so they run with no network or API keys

### 🏠 [Property Prospects](https://github.com/illegalfish14/Property_prospect)
**Plain-English property search with AI market reports.** Type *"3 bed house in Birmingham under £350k"* and get live listings, price charts by street, a GPT-4 buy/hold/sell summary, and Excel / PDF exports.
`Python` `Flask` `BeautifulSoup` `pandas` `seaborn` `OpenAI API` `FPDF`

### 🦆 [Ducksnsuits](https://github.com/illegalfish14/NFTproject)
**My first web project:** a hand-built responsive site for a 100-piece pixel-art NFT collection, with no framework.
`HTML` `CSS` `JavaScript` `GitHub Pages`

## Coming soon

**Outbound**: a deliverability-first outreach engine with paced sending, MX verification, bounce and reply handling, and compliance (suppression lists, unsubscribe, approval) built in.

## Toolbox

**Languages:** JavaScript / TypeScript · Python · HTML / CSS
**AI:** Claude API (tool use, agents, prompt caching) · OpenAI API
**Backend & data:** Node.js · Flask · pandas · SQLite · Supabase · Cloudflare Workers
**Integrations:** Notion · GitHub · Gmail · Microsoft Graph · Discord
**Frontend:** React · Tailwind · Vite
