---
type: Topic
title: The Annual AI Slowdown Panic Is Here
description: "NLW argues the recurring summer AI-slowdown panic has arrived early — this year built on token sticker shock and the Uber ROI story — and dismantles it with supply-demand data; headlines cover the Deep SWE benchmark, Altman's jobs-apocalypse walk-back, and inference-layer fundraises."
tags:
- ai-bubble-narrative
- deep-swe-benchmark
- token-scarcity
- ai-jobs-debate
- inference-infrastructure
- coding-agents
status: stable
published_at: '2026-05-29T15:04:41+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:18Z'
sources:
- id: the-annual-ai-slowdown-panic-is-here-Af18iulLsSs
  resource: https://www.youtube.com/watch?v=Af18iulLsSs
  title: The Annual AI Slowdown Panic Is Here
---

# Overview

Nathaniel Whittemore observes that every summer since 2023 has produced an AI slowdown panic — ChatGPT's first down month in 2023, the pre-training data wall in 2024, the "95% of AI projects fail" MIT study plus GPT-5 disappointment in 2025 — and each was smashed within months by new capabilities (Gemini, o1 reasoning models, and the Claude Code/Opus 4.5 agentic breakthrough respectively). This year's panic has arrived early, built on the end of the AI subsidy era: Uber's COO saying the token budget the company burned in four months lacked ROI, CNBC warnings about pricing power, and a viral chart of plateauing VS Code coding-assistant installs. Whittemore calls these panics "an unintentional collaboration between the professional critics... with the people who are just tired and desperate for AI not to be as big a deal as it seems."[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]

His rebuttal leans on market data: Epoch AI estimates token supply is tripling annually while demand grows roughly 10x, GPU rental prices are up 2x in four months (Derek Thompson's New York hotel-prices analogy), and the VS Code chart mostly reflects interface migration — Simon Willison's point that Codex NPM installs grew from ~100,000/day in January to 1.5-1.8 million/day. Headlines cover Data Curve's Deep SWE benchmark, Sam Altman's and David Solomon's jobs-apocalypse walk-backs, and billion-dollar inference-layer raises by Baseten and OpenRouter.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]

# Key points

- Data Curve's Deep SWE benchmark builds tasks from scratch (avoiding SWE-bench's memorization and triviality problems): GPT-5.5 scored 70%, GPT-5.4 56%, Opus 4.7 54%, with Chinese models far behind (DeepSeek-V4 at 8%); GPT-5.5 also used ~half the tokens, half the time, and a third the cost of Opus 4.7.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Deep SWE's qualitative harness found self-verification separates leaders from the rest — GPT-5.4 and Opus 4.7 wrote their own tests over 80% of the time — and identified a Claude-specific failure pattern of missing parts of multi-part prompts; Garry Tan called it "the new standard for engineering evals."[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Sam Altman: "I don't think we're going to have the kind of jobs apocalypse that some of the companies in our space advocate," admitting his intuitions on entry-level white-collar elimination "were just off" because people care about human interactions.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Goldman Sachs CEO David Solomon's NYT op-ed called job-apocalypse fears overblown while estimating AI has displaced 16% of entry-level tasks at his firm, arguing markets use productivity to deliver better products at the same price rather than cheaper ones.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Baseten is closing a ~$1B round at $11B (annualized revenue tripled from $200M to $600M in Q1; run rate up 20x since March last year); OpenRouter's $113M Series B led by CapitalG valued it at $1.3B, now serving 100 trillion tokens/month, 5x in six months.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Prior panics resolved: 2023's usage dip answered by Gemini; 2024's data-wall by o1's reasoning-scaling approach; 2025's bubble narrative smashed by Claude Code, Opus 4.5, and GPT-5.3/5.4 crossing an agentic "Rubicon of capability."[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- The new denier line: vibe-coded apps are crap, so token spending will get cut, so lab revenue (OpenAI ~$30B, Anthropic ~$45B run rates) stops, so the infrastructure buildout collapses — a narrative Whittemore says was "completely inevitable."[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Ethan Mollick: rising demand yields higher costs yields lower demand — "It's almost like some sort of equilibrium is being achieved... there's no indication companies are finding AI less valuable"; Epoch AI: supply ~3x/year vs demand ~10x/year.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- The VS Code install plateau reflects interface shift, not slowing adoption: Codex terminal (NPM) installs surged from ~100,000/day in January to 1.5-1.8M/day — "this chart is as much or more about VS Code as it is about Claude Code or Codex."[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Market adaptation to scarcity: Cursor's Composer 2.5 is third on Artificial Analysis's coding agent index at 10-60x lower cost than Opus 47 Max/GPT 55; Google's Gemma 4 adoption is outpacing Qwen 3.5/3.6 (Swyx: "Not enough people talking about the US to China catch-up").[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]
- Greg Eisenberg surfaced "agent debt" — technical debt for hastily built agent workflows with conflicting system prompts, polluted memory, and overlapping tools — as the kind of discourse a slower period enables.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]

# Takeaways

Whittemore tells listeners not to put stock in the resurgent bubble narrative: with demand growing ~10x against ~3x supply, labs "won't have any problem selling every token they produce," and a market forced to pay sustainable prices is less bubble-prone than a subsidized one. He mourns the end of the brief "golden age of agent experimentation" (which risks AI inequality favoring the well-resourced) but sees genuine upside: expensive agentic usage buys society time to adapt, market-based slowing is healthier than a forced pause, and constrained periods produce valuable discourse like agent debt. His competitive advice: slowdown panics "are amazing" for anyone who keeps building while everyone else opts out hoping AI goes away.[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]

[^the-annual-ai-slowdown-panic-is-here-Af18iulLsSs]: "The Annual AI Slowdown Panic Is Here", The AI Daily Brief, YouTube, 2026-05-29 [Mirrored transcript](/references/the-annual-ai-slowdown-panic-is-here-Af18iulLsSs.md)

# Related topics

- [A Field Guide to AI Freakouts](/topics/a-field-guide-to-ai-freakouts-rGd91f4ohZk.md) — agreement — recurring panic patterns, another instance rebutted
- [The AI Chart Everyone Is Getting Wrong](/topics/the-ai-chart-everyone-is-getting-wrong-05VE_9rI954.md) — agreement — rebutting token-panic narratives with supply-demand data
- [The AI Token Shortage Begins](/topics/the-ai-token-shortage-begins-ex6abzvzaIo.md) — outcome — token scarcity's sticker shock sparks the slowdown panic
- [Is AI Doom Going Out of Style?](/topics/is-ai-doom-going-out-of-style-Bn43KmcMMB8.md) — agreement — both rebut bubble narratives with demand data
- [In Defense of Tokenmaxxing](/topics/in-defense-of-tokenmaxxing-izRIZ1bMq4A.md) — agreement — both defend token spend against revived skepticism
