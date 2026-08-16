---
type: Topic
title: A Primer on Using Agent Skills
description: "A hands-on primer on agent skills — what they are, how progressive disclosure works, and best practices from the Claude Code team's Tariq — framing skills as the shift from ad hoc prompting to reusable capabilities."
tags:
- agent-skills
- claude-code
- anthropic
- context-engineering
- agentic-ai
- prompt-engineering
status: stable
published_at: '2026-03-19T01:51:06+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:16:04Z'
sources:
- id: a-primer-on-using-agent-skills-NU6wRAT9VQ0
  resource: https://www.youtube.com/watch?v=NU6wRAT9VQ0
  title: A Primer on Using Agent Skills
---

# Overview

In this practical episode inspired by "Lessons from Building Claude Code: How We Use Skills," a post by Tariq of Anthropic's Claude Code team, Whittemore lays out a primer on agent skills — in his view a key component of getting value from agents in 2026's agentic era. Skills arose because system prompts kept ballooning as agents grew capable: every new capability meant more instructions crammed into one context window, degrading performance. The insight behind skills is that agents don't need all their knowledge all the time — they need to load the right knowledge at the right moment. Anthropic formally announced the format on October 16 as "organized folders of instructions, scripts, and resources that agents can discover and load dynamically," and it was quickly adopted by OpenAI (ChatGPT and the GitHub Copilot coding agents), Cursor, and other harnesses, with the OpenClaw wave pushing a site like ClaudeHub to roughly 28,000 published skills.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]

Whittemore walks through the mechanics (skill.md, progressive disclosure), Anthropic's nine-category taxonomy of what skills people actually build, the new skill-creator tooling for evals and A/B testing, and Tariq's authoring tips — then maps the lessons onto three user tiers, from multi-agent architects to mainstream users of tools like Notion's new custom skills.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]

# Key points

- A skill is a directory anchored by a skill.md file with name and description metadata (~100 tokens per skill). Progressive disclosure has three layers: the description the agent always sees, the skill.md body it reads when relevant, and linked files, scripts, and assets for specific scenarios — "a well-organized manual that starts with a table of contents, then specific chapters, and finally a detailed appendix."[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Tariq's correction of a common misconception: skills "are not just text files. They're folders that can include scripts, assets, data, etc. that the agent can discover, explore, and manipulate" — the entire file system is a form of context engineering.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Anthropic's nine skill categories: library/API reference, product verification, data and analysis, business automation, scaffolding and templates, code quality and review, CI/CD and deployment, incident runbooks, and infrastructure ops. Tariq calls verification skills one of the highest-ROI categories — worth an engineer spending a week perfecting them, with techniques like having Claude record a video of its output or enforcing programmatic state assertions.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Code-review skills matter because, in Whittemore's strong instinct, the volume of AI-generated code means the human-reviews-everything paradigm "doesn't get out of 2026" — examples include adversarial review (a fresh-eye subagent critiquing and iterating until findings degrade into nitpicks) and style-enforcement skills.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- The updated skill-creator tool targets non-engineer authors: run evals scoring a skill against multiple prompts, A/B test skill vs raw Claude across model updates, and auto-rewrite descriptions so skills trigger correctly — Anthropic saw better triggering in five of six of its own skills. Ali Lemon flagged these as fixing the three problems everyone hits.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Two-category framework: capability-uplift skills (things the base model can't do consistently — likely to fade as models improve) versus encoded-preference skills (sequencing steps the model can already do according to your team's process — more durable, but only as valuable as their fidelity to the actual workflow).[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Authoring tips: don't state the obvious — focus on what pushes Claude out of its defaults (the front-end design skill avoids "classic patterns like the Inter font and purple gradients"); build a gotcha section — "the highest signal content in any skill" — updated each time the agent errs; and avoid railroading, giving Claude flexibility to adapt.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]
- Three user tiers: advanced agent builders (skills as modular architecture — Tariq's core audience); individual power users (skills as "reusable prompts with superpowers" that can include code, templates, and reference data, portable across Codex, Claude Code, and Cursor); and mainstream users, where the pattern is spreading — Notion just launched custom skills ("Write a prompt, you'll use it once. Write a skill, and you'll use it forever"), letting any page become a skill.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]

# Takeaways

Whittemore's framing is that skills represent a mental-model shift converging across the entire AI stack: from ad hoc prompting to a library of reliable, repeatable capabilities. Most users won't ever care about skill.md architecture or progressive disclosure — they'll just know they can teach the AI to do a specific thing their way, name it, and invoke it forever, making skills something like a successor to custom GPTs that actually sticks. He stresses, echoing Tariq, that all current advice is a work in progress as everyone races to engage with new agent capabilities, and floats a deeper future operator episode.[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]

[^a-primer-on-using-agent-skills-NU6wRAT9VQ0]: "A Primer on Using Agent Skills", The AI Daily Brief, YouTube, 2026-03-19 [Mirrored transcript](/references/a-primer-on-using-agent-skills-NU6wRAT9VQ0.md)

# Related topics

- [How To Build a Personal Agentic Operating System](/topics/how-to-build-a-personal-agentic-operating-system-ntvkDnk_5jA.md) — shared-mechanism — portable reusable layers for agentic tools
- [5 AI Engineering Trends That Non Engineers Should Know About](/topics/5-ai-engineering-trends-that-non-engineers-shoul-wGOsOMXMCG0.md) — continuation — skills trend gets its own primer
- [Agent Skills Masterclass with Nufar Gaspar](/topics/agent-skills-masterclass-with-nufar-gaspar-fs_Y3gvj7lk.md) — continuation — primer followed by advanced skills masterclass
- [How the Best Companies Use AI](/topics/how-the-best-companies-use-ai-t8vitqIj7u4.md) — shared-mechanism — skills as organizational capability infrastructure
- [Context Graphs: AI''s Next Big Idea](/topics/context-graphs-ai-s-next-big-idea-SVUymPVBvfo.md) — shared-mechanism — packaging context so agents work better
