---
type: Topic
title: All of AI's New Models and Tools
description: "A whistle-stop tour of the week's releases: Meta's first Superintelligence Labs model Muse Spark, Z.ai's open-source coding leader GLM 5.1, Anthropic's Claude Managed Agents platform, and Gemini's new notebooks feature."
tags:
- meta-muse-spark
- zai-glm
- open-source-ai
- claude-managed-agents
- agent-harness
- gemini
- model-releases
- ai-benchmarks
status: stable
published_at: '2026-04-10T00:45:11+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:13Z'
sources:
- id: all-of-ai-s-new-models-and-tools-20vZc0cOpOw
  resource: https://www.youtube.com/watch?v=20vZc0cOpOw
  title: All of AI's New Models and Tools
---

# Overview

Nathaniel Whittemore tours a week of hands-on releases that were overshadowed by models nobody can touch — Anthropic's Mythos, deemed too powerful for normal release and limited to ~40 cybersecurity-focused partners, and OpenAI's similarly staggered rollout plans. The accessible news: Meta Superintelligence Labs shipped Muse Spark, its first model in over a year and the first under the new Muse name (ditching Llama); Chinese lab Z.ai open-sourced GLM 5.1, the first open model to overtake leading Western models on coding benchmarks; Anthropic launched Claude Managed Agents; and Google added notebooks to Gemini.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]

The throughline Whittemore draws is agentic capability everywhere: Muse Spark aimed at personal agents, GLM 5.1 built for eight-hour autonomous execution, and Managed Agents packaging the harness and infrastructure needed to run agents at scale.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]

# Key points

- Muse Spark, from the Alexandr Wang-led Meta Superintelligence Labs, is a natively multimodal reasoning model with tool use, visual chain of thought, and multi-agent orchestration; it scored 52.4 on SWE-Bench Pro (a few points behind Opus 4.6, Gemini 3.1 Pro, GPT-5.4) and 42.8 on Humanity's Last Exam, but posted a state-of-the-art 86.4 on the CharXiv visual-comprehension benchmark, beating Gemini 3.1 Pro by six points.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Zuckerberg positioned Muse Spark for "personal superintelligence" — visual understanding, health, social content, shopping, games — with three modes (instant, thinking, contemplating), physician-curated health training data from a thousand doctors, and a promise: "products that don't just answer your questions, but act as agents and do things for you."[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Reception was mixed: Ethan Mollick found it "fine... just not the vibe level that the benchmarks might indicate"; François Chollet called it "over-optimized for public benchmark numbers"; Wang engaged directly, noting Meta publishes weak ARC-AGI-2 results and plans to open source future versions.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Z.ai's GLM 5.1 — a 754B-parameter full open-source release with commercial licensing — scored 58.4 on SWE-Bench Pro, beating GPT-5.4 (57.7) and Opus 4.6 (57.3); it reportedly built a Linux desktop autonomously over eight hours and ran 600+ iterations with 6,000+ tool calls on a database-optimization test.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Z.ai's leader framed autonomous work time as "the most important curve after scaling laws": agents did ~20 steps at end of last year, GLM 5.1 does 1,700. The model was trained entirely on less powerful Huawei chips, and its arrival two months after Opus 4.6/GPT-5.4 suggests the US lead over China remains only months.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Claude Managed Agents pairs a performance-tuned agent harness with production infrastructure — sandboxed environments, hours-long autonomous cloud runs, agent monitoring, and permission toggles — to close what Anthropic's Angela Jiang called a "notable gap" between model capability and business usage; a Notion demo showed drop-in client-onboarding agents without days of permissions setup.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Common Managed Agents patterns per Anthropic's Lance Martin: event-triggered (bug flagged, agent writes the patch and opens the PR), scheduled daily briefs, fire-and-forget tasks from Slack/Teams, and long-horizon tasks; persistent memory across sessions is not yet available, keeping current use cases transactional.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]
- Google's new Gemini notebooks replace the unintuitive Gems approach with proper project-style resource management plus custom instructions — "some of the magic of NotebookLM directly integrated into Gemini," pitched as personal knowledge bases shared across Google products.[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]

# Takeaways

Whittemore reads Muse Spark as Meta "coming back to life" — behind the leaders but a real re-entry within a year of the lab's formation — and GLM 5.1 as evidence that leading Chinese labs will still open-source their best models and that the Chinese hardware stack can deliver. On Managed Agents, he predicts it will "very quickly become a core part of Claude and Claude Code ecosystem," flagging a coming episode on harness engineering. And he argues Gemini notebooks, though not a model, may improve many users' daily experience more "than if they had released Gemini 3.3," as Google consolidates feature transportability so "any door you walk in gets you to the same room."[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]

[^all-of-ai-s-new-models-and-tools-20vZc0cOpOw]: "All of AI's New Models and Tools", The AI Daily Brief, YouTube, 2026-04-10 [Mirrored transcript](/references/all-of-ai-s-new-models-and-tools-20vZc0cOpOw.md)

# Related topics

- [How the 4 New Models Released This Week Will Change How You Work](/topics/how-the-4-new-models-released-this-week-will-cha-ZX9dXdAL5IU.md) — same-series — weekly new-model release roundups
- [Why AI Users Are Raving About GLM 5.2](/topics/why-ai-users-are-raving-about-glm-5-2-HkVpSoaIKsc.md) — continuation — Z.ai's GLM line surges a version later
- [Harness Engineering 101](/topics/harness-engineering-101-OTjZBjq5FPg.md) — shared-mechanism — Claude Managed Agents as harness productization
- [Meta Delays New AI Model](/topics/meta-delays-new-ai-model-eDGI3sNRnhg.md) — continuation — Meta ships Muse Spark after Avocado delay
- [How Harness-as-a-Service Will Change Agents](/topics/how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w.md) — same-series — Claude Managed Agents launch covered in weekly tour
