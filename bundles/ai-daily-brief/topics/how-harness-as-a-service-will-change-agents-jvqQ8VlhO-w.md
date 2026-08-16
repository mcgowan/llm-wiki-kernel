---
type: Topic
title: How Harness-as-a-Service Will Change Agents
description: "NLW coins 'harness as a service' — Cursor SDK, Claude managed agents, OpenAI's Agents SDK, and Microsoft's Foundry hosted agents selling pre-built agent runtimes the way AWS sells compute — likening the DIY Open Claw era to 1970s hobbyist kit computers, plus a big-tech earnings blowout led by Google Cloud's 63% growth."
tags:
- harness-as-a-service
- cursor-sdk
- ai-agents
- agent-runtimes
- big-tech-earnings
- google-cloud
- harness-engineering
status: stable
published_at: '2026-05-01T14:51:50+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:41Z'
sources:
- id: how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w
  resource: https://www.youtube.com/watch?v=jvqQ8VlhO-w
  title: How Harness-as-a-Service Will Change Agents
---

# Overview

Nathaniel Whittemore proposes a name for an emerging infrastructure category: "harness as a service" — companies selling access to their agent runtime (the engine that turns an LLM into something that can do work) the way AWS sells compute and Stripe sells payment rails. The trigger is Cursor's new Cursor SDK, but he groups it with OpenAI's updated Agents SDK, Anthropic's Claude managed agents, and Microsoft's hosted agents in Foundry (Nadella: "Every agent will need its own computer"). His central analogy: the Open Claw era — where builders hand-assembled the agent loop, tool dispatch, context management, state, and error handling — was the 1970s hobbyist kit-computer era; harness as a service is the Apple II/Dell moment, where the loop, sandboxing, streaming, and error handling come pre-built and you bring only the model, the tools, and the task.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]

He frames the shift via Akshay's three phases of agents — weights, context, and now harness engineering, where "the model is no longer the sole location of intelligence" — and quotes Sam Altman telling Ben Thompson it is "hard to overstate how critical" the harness is, to the point he no longer thinks of harness and model as separable. Evidence that harnesses move performance: Endor Labs found the same models scoring markedly differently across harnesses, with GPT-5.5 jumping from 61.5% to 87.2% on functionality just by switching from Codex to Cursor's harness. The headlines cover a big-tech earnings blowout: Google Cloud +63%, Azure +39-40%, Meta revenue +33%, AWS +28%.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]

# Key points

- Earnings: Google was the clear winner — Google Cloud +63% year over year, a $460B backlog (up from $240B), a 40% quarter-over-quarter surge in paid Gemini enterprise customers, infrastructure processing 16 billion tokens a minute (+60% QoQ), search revenue +19%, net income $62.6B (+81%), and stock up 7% overnight; Pichai: "We are compute-constrained in the near term."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Amazon: AWS +28% (a $152B ARR business, fastest growth in nearly four years), Q1 capex of $43.2B, free cash flow down from ~$26B to $1.2B; Jassy says Trainium demand is unlimited and the custom silicon business would be at $50B ARR standalone — "one of the top three data center chip businesses in the world."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Microsoft: Azure +39%, capex guidance lifted $25B to $190B (attributed to component prices), Copilot at 20 million paid seats (vs. ~320 million Office 365 seats); Nadella on losing OpenAI exclusivity: "We have a frontier model royalty-free... all the way to 32."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Meta: record quarter (revenue $56.3B, +33%, highest since 2021) but the biggest earnings loser, down 5% overnight on a capex hike to $145B and the first-ever decline in daily active people since reporting began in 2019.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Whittemore's earnings takeaway: the AI boom is categorically here — everything from memory foundries to data-center construction is at 100% capacity in "a frankly vain attempt to keep up with the endless demand for tokens."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Harness-as-a-service category: Cursor SDK ("local hackable agents with any model or ship products on top of managed cloud agents"), OpenAI Agents SDK, Claude managed agents, and Microsoft Foundry hosted agents — pre-built agent loops, tool dispatch, sandboxing, streaming, error handling, and context compression.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Akshay's three phases: weights (bigger models), context (prompting, RAG), and harness (persistent memory, skills, MCP/A2A protocols, sandboxes, approval gates, observability) — each layering on rather than replacing the last.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Altman to Ben Thompson: when Codex does something amazing, he doesn't know how much credit goes to the model versus the harness — "I no longer think of the harness and the model as these entirely separable things."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Endor Labs benchmark: Cursor + GPT-5.5 set a security-correctness record (23.5%, edging Cursor + Opus 4.7's 22.9%, both beating each model's native harness); on functionality, Opus 4.7 rose from 87.2% to 91.1% and GPT-5.5 from 61.5% to 87.2% by switching to Cursor — "same model, same week, two harnesses, two different functional results."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Early builds: Jack Driscoll embedded a Cursor agent in Gmail; Tejas Vavery built a bug-catching agent with its own browser window to close the verification feedback loop; Robert Brochery put a Cursor agent in a Chrome plugin for IT triage.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]
- Because agents now handle the coding, the audience for tools like the Cursor SDK extends well beyond developers — Whittemore counts himself in the new builder category.[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]

# Takeaways

Whittemore argues harness as a service is a shift in kind, not scale: just as the productivity revolution came from Dell desktops rather than more people assembling motherboards, agent adoption will come from pre-fabbed runtimes with a few knobs, not everyone wiring their own Open Claw. Harness innovations will no longer be locked inside specific tools but become building blocks anyone can leverage. His practical advice for non-developers: drop Cursor's GitHub cookbook into Claude or ChatGPT with your own project context and ask what it unlocks — "I give you full permission to call in sick on Friday and just dive all the way in."[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]

[^how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w]: "How Harness-as-a-Service Will Change Agents", The AI Daily Brief, YouTube, 2026-05-01 [Mirrored transcript](/references/how-harness-as-a-service-will-change-agents-jvqQ8VlhO-w.md)

# Related topics

- [Harness Engineering 101](/topics/harness-engineering-101-OTjZBjq5FPg.md) — continuation — harness engineering primer extended to harness-as-a-service thesis
- [All of AI's New Models and Tools](/topics/all-of-ai-s-new-models-and-tools-20vZc0cOpOw.md) — same-series — Claude Managed Agents launch covered in weekly tour
- [The OpenClaw-ification of AI](/topics/the-openclaw-ification-of-ai-GR-j31Nrl0Y.md) — shared-mechanism — productizing primitives OpenClaw hobbyists pioneered
