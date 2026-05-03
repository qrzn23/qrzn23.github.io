---
title: ChatGPT 5.2 arrives
date: 2025-12-13 09:00:00 +0000
categories: updates
tags: ai chatgpt release
description: "Quick notes on ChatGPT 5.2: faster responses, sharper multi-step reasoning, and improved instruction adherence."
---

ChatGPT 5.2 is out. Here’s a quick rundown of what changed and what to expect.

## Highlights

- Faster: average response latency is roughly 30% lower than 5.1 in my tests.
- Sharper reasoning: better multi-step math and code generation, fewer hallucinated APIs.
- More controllable: improved system message adherence and JSON formatting reliability.
- Longer focus: modest context boost with better retention across longer chats.

## What feels different

- Instructions stick: nuanced tone and formatting prompts are respected more consistently.
- Code answers: 5.2 returns smaller, runnable snippets and includes lint-friendly formatting.
- Tool use: the model follows function/tool schemas with fewer edge-case failures.
- Search-style answers: citations and inline references are cleaner when browsing is enabled.

## New capabilities

- JSON mode is stricter, reducing trailing prose after structured replies.
- Inline planning: you can ask for a plan plus execution; it now separates steps more cleanly.
- Tabular summaries: improved Markdown tables and alignment.
- Vision: better OCR for documents and more accurate chart/table reads.

## Safety and guardrails

- Reduced content drift in long sessions.
- Better refusal clarity when policies are triggered.

## Availability and pricing

- Rolling out to ChatGPT and API with the 5.2 checkpoint; availability may take a few hours to propagate.
- Model ID exposed via the API as `gpt-5.2` (name subject to change; check the docs).

## Tips to get the most out of it

- Be explicit about output shape: “Return valid JSON with keys X, Y.”
- For code, ask for brief rationale plus the minimal snippet; it keeps responses compact.
- When chaining tools, provide short, numbered steps; 5.2 follows enumerations well.

I’ll update this post as I learn more from real-world use. Let me know if you spot quirks or regressions.
