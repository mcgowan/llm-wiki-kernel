---
type: Topic
title: How To Build a Personal Agentic Operating System
description: "Nofar Gaspar introduces the free Agent OS training program: a seven-layer, tool-neutral framework of text files — identity, context, skills, memory, connections, verification, and automations — that makes any agentic tool work better."
tags:
- agent-os
- agentic-systems
- personal-ai-systems
- context-engineering
- agent-skills
- ai-training-programs
- chief-of-staff-agent
status: stable
published_at: '2026-04-25T18:59:36+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:50Z'
sources:
- id: how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA
  resource: https://www.youtube.com/watch?v=ntvkDnk_5jA
  title: How To Build a Personal Agentic Operating System
---

# Overview

In this Operators bonus episode, Nathaniel Whittemore is joined by Nofar Gaspar to introduce Agent OS, a free AIDB training program (following AIDB New Year and Claw Camp) that is deliberately platform-, model-, and harness-neutral. Gaspar's core argument: every agentic tool is converging on the same capabilities — Cursor adding agents and automations, Claude Code adding memory systems, OpenClaw reading files and running background work — so the tool you pick matters less and less, while the system you build underneath matters more and more. Because these tools all ultimately read human-readable text files, the system is portable: switch tools, point the new one at the same folder, no migration needed.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]

Gaspar walks through the seven layers of an agentic operating system — identity, context, skills, memory, connections, verification, and automations — using a "chief of staff" agent (her own is named Chloe, running on OpenClaw) as the running example, with the emphasis on knowledge work rather than coding: strategy, communication, operations, decision-making, research, and management.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]

# Key points

- Layer 1, identity: the file the tool reads first (soul in OpenClaw, agents.md in Cursor, CLAUDE.md in Claude Code, copilot-instructions in GitHub Copilot) capturing who you are, how you communicate, what you value, and hard rules like "never send external email without showing me a draft."[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Gaspar's build method for every layer: don't write from scratch — brain dump to an AI, have it interview you ("ask me 15 questions about how I work"), ship a ~70%-right MVP, then patch gaps over the following weeks.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 2, context: "what you know" is the single biggest predictor of useful versus generic output, and it will never be solved by better models — no model will know your roadmap or stakeholders unless you tell it. Aim for 3-5 focused one-page files (my team, my product, my quarter), dated and fresh, rather than a stale 40-page document.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- "Context curation" is a practice, not a project: any time you catch yourself re-explaining your situation to AI, that thing belongs in a context file — Gaspar calls it "the single fastest path to AI value."[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 3, skills: reusable instruction sets for repeated workflows (weekly status updates, meeting pre-reads, voice matching, commitment tracking); every knowledge worker has 20-30 such patterns, and a skill written once "fires forever."[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 4, memory: lean on your tool's built-in memory but understand its limitations (ask it directly "explain how your memory system works"), and be deliberate about what gets remembered — e.g., dedicated decision logs and relationship context for the chief of staff.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 5, connections (MCP, CLI tools, direct APIs): start read-only and add write access only after weeks of observed trust, because risk scales with capability — she cites real incidents of agents with loose Slack permissions gossiping private notes and draft feedback to colleagues.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 6, verification: the worst failure mode is an agent that "works confidently and wrongly"; run 3-5 quick task-specific checks per output, plus periodic retrospectives auditing which skills go uncalled and which context files are stale — without this discipline the OS goes stale in about 8 weeks.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- Layer 7, automations: powerful but risky ("an agent running at 3:00 a.m. with a wrong answer can do damage before you wake up") — only automate workflows you've run manually, start with drafts for review, and always add logs.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]
- The compounding payoff: the first agent is hard because you build the OS and the agent simultaneously (a weekend), but the second agent inherits everything and takes an afternoon, and each subsequent one gets faster — agents become cheap once the OS exists.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]

# Takeaways

Whittemore frames Agent OS as the third stage in a rapid evolution of AIDB's free programs: AIDB New Year taught disconnected foundational skills, Claw Camp was tool-specific, and Agent OS reflects the new reality that "it's not about the tool, it's not about the model, it's not about the harness" — the durable asset is the system underneath that lets you swap harnesses and models freely. Gaspar's closing argument is that the people who build this foundation now will have it compound indefinitely, while everyone else keeps starting over with each new tool; the OS travels with you, and every new capability that drops lands on the same foundation.[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]

[^how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA]: "How To Build a Personal Agentic Operating System", The AI Daily Brief, YouTube, 2026-04-25 [Mirrored transcript](/references/how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA.md)

# Related topics

- [A Primer on Using Agent Skills](/topics/a-primer-on-using-agent-skills-NU6wRAT9VQ0.md) — shared-mechanism — portable reusable layers for agentic tools
- [Agent Skills Masterclass with Nufar Gaspar](/topics/agent-skills-masterclass-with-nufar-gaspar-fs_Y3gvj7lk.md) — same-series — Gaspar's agentic training frameworks
- [How I Built My 10 Agent OpenClaw Team](/topics/how-i-built-my-10-agent-openclaw-team-HzVYgpMxMLE.md) — shared-mechanism — assembling personal multi-agent systems for non-engineers
- [How to Use Opus 4.7 and the New Codex](/topics/how-to-use-opus-4-7-and-the-new-codex-5LdCJHnGwNo.md) — shared-mechanism — chief-of-staff agent pattern for personal work
- [The 16 Coolest Agents I've Built So Far](/topics/the-16-coolest-agents-i-ve-built-so-far-CnxQpf02_js.md) — shared-mechanism — chief-of-staff style agents running personal operations
- [The Best Way to Talk to Your Agents](/topics/the-best-way-to-talk-to-your-agents-NNxGQw1uQHc.md) — shared-mechanism — portable text-file layers structure agent communication
