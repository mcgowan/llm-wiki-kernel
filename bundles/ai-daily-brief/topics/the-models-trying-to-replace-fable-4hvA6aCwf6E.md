---
type: Topic
title: The Models Trying to Replace Fable
description: "With Claude Fable 5 banned by the US government, Whittemore surveys the fallout: G7 allies pleading for frontier-model access, and enterprises turning to open-weight alternatives like GLM 5.2, Composer 2.5, and multi-model routing strategies."
tags:
- fable-ban
- open-source-models
- glm
- export-controls
- g7
- inference-optimization
- model-routing
status: stable
published_at: '2026-06-19T17:37:51+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:27Z'
sources:
- id: the-models-trying-to-replace-fable-4hvA6aCwf6E
  resource: https://www.youtube.com/watch?v=4hvA6aCwf6E
  title: The Models Trying to Replace Fable
---

# Overview

With the US government's effective banning of Anthropic's Fable 5 and Mythos entering its second week and no resolution in sight, Nathaniel Whittemore covers both the geopolitical fallout at the G7 and the scramble among builders and enterprises to assemble replacement systems. At the G7 in France — attended by Sam Altman, Demis Hassabis, Dario Amodei, Alexandr Wang, Arthur Mensch, and Aidan Gomez in the heaviest AI-industry representation the summit has seen — allied leaders confronted the new reality that access to US frontier models is not a given. Macron warned the US "holds the AI kill switch," the UK's requested carve-out was denied, and the US gave no ground on Mythos access.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]

The main episode surveys the models trying to fill the Fable gap: Chinese open-weight releases like Kimi 2.7 Code, Weibo AI's tiny Vibe Thinker 3B, and especially Z.ai's GLM 5.2 — number one on several benchmarks at a tenth of Fable's cost — plus Cursor's Composer 2.5, OpenRouter's Fusion compound-model API, and Harvey's open-worker/frontier-advisor architecture. Whittemore argues the ban accelerates a shift toward inference optimization and multi-model sophistication that rising frontier costs were forcing anyway.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]

# Key points

- At a closed-door G7 lunch, Amodei and Hassabis led calls for US-led international cooperation on AI risk; Amodei proposed structured frontier-model access, chip trade deals excluding China, and unified approaches to cyberattack and bioterrorism risks, urging leaders to "resist the temptation to splinter."[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Macron pleaded for the US not to keep frontier AI to itself; Keir Starmer's request for a UK carve-out from export controls was denied; Italian politician Bruno Benafee said "the Anthropic kill switch shows that tech sovereignty was never abstract."[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Altman called for an international forum setting globally accepted testing standards; OpenAI's Chris Lehane said democratic countries are coalescing around a US-led AI-safety-standards body tied to continued frontier-model access.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Europe's compute gap: the European Commission's five AI gigafactories plan committed only 20 billion euros for ~100,000 GPUs, while US hyperscalers spend roughly three times that every month.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Wired reported the US ordered Anthropic to revoke SK Telecom's Mythos access days before the ban over alleged China ties — a rationale analysts disputed, noting SK Telecom doesn't use Huawei equipment.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Transformer co-author Noam Shazeer left Google for OpenAI to work on new model architectures, less than two years after Google's $2.7B Character AI licensing deal to retain him; observers say his exit clouds Gemini's roadmap, with Gemini 3.5 Pro rumors gone quiet.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- OpenAI is sunsetting Pulse, its daily-briefing feature, pushing users toward scheduled tasks (now available on all paid tiers) — read by some as a signal OpenAI is deprioritizing non-coder subscribers.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Bloomberg, Fortune, and CNBC converged on the view that open source is the ban's biggest winner: locally run open models "never have to worry about being yanked on a whim" — predictability, not just cost, now drives the open-weight case.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- GLM 5.2 dropped the day after the ban: number one on BridgeBench and reasoning, beating Fable 5 at 1/10 the cost and 300 tokens/second, ahead of all Opus models on frontend code arena — though internal evals and benchmark-maxing caveats place it behind Opus 4.8 and GPT 5.5, and it reportedly insists it is Claude, fueling distillation talk.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Other alternatives: Kimi 2.7 Code (22% better on Kimi Code Bench V2 but ranked only 19th on Agent Arena) and Vibe Thinker 3B, a 3-billion-parameter model posting Opus 4.5-league coding scores by cranking reasoning and externalizing knowledge.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Axios reports Microsoft may power Copilot Co-work with a locally hosted DeepSeek V4 fine-tune in coming weeks — an irony commentators noted: the US bans its own frontier models worldwide while its most embedded enterprise vendor ships a Chinese model into the Fortune 500.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Cursor's Composer 2.5 (built on a Kimi base) draws price-performance praise — "$1 for 65% versus Fable's $12 for 70%" — but fell significantly on Artificial Analysis's updated agentic-coding benchmarks, landing nearer GLM 5.1 than Opus 4.7.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- OpenRouter's Fusion API fans prompts out to a model panel with a judge and synthesizer, claiming Fable-level intelligence at half the price; Harvey's Fireworks experiment pairs an open-weight GLM 5.1 worker with an Opus 4.7 advisor, cutting cost while increasing performance.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]
- Harvey's Gabe Perriello: agents exploded costs rather than tokens getting cheap — "every company is about to get the ability to hire infinite employees," and the challenge is managing them within a workable business model.[^the-models-trying-to-replace-fable-4hvA6aCwf6E]

# Takeaways

Whittemore concludes that most observers extended, not shortened, their timelines for Fable's return, and that the White House's actions have durably shifted global tone on AI dependency. His core argument: "smart routing beat brute force" — as Patrick O'Shaughnessy put it, inference optimization is now a first-class competitive advantage, and using the most expensive model for every task is laziness, not quality strategy. The silver lining of the chaos is that companies are being forced to develop the multi-model sophistication that rising frontier costs would have demanded anyway, rather than staying "lost in the sauce of the glory of Fable 5."[^the-models-trying-to-replace-fable-4hvA6aCwf6E]

[^the-models-trying-to-replace-fable-4hvA6aCwf6E]: "The Models Trying to Replace Fable", The AI Daily Brief, YouTube, 2026-06-19 [Mirrored transcript](/references/the-models-trying-to-replace-fable-4hvA6aCwf6E.md)

# Related topics

- [Fable 5 Shut Down by US Government](/topics/fable-5-shut-down-by-us-government-5-CGzLrA4fg.md) — outcome — ban pushes enterprises to GLM and routing alternatives
- [Fable Is Back: Here''s What You Should Try First](/topics/fable-is-back-here-s-what-you-should-try-first-ztCLWKwyMJY.md) — counterpoint — return challenges the replacement stack built during ban
- [Why AI Users Are Raving About GLM 5.2](/topics/why-ai-users-are-raving-about-glm-5-2-HkVpSoaIKsc.md) — agreement — GLM 5.2's rise amid ban fallout
- [How AI Changes if Open Source Gets Banned](/topics/how-ai-changes-if-open-source-gets-banned-kpGZ83XqDqA.md) — shared-mechanism — routing around a suddenly unavailable frontier model
- [The Era of Vertical AI Models](/topics/the-era-of-vertical-ai-models-DvNKYftvPW0.md) — continuation — Composer and routing adopted after Fable ban
