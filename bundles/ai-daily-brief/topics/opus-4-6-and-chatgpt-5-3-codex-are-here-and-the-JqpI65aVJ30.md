---
type: Topic
title: Opus 4.6 and ChatGPT 5.3-Codex Are Here and the Labs Are at War
description: "Anthropic's Claude Opus 4.6 and OpenAI's GPT-5.3 Codex drop within 20 minutes of each other — dueling frontier coding models with agent teams, million-token context, and 3x token efficiency that show the labs converging on the general-purpose work agent."
tags:
- anthropic
- openai
- claude-opus
- gpt-codex
- coding-models
- agent-teams
- benchmarks
- agentic-coding
status: stable
published_at: '2026-02-06T19:39:56+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:09Z'
sources:
- id: opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30
  resource: https://www.youtube.com/watch?v=JqpI65aVJ30
  title: Opus 4.6 and ChatGPT 5.3-Codex Are Here and the Labs Are at War
---

# Overview

Whittemore covers an unprecedented moment: Anthropic's Claude Opus 4.6 and OpenAI's GPT-5.3 Codex released within 20 minutes of each other — "Kendrick versus Drake, but for nerds" — making clear the two labs are at war, with coding as the first and most important battleground. Opus 4.6 brings better code review and debugging, a million-token context window with state-of-the-art long-context performance, "agent teams" (the rebranded swarms, with a coordination layer for parallel work), and adaptive thinking; OpenAI countered by shipping the coding-tuned 5.3 Codex before the base GPT-5.3 even exists, claiming a state-of-the-art 77.3% on Terminal Bench 2.0 and roughly 3x token efficiency.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]

Both labs emphasized the same two things: their models now build themselves (Opus 4.6 was created with Claude as the key driver of all coding at Anthropic; GPT-5.3 Codex "was instrumental in creating itself"), and coding capability is the foundation for general knowledge work — reaffirming Whittemore's "code AGI is functional AGI" thesis. Early verdicts split hairs: OpenAI stronger on coding benchmarks and speed, Opus on orchestration and long context, with developer loyalty still favoring Anthropic (53.3% vs 24.9% in one poll).[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]

# Key points

- Opus 4.6 claims the top of Terminal Bench 2.0 and Humanity's Last Exam, leads with knowledge work in its benchmark presentation, and adds million-token context, agent teams, and adaptive thinking (context-driven reasoning-effort allocation with manual dials).[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Anthropic's distinction: use sub-agents for "quick focused workers that report back"; use agent teams when teammates must "share findings, challenge each other, and coordinate on their own."[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Anthropic's autonomous demo: Opus 4.6 with agent teams built a C compiler using a Ralph loop, no internet access, consuming ~2 billion tokens (140M+ output) at roughly $20,000 in standard API pricing.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- GPT-5.3 Codex scored 77.3% on Terminal Bench 2.0 versus 64% for Codex 5.2 and 65.4% for Opus 4.6 (self-reported), nearly doubled GPT-5.2 on OSWorld computer-use (64.7%), and is ~3x more token efficient — 5.3-high is smarter than 5.2-high on one-third the tokens.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- OpenAI's ChatGPT MCP-apps feature was built entirely by 5.3 Codex — "zero lines of code written by hand," with the CLI working autonomously for hours.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Early testers: Box's Aaron Levie measured a 10% jump over Opus 4.5 on hardest knowledge-work tasks; McKay Wrigley found teams mode 2.5x faster with better results; Simon Willison shrugged — "both incremental improvements on their predecessors and very capable."[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Latent Space gave the round to Anthropic on developer attention (plus a $50 tinkering credit) while noting OpenAI won most benchmarks with a 25% faster model — and warned all first-day third-party reactions are "either biased or superficial."[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Ryan Carson's poll of 700+ developers: 53.3% chose Opus 4.6 for the week's coding versus 24.9% for Codex 5.3.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Dan Shipper's convergence thesis: both labs are moving toward an "über coding model" because "a great coding agent turns out to be the basis for a great general purpose work agent" — the holy grail of AI.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]
- Greg Brockman announced OpenAI's internal mandate: by March 31, agents — not editors or terminals — become the tool of first resort for any technical task, claiming a "step function improvement" since December with Codex now writing "essentially all the code" for some OpenAI engineers.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]

# Takeaways

Whittemore counsels ignoring day-one and even week-one reactions — after Opus 4.5 and GPT-5.2 Codex it took over a month for people to appreciate how much the capability set had shifted. The real signal is the workflow change: Anthropic's Alex Albert describes "learning to let it run," and Brockman's agent-first deadline is, in Whittemore's words, the starting gun for how everyone should be rethinking their own workflows. The moment is exciting enough, he adds, that it even has people rethinking the whole idea of an AI bubble.[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]

[^opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30]: "Opus 4.6 and ChatGPT 5.3-Codex Are Here and the Labs Are at War", The AI Daily Brief, YouTube, 2026-02-06 [Mirrored transcript](/references/opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30.md)

# Related topics

- [Claude Code Turns One](/topics/claude-code-turns-one-dpegtfwlb0M.md) — continuation — GPT-5.3 rumors here become the actual launch
- [How to Use Opus 4.7 and the New Codex](/topics/how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo.md) — continuation — next versions of both dueling model lines
- [The Perils of the AI Exponential](/topics/the-perils-of-the-ai-exponential-dztw1yctjI4.md) — outcome — Opus 4.6 sets METR's record 14.5-hour horizon
- [GPT-5.4 First Test Results](/topics/gpt-5-4-first-test-results-xIIj9hkISUE.md) — continuation — GPT line's next step after 5.3 Codex
- [The Latest AI Models and Model Rumors](/topics/the-latest-ai-models-and-model-rumors--plNBWEQhHU.md) — continuation — GPT-5.3 Codex gets Spark variant on Cerebras
- [Why Everyone Is Obsessed with Claude Code](/topics/why-everyone-is-obsessed-with-claude-code-_WXyavHYb5c.md) — continuation — next Opus pushes the same capability threshold
