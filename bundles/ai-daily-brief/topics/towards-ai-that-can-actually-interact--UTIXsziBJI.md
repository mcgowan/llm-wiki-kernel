---
type: Topic
title: Towards AI That Can Actually Interact
description: Thinking Machines Lab introduces interaction models built for continuous real-time exchange rather than turn-based chat, plus OpenAI's DeployCo consulting venture and a crackdown on gray-market private shares.
tags:
- thinking-machines-lab
- interaction-models
- real-time-ai
- openai
- ai-consulting
- private-markets
- ai-policy
status: stable
published_at: '2026-05-13T17:38:56+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:36Z'
sources:
- id: towards-ai-that-can-actually-interact--UTIXsziBJI
  resource: https://www.youtube.com/watch?v=-UTIXsziBJI
  title: Towards AI That Can Actually Interact
---

# Overview

The main episode covers what Nathaniel Whittemore treats as a rare genuine category opening: Thinking Machines Lab's announcement of "interaction models," a class of model trained from scratch for continuous, time-aware exchange rather than turn-based conversation. Mira Murati's framing is that the current AI experience is a conversation that only begins after we stop talking, forcing users to batch thoughts and phrase questions like emails; Thinking Machines' bet is that interactivity must live inside the model and scale with intelligence rather than trail behind it as scaffolding.[^towards-ai-that-can-actually-interact--UTIXsziBJI]

The headlines cover OpenAI formalizing its consulting arm as DeployCo, Anthropic and OpenAI moving against gray-market secondary trading of their shares, the White House walking back an FDA-style model approval comparison, and Jensen Huang's conspicuous absence from Trump's China trade delegation.[^towards-ai-that-can-actually-interact--UTIXsziBJI]

# Key points

- OpenAI's DeployCo is a separate forward-deployed engineering company structured as a joint venture with 19 consulting, private equity, and finance partners; the initial $4 billion investment came at a $10 billion pre-money valuation, led by TPG with Advent International, Bain Capital, and Brookfield as co-lead founding partners. Goldman Sachs is the only partner backing both DeployCo and Anthropic's parallel effort.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- DeployCo is built around acquiring engineering firm Tomorrow, giving it roughly 150 experienced staff immediately; Whittemore notes investors reportedly want first access to these engineers for portfolio companies, and expects much more M&A since organic growth cannot meet demand.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Anthropic updated its support documentation to state that it does not permit SPVs to acquire its stock, that such transfers are void, and that third parties selling shares to the general public are likely committing fraud or offering something worthless; it named specific firms. OpenAI issued a similar blog post. Anthropic's notice halved the price on these gray markets in a day.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Lawyer Gabriel Shapiro warned that voiding transactions could trigger an avalanche of lawsuits; Brian Norgard predicted a private-market reckoning and said the SpaceX IPO will expose accumulated synthetic ownership; Kingsley Advani countered that Anthropic is unlikely to void half its investors given dozens of registered SPVs.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- NEC Chairman Kevin Hassett walked back his FDA-style safety approval comparison after industry backlash, saying nobody at the White House wants a giant new bureaucracy to approve AIs and that officials are instead working directly with labs pre-release; David Sacks said no senior official supported the FDA framing.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Trump's China delegation includes Elon Musk, Tim Cook, and Meta's Dina Powell McCormick plus Micron and Qualcomm executives, but not Jensen Huang, who had said he would join if invited; H200 export approvals have stalled with zero licenses issued by Commerce.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Thinking Machines' model, technically called TML Interaction Small, processes parallel input and output streams in 200-millisecond micro-turns rather than flattening exchanges into a single ordered token sequence, and pairs a real-time interaction model with a background model that handles longer reasoning, browsing, tools, and agentic work.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Demonstrated capabilities include noticing when someone new enters frame, simultaneous translation that begins before a sentence ends, dialogue management that tracks when a speaker is thinking or yielding, visual interjection (flagging slouching), real-time softening of blunt phrasing, and answering about a film released after training cutoff by searching in the background mid-conversation.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- The team introduced two new internal benchmarks for proactive audio — TimeSpeak (initiating speech at user-specified times with correct content) and QSpeak (speaking at the appropriate moment with the semantically correct response) — arguing no existing model can meaningfully perform tasks involving time awareness, verbal or visual cue triggers, or visual counting.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Background on the lab: Thinking Machines was founded by former OpenAI CTO Mira Murati, released Tinker (reinforcement learning as a service) last October to modest attention, and saw co-founders Barrett Zoph and Luke Metz return to OpenAI in January.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Team member Claire Birch framed interaction models as a GUI moment for AI, arguing chat remains surprisingly CLI-like in rewarding verbal fluency and procedural skill, and that the next interface should let people speak, show, point, interrupt, and revise in context — staying fluent in the task rather than fluent in the tool. Co-founder John Schulman predicted every AI system will eventually have an interaction model as its outer user-facing layer.[^towards-ai-that-can-actually-interact--UTIXsziBJI]
- Reactions: Swyx said everyone's definition of real-time just got a massive upgrade; Ethan Mollick complained the demos showcased fun or annoying real-time corrections rather than valuable uses in meetings, education, or training, which Nick Dobos attributed to it being a tech demo for an enterprise-and-VC audience; others predicted frontier labs will copy the abstraction quickly, noting OpenAI showed GPT Real-Time 2 acting as a background agent updating a Kanban board during a standup.[^towards-ai-that-can-actually-interact--UTIXsziBJI]

# Takeaways

Whittemore reaches for a concept he proposed around Nano Banana — an "unlock index" measuring models by how many and what kinds of new use cases they enable rather than by traditional benchmarks — and argues interaction models qualify, since Thinking Machines had to invent benchmarks to measure the capability at all. He reframes Murati's claim that how we work with AI matters as much as how smart it is as "situational smartness": creating the right setting for AI to be smart rather than dropping it into a world built for human-only work. He praises the team's messaging discipline, expects the capability not to remain unique for long given how fast frontier labs iterate on each other's abstractions, and reads the announcement plus OpenAI's real-time demos as evidence that the background agent paradigm — work proceeding passively alongside other activity — will matter. He calls it a surprising day when something feels like the beginning of an entirely new category, and says this does.[^towards-ai-that-can-actually-interact--UTIXsziBJI]

[^towards-ai-that-can-actually-interact--UTIXsziBJI]: "Towards AI That Can Actually Interact", The AI Daily Brief, YouTube, 2026-05-13 [Mirrored transcript](/references/towards-ai-that-can-actually-interact--UTIXsziBJI.md)

# Related topics

- [How the 4 New Models Released This Week Will Change How You Work](/topics/how-the-4-new-models-released-this-week-will-cha-ZX9dXdAL5IU.md) — shared-mechanism — interaction patterns moving beyond turn-based text chat
- [The Social Network for Agents Just Got Acquired](/topics/the-social-network-for-agents-just-got-acquired-2Ws3YiSzCX0.md) — continuation — Thinking Machines' Nvidia gigawatt follows interaction-model push
- [You Can Now Vibecode Mobile Apps](/topics/you-can-now-vibecode-mobile-apps-ltPO1ZgH4yw.md) — continuation — Thinking Machines exodus follows its interaction-model bet
