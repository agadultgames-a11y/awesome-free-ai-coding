---
layout: default
title: 'LLM Tech free tier (archived): what it offered, and why it left the list'
description: 'EU provider of one model whose quickstart prints a shared trial key for anyone: 2M tokens a day per address and 4 concurrent requests, tool calls included, no account. Free models: qwen3.8-27b. The public trial key shares its concurrency among all callers; the daily token budget is per IP and…'
permalink: /providers/llmtech/
last_modified_at: 2026-11-05
crumb: LLM Tech
---

{% raw %}

# LLM Tech free tier (archived)

🔌 LLM APIs with free tier · no card · **archived** — 3 failed probes in a row, last passed 2026-10-26 · [llmtech.eu](https://llmtech.eu) · [back to the whole list](https://mvalentsev.github.io/awesome-free-ai-coding/)

## What it offered

EU provider of one model whose quickstart prints a shared trial key for anyone: 2M tokens a day per address and 4 concurrent requests, tool calls included, no account

## Free models it listed

[`qwen3.8-27b`](https://mvalentsev.github.io/awesome-free-ai-coding/models/qwen3.8-27b/)

## Limits, in the vendor's words

2,000,000 tokens/day per IP. reset at 00:00 UTC

Shared trial key: 4 requests at once per key

64 requests at once shared across the endpoint

The public trial key shares its concurrency among all callers; the daily token budget is per IP and counts both prompt and completion. Its context is 131,072 tokens; personal paid keys have the full 262,144 and share the endpoint's separate inflight ceiling. Paid keys are issued by email, per token without subscription or minimum. Prompts and completions are volatile and never persisted or trained on; metadata, including IP, is retained 13 months. The sole proprietor operates in Poland, with GPUs in Italy behind a German edge.

## Evidence

- Probe: the page at <https://llmtech.eu/docs/>, anchored on `4 concurrent requests and 2M tokens per day per address`; ids checked in <https://api.llmtech.eu/v1/models>
- Source: <https://llmtech.eu/docs/>
- Source: <https://llmtech.eu/agents/>
- Source: <https://llmtech.eu/security/>
- Source: <https://llmtech.eu/about/>
- Source: <https://api.llmtech.eu/v1/models>
- Source: <https://llmtech.eu/pricing/>
- Source: <https://llmtech.eu/changelog/>

## History

Each line is a change to what this page publishes, dated the day it reached the list, in UTC.

- `2026-11-05` — Archived: 3 failed probes in a row, last passed 2026-10-26
- `2026-09-18` — Added: EU provider of one model, Qwen3.8 27B, whose quickstart prints a shared trial key for anyone: 2M tokens a day per address and 2 concurrent requests, tool calls included, no account

---

Generated from `registry.yaml` on 2026-11-05. A probe still reads it twice a week, and the first probe it passes brings it back to the list; the full list, the Atom feed and the machinery are at <https://github.com/mvalentsev/awesome-free-ai-coding>.

{% endraw %}
