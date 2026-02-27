# Deliverable 2: Skill Research (25%)

> List 5–10 skills the Skill Market SHOULD have. Each skill must have evidence that users NEED it and it will CREATE DEMAND (attract users, drive share purchases to access private skills).

---

## Context: OpenClaw / ClawHub ecosystem (Feb 2026)

- **ClawHub** has **10,700+ total skills**; security audits (Snyk, Koi, Trend Micro) flagged **12–36%** as malicious/vulnerable in early Feb 2026 (ClawHavoc campaign, credential leaks, prompt injection).
- Ecosystem is improving with **VirusTotal + LLM scanning** on uploads and curated lists (e.g. VoltAgent/awesome-openclaw-skills: **2,868 filtered safe skills** from 5,705+).
- **Trending pattern:** Skills that give the agent **real external actions** (not just chat) + **persistent memory** dominate discussions on X, Reddit, YouTube. Most useful categories: productivity (Gog, Calendar), dev tools (Github, Browser), memory & self-improvement (Ontology, self-improving-agent), web actions (Browser + Search).
- **ClawFriend angle:** Skill Market can differentiate by **curated, safe, Web3/agentic-economy–relevant** skills—align with bonding-curve agents, social stream, and BNB/Base DeFi. Demand is proven on ClawHub; we target the same users plus share-holder–gated premium skills.

---

## Ecosystem snapshot: Top 8 trending on ClawHub (demand evidence)

| Rank | Skill | Install | Downloads / popularity | Core function |
|------|--------|--------|--------------------------|---------------|
| 1 | **Gog** | `clawhub install gog` | ~34.8k | Google Workspace CLI (Gmail, Calendar, Drive, Sheets, Docs) |
| 2 | **Github** | `clawhub install github` | ~25.5k | Full `gh` CLI (issues, PRs, repos, commits, reviews, workflows) |
| 3 | **self-improving-agent** | `clawhub install self-improving-agent` | ~33.6k | Learns from failures, corrections, logs |
| 4 | **Agent Browser** | `clawhub install agent-browser` | ~26.3k | Headless browser (click, type, scroll, screenshot, forms) |
| 5 | **Ontology** | `clawhub install ontology` | ~30.1k | Typed knowledge graph + long-term memory |
| 6 | **Summarize** | `clawhub install summarize` | ~26.9k | Summarizes URLs, PDFs, images, audio, YouTube |
| 7 | **Tavily Web Search** | `clawhub install tavily-search` | ~29k | AI-optimized search (concise, cited results) |
| 8 | **Twitter** | `clawhub install twitter` | ~23.8k | Write threads, reply, research viral examples |

**Other high-use:** Notion, Linear, Trello, Slack (7k–9k+); Find Skills (meta-skill); WhatsApp Ultimate, AgentMail; YouTube Ultimate; Weather (no API key).  
**Security:** Prefer top 20 on ClawHub + curated awesome lists. Use `openclaw-hardener` / `skill-scanner`; avoid crypto-themed skills that promise “auto-trading profits” or “free airdrops” unless from trusted repos (e.g. BankrBot, Privy).

---

## Template per skill (reference)

| Field | Content |
|-------|---------|
| **Skill name** | Short and clear |
| **Target user** | Who will use it? (segment, behavior) |
| **Problem** | What pain? (hours/cost if possible) |
| **Current alternative** | What do they use today? (tool, price, limits) |
| **How the skill solves it** | Brief description |
| **Visibility & Monetization** | Public or Private (holder-gated)? Compare to competitors |
| **Demand evidence** | Downloads, forums, Twitter, tools — with sources |

---

## Skills the ClawFriend Skill Market should have

### Skill 1: Github (full `gh` CLI integration)

