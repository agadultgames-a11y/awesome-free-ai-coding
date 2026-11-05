---
layout: default
title: 'Ollama Cloud free tier (archived): what it offered, and why it left the list'
description: Cloud-hosted open models on a $0 plan that grants starter usage credits for a starter subset of the catalog. The Free plan includes starter usage and starter models, whose amount and list are unpublished. Usage resets monthly from signup and does not roll over; adding credit unlocks all models…
permalink: /providers/ollama-cloud/
last_modified_at: 2026-11-05
crumb: Ollama Cloud
---

{% raw %}

# Ollama Cloud free tier (archived)

🔌 LLM APIs with free tier · no card · **archived** — 3 failed probes in a row, last passed 2026-10-26 · [ollama.com](https://ollama.com/cloud) · [back to the whole list](https://mvalentsev.github.io/awesome-free-ai-coding/)

## What it offered

Cloud-hosted open models on a $0 plan that grants starter usage credits for a starter subset of the catalog

## Free models it listed

The row named no free model.

## Limits, in the vendor's words

Starter usage: Monthly credits allowance: amount not published per account

1 requests at once per account

The Free plan includes starter usage and starter models, whose amount and list are unpublished. Usage resets monthly from signup and does not roll over; adding credit unlocks all models. Per-token catalog prices do not identify the starter set. In a 2026-09-02 test, a Free key answered gpt-oss:120b, gemma4:31b and nemotron-3-ultra but returned 402 for minimax-m3. That measurement does not establish the current starter set.

## Evidence

- Probe: the page at <https://ollama.com/cloud>, anchored on `Starter usage credits included`, `Includes access to starter models`; ids checked in <https://ollama.com/v1/models>
- Source: <https://ollama.com/cloud>

## History

Each line is a change to what this page publishes, dated the day it reached the list, in UTC.

- `2026-11-05` — Archived: 3 failed probes in a row, last passed 2026-10-26
- `2026-08-14` — Free models changed: dropped gpt-oss, minimax-3, nemotron
- `2026-07-20` — Free models changed: added minimax-3, nemotron; dropped qwen3-coder
- `2026-07-19` — Added: Cloud-hosted open models with free usage tier

---

Generated from `registry.yaml` on 2026-11-05. A probe still reads it twice a week, and the first probe it passes brings it back to the list; the full list, the Atom feed and the machinery are at <https://github.com/mvalentsev/awesome-free-ai-coding>.

{% endraw %}
