---
type: Topic
title: 9 Codex Tips from the Codex Team
description: "A practical walkthrough of Codex team member Jason Liu's 'Codex maxing' tips — durable mono-threads, voice rambling, steering, file-based memory vaults, heartbeats — plus headlines on Cursor's Composer 2.5 and the verdict in Musk v. OpenAI."
tags:
- openai-codex
- agent-workflows
- cursor
- composer
- elon-musk
- openai
- coding-agents
status: stable
published_at: '2026-05-20T02:15:46+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:04Z'
sources:
- id: 9-codex-tips-from-the-codex-team-dB-Kbylgrdk
  resource: https://www.youtube.com/watch?v=dB-Kbylgrdk
  title: 9 Codex Tips from the Codex Team
---

# Overview

With Codex on a tear — from almost no users at the start of the year to mid single-digit millions, aided by Anthropic cutting off subsidized usage outside its own harnesses — Whittemore devotes the main episode to a hands-on 101 drawn from "Codex maxing," a GitHub post by Jason Liu of the Codex team. Liu's nine practices add up to one larger shift: treating Codex not as a prompt-and-wait chat interface but as an entire workspace, and above all "not breaking the loop" — keeping agents working in parallel with their human partner instead of in an endless series of turns.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]

The headlines argue that Cursor's Composer 2.5 is more interesting than the Musk-OpenAI verdict: the "harness-first labs" are now genuinely competing on models, with Composer 2.5 landing within a point of Opus 4.7 on key benchmarks at half the cost and roughly 10x the token efficiency. Meanwhile Cloudflare published one of the most useful reviews of Anthropic's secretive Mythos model, and a jury took just two hours to unanimously reject Elon Musk's breach-of-charitable-trust suit against OpenAI on statute-of-limitations grounds.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]

# Key points

- Composer 2.5 scored 69.3% on Terminal Bench 2.0 (Opus 4.7: 69.4%) and 79.8% on SWE-bench multilingual (Opus 4.7: 80.5%, GPT-5.5: 77.8%), served at $0.50/M input and $2.50/M output tokens — half the cost of Opus 4.7 or GPT-5.5 — with SWE-bench runs under $1 per task versus ~$5 (GPT-5.5 extra-high) and ~$11 (Opus 4.7 max).[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Composer 2.5 is still built on Moonshot's Kimi 2.5 base, implying the whole gain came from better RL post-training — evidence there's huge room to post-train open-source models to frontier level on discrete tasks; Cursor is also training a model from scratch on xAI's Colossus 2 cluster ("a million H100 equivalents"), following the deal giving xAI an option to buy Cursor for $60 billion. CEO Michael Truell had declared "wartime" in January, making the best coding model the company's top priority.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Chamath Palihapitiya's warning to consulting firms deploying OpenAI/Anthropic directly ("you're letting the fox into the hen house... controlling the tokens is controlling the spice") illustrates the open lane for model-agnostic harness companies.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Cloudflare on Mythos preview: "a real step forward" — unlike prior models it synthesizes multiple attack primitives into functional exploit chains ("more like a senior researcher rather than an automated bug scanner") and generates working proofs rather than false-positive lists, testing and refining exploits that fail.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Musk v. OpenAI: after 3 weeks of testimony the jury needed 2 hours to find the charitable-trust claim time-barred — OpenAI showed Musk knew of for-profit plans as early as 2018 (term sheet) and had himself proposed folding OpenAI into Tesla in 2017; the Microsoft aiding-and-abetting and restitution claims fell with it. Musk had sought removal of Altman and Brockman plus $134 billion in damages. The Verge: the trial "accomplished nothing but airing dirty laundry" (including the Altman ouster week, internally called "the blip").[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Liu's tips 1-3: durable mono-threads per key work stream, relying on Codex's improved compaction (e.g., his "chief of staff" thread); voice input — "the art of the ramble" gives the model the messy version of your thinking ("a lot of plans get better when the model has access to the messy version of what I think, not just the polished one"), with Codex's built-in speech-to-text "the gold standard"; and the steer feature, adding or updating the prompt mid-flow so human and agent work in parallel rather than turn-by-turn.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Tip 4 — memory as files: native memory settings suit stable preferences, but work should "leave behind structured memory, not just a longer chat." Liu keeps an Obsidian vault (also a GitHub repo for cloud work) with a top-level agents.md instructing the agent to update pages on people, projects, decisions, and open loops; "files force the agent to compress experience into a form that can survive the thread," so pinned threads become "different workers reading from the same notebook."[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Tips 5-7: tools (computer use for local artifacts, browser use for visual/live inspection, connectors for Slack/Gmail/GitHub/Notion) turn Codex into an evidence gatherer; remote control and the ChatGPT-app version disentangle work from the desk for steering hours-long jobs on the go; heartbeats — scheduled or triggered thread wake-ups, e.g., checking Slack/Gmail every 30 minutes, or an animation loop that checked a Slack thread every 15 minutes, re-rendered on feedback, and used computer use to upload the file when the Slack MCP server couldn't.[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]
- Tips 8-9: the /goal feature (now in both Codex and Claude Code) keeps agents pushing against verifiable success criteria — Whittemore defers a full goals guide to a coming episode; and the side panel, which Liu calls the part of Codex he's most excited about — inspecting artifacts, operating web services, and reviewing changes "without breaking the loop," where "Codex stops being only a chat app and starts becoming the place where work happens."[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]

# Takeaways

Whittemore frames this as the "year of the harvest": unlocking agents means getting good at the harness software itself. The meta-lesson of Liu's nine tips is the behavior shift from turn-based prompting toward continuous parallel collaboration — capturing intent by voice, steering work in flight, serializing what threads learn into inspectable files, and wiring heartbeats, connectors, and computer use into feedback loops "that keep running without me sitting there." He stresses this doesn't mean 24/7 agents are mandatory, but for anyone distracted by context-switching while waiting on ever-bigger jobs, the reframing has "a lot of potential to reintegrate those work experiences." On the Musk trial, his conclusion is relief: leaders' public feuding only reinforces the popular view of AI as a rich man's game, and he's glad "this particular bun fight is done."[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]

[^9-codex-tips-from-the-codex-team-dB-Kbylgrdk]: "9 Codex Tips from the Codex Team", The AI Daily Brief, YouTube, 2026-05-20 [Mirrored transcript](/references/9-codex-tips-from-the-codex-team-dB-Kbylgrdk.md)

# Related topics

- [How to Use Opus 4.7 and the New Codex](/topics/how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo.md) — agreement — mono-thread and heartbeat patterns appear in both
- [Automating Your AI Context](/topics/automating-your-ai-context-jSPFi-mW0ns.md) — continuation — Codex gains Chronicle screenshot memory
- [10 Sites Knowledge Workers Should Build with AI](/topics/10-sites-knowledge-workers-should-build-with-ai-45UGHbqq2fQ.md) — same-series — practical Codex usage guidance episodes
- [The Whole World Gets Claude-Pilled](/topics/the-whole-world-gets-claude-pilled-YDQ4Fpcv4Z8.md) — continuation — Musk-OpenAI legal fight, verdict then aftermath
- [The Era of Vertical AI Models](/topics/the-era-of-vertical-ai-models-DvNKYftvPW0.md) — continuation — Cursor's Composer line advances to 2.5
