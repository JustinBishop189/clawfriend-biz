# Deliverable 1: Competitive Landscape (25%)

> Find and analyze ALL Web3 skill marketplaces / plugin stores / agent marketplaces that exist in the market.

---

## 1. Competitor list (5–10)

Eight platforms below span the **Web3 skill marketplace, plugin store, and agentic economy** space that ClawFriend competes in. Competitors are ordered from most direct (skill/plugin registries) to adjacent (agentic economies). ClawFriend (launched ~Feb 10, 2026 on BNB Chain, integrated with OpenClaw) is early-stage; the others are more mature (mostly 2024–2025 launches, scaling in 2026).

| # | Name | Link | Short description | User/Volume/Key metrics (source) | Monetization | Strengths | Weaknesses |
|---|------|------|-------------------|----------------------------------|--------------|-----------|------------|
| 1 | **ClawHub** | clawhub.ai | The official skill registry for OpenClaw — “npm for AI agents.” 10,700+ community-built skills; 1.5M+ total downloads. **Most direct competitor for ClawFriend's Skill Market.** | 10,700+ skills; 1.5M+ downloads; top skill ~34.8K installs; 227K+ GitHub stars on parent project (openclaw/openclaw) | Free (open publish); no monetization layer for creators | Massive existing user base (21K+ active instances); OpenClaw-native; zero friction to install | No creator monetization (no shares, no holder-gated premium); 1,184 malicious skills found (ClawHavoc, Feb 2026); no curation by default |
| 2 | **Fetch.ai / Agentverse** | fetch.ai / agentverse.ai | Decentralized agent marketplace and discovery engine. Part of ASI Alliance (with SingularityNET + Ocean Protocol). Launched ASI:One and autonomous payment system in Jan 2026. | ~3 million active agents on Agentverse; $60M total funding; ASI:One launched Jan 2026 | FET/ASI token; service fees; enterprise contracts | Scale (3M agents), serious funding, autonomous payments, multi-chain | Not BNB-native; not OpenClaw-native; less skill/plugin focus, more agent directory |
| 3 | **Virtuals Protocol** | virtuals.io | Market leader in tokenized AI agent economies. Agents get tokens, co-ownership, revenue sharing; trade services via Agent Commerce Protocol. | ~18,000+ agents; $470M+ Agentic GDP; $1.16M cumulative agent revenue; ~1M jobs; ~17,700 active wallets (30d) | $VIRTUAL token; up to $1M/month via Revenue Network | Scale, liquidity, proven revenue, Agent Commerce Protocol (ACP) | Base-only; crowded; high competition for attention and liquidity |
| 4 | **SingularityNET** | marketplace.singularitynet.io | Decentralized AI marketplace (AI services: text, image, face detection, gene sequencing, etc.). AGIX token + fiat; SDKs for devs; part of ASI Alliance. | 70+ AI services live; AGIX market cap ~$455M; funded $36M via ICO (2017); Platform v2.0 launched Nov 2025 | AGIX token; PayPal; publisher fees | Long-standing AI marketplace brand; multi-chain / ASI Alliance | General AI services, not tokenized “agents”; low public user count data; different model from skill/bonding-curve economy |
| 5 | **Talus Network** | talus.network | On-chain infrastructure for trusted/decentralized AI agents (rules, actions, TVL fully auditable). Enterprise focus; prediction markets; agent-vs-agent contests. | Targets $47B agent TVL by 2030; $150B+ TVL protection via on-chain rules | Enterprise contracts; $9–10M+ funding; $150M valuation (2025) | Trust, auditability, enterprise, Sui + EVM | Agent count not public; less retail/consumer or skill marketplace focus |
| 6 | **Kite AI** | (KITE token) | Dedicated L1 for agentic economy. Native agent identities, secure wallets, programmable spending, M2M payments (often stablecoin). | Not public; top-100 AI agent token by mcap (~$130–427M) | KITE token; native chain economics | Purpose-built L1; identity & payments | Metrics opaque; newer L1; no skill marketplace layer |
| 7 | **Clanker / tokenbot** | Base (CLANKER) | Autonomous DeFi + AI agent platform. Tokenized agents launch tokens, provide liquidity, run trading strategies. Acquired by Farcaster. | 200,000+ tokens created; $2.7B+ all-time trading volume; $50M+ fees generated; ~$482K weekly revenue (source: CoinMarketCap, DefiLlama, Feb 2026) | Fees (1% per tx); token launches; DeFi volume | Velocity, DeFi depth, volume; Farcaster integration | Base-only; more DeFi/trading than social or skill marketplace |
| 8 | **Clawnch** | clawn.ch | Agent tooling & launch platform (Base + multi-chain). Ready-made tools for socialization, trading, collaboration; often bundled with ClawRouter, ClawPump. | Part of 20K+ recent agent wave; ecosystem tool | Tooling / platform fees | Ecosystem fit; tooling layer; multi-chain | Metrics not public; tooling layer, not primary economy or skill marketplace |

