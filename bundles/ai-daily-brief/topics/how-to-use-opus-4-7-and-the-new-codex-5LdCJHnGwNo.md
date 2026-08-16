---
type: Topic
title: How to Use Opus 4.7 and the New Codex
description: "A hands-on guide to Anthropic's Opus 4.7 and OpenAI's new Codex app — computer use, heartbeats, the mono-thread/chief-of-staff pattern, and diverging UI philosophies between the two ecosystems."
tags:
- opus-4-7
- codex-app
- computer-use
- mono-thread
- chief-of-staff-agent
- knowledge-work
- model-releases
status: stable
published_at: '2026-04-18T18:35:46+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:50Z'
sources:
- id: how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo
  resource: https://www.youtube.com/watch?v=5LdCJHnGwNo
  title: How to Use Opus 4.7 and the New Codex
---

# Overview

Nathaniel Whittemore unpacks a double release day — Anthropic's Opus 4.7 model and a major new iteration of OpenAI's Codex app — focusing on what knowledge workers, not just developers, should actually try. His framing tweet captures the theme: the problem with "vibe coding" wasn't that all coding became vibe coding, but that "all knowledge work is becoming coding work" — visible in Codex's evolution from a coding app into a general work surface with computer use on Mac, an in-app browser with comment mode, native image generation (GPT Image 1.5), rich file previews, heartbeats, and project-less threads.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]

Opus 4.7 arrives shadowed by the anticipated Mythos preview it is not, but Whittemore argues it's a meaningful jump in its own right — "literally one step better than 4.6 in every dimension" per Latent Space — and requires new interaction habits: delegate rather than micromanage, front-load full goals and constraints, and build in verification loops. He closes on the diverging UI philosophies: Codex bets the interface should disappear into one thread, while Claude desktop bets that chat, co-work, and code are distinct enough to warrant separate modes.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]

# Key points

- New Codex features: computer use on Mac (its own cursor, parallel background agents, works on apps without APIs; Windows coming), in-app browser comment mode for pointing at page elements, native GPT Image 1.5 generation, inline previews of PDFs/spreadsheets/slides, tabbed terminals, a menu-bar mini window with global hotkey, and project-less threads (Jason Liu's "new notes app").[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Heartbeats — automations that maintain context in a single thread over time — are an explicit Open Claude lesson per OpenAI's Pash: "a good teammate doesn't start from scratch every time you check in"; Codex can even schedule its own next steps.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Nick Bowman's "mono-thread pilled" pattern: one main teammate thread orchestrates and exercises judgment while long-lived specialist sub-agent threads keep depth, waking on automations to check Slack, Gmail, and GitHub and interrupting only when something matters — enabled by compaction improvements that break the old assumption that long threads degrade ("It can compact like three times and the model still remembers the details").[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Jason Liu's Codex chief-of-staff recipe: a local folder vault as durable memory with a small agents.md, projects and notes folders, an onboarding interview, and a 15-minute heartbeat loop that checks sources, spots blockers, and keeps improving its own prompts and notes over time — the one thing Whittemore says to try first.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Aaron Levie reads the new Codex as "another jump in what agents will look like for knowledge workers" — drafting reports, setting up merger data rooms, reviewing contracts, processing invoices.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Opus 4.7 benchmark jumps: 4.7-low beats 4.6-medium and 4.7-high beats 4.6-max on agentic coding; Finance Agent 60.1→64.4%, Office QA Pro 57.1→80.6%, OSWorld computer use 72.7→78%; it made ~20% more money on Vending Bench 2, and testers praise its design sensibility ("the best PowerPoint I've ever seen in an LLM" — Mike Taylor; state-of-the-art agentic CAD per Adam.new).[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- One regression: a long-context retrieval benchmark fell from 78.3% to 32.2%, though Claude Code creator Boris Cherny said that benchmark is being phased out for overweighting distractor-stacking tricks.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Anthropic's usage tips (Cat Wu): treat 4.7 like a capable engineer, not a pair programmer — progressive clarification across turns can reduce quality; give goals, constraints, and acceptance criteria up front; and explicitly build verification loops since 4.7 self-verifies better than any previous Claude. Cherny: use extra-high effort by default, max (session-only) for the hardest tasks.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Whittemore's own design test (redesigning the AI Daily Brief site) found 4.7 offers more visual variety and thoughtful reasoning than 4.6, but only when deliberately slowed down before it "rips out" something good-looking but under-considered.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- Things to try with 4.7: vision-heavy tasks (whiteboard photos, dashboard screenshots, charts in 10-Ks, competitor onboarding-flow comparisons) and longer un-chunked tasks — end-to-end research, legal argument construction, investment theses — that previously required breaking into pieces.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]
- UI philosophy split: Codex is "one text box, infinite capabilities" (Riley Brown: "If you ask for a coding task, it writes code... If you ask for a presentation or doc, it gives you a presentation or doc"), betting mode-switching is friction; Claude desktop toggles between chat, co-work, and code, betting the modes are different enough that collapsing them creates compromise.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]

# Takeaways

Whittemore concludes that even without Mythos or OpenAI's "Spud," this pair of releases represents a significant capability and feature set that will take time to integrate into how people work. The recurring theme from Anthropic — "less babysitting and more real delegation" — and from OpenAI's mono-thread architecture points the same direction: persistent, context-accumulating agent relationships replacing fresh-start chats. His personal weekend experiment: the mono-thread/Codex chief of staff, to compare against the version he originally built in Open Claw, with 11 more try-now ideas at his companion site play.aidailybrief.ai.[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]

[^how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo]: "How to Use Opus 4.7 and the New Codex", The AI Daily Brief, YouTube, 2026-04-18 [Mirrored transcript](/references/how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo.md)

# Related topics

- [9 Codex Tips from the Codex Team](/topics/9-codex-tips-from-the-codex-team-dB-Kbylgrdk.md) — agreement — mono-thread and heartbeat patterns appear in both
- [Opus 4.6 and ChatGPT 5.3-Codex Are Here and the Labs Are at War](/topics/opus-4-6-and-chatgpt-5-3-codex-are-here-and-the-JqpI65aVJ30.md) — continuation — next versions of both dueling model lines
- [First Impressions of the New Opus 4.8](/topics/first-impressions-of-the-new-opus-4-8-zf8BfgJghd8.md) — continuation — successor release in the same Opus line
- [GPT-5.4 First Test Results](/topics/gpt-5-4-first-test-results-xIIj9hkISUE.md) — counterpoint — rival Anthropic release with diverging computer-use UI
- [How To Build a Personal Agentic Operating System](/topics/how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA.md) — shared-mechanism — chief-of-staff agent pattern for personal work
- [Where Should Claude Opus 5 Fit In Your Model Rotation](/topics/where-should-claude-opus-5-fit-in-your-model-rot-PL2JrJRaDSg.md) — continuation — Opus line's next major release
