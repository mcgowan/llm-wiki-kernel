---
type: Topic
title: The Latest AI Models and Model Rumors
description: "A headlines catch-up covering OpenAI's 1,000-tokens-per-second GPT-5.3 Codex Spark on Cerebras chips, Google's benchmark-smashing Deep Think upgrade with the Alethea math agent, DeepSeek V4 anticipation, and Anthropic's $30B raise at $380B."
tags:
- gpt-codex-spark
- cerebras
- gemini-deep-think
- deepseek
- anthropic-funding
- claude-cowork
- chinese-ai-labs
status: stable
published_at: '2026-02-17T13:37:46+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:27Z'
sources:
- id: the-latest-ai-models-and-model-rumors--plNBWEQhHU
  resource: https://www.youtube.com/watch?v=-plNBWEQhHU
  title: The Latest AI Models and Model Rumors
---

# Overview

Catching up after travel, Nathaniel Whittemore runs through a dense week of model news. OpenAI released GPT-5.3 Codex Spark, a speed-first coding model serving 1,000 tokens per second — roughly 15x faster than regular GPT-5.3 Codex — served exclusively on Cerebras wafer-scale chips, OpenAI's first model designed for non-Nvidia hardware. Google answered with an upgraded Gemini Deep Think that smashes benchmarks (84.6% on ARC-AGI-2 versus Opus 4.6's 68.8%) and adds Alethea, an agent built to autonomously generate and verify novel proofs in pure mathematics.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]

On the rumor front, a flurry of Chinese releases — Zhipu's GLM-5, ByteDance's SeeDance — is read as labs getting in under the wire before DeepSeek V4's expected Lunar New Year release, which Swyx says may finally change his three-year cynicism on open-source AI. Anthropic closed its $30 billion round at a $380 billion post-money valuation on the back of ARR growth from $1 billion in January 2025 to $14 billion, and pushed Claude Co-work to Windows with full macOS parity as Microsoft scrambles to build rival Copilot features.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]

# Key points

- GPT-5.3 Codex Spark serves inference at 1,000 tokens/second (~15x regular 5.3 Codex) with tradeoffs: a 128K context window, no multimodal inputs, no long-horizon tasks, and a benchmark step-down — though still well above 5.1 Codex Mini.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Dan Shipper of Every: Spark suits pair-programming flow and easy-to-validate, non-production tasks, but "this kind of speed introduces totally new bottlenecks... It requires a totally new UX to manage."[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Spark is OpenAI's first model built for non-Nvidia hardware, served exclusively on Cerebras wafer-scale chips; Cerebras CEO Andrew Feldman: "In coding, responsiveness is the product."[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- OpenAI frames Spark as step one toward a two-mode Codex — long-horizon reasoning plus real-time collaboration — that will eventually blend, delegating longer work to background sub-agents.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Google's upgraded Deep Think (the model that earned gold-medal performances at the IMO and ICPC) scores 84.6% on ARC-AGI-2 (previous best: Opus 4.6 at 68.8%) and a state-of-the-art 48.6% on Humanity's Last Exam (previous best: Opus 4.6 at 40%), at ~$14 per task — comparable to GPT-5.2 Pro.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Deep Think's new agentic scaffold Alethea targets math research — generate, verify, and loop until a correct solution — with expansions planned into physics and computer science; the model has already contributed to several academic papers this year.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Pre-Spring Festival China deluge: Zhipu's frontier GLM-5, ByteDance's state-of-the-art SeeDance video model, and Alibaba/Baidu shopping-agent pushes — with DeepSeek V4 expected at Lunar New Year. Swyx: "the stage is set for whale fall," suggesting rivals released early because they couldn't compete with what's coming.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Anthropic closed $30B at a $380B post-money valuation with VCs, sovereign wealth funds, and Fidelity, BlackRock, Blackstone, Goldman Sachs, Morgan Stanley, and JP Morgan participating.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Anthropic ARR grew from $1B (January 2025) to $14B; $100K+ customers grew 7x in a year; $1M+ customers went from a dozen two years ago to over 500; eight of the Fortune 10 use Anthropic tools; Claude alone generates $2.5B, more than doubling this year.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Ramp data shows Anthropic at 19.5% of businesses (up from 16.7%) while OpenAI slipped to 35.9%; Whittemore notes 79% of Anthropic customers are already OpenAI customers with nearly identical 4% churn — growth is overlapping, not zero-sum displacement.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Anthropic donated to new social-welfare organization Public First Action for AI public education and safeguards, citing polling that 69% of Americans think government isn't doing enough to regulate AI.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]
- Claude Co-work launched on Windows with full macOS parity (file access, multi-step tasks, plugins, MCP connectors); The Information reports Microsoft set up an internal channel — including Satya Nadella, who has been testing OpenClaw — to rapidly develop rival Copilot features.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]

# Takeaways

Whittemore reads the week as evidence that coding has cemented itself as AI's most important use case — important enough that models are now specializing by coding-task type, and that OpenAI will diversify beyond Nvidia silicon to win on responsiveness. He flags the DeepSeek V4 release as the potential moment open-source skeptics change their stance, and cautions against simple "Anthropic is beating OpenAI" narratives given the heavy customer overlap. More on the White House-Anthropic tension, he notes, is coming later in the week.[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]

[^the-latest-ai-models-and-model-rumors--plNBWEQhHU]: "The Latest AI Models and Model Rumors", The AI Daily Brief, YouTube, 2026-02-17 [Mirrored transcript](/references/the-latest-ai-models-and-model-rumors--plNBWEQhHU.md)

# Related topics

- [How Deepseek v4 Connects to the US Grid](/topics/how-deepseek-v4-connects-to-the-us-grid-qkKEV9rkFqI.md) — continuation — anticipated DeepSeek V4 finally ships
- [Grok 4.6 Shows How Fast Your AI Options Are Expanding](/topics/grok-4-6-shows-how-fast-your-ai-options-are-expa-8exG3NcsKxw.md) — continuation — DeepSeek V4 anticipation ends in disappointment here
- [Opus 4.6 and ChatGPT 5.3-Codex Are Here and the Labs Are at War](/topics/opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30.md) — continuation — GPT-5.3 Codex gets Spark variant on Cerebras
- [What Google Needs to Do at I/O This Week](/topics/what-google-needs-to-do-at-i-o-this-week-8uCkUyRFUqY.md) — agreement — Cerebras IPO storyline corroborated
