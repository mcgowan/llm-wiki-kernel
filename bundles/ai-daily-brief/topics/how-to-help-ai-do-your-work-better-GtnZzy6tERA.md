---
type: Topic
title: How to Help AI Do Your Work Better
description: "Grok Bot's teach-a-task and ChatGPT's computer history mark the shift from capability to context as AI's bottleneck, and NLW introduces a five-criteria 'deputization audit' for deciding what work to hand to AI."
tags:
- ai-deputization
- grok-bot
- chatgpt-computer-history
- workflow-automation
- gemini-3-7-flash
- context
- ai-privacy
status: stable
published_at: '2026-08-16T11:14:46+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:50Z'
sources:
- id: how-to-help-ai-do-your-work-better-GtnZzy6tERA
  resource: https://www.youtube.com/watch?v=GtnZzy6tERA
  title: How to Help AI Do Your Work Better
---

# Overview

Nathaniel Whittemore pairs a news story with a practical activity: two features launched this week — Grok Bot's "teach a task" (record yourself doing something in the browser and the bot learns it) and ChatGPT's "computer history" (which learns from everything you do on your computer) — signal that AI's biggest bottleneck has moved from model capability to access to context. He frames them as two paradigms for AI learning how you work: "ambient observation" (computer history's background watching) versus "deliberate demonstration" (Grok Bot's intentional teaching), and notes the echo of Microsoft's panned Windows Recall — arguing attitudes have shifted partly because getting an agent to do your work is a far stronger value proposition than merely finding old screenshots.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]

The practical half introduces the "AI deputization audit": inventory your recurring processes, score each on five dimensions, and sort them into deputize, duet, or defend tiers — then name the specific blocker for anything you can't yet hand off, since new tools like these may dissolve particular blockers. Headlines cover Google's Gemini 3.7 Flash speed play, an AlphaSense study showing US frontier models beating Chinese models on real-world cost-per-quality, OpenAI's ultra fast mode, and CRO Denise Dresser's departure from OpenAI.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]

# Key points

- The deputization audit's five scoring criteria (0-2 each): is it worth automating (frequency x time), teachability (could a 10-minute screen share cover it), checkability (verification much faster than doing), stakes if it goes wrong, and how much you personally are essential to the output.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- Scores of 8-10 = deputize (hand over and spot-check), 4-7 = duet (AI does part, you stay involved — where most knowledge work sits today), 0-3 = defend (keep it yourself); Whittemore deliberately says "deputize" rather than "automate" to reflect an ongoing relationship rather than never thinking about a task again.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- Step four is naming the blocker: computer-use agents solve the no-API legacy-portal blocker, teach-a-task solves "easy to show, hard to explain," ambient observation may solve missing context — but taste, judgment, costly mistakes, and human relationships remain unsolved, and screen recording itself can create a new privacy blocker.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- ChatGPT computer history (per OpenAI's Ari Weinstein) learns how you work to finish in-progress tasks and suggest skills/automations; Simon Smith notes it records interaction events rather than screenshots or audio, unlike Windows Recall.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- Early Grok Bot patterns: a plumbing-company owner went from zero to automated dispatch in 24 hours with no engineers; "topic per bot" coordinated through a chief-of-staff bot is an emerging best practice; the inbox/Slack tracker and morning brief is "the universal starter job" (Matt Van Horn); but advanced users like Nofar Gaspar find it limiting (no control over context folders or model choice).[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- Gemini 3.7 Flash runs at 340 tokens/second (twice GPT 5.6 Luna), jumped from 48.6 to 65.3% on the Deep Sweep coding benchmark, and halved prices — but at 40 cents per task it sits in "an uncomfortable middle ground" on cost-per-intelligence, though Vercel's Brandon Galang argues it "sits on the Pareto frontier" and is trying it as a daily driver.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- An AlphaSense study of several hundred financial-analysis questions found GPT-5.6 Soul completed the task ~13% cheaper than Kimi K3 with ~20% higher quality; Kimi K3 and GLM 5.2 landed around Sonnet 5's level; Opus 5 was an outlier — lower quality than Opus 4.8 at over five times the cost. CEO Jack Kokko: models that look expensive per token can be cheaper because they use tokens more efficiently.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- OpenAI introduced ultra fast mode for GPT 5.6 Soul — 750 tokens/second (14x speed) via Cerebras hardware, API-only for select customers, aimed at latency-sensitive workflows like real-time voice, commerce, and security response.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]
- OpenAI CRO Denise Dresser (ex-Slack CEO) is leaving after nine months, replaced by former Wiz president/COO Dolly Rajek; following Brad Lightcap's and Fiji Simo's departures, the market reads a pattern of executive turnover ahead of the now-delayed IPO, though Whittemore cautions most personnel moves are personal.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]

# Takeaways

Whittemore's conclusion is that the model race is branching into multiple races — frontier, distribution, harnesses, revenue, and now speed — and that for individuals, the arrival of teach-a-task and ambient-observation features makes it worth conscientiously auditing which recurring work to deputize. He acknowledges the hardest part: highly productive people have workflows so dialed in that changing them feels like a short-term waste of time even when it would save enormous time long-term — but he argues the experiments are worth it, and invites listeners to watch Grok Bot costs come down and report what they find.[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]

[^how-to-help-ai-do-your-work-better-GtnZzy6tERA]: "How to Help AI Do Your Work Better", The AI Daily Brief, YouTube, 2026-08-16 [Mirrored transcript](/references/how-to-help-ai-do-your-work-better-GtnZzy6tERA.md)

# Related topics

- [Grok Bot Finally Makes AI Agents Easy](/topics/grok-bot-finally-makes-ai-agents-easy-kckD1hgkYvk.md) — continuation — Grok Bot gains teach-a-task capability
- [Automating Your AI Context](/topics/automating-your-ai-context-jSPFi-mW0ns.md) — agreement — captured computer history makes context the bottleneck
- [Context Graphs: AI''s Next Big Idea](/topics/context-graphs-ai-s-next-big-idea-SVUymPVBvfo.md) — shared-mechanism — captured context as the agent performance bottleneck