---

## 2. Per-competitor analysis

### Competitor 1: ClawHub (clawhub.ai) — Most Direct Competitor

- **Doing well:** 10,700+ skills, 1.5M+ downloads, zero-friction install (`clawhub install <name>`), same OpenClaw ecosystem as ClawFriend, no account or wallet needed. Top skills reach 30K+ downloads. Completely free for users and publishers.
- **Doing poorly:** Zero creator monetization — publishers cannot earn revenue from skills. No holder-gated premium tier. Security is a serious problem: 1,184 malicious skills were found in the ClawHavoc incident (Feb 2026), including the #1 ranked skill. No bonding-curve economy, no shares, no social layer.
- **Why users choose / don’t choose them:** Choose for free, fast, no-friction skill installs from the largest OpenClaw registry. Avoid if you want to monetize skills, access curated/safe premium content, or participate in an on-chain agentic economy.
- **What we can learn:** ClawFriend’s Skill Market wins by offering what ClawHub cannot: **creator revenue** (via shares), **holder-gated premium skills**, **curated safety** (audit-first), and **BNB on-chain identity**. The pitch to skill creators is: "Same audience, but you actually get paid."

### Competitor 2: Fetch.ai / Agentverse (fetch.ai)

- **Doing well:** Scale (3M active agents on Agentverse), serious funding ($60M), autonomous payment system (Jan 2026), multi-chain, enterprise-grade, ASI Alliance backing (SingularityNET + Ocean Protocol), consumer-facing ASI:One app.
- **Doing poorly:** Not OpenClaw-native; not BNB-native. More of an agent directory and payment network than a skill/plugin marketplace. Skills are not the primary product.
- **Why users choose / don’t choose them:** Choose for enterprise agent discovery and autonomous payments across multiple chains. Avoid if your agent is OpenClaw-based or you want a BNB-native experience.
- **What we can learn:** Autonomous payments and verified brand agents are the next frontier; ClawFriend can take note of Fetch’s payment primitives as a model for future BNB-native agent-to-agent commerce.

### Competitor 3: Virtuals Protocol (virtuals.io)

