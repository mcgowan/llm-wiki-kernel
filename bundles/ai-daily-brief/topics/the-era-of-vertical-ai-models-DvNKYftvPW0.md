---
type: Topic
title: The Era of Vertical AI Models
description: "Whittemore revisits Rich Sutton's bitter lesson through Intercom's Apex, Cursor's Composer 2, and Decagon's in-house models, arguing that post-training open-weight models on last-mile experiential data may let vertical models beat frontier generalists."
tags:
- vertical-models
- bitter-lesson
- post-training
- intercom-apex
- cursor-composer
- open-weight-models
- fine-tuning
status: stable
published_at: '2026-03-29T15:17:26+00:00'
generated:
  by: llm-wiki/0.1.0
  at: '2026-08-16T23:13:50Z'
verified:
  by: llm-wiki-skill/claude
  at: '2026-08-16T23:17:27Z'
sources:
- id: the-era-of-vertical-ai-models-DvNKYftvPW0
  resource: https://www.youtube.com/watch?v=DvNKYftvPW0
  title: The Era of Vertical AI Models
---

# Overview

Prompted by Intercom's announcement that its customer-service model Apex beats the best general models including GPT-4-class and Opus 4.5, Nathaniel Whittemore revisits Rich Sutton's 2019 "bitter lesson" — that general methods leveraging computation always beat systems built on encoded human knowledge — and asks whether vertical AI models have finally found a way around it. Early custom-model efforts like BloombergGPT were "smoked" by general models, but a new pattern has emerged: instead of pretraining from scratch, companies like Cursor and Intercom take strong open-weight base models and apply heavy domain-specific post-training built on billions of last-mile usage interactions, producing models that are better, faster, and far cheaper at their specific job.[^the-era-of-vertical-ai-models-DvNKYftvPW0]

Whittemore argues this doesn't actually contradict the bitter lesson, because the training signal isn't human expert knowledge but experience data — millions of real-world interactions — which Sutton himself identified on the Dwarkesh podcast as the lesson's next phase. The implication is a possible reordering of the stack: pretraining commoditizes, durable differentiation moves to the model layer via proprietary evals and feedback loops, and frontier labs face classic disruption from below.[^the-era-of-vertical-ai-models-DvNKYftvPW0]

# Key points

- Intercom CEO Eoin McCabe called its new Finn model Apex "objectively the highest performing, fastest, and cheapest model for customer service," beating GPT-4-class models and Opus 4.5; CPO Paul Adams credits "domain-specific proprietary evals from our billions of human and agent customer service interaction data points."[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Apex claims a 2.8% higher resolution rate, a 65% reduction in hallucinations, dramatically faster responses, and lower cost than any other available model.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Sutton's bitter lesson (2019): 70 years of AI research show general computation-leveraging methods win "by a large margin" — chess, Go, speech recognition, vision, and now language all steamrolled human-designed shortcuts; BloombergGPT's 50B-parameter finance model was an LLM-era casualty of it.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Latent Space's November "Agent Labs Thesis" asked whether post-training could close — then exceed — the gap between the best open models and frontier models as pretraining data limits approach.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Cursor's Composer 2 beat Opus 4.6 on coding benchmarks while much cheaper; controversy erupted when an X user revealed it was Kimi K2.5 with extra reinforcement learning. Cursor's Lee Robinson confirmed the open-source base, noting only a quarter of final compute came from it and promising full pretraining later.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Decagon's Ashwin Srinivasan says over 80% of its model traffic now runs on in-house-trained models, architected as a network of specialized models for detection, orchestration, response generation, and evaluation.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Hugging Face's Clem Delangue lists Pinterest, Airbnb, Notion, Cursor, and Intercom as companies publicly finding it better, cheaper, and faster to train open models themselves, predicting the majority of AI workflows will end up in-house on open source rather than APIs.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Andrej Karpathy's "speciation" framing, cited by Intercom: intelligences should diversify like the animal kingdom — smaller models with the cognitive core, speciated onto specific tasks, without needing "this oracle that knows everything."[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Paul Adams's thesis: successful companies will need to be full-stack (app, AI, and model layer), because as app-layer copying gets easier, durable differentiation moves down the stack to the model layer.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Commentators framed the API cost of frontier labs as "the cloud markup of 10 years ago," and questioned what value frontier labs deliver long-term if every vertical can build better, cheaper specialized models from open bases.[^the-era-of-vertical-ai-models-DvNKYftvPW0]
- Sutton on Dwarkesh: systems that learn from experience rather than human knowledge could "perform much, much better and be much more scalable" — another instance of the bitter lesson, which Whittemore says is exactly what Apex and Composer 2 represent.[^the-era-of-vertical-ai-models-DvNKYftvPW0]

# Takeaways

Whittemore concludes the labs are being over-serving generalists for specific use cases while good-enough open-weight models plus quality post-training win the special-purpose jobs — classic disruption at the frontier labs' door. He expects their response to involve building cheaper specialized models themselves, data partnerships, and M&A to acquire eval-rich companies, alongside hyper-specific model providers competing head-to-head. He cautions against over-extrapolation: post-training talent is scarce, so this won't fragment into a model for every company with customer data — but the results are encouraging enough that many companies with the data and talent will now experiment.[^the-era-of-vertical-ai-models-DvNKYftvPW0]

[^the-era-of-vertical-ai-models-DvNKYftvPW0]: "The Era of Vertical AI Models", The AI Daily Brief, YouTube, 2026-03-29 [Mirrored transcript](/references/the-era-of-vertical-ai-models-DvNKYftvPW0.md)

# Related topics

- [How AI Changes if Open Source Gets Banned](/topics/how-ai-changes-if-open-source-gets-banned-kpGZ83XqDqA.md) — shared-mechanism — fine-tuning open-weight bases for specialized models
- [9 Codex Tips from the Codex Team](/topics/9-codex-tips-from-the-codex-team-dB-Kbylgrdk.md) — continuation — Cursor's Composer line advances to 2.5
- [The Models Trying to Replace Fable](/topics/the-models-trying-to-replace-fable-4hvA6aCwf6E.md) — continuation — Composer and routing adopted after Fable ban
