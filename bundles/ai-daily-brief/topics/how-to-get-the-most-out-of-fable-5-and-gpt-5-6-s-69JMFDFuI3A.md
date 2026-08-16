---
type: Topic
title: How to Get the Most Out of Fable 5 and GPT 5.6 Sol
description: "Prompting and interaction tips for the new frontier-model class — setting boundaries for tenacious models, right-sizing compute, raising ambition levels, discovering unknowns, and loop-based workflows."
tags:
- fable-5
- gpt-5-6
- prompting-techniques
- agentic-loops
- context-engineering
- interaction-patterns
status: stable
published_at: '2026-07-25T19:00:06+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:50Z'
sources:
- id: how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A
  resource: https://www.youtube.com/watch?v=69JMFDFuI3A
  title: How to Get the Most Out of Fable 5 and GPT 5.6 Sol
---

# Overview

A few weeks into the Fable 5 / GPT 5.6 Soul era, Nathaniel Whittemore rounds up the emerging tips and tricks for getting the most out of the new frontier-model class — the kind of knowledge that benchmarks can't capture and only surfaces through trial and error. Drawing on OpenAI's official prompting guides, Codex team member Eric Provencal's advice, and community posts from Christine Zhu, Tariq of the Claude Code team, Daniel Miessler, and Matt Shumer, he identifies common threads that point to genuinely new interaction patterns rather than mere prompting tweaks.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]

The recurring themes: newer models are more tenacious, so boundaries matter more than ever; old prompt scaffolding built for weaker models now actively hurts; compute should be matched to the job rather than maxed out; and — most importantly — users should dramatically ratchet up ambition, moving AI from busy-work automation into high-leverage "impact work" and loop-based workflows where the model iterates against an explicit bar for done.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]

# Key points

- Eric Provencal (Codex team): people still prompt GPT 5.6 Soul like 5.5, but Soul is "a lot more tenacious and thorough" — so set boundaries ("keep the approved dates and budget figures unchanged," "use only the supplied sources," "prepare the message as a draft, don't send it") to prevent unintended actions and token burn.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Codex-style mid-run steering is coming to the main ChatGPT experience: "Steer" injects a message into the current run to change direction; "Queue" saves it for the next run — reducing collaboration latency.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- From OpenAI's GPT-5.6 best-practices doc (summarized by Ollie Leeman): state each instruction exactly once — removing repeated instructions raised scores 10-15% while cutting tokens up to 66%; old giant rule lists now make answers worse.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Match compute to the job across two dials — model size (Soul for hardest problems, Terra for everyday business work, Luna for cheap fast tasks) and six thinking-effort levels; OpenAI's advice is to start at your old setting and test one level lower, saving max for genuinely hard problems.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Audit old brevity rules (5.6 already defaults shorter than 5.5) and replace abstract tone words like "friendly" with concrete writing behaviors ("name the customer's problem in your first line, give the fix as numbered steps, skip the apology paragraph").[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Christine Zhu (Intuit): "You're Not Ambitious Enough with Claude" — using Shreyas Doshi's three levels, she automates optics work ruthlessly (scheduled status boards), uses Claude as co-pilot for execution work (weekly context-dump coaching, Jira planning, monthly support-channel analysis), and uses Fable as sparring partner for impact work, which she says Fable unlocks for the first time thanks to its "calmness."[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Tariq (Claude Code team), "A Field Guide to Fable": Fable is the first model where work quality is bottlenecked by the user's ability to clarify its unknowns; he maps known knowns / known unknowns / unknown knowns / unknown unknowns and recommends "blind spot passes" and brainstorming prototypes (e.g., "make me an HTML page with four wildly different design directions so I can react to them").[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Daniel Miessler's "tactical meta prompts" to rerun on every model jump: a self-model audit that finds where your harness models a stale or aspirational version of you, and massive-scope life/work-optimization prompts (e.g., an ikigai analysis).[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- Matt Shumer's "loop it until it hits the bar": don't use adjectives like "high quality" — give Fable a concrete testable bar ("a stranger can't tell a render from the real photo"), then run it on a loop (/loop command) where it builds, self-checks, finds the biggest gap, and goes again; "Fable never gets to decide it's finished."[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]
- A Claude Devs post taxonomizes loops: turn-based (user-directed, short tasks), goal-based (evaluator model enforces verifiable exit criteria), time-based (recurring intervals), and proactive (event- or schedule-triggered without a human in the loop).[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]

# Takeaways

Whittemore distills two lessons: every big model jump requires the hard work of re-testing everything, since old prompting habits may no longer help or may actively harm; and, more importantly, unlocking the differentiated capabilities of a new intelligence tier requires entirely new interaction patterns — like loops — not just prompt tweaks. His single takeaway: ratchet up ambition and "assume no limits on what the newest model can do," trying the biggest, most challenging things until real limits reveal themselves. He extends the point to organizations: the trap is using AI to do existing work faster and cheaper, when the true unlock is a new relationship with work and new categories of work that weren't possible before.[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]

[^how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A]: "How to Get the Most Out of Fable 5 and GPT 5.6 Sol", The AI Daily Brief, YouTube, 2026-07-25 [Mirrored transcript](/references/how-to-get-the-most-out-of-fable-5-and-gpt-5-6-s-69JMFDFuI3A.md)

# Related topics

- [Fable 5 Raises the Bar for AI Ambition](/topics/fable-5-raises-the-bar-for-ai-ambition-it7VUqfVorw.md) — continuation — practical usage guidance for the launched model
- [Fable Is Back: Here''s What You Should Try First](/topics/fable-is-back-here-s-what-you-should-try-first-ztCLWKwyMJY.md) — continuation — deeper usage tips after the model's return
- [How the 4 New Models Released This Week Will Change How You Work](/topics/how-the-4-new-models-released-this-week-will-cha-ZX9dXdAL5IU.md) — continuation — GPT-5.6 release coverage followed by usage tips
- [Mythos Returns But Not For Everyone](/topics/mythos-returns-but-not-for-everyone-187eNPPTa_w.md) — continuation — GPT-5.6's restricted launch precedes these tips