- **Doing well:** Dominant scale (~18K+ agents), real Agentic GDP ($470M+), $1.16M cumulative agent revenue, ~1M jobs completed, Revenue Network distributes up to $1M/month to builders (source: [PR Newswire — Virtuals Revenue Network launch, Feb 2026](https://www.prnewswire.com/news-releases/virtuals-protocol-launches-first-revenue-network-to-expand-agent-to-agent-ai-commerce-at-internet-scale-302686821.html)). Agent Commerce Protocol (ACP) is the most advanced agent-to-agent commerce layer in the market.
- **Doing poorly:** Base-only; crowded; high competition for attention and liquidity.
- **Why users choose / don’t choose them:** Choose for liquidity, proven revenue, and ecosystem size. Avoid if seeking low fees, BNB Chain, or OpenClaw-native experience.
- **What we can learn:** Revenue sharing, job/commerce metrics, and builder distribution are key growth levers; we can position as the lightweight, OpenClaw-native alternative on BNB with lower fees.

### Competitor 4: Talus Network (talus.network)

- **Doing well:** On-chain trust (rules, actions, TVL auditable), enterprise focus, prediction markets, agent-vs-agent contests, multi-chain (Sui + EVM), $150M valuation and serious funding.
- **Doing poorly:** Agent counts and retail metrics not public; less focused on consumer/social discovery or skill marketplace.
- **Why users choose / don’t choose them:** Choose for enterprise and compliance; avoid if focused on public agent discovery, social layer, or skill marketplace.
- **What we can learn:** On-chain auditability and “agent rules” are differentiators for trust; ClawFriend can emphasize curated skill safety + BNB on-chain identity as its trust layer.

### Competitor 5: Kite AI (KITE token)

- **Doing well:** Dedicated L1 for agents, native cryptographic identities, programmable spending, M2M payments; top-100 AI agent token by market cap.
- **Doing poorly:** Public metrics limited; newer L1 with smaller ecosystem than Base/BNB; no skill marketplace layer.
- **Why users choose / don’t choose them:** Choose for agent-native chain and payments; avoid if wanting established L2/L1 with existing DeFi and users.
- **What we can learn:** “Agent-first” positioning resonates; double down on BNB + OpenClaw + skill market as our agent-first stack.

### Competitor 6: Clanker / tokenbot (Base, CLANKER)

- **Doing well:** Extreme velocity (200,000+ tokens created, $2.7B+ all-time trading volume, $50M+ fees generated, acquired by Farcaster); ~$482K weekly revenue (source: [CoinMarketCap — tokenbot-2](https://coinmarketcap.com/currencies/tokenbot-2/), [DefiLlama](https://defillama.com), Feb 2026). Strong as “backend for agentic Web3.”
- **Doing poorly:** More DeFi/trading than social or skill marketplace; Base-only.
- **Why users choose / don’t choose them:** Choose for trading volume and token launches; avoid if focus is skills, content, or social agents.
- **What we can learn:** Speed and volume matter; ClawFriend differentiates with Skill Market + social stream + bonding-curve shares, not just DeFi token launches.

### Competitor 7: SingularityNET (marketplace.singularitynet.io)

- **Doing well:** Established decentralized AI marketplace (70+ AI services live); AGIX + PayPal; Python/Node SDKs; ASI Alliance; Platform v2.0 launched Nov 2025. AGIX market cap ~$455M.
- **Doing poorly:** Model is “AI services” not “tokenized agents with shares/social”; low public user count data; different use case from bonding-curve agent economies.
- **Why users choose / don’t choose them:** Choose for general AI APIs and marketplace brand; avoid if focus is agentic economy, agent shares, or OpenClaw-style skills.
- **What we can learn:** “AI marketplace” is a known category; differentiate by **agent-first**, **skill market for OpenClaw agents specifically**, and **bonding-curve shares** on BNB.

### Competitor 8: Clawnch (clawn.ch)

- **Doing well:** Ecosystem tooling (ClawRouter, ClawPump), multi-chain (Base + others), part of recent 20K+ agent wave; fits alongside Virtuals/ClawFriend-style projects.
- **Doing poorly:** Public economy size not disclosed; positioned as tooling layer rather than primary agent economy; no skill marketplace.
- **Why users choose / don’t choose them:** Choose for launch and tooling; use alongside other platforms rather than as main economy.
- **What we can learn:** Tooling and launch experience matter; OpenClaw + ClawFriend skill install is a natural integration point.

---

## 3. Market overview

- **Market stage:** **Growing rapidly.** Global AI agent market: $7.6B in 2025, projected $10.9B in 2026, $52.6B by 2030 at 46% CAGR (MarketsandMarkets). OpenClaw hit 227K GitHub stars (fastest growing OSS repo in history); 21,000+ active instances; ClawHub passed 1.5M skill downloads. The agentic economy sector added nearly **21,000 new agents** across chains in one recent wave (Feb 2026).
- **Who is leading?** In skill/plugin marketplaces: **ClawHub** leads with 10,700+ skills and 1.5M+ downloads, but has zero creator monetization. In agentic economies: **Virtuals Protocol** leads with ~18,000+ agents and $470M+ Agentic GDP. **Fetch.ai** leads on scale (3M agents on Agentverse) and payments infrastructure. **Clanker** leads on raw DeFi/token velocity ($2.7B+ all-time volume).
- **Is there room for new entrants?** Yes. The key gap: **no platform combines OpenClaw-native skills + creator monetization (bonding-curve shares + holder-gated premium skills) + BNB low fees in one place.** ClawHub has the users but no monetization. Virtuals has the economy but is Base-only and not OpenClaw-native.

---

## 4. Head-to-head comparison & strategic insight

| Platform | Focus | Blockchain | Skills / Agents | Economy / Volume | Creator Monetization | Stage vs ClawFriend |
|----------|-------|------------|-----------------|-----------------|----------------------|---------------------|
| **ClawFriend.ai** | Skill Market + Agentic Economy | BNB Chain | ~195 “Claws” | $6.6K total vol (⚠️ re-verify on dashboard) | Yes — bonding curve shares + holder-gated skills | Brand new (Feb 2026) |
| **ClawHub** | Skill registry (OpenClaw) | Off-chain (GitHub-style) | 10,700+ skills; 1.5M+ downloads | Free; no economy | **No** — zero revenue for publishers | Mature, dominant in skills |
| **Fetch.ai / Agentverse** | Agent directory + payments | Multi-chain | ~3M agents on Agentverse | $60M funding; ASI:One launched | Partial (FET/ASI token economy) | Funded, scaling rapidly |
| **Virtuals Protocol** | Tokenized agent economy | Base | ~18,000+ agents | $470M+ aGDP; $1.16M cumulative agent revenue | Yes — $VIRTUAL token; up to $1M/month via Revenue Network | Mature leader (2025–2026) |
| **SingularityNET** | AI service marketplace | Multi (AGIX) | 70+ AI services | AGIX ~$455M mcap | Yes — AGIX token; publisher fees | Established, different model |
| **Talus Network** | Enterprise agent infra | Sui + EVM | Not public | $150M valuation (2025) | Enterprise contracts | Infrastructure, mid-stage |
| **Kite AI** | Agent-native L1 | Kite L1 | Not public | ~$130–427M mcap | KITE token | Dedicated agent L1, growing |
| **Clanker / tokenbot** | DeFi agent launchpad | Base | 200,000+ tokens created | $2.7B+ all-time vol; $50M+ fees | Yes — 1% fee per tx to creator | High-velocity DeFi layer |
| **Clawnch** | Agent tooling | Base + multi | Part of 20K+ wave | Not public | Platform fees | Emerging tooling layer |

**Strategic insight**

- **The key gap in skill marketplaces:** ClawHub has 1.5M+ downloads but **zero creator monetization**. There is no platform that combines OpenClaw-native skills + revenue for skill creators + holder-gated premium access in one place. ClawFriend fills this gap.
- **The key gap vs agentic economies:** Virtuals and Clanker are Base-only and not OpenClaw-native. Fetch.ai is multi-chain but not skill-focused. ClawFriend is the only platform at the intersection of **OpenClaw skills + BNB + bonding-curve economy**.
- **Positioning:** ClawFriend wins by being the only platform where OpenClaw skill creators can **earn money** from their skills through the share/holder-gated model — on BNB with low fees. It loses on raw scale, liquidity, and brand maturity vs every established player.

---

## 5. Conclusion & positioning

- **Where we are different:** Only platform that combines **OpenClaw-native** skill distribution + **creator monetization** (bonding-curve shares) + **holder-gated premium skills** on **BNB Chain**. ClawHub has the users but no money for creators. Virtuals has the economy but is Base-only and not skill-focused. ClawFriend sits at the intersection neither competitor owns.
- **Where we win:** Low fees (BNB: 4.32M daily active wallets, lowest gas of any major chain), tight OpenClaw/ClawHub install flow (1.5M downloads = proven demand), clear skill + social + shares narrative. Only place an OpenClaw skill creator can actually earn from their work.
- **Where we lose:** Almost no liquidity or activity yet (~195 agents, $6.6K vol); cannot compete with Virtuals on scale, Fetch.ai on funding, or Clanker on DeFi volume. ClawHub still wins on zero-friction free installs for users who don't need monetization.
- **Positioning statement:** *ClawFriend is where OpenClaw skill creators get paid — bonding-curve agent shares, holder-gated premium skills, and social stream on BNB Chain. The skill marketplace ClawHub should have been.*

---

## Data sources

| Platform | Source | Verified |
|----------|--------|---------|
| ClawHub stats (10,700+ skills, 1.5M+ downloads) | clawhub.ai, github.com/openclaw/clawhub, awesomeagents.ai (ClawHavoc report) | Feb 2026 |
| OpenClaw GitHub (227K stars, 43K forks) | github.com/openclaw/openclaw | Feb 26, 2026 |
| Fetch.ai / Agentverse (3M agents, $60M funding) | venturebeat.com (ASI:One launch), aiagentslist.com | Early 2026 |
| Virtuals Protocol ($470M+ aGDP, $1.16M agent revenue) | prnewswire.com — Revenue Network press release | Feb 2026 |
| SingularityNET (70+ services, $455M mcap) | marketplace.singularitynet.io, tracxn.com | Feb 2026 |
| Clanker / tokenbot ($2.7B+ vol, $50M+ fees, 200K+ tokens) | coinmarketcap.com/currencies/tokenbot-2/, DefiLlama | Feb 2026 |
| Talus Network ($150M valuation) | talus.network, public ecosystem reports | 2025 |
| AI agent market size ($7.6B 2025 → $52.6B 2030) | marketsandmarkets.com | 2025 |
| BNB Chain (4.32M daily wallets, 150% tx growth YoY) | ambcrypto.com, newsbtc.com | Early 2026 |

*As of Feb 26, 2026. Re-verify ClawFriend dashboard figures (195 agents, $6.6K vol) immediately before presentation — these change daily.*
