---
type: Topic
title: What I Learned Testing GPT 5 5
description: "First reactions, benchmarks, and roughly a dozen hands-on tests of OpenAI's GPT-5.5 (\"Spud\") — a fast, agentic knowledge-work model positioned as the public answer to Anthropic's withheld Claude Mythos."
tags:
- gpt-5-5
- openai
- openai-codex
- claude-mythos
- model-benchmarks
- agentic-coding
- openai-anthropic-rivalry
status: stable
published_at: '2026-04-24T17:13:06+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:45Z'
sources:
- id: what-i-learned-testing-gpt-5-5-jblguhXunZs
  resource: https://www.youtube.com/watch?v=jblguhXunZs
  title: What I Learned Testing GPT 5 5
---

# Overview

Whittemore reviews GPT-5.5 (nicknamed "Spud"), released Friday at 2 p.m. after months of anticipation dating to OpenAI's December "code red." He frames the stakes around Anthropic's Claude Mythos — a model Anthropic announced as a step change but withheld from public release — meaning whatever OpenAI shipped would be judged as its answer. OpenAI billed GPT-5.5 as "a new class of intelligence for real work and powering agents": writing, debugging, research, data analysis, documents and spreadsheets, operating software, and moving across tools until a task is finished. Benchmarks largely delivered — 82.7 on Terminal Bench 2.0 versus Opus 4.7's 69.4, top of the Artificial Analysis Intelligence Index by three points — though it lagged on Vending Bench and SWE-bench Pro, the latter of which OpenAI and many observers dismissed as noise.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]

Whittemore then runs about ten of his own tests in Codex — podcast script prep, a sponsored-episode companion kit, an art book, a media kit refresh, a jobs portal with model-debate backend, and podcast data analysis — and comes away positive enough to start alternating between Codex/GPT-5.5 and his Opus/Claude Code daily drivers. He also reads OpenAI's notably humble comms as a deliberate contrast with Anthropic's Mythos posture and throttling complaints.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]

# Key points

- Codex grew from a couple hundred thousand users at the start of the year to over 4 million; GPT-5.5's launch capped OpenAI's refocusing after the December code red and elimination of side quests.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Benchmarks: 82.7 vs Opus 4.7's 69.4 on Terminal Bench 2.0; first model to score in the 60s on Artificial Analysis (extra-high version); topped the Artificial Analysis Intelligence Index by three points, breaking a three-way tie with Anthropic and Google. It trailed Opus 4.7 on Vending Bench (about on par with Opus 4.6) but won Vending Bench Arena without Opus's underhanded tactics, and Vals AI still had Opus 4.7 ahead on professional tasks.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- The disputed SWE-bench Pro underperformance was waved off by OpenAI's Tibo ("You'll be missing out if you think SWE-bench is representative of anything real"), pointing to OpenAI's February piece on why SWE-bench Verified no longer measures frontier coding.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Pricing is $5/$30 per million tokens in/out — double GPT-5.4 and 20% above Opus 4.7 — but Noam Brown argued what matters is "intelligence per token or per dollar," and the 5.5 family dominates the cost-performance frontier.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Scaling01 estimated GPT-5.5 is close to Mythos despite being a fifth to half its size (speculating ~3-5T parameters vs ~10T for Mythos) and noted Mythos's $125 pricing "looks kind of ridiculous"; Riley Brown's line — "Mythos benchmarks do not matter until released to the public. As far as I'm concerned, it does not exist" — captures Whittemore's view.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Every's Vibe Check found GPT-5.5 uniquely trade-off-free — faster than Opus 4.7, better at writing than any OpenAI model since 5.4/4o, strongest on their senior-engineer benchmark — though Opus 4.7 still writes better plans and has a superior design eye; Siki Chen's optimal setup: Opus 4.7 extra-high to plan, GPT-5.5 high to execute.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Matt Shumer's nuance: "a massive leap forward, but for 99% of users it probably won't matter" because the last generation already crushed normal work; the value is in rounding out weaknesses like design.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- Long-running reliability stood out: Peter Gostev ran a migration 7+ hours overnight with queued prompts; OpenAI's Aidan McLaughlin returned after days to a 31-hour industrial-scale RL run; CodeRabbit measured 79.2% expected-issue detection in code review vs a 58.3% baseline; Vals found a 10-point accuracy jump on enterprise content tasks over 5.4.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- In Whittemore's own tests, 5.5 followed "clear, simple, journalistic" writing instructions instead of Opus 4.7's dramatic AI affectations; it excelled at podcast data analysis and spreadsheets; design remained mediocre natively but improved substantially with front-end skills installed — leading him to argue we're in the era where "anything that you do is going to be model and harness together."[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- OpenAI's comms shifted to humility — Altman's "GPT-5.5 is here. We hope it's useful to you. I personally like it." — with pointed emphasis on iterative deployment, democratized access, and inference efficiency, read widely as a jab at Anthropic's withheld Mythos and usage limits.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- The same day, Anthropic published a postmortem confirming Claude Code quality issues were real, prompting loud "I told you so" reactions (Theo: "They shipped slop and it made the models worse"; Peter Levels: "Claude was dumbified on March 4th").[^what-i-learned-testing-gpt-5-5-jblguhXunZs]
- OpenAI signaled more coming: chief scientist Jakub Pachocki expects "extremely significant improvements in the medium term" and called the last few years "surprisingly slow"; Greg Brockman called 5.5 "a beginning point"; No More ID likened it to an O1-preview-style initial RL checkpoint whose "O3 moment will come soon."[^what-i-learned-testing-gpt-5-5-jblguhXunZs]

# Takeaways

Whittemore's verdict: first impressions are very positive — strong enough that after six-plus months of Opus models as daily drivers and Claude Code as his main building app, he will now jump back and forth between models and harnesses per task, and he urges listeners to invest in Codex as OpenAI's core workspace for knowledge workers. He judges the release moment a clear competitive win for OpenAI but won't count Claude out (citing Anthropic's new memory for managed agents), and stresses that users are the unambiguous beneficiaries of the competition. Echoing Ethan Mollick, he sees 5.5 as evidence that capability gains are accelerating, not plateauing.[^what-i-learned-testing-gpt-5-5-jblguhXunZs]

[^what-i-learned-testing-gpt-5-5-jblguhXunZs]: "What I Learned Testing GPT 5 5", The AI Daily Brief, YouTube, 2026-04-24 [Mirrored transcript](/references/what-i-learned-testing-gpt-5-5-jblguhXunZs.md)

# Related topics

- [ChatGPT 5.5 Rumors Start to Bubble](/topics/chatgpt-5-5-rumors-start-to-bubble-Smh50q7UTcY.md) — continuation — garlic rumors become hands-on GPT-5.5 review
- [Work AGI is the Only AGI that Matters](/topics/work-agi-is-the-only-agi-that-matters-gmkURB_HmQI.md) — continuation — Spud finished here, hands-on reviewed there
- [GPT-5.4 First Test Results](/topics/gpt-5-4-first-test-results-xIIj9hkISUE.md) — same-series — Whittemore's hands-on tests of successive GPT releases
- [Mythos Returns But Not For Everyone](/topics/mythos-returns-but-not-for-everyone-187eNPPTa_w.md) — counterpoint — OpenAI ships broadly what Anthropic withholds
- [Anthropic's New Mythos Model a "Step Change" in Capabilities](/topics/anthropic-s-new-mythos-model-a-step-change-in-ca-EBXZ4zZwS7c.md) — counterpoint — OpenAI ships openly what Anthropic withholds as Mythos
