---
type: Topic
title: How to Use Claude's Massive New Upgrades
description: "A month-long retrospective of Anthropic's feature blitz — remote control, Dispatch, channels, scheduled tasks, and computer use — converging on an always-on, persistent orchestration model for working with Claude."
tags:
- claude-code
- claude-cowork
- computer-use
- dispatch
- anthropic
- remote-control
- agent-orchestration
status: stable
published_at: '2026-03-24T21:44:41+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:50Z'
sources:
- id: how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA
  resource: https://www.youtube.com/watch?v=wZB5fpm8oUA
  title: How to Use Claude's Massive New Upgrades
---

# Overview

Nathaniel Whittemore devotes a full retrospective to the "absolute boatload" of features Anthropic shipped across the Claude ecosystem in a month — a response, he suggests, to everyone talking about Open Claude instead of Claude Code. He places the blitz in a lineage: the Opus 4.5 / GPT 5.2 model generation created a new capability era, Open Claude's harness made personal agents viable, and the ensuing "Claudification" race pushed those interaction patterns into every major product — with Anthropic folding them into its own suite via remote control, Dispatch, channels, scheduled tasks, and — the blockbuster — computer use, whose announcement drew 40 million views in 16 hours.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]

The aggregate picture, Whittemore argues, is a massive shift in how Anthropic imagines people working with Claude: "an always-on, context-maintaining, persistent, interactive orchestration experience where work is happening all the time, even when you're not doing it," reachable from wherever you are.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]

# Key points

- Remote control (late February): start a Claude Code task in your terminal, continue from your phone — the session runs entirely locally with your full environment (file system, MCP servers, tools); start via the remote control command, a QR code, or /rc in an existing session. Peter Levels compared it favorably to SSH; one user shipped an App Store update during a half-day walk.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Gagan Saluja's framing of remote control: "That's not a productivity feature. That's a relationship shift. You stop thinking of it as a tool you operate and start thinking of it as something you delegate to and check in with."[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Dispatch (Claude Co-work research preview): one persistent, context-retaining conversation that spawns the right session per task (Claude Code for dev, Co-work for knowledge work), messaging you outcomes — a spreadsheet, memo, or PR — with push notifications for approvals; the desktop must be running.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Pavel Huryn's 48-hour Dispatch report: it's "an orchestrator," not Claude chat on your phone — "your phone is the command chair, your desktop does the heavy lifting"; ~25 minutes of direction across gaps in his day yielded 3+ hours of parallel Claude execution, letting him "design your day differently."[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Claude Code channels: MCP servers (starting with Telegram and Discord) that push outside events — CI failures, webhooks, monitoring alerts, chat messages — into a running session so Claude can react while you're away; positioned as the hackable, dev-focused option, with one builder shipping a custom iOS orchestration app four days after launch.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Scheduled tasks arrived in three waves: Co-work scheduled tasks (morning briefings, weekly spreadsheets), local scheduled tasks in Claude Code desktop (e.g., checking error logs every few hours and creating PRs), and recurring cloud-based tasks that run on cloud infra without your machine on — used by the Claude Code team for PR sweeps, overnight CI analysis, and doc syncs.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Computer use (Monday night): Claude controls mouse, keyboard, and screen to use any app, reaching for precise connectors first and falling back to pointing and clicking with no setup — supercharging Dispatch (morning briefings from the train, IDE changes and PRs, even keeping a 3D-printing project moving).[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Peter Gostev notes computer use matters for corporates "stuck in custom crappy apps from 20 or 30 years ago"; Aaron Levie calls computer use plus on-the-fly code "the ultimate primitives for agents," while flagging open problems in security, agent identity, prompt injection, and headless-software readiness.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Quality-of-life additions: projects in Co-work, code review (a dispatched team of bug-hunting agents), general availability of the 1M-token context window for Opus and Sonnet (Garry Tan: "Claude Code is so much better"), interactive charts in the Claude app, integrated Claude for Excel/PowerPoint with shareable skills, memory and connectors on the free plan, and an enterprise plugin marketplace.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]
- Ethan Mollick observes that the Claude team's ability to learn from Open Claude and ship features daily "is a very strong argument that for AI-powered coding teams, a very different software development process is possible with large strategic implications."[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]

# Takeaways

Whittemore's summary checklist: computer use (Claude controls your computer, even non-native apps), Dispatch (orchestrate Co-work from your phone), remote control (Claude Code on the go), channels (external events piped into sessions via Telegram/Discord), and scheduled tasks (local or cloud). He advises hacking at all of them to find personal fits, since the variations on remote interaction only make sense once lived rather than heard about — and points listeners to a companion checklist at play.aidailybrief.ai. The through-line is that Anthropic has vindicated the "let him cook" camp on losing Open Claude's founder to OpenAI, out-shipping the moment with a persistent, always-on orchestration vision of work.[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]

[^how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA]: "How to Use Claude's Massive New Upgrades", The AI Daily Brief, YouTube, 2026-03-24 [Mirrored transcript](/references/how-to-use-claude-s-massive-new-upgrades-wZB5fpm8oUA.md)

# Related topics

- [The OpenClaw-ification of AI](/topics/the-openclaw-ification-of-ai-GR-j31Nrl0Y.md) — agreement — same Anthropic feature wave read as OpenClaw-ification
- [Vibe Coding Gets an Upgrade](/topics/vibe-coding-gets-an-upgrade-rNDaRO68JEc.md) — agreement — Anthropic products converging on agent orchestration
- [How to Use Claude Cowork on the Go](/topics/how-to-use-claude-cowork-on-the-go-vIBXClZf2dM.md) — same-series — both chart Anthropic's Dispatch upgrade wave
- [Why Claude Cowork is a Big Deal](/topics/why-claude-cowork-is-a-big-deal-mJWi_koYY70.md) — continuation — Cowork's debut precedes this upgrade month
