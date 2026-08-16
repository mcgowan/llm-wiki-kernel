---
type: Topic
title: Why AI Needs Better Benchmarks
description: "Occasioned by the launch of ARC-AGI-3 — an interactive-reasoning benchmark where humans score 100% and frontier models under 1% — NLW traces the history of benchmark saturation, benchmark maxing, and the attempts to measure AI beyond narrow tasks."
tags:
- ai-benchmarks
- arc-agi
- benchmark-saturation
- ai-evaluation
- agentic-reasoning
- francois-chollet
status: stable
published_at: '2026-03-27T02:29:01+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:54Z'
sources:
- id: why-ai-needs-better-benchmarks-kLZeFWZewH0
  resource: https://www.youtube.com/watch?v=kLZeFWZewH0
  title: Why AI Needs Better Benchmarks
---

# Overview

Using the launch of ARC-AGI-3 from Arc Prize as its occasion, Whittemore surveys why benchmarks exist — comparing models and tracking progress over time — and why they keep breaking down. He splits the historical landscape into knowledge benchmarks (MMLU, GPQA, Humanity's Last Exam) and functional benchmarks (SWE-bench, Terminal Bench), noting many begin as knowledge tests and evolve into implicit tool-use tests. Two problems recur: benchmark saturation, where every frontier model bunches at the top so scores stop showing meaningful progress or differences, and benchmark maxing, where labs train specifically to beat known or semi-public tests regardless of real-world relevance.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]

The episode then walks the lineage of fixes — harder questions, more practical tests, real-world task simulations like SWE-Lancer and GDPval, and METR's long-task chart — before landing on ARC-AGI-3: 135 instruction-free graphical games testing whether agents can explore, build mental models, and adapt in real time. Humans score 100%; every frontier model scores under 1%.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]

# Key points

- Saturation timeline: by May 2024 all major models exceeded 80% on MMLU (GPT-4o at 88.7%); by mid-2025 o3 hit 83.3% on GPQA Diamond without tools and 88.9% on AIME; today GPT-5.4 scores 52.1% on Humanity's Last Exam with tools, near Opus 4.6's 53%, and SWE-bench Verified scores from all major labs converged near 80%.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- Benchmark maxing evidence: on the variant SWE-Rebench (different problems), Chinese models dived in rankings far more than Western ones, suggesting training against SWE-bench Verified's narrow problem set; Meta was accused of testing multiple Llama 4 Maverick variants on Arena to launch as its second-ranked model, which hands-on users found implausible.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- Deeper issue: traditional benchmarks measure narrow single tasks — good at demonstrating "task AGI" (competition math solved via IMO gold medals) but useless for understanding jagged frontiers and how AI brings tasks together.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- Real-world attempts: OpenAI's SWE-Lancer tested against $1M of actual Upwork tasks; GDPval extended this to white-collar deliverables like spreadsheets and slide decks, revealing models often failed on tool calls rather than the work itself; Artificial Analysis runs an automated AI-only GDPval variant.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- METR's long-task benchmark — "the chart holding up the entire global market" during bubble talk — went from agents completing 5-minute human tasks (GPT-4o) to 10-hour tasks (Opus 4.6) in two years, but METR is running out of tasks: 10-hour tasks are full software builds, so extending the benchmark would fundamentally change it.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- ARC-AGI history: Chollet's thesis that LLMs are "great memorization engines" that memorize reasoning patterns rather than reason; ARC-AGI-1's hidden visual-logic puzzles resisted models until o3's December 2024 bombshell (76% low-compute, 88% high); ARC-AGI-2 countered test-time compute with symbolic interpretation, compositional reasoning, and contextual rules, holding most 2025 releases below 30% before Gemini 3.1 Pro (77.1%), GPT-5.4 Pro (83.3%), and leader Gemini 3 DeepThink (84.6% at $13.62 per task) saturated it.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- ARC-AGI-3: "the only unsaturated agentic general intelligence benchmark in the world" — no instructions, real-time grid manipulation; models failed by mistaking one game for another, carrying theories between games, and failing to forecast cause and effect; a DeepMind researcher shared Gemini mistaking a game for Activision Tennis.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- Critiques and praise: one critic noted scoring uses squared efficiency versus humans (100 model steps vs 10 human steps = 1%), making scores incomparable to earlier ARC tests; researcher Brandon Hancock praised that "an alien species with zero knowledge of human language could ace ARC-AGI-3" — the only frontier benchmark requiring no language or cultural knowledge.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]
- Chollet's caveat: ARC-AGI "is not a final exam that you pass to claim AGI" but a moving target tracking the residual gap between what's hard for AI and easy for humans.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]

# Takeaways

Whittemore's takeaway is that "solving" benchmark saturation may simply mean not expecting benchmarks to last: just as model-building needs constant innovation, so does model measurement. He expects models to jump from under 1% to meaningful scores on ARC-AGI-3 before long — at which point yet another new instrument will be needed for whatever capability comes next.[^why-ai-needs-better-benchmarks-kLZeFWZewH0]

[^why-ai-needs-better-benchmarks-kLZeFWZewH0]: "Why AI Needs Better Benchmarks", The AI Daily Brief, YouTube, 2026-03-27 [Mirrored transcript](/references/why-ai-needs-better-benchmarks-kLZeFWZewH0.md)

# Related topics

- [Does Gemini 3.1 Pro Matter?](/topics/does-gemini-3-1-pro-matter-of85FKh_6yY.md) — shared-mechanism — ARC-AGI and benchmark saturation framing releases
- [Just How Good is GPT 6 Going to Be](/topics/just-how-good-is-gpt-6-going-to-be-YweN5PUyGgc.md) — shared-mechanism — eval gaming undermining benchmark integrity
- [Introducing Maturity Maps: A New Way to Measure AI Adoption](/topics/introducing-maturity-maps-a-new-way-to-measure-a-Jg-wQBw0LDQ.md) — shared-mechanism — new frameworks replacing saturated AI measurement approaches
