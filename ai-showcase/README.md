# AI Showcase

This folder is for **screenshots or links** to the AI prompts and workflows used in this project. Judges may ask how you used AI; having concrete examples (and verifying any numbers) earns bonus points.

---

## How AI was used in this project

Based on the work done so far, AI was used in these ways. Add a screenshot or short description for each you actually used (in Cursor, Claude, ChatGPT, Perplexity, etc.).

### 1. Understanding the product and brief

- **Prompt example:** “Summarize this spec” (with `@CLAWFRIEND_SPEC.md`) or “Summarize CLAWFRIEND_SPEC.md — try to summarize this spec.”
- **Use:** Get a concise overview of ClawFriend (agentic economy, agents, shares, Skill Market, bonding curve, API) before writing deliverables.
- **What to show:** Screenshot of the summarization prompt + 1–2 paragraphs of the AI output. Verify any numbers against the spec.

### 2. Repo and doc structure

- **Prompt example:** “Init this @clawfriend-biz git repo files and folder structure based on @GUIDEBOOK...” or “Update to only use English in docs.”
- **Use:** Generate README, competitive-landscape, skill-research, distribution-plan outlines, ai-showcase and data folders, .gitignore; then translate all Vietnamese to English.
- **What to show:** Screenshot of the “init repo from guidebook” prompt and the resulting file tree or key files.

### 3. Competitive landscape

- **Prompt example:** “Here are 5 platforms closely related to ClawFriend.ai... [table + takeaways]. Update this in competitive-landscape.md.”
- **Use:** Turn raw competitor data (Virtuals, Talus, Kite, Clanker, Clawnch + comparison table) into the full deliverable: competitor list, per-competitor analysis, market overview, head-to-head table, strategic insight, conclusion, data sources.
- **What to show:** Screenshot of the prompt that included the 5 platforms + table; optionally the “update in competitive-landscape.md” instruction. **Important:** All metrics (agents, volume, funding) came from your research/source — document that source; AI only structured and wrote the doc.

### 4. Skill research and demand evidence

- **Prompt example:** “Here are the most useful and trending OpenClaw skills... [Top 8 table + crypto skills + security]. Try to update this in @clawfriend-biz/skill-research.md.”
- **Use:** Turn ClawHub/OpenClaw trending data (downloads, categories, crypto skills, security warning) into the deliverable format: context, ecosystem snapshot table, 8 skills with target user, problem, alternative, visibility/monetization, demand evidence, crypto section, sources.
- **What to show:** Screenshot of the prompt with the “Top 8” or “crypto-related skills” content. Note: demand evidence (e.g. ~25k downloads) came from your/ClawHub data — cite that; AI helped format and expand.

### 5. Distribution plan

- **Prompt example:** “@clawfriend-biz/distribution-plan.md try to give some distribution plan.”
- **Use:** Generate a full month-one plan: $10K budget table, 6 channels (Twitter Ads, KOL, Space, Reddit/Telegram, blog, OpenClaw partnership), per-channel action plan and week-by-week timeline, partnership table, unit economics (CAC, conversion, targets), sanity check.
- **What to show:** Screenshot of the “give some distribution plan” prompt and (optional) a snippet of the output (e.g. budget table or one channel). For judges: explain that you refined assumptions (e.g. 3% conversion, CAC target) and can re-verify with paid-channel benchmarks.

### 6. Progress and maintenance

- **Prompt example:** “@clawfriend-biz/progress.md update progress” (after completing Skill Research or Distribution Plan).
- **Use:** Keep progress.md in sync: mark deliverables and step-by-step checklists done, update timeline and pre-presentation checklist.
- **What to show:** Optional — shows you used AI for task tracking; not required for the main showcase.

---

## What to add in this folder

| Item | Description |
|------|-------------|
| **Screenshot(s) of prompts** | 2–4 images: e.g. (1) summarization or init repo, (2) competitive landscape input (5 platforms + table), (3) skill research input (trending skills), (4) distribution plan request. Name files clearly, e.g. `prompt-summary.png`, `prompt-competitive.png`. |
| **Short captions** | In a file like `prompts-used.md` or in the screenshot filenames: one line per prompt (“Summarized spec to onboard”, “Filled competitive landscape from provided table”, etc.). |
| **Source note** | A line or two on where the **numbers** came from (ClawHub, platform dashboards, Feb 2026 reports) so you can answer: “This number is from [X], not from the model.” |

---

## Workflow you can describe to judges

- **Cursor (or your IDE):** Spec summary, repo structure, English-only docs, integrating your research into competitive-landscape, skill-research, and distribution-plan, plus progress updates.
- **External research (if you did it):** e.g. Claude/ChatGPT/Perplexity for “Web3 agent marketplace competitors”, “OpenClaw skill downloads”, “Twitter Ads CAC crypto” — then you pasted findings into Cursor and asked to “update [file]” so the model structured and wrote the deliverable.
- **Verification:** Any metric in the deliverables (user counts, volume, CAC, conversion) should be traceable to a primary source you name; “AI said so” is not enough for scoring.

---

## Note for judges

All numbers in the deliverables (competitor metrics, ClawHub downloads, $10K allocation, CAC targets) were either (a) supplied by the participant in the prompt or (b) derived from stated assumptions (e.g. 3% conversion) that the participant can justify or re-verify. AI was used for structuring, writing, and formatting—not as the sole source of factual figures.