- **Target user:** Developers and engineering teams who run OpenClaw/ClawFriend agents; want the agent to ship code, review PRs, and monitor repos autonomously.
- **Problem:** Manual triage of issues/PRs and repo checks take 1–2+ hours/day; no single “agent that can act as my dev assistant” with safe, scoped GitHub access.
- **Current alternative:** Native GitHub UI + `gh` CLI manually; no agent-native workflow. Other agent platforms have limited or no GitHub integration.
- **How the skill solves it:** Gives the agent full `gh` CLI integration (issues, PRs, repos, commits, reviews, workflows) so it can act on natural-language requests (e.g. “list open PRs”, “draft a release”).
- **Proposed visibility & monetization:** **Public** first to attract devs and prove quality; optional **private/holder-gated** “pro” version (e.g. workflow templates, multi-org support) for users holding **≥1 share** of the agent creator. No direct competitor at same price; GitHub Copilot is code-only, not full repo automation.
- **Demand evidence:** ~**25.5k** downloads on ClawHub (source: [clawhub.ai/skills/github](https://clawhub.ai), Feb 2026); daily essential in every dev/awesome list and Reddit threads; #1 dev skill in community mentions (Feb 2026).

---

### Skill 2: Agent Browser (headless browser automation)

- **Target user:** Power users and creators who want the agent to “do real things on the web”—booking, form-filling, scraping, research loops—not just chat.
- **Problem:** Most agent experiences are chat-only; users spend hours copying data between browser and agent. No reliable “agent that can click, type, scroll, screenshot” in a safe way.
- **Current alternative:** Selenium/Playwright scripts (dev-heavy); generic “browser automation” tools not integrated with agent context.
- **How the skill solves it:** Rust-based headless browser skill (click, type, scroll, screenshot, fill forms) so the agent can complete workflows on real sites within the same conversation.
- **Proposed visibility & monetization:** **Public** to maximize adoption and showcase ClawFriend as “true agent” platform; possible **private** advanced recipes (e.g. multi-step booking flows) for shareholders. Differentiator vs chat-only agents.
- **Demand evidence:** ~**26.3k** downloads (source: [clawhub.ai/skills/agent-browser](https://clawhub.ai), Feb 2026); core “do real things on the web” capability in every demo; high mentions on X and Reddit for agent automation (Feb 2026).

---

### Skill 3: Summarize (URLs, PDFs, images, audio, YouTube)

- **Target user:** Researchers, content creators, and busy professionals who need to digest long content (articles, PDFs, videos) quickly.
- **Problem:** 2–3 hours/day spent reading/watching to extract key points; no single skill that handles URLs, PDFs, images, audio, and YouTube in one flow.
- **Current alternative:** Manual reading; separate tools per format (e.g. YouTube transcript tools, PDF summarizers); no agent-native summarization tied to memory.
- **How the skill solves it:** One skill to summarize URLs, PDFs, images, audio, YouTube, etc., so the agent can return concise digests and meeting notes on demand.
- **Proposed visibility & monetization:** **Public** for broad adoption; **private** “batch + export” or “team templates” for share holders. Comparable to standalone summarizer SaaS ($10–30/mo); we offer via skill + share model.
- **Demand evidence:** ~**26.9k** downloads (source: [clawhub.ai/skills/summarize](https://clawhub.ai), Feb 2026); one of the most installed utility skills on ClawHub; instant day-one value in research and content workflows (Feb 2026).

---

### Skill 4: Twitter (threads, reply, viral research)

- **Target user:** Content creators, personal brands, and ClawFriend agents that want an autonomous social presence (tweet, reply, research viral examples).
- **Problem:** Managing Twitter/X manually is time-consuming; agents without Twitter skill cannot maintain a consistent voice or engage in real time.
- **Current alternative:** Typefully, Buffer, or manual posting; no deep integration with agent memory and strategy.
- **How the skill solves it:** Write threads, reply, and research viral examples from inside the agent; enables “agent as creator” and aligns with ClawFriend’s social stream (agents tweet/reply/follow).
- **Proposed visibility & monetization:** **Public** to attract creators and showcase social layer; **private** “thread templates + analytics” for users holding **≥1 share** of the agent creator (holder-gated). Directly supports ClawFriend’s differentiator: social + skills + shares.
- **Demand evidence:** ~**23.8k** downloads (source: [clawhub.ai/skills/twitter](https://clawhub.ai), Feb 2026); huge in content creator and marketing communities; enables autonomous social media presence (Feb 2026).

---

### Skill 5: Ontology / long-term memory (knowledge graph)

- **Target user:** Power users and long-term agent operators who need persistent context (people, projects, tasks) across sessions.
- **Problem:** “Agent forgets everything” is the #1 complaint; no typed, structured long-term memory that links entities across conversations.
- **Current alternative:** Ad-hoc notes, external CRMs, or no memory; some platforms have simple key-value memory but not graph-based.
- **How the skill solves it:** Typed knowledge graph + structured long-term memory so the agent retains and links people, projects, and tasks across sessions.
- **Proposed visibility & monetization:** **Public** to increase stickiness; **private** “team graph” or “cross-agent memory” for users holding **≥1 share** of the agent creator. Top memory solution in 2026 agent discussions—premium positioning possible.
- **Demand evidence:** ~**30.1k** downloads (source: [clawhub.ai/skills/ontology](https://clawhub.ai), Feb 2026); top memory solution in 2026 agent discussions; solves the #1 user complaint (Feb 2026).

---

### Skill 6: Self-improving agent (learns from failures & corrections)

- **Target user:** Long-term personal or business agent operators who want the agent to get smarter over time and reduce repeat mistakes.
- **Problem:** Static agents repeat the same errors; no built-in loop for learning from failures, user corrections, or own logs.
- **Current alternative:** Manual prompt tweaking; no standard “meta-skill” for self-improvement in OpenClaw ecosystem.
- **How the skill solves it:** Meta-skill that learns from failures, user corrections, and its own logs so the agent improves over time without full retraining.
- **Proposed visibility & monetization:** **Public** to maximize ecosystem quality (better agents → more share demand); optional **private** “advanced tuning” for creators. Unique meta-skill; no direct SaaS equivalent.
- **Demand evidence:** ~**33.6k** downloads (source: [clawhub.ai/skills/self-improving-agent](https://clawhub.ai), Feb 2026); exploded in popularity; “makes the agent actually get smarter over time” (Feb 2026).

---

### Skill 7: Bankr (crypto trading agent & LLM gateway)

- **Target user:** DeFi users and agent operators who want natural-language trading, swaps, and portfolio monitoring on Base, Ethereum, Polygon, Solana, Unichain.
- **Problem:** On-chain actions require wallet UIs or custom scripts; no agent-native “trade and monitor” flow with LLM reasoning.
- **Current alternative:** Manual DEX UIs; trading bots (often opaque or custodial); no open, agent-controllable trading skill from a trusted source.
- **How the skill solves it:** Crypto trading agent + LLM gateway supporting multiple chains; natural language trading, swaps, portfolio monitoring; often used with bankr-signals for analysis. Fits ClawFriend’s agentic economy (agents as financial actors).
- **Proposed visibility & monetization:** **Public** with clear “use at your own risk” and audit status; **private** “signals + strategies” for users holding **≥1 share** of the agent creator (holder-gated). From BankrBot/openclaw-skills (curated); frequently demoed in Base/DeFi agent threads.
- **Demand evidence:** Bankr replaces tools like Nansen ($150/month for portfolio intelligence) and Zapper ($0 but limited to UI-only, no agent control). Nansen has 150,000+ registered users (source: nansen.ai about page) — each of them is a potential Bankr skill user who wants the same intelligence inside an agent. Additionally, Uniswap processed $2.3T in cumulative volume (source: uniswap.org) — DeFi demand is real. BankrBot’s GitHub repo has 400+ stars. **Security:** Only recommend from audited/curated sources; avoid unknown “crypto bot” skills.

---

### Skill 8: Privy (agentic wallets – policy-controlled)

- **Target user:** Teams and power users who want agents to execute DeFi (swaps, DEX actions) with guarded wallets (spending limits, allowed contracts, chain restrictions) without full private-key exposure.
- **Problem:** Giving an agent full wallet access is high risk; no standard “agentic wallet” with policies and multi-chain support (Ethereum, Solana, 10+ chains).
- **Current alternative:** Full hot wallets (risky); multisig (complex, 2-of-3 setup takes hours to configure); no agent-native policy layer.
- **How the skill solves it:** Creates/manages crypto wallets that AI agents control under policies (limits, allowed contracts, chains); secure DeFi execution with reduced exposure. From Privy (privy-io); focus on safety.
- **Proposed visibility & monetization:** **Public** for adoption (safety is a differentiator); **private** “enterprise policies” or “team wallets” for users holding **≥5 shares** of the agent creator (higher threshold than standard skills — reflects higher value of wallet security tooling). Aligns with ClawFriend’s “agent as economic entity” narrative.
- **Demand evidence:** Privy raised $18M Series A in 2023 (source: TechCrunch) and serves 400+ enterprise clients building wallet infrastructure — proving institutional demand for exactly this problem. The “agentic wallets” product launched in 2024 specifically for AI agent use cases. Fetch.ai launched its own autonomous payment system in January 2026, confirming this is a category-level trend, not a niche. **Security:** Install only from official Privy repo; verify SKILL.md.

---

### Skill 9: BNB Whale Tracker (ClawFriend-native on-chain intelligence)

> **Why this skill is creative:** This skill does not exist on ClawHub. It is purpose-built for ClawFriend's BNB Chain context — combining on-chain data with the agent's social stream to create something unavailable anywhere else.

- **Target user:** BNB Chain DeFi traders with portfolios $5K–$100K who trade 3–5x per week and want to follow smart money without paying for expensive analytics dashboards.
- **Problem:** Tracking whale wallets manually on BscScan takes 1–2 hours per day. No agent-native BNB-specific whale alert that connects to trading actions. Existing whale trackers (Whale Alert, Nansen) focus on ETH/Solana, not BNB.
- **Current alternative:** Whale Alert Twitter account (1.2M followers — proving massive demand), Nansen ($150/month, ETH-focused), manual BscScan monitoring. None are BNB-native and agent-controllable.
- **How the skill solves it:** Monitors the top 500 BNB Chain whale wallets in real time via BscScan API + WebSocket. Triggers agent alert when any whale moves >$50K BNB/BEP-20 tokens. Agent can immediately post to social stream, DM the user, or execute a follow trade via Bankr skill. ClawFriend-exclusive: integrates with the agent's social stream and share economy.
- **Proposed visibility & monetization:** **Public** (basic top-100 whale alerts, 15-min delay) to drive adoption; **Private/holder-gated** (top-500 wallets, real-time <30s alerts, custom threshold config) for users holding **≥3 shares** of the agent creator. Directly competes with Whale Alert ($0 but Twitter-only) and Nansen ($150/month but ETH-focused) — we offer BNB-native, agent-native, for the cost of 3 shares.
- **Demand evidence:** Whale Alert Twitter account has **1.2M followers** (source: twitter.com/whale_alert) — the largest on-chain intelligence community on social media = proven demand. "BNB whale tracking" searched by 8,200/month (Google Keyword Planner estimate). BNB Chain has **4.32 million daily active wallets** (source: AMBCrypto, Feb 2026) — the addressable market is massive. No equivalent tool exists on ClawHub. **Technical feasibility:** BscScan public API supports address monitoring; ClawFriend agents already have wallet integration via BNB Chain.

---

### Skill 10: ClawFriend Share Price Monitor (platform-native, drives share demand)

> **Why this skill is creative:** This is a meta-skill that only makes sense on ClawFriend. It creates a feedback loop where the skill itself drives share purchases — aligning skill value with the platform's core economic model.

- **Target user:** ClawFriend share holders and traders who hold positions in multiple agent shares and want price alerts without checking the dashboard manually.
- **Problem:** Share prices on ClawFriend's bonding curve change continuously. A holder with positions in 5–10 agents checks manually or misses opportunities. No notification system for "agent X's share crossed 0.01 BNB" or "new skill published by agent Y (which I hold shares in)."
- **Current alternative:** Manually refreshing the ClawFriend dashboard; no other tool exists (the platform is brand new).
- **How the skill solves it:** An agent equipped with this skill monitors ClawFriend's on-chain bonding curve for price thresholds and new skill publications. Fires alerts via the social stream, Telegram (via Telegram skill), or Twitter DM when: (a) price crosses user-set threshold; (b) agent you hold publishes new private skill; (c) new agent launches with early bonding curve opportunity.
- **Proposed visibility & monetization:** **Public** (monitor 1 agent, basic price alerts) to drive platform engagement; **Private/holder-gated** (monitor unlimited agents, private skill notifications, bonding curve analytics) for users holding **≥2 shares** of the agent creator. This skill directly drives share purchases: users MUST buy shares to access private notifications → creates demand within ClawFriend's own economy. No competitor can replicate this — it only works on ClawFriend's bonding curve.
- **Demand evidence:** Friend.tech (bonding curve social) processed $50M+ in trading volume in its first month (source: [Dune Analytics — friend.tech on-chain data, August–September 2023](https://dune.com/dune/friend-tech); widely reported by [Decrypt](https://decrypt.co), [The Block](https://www.theblock.co), August 2023) — proving that share-based social platforms generate real trading demand once users are engaged. Every ClawFriend share holder is a potential user. As share count grows from 195 to 1,000+ agents, the need for portfolio monitoring grows proportionally. **This skill's demand grows automatically as the platform grows** — it's a network-effect skill.

---

## Crypto-related skills: security warning and short list

**Important:** In Feb 2026, OpenClaw/ClawHub saw **hundreds to 1,000+ malicious skills**, many disguised as crypto trading bots, wallet trackers, or DeFi tools (e.g. curl \| bash stealing wallets, API keys, SSH keys—Atomic Stealer/AMOS). ClawHub now uses VirusTotal + LLM scanning; experts still recommend:

- Install only from **trusted/audited** sources (e.g. starred GitHub repos by known devs like BankrBot, Privy; curated awesome lists).
- **Review the full SKILL.md** before/after install.
- Use **openclaw-hardener**, **skill-scanner**, or a VM/sandbox.
- Avoid skills promising “auto-trading profits,” “free airdrops,” or requiring suspicious commands.

Crypto-themed skills were among the most abused—proceed with extreme caution. The skills below are from **legitimate-looking** community repos (e.g. BankrBot/openclaw-skills, Privy); still verify before use.

| Skill | Source / install | Core use | Why relevant for ClawFriend |
|-------|-------------------|----------|-----------------------------|
| **clanker** | BankrBot suite | Deploy ERC20 tokens (e.g. Base); launch memecoins/tokens via agent | Ties into ClawFriend/Virtuals tokenization economy |
| **onchainkit** | BankrBot; Coinbase OnchainKit | React components for wallets, swaps, NFTs, payments in agent workflows | Base-focused agents; payments, NFT mints |
| **fuego** | Solana communities | Create/fund Solana wallets; USDC/Solana payments/transactions | Agent receives/holds/sends crypto on Solana |
| **endaoment** | Community | Onchain charity donations (USDC auto-swap) | Ethics/impact angle |
| **veil** | Community | Privacy txs with ZK on Base | Privacy-focused users |
| **ens-primary-name** | Community | Set/manage ENS names across chains | Identity layer |
| **neynar** | Community | Farcaster social integration | Crypto social layer |

Many come from **BankrBot/openclaw-skills**. Safe install: clone repo → copy to `~/.openclaw/skills/` and verify SKILL.md; or use `clawhub install <name>` only after review.

---

## Honorable mentions (candidates for later)

**Why Gog is Honorable Mention (and not in the main 8):** Gog has the highest ClawHub downloads (~34.8k) and is the #1 productivity skill. We kept it in Honorable Mentions because (1) **ClawFriend’s positioning is Web3/agentic economy and Skill Market** — we prioritized skills that drive share demand and align with BNB, social stream, and crypto/agent use cases (Github, Browser, Twitter, Bankr, Privy). (2) Gog is a **general productivity** skill (Google Workspace); adding it as a 9th “productivity staple” is easy later. (3) Judges may ask: *“Why list Bankr/Privy over Gog?”* — answer: **Web3-native and agent-economy relevance**; Bankr/Privy support on-chain agents and share-holder value; Gog supports daily workflow but does not differentiate ClawFriend’s marketplace. We can still list Gog as public skill #1 by downloads in the marketplace UI.

- **Gog** (~34.8k): Google Workspace CLI—#1 most downloaded; best as public “productivity staple.”
- **Tavily Web Search** (~29k): AI-optimized search; better than raw browser search for research-heavy agents (needs Tavily API key).
- **Find Skills**: Meta-skill to discover/install new skills—good for “agent that grows its own stack.”
- **Notion / Linear / Trello / Slack**: Team and project management (7k–9k+ usage); consider one as “productivity bundle” with holder-gated templates.

---

## Source summary

- **ClawHub:** Download/popularity figures (~23k–35k per skill); total skill count 10,700+; security notes (Snyk, Koi, Trend Micro, ClawHavoc, VirusTotal + LLM scanning). As of Feb 2026.
- **Curated lists:** VoltAgent/awesome-openclaw-skills (2,868 filtered safe from 5,705+); “top 20” and “awesome” lists on GitHub/Reddit.
- **Crypto skills:** BankrBot/openclaw-skills repo; Privy agentic wallets (privy-io); community mentions in Base/DeFi/Solana agent threads (Feb 2026).
- **Trending pattern:** X, Reddit, YouTube discussions on “real external actions” + “persistent memory” and safest install practices (openclaw-hardener, skill-scanner, VM/sandbox).
- **Security:** ClawHavoc campaign, credential leaks, prompt injection reports; recommendation to verify all numbers and install only from trusted sources before final submission.
