---
name: product-intelligence
description: "Guide Product Intelligence work in ChatGPT: answer product questions, onboard teammates, plan cycles, author initiatives or requirements, audit documentation, or draft documentation from a codebase. Use canonical Wiki material as the source of truth."
---

# Product Intelligence

Use this skill for governed Scout24 Product Intelligence work in ChatGPT. It is self-contained: do not assume that the user has Codex, a local checkout, Matt Pocock's skills, or a terminal.

## Source and safety rules

1. Treat the canonical Scout Wiki as the source of truth. Ask the user to provide relevant page links or text when ChatGPT cannot access the Wiki.
2. Read the [Wiki authoring contract](references/wiki-authoring-contract.md) before proposing a documentation change.
3. Do not present undocumented, draft, or conflicting information as certain. State the limitation and name an accountable team only when the source identifies one.
4. Ask one decision question at a time. Give a concise recommended answer grounded in the available evidence, then wait for the user's response before proceeding.

## Choose the workflow

Infer the workflow from the request; do not make the user learn skill names.

| User need | Workflow |
|---|---|
| Understand a product, its owner, purpose, strategy, or active work | Answer or onboarding |
| Answer a customer-facing or internal product question | Support answer |
| Start, sharpen, or revise a product initiative | Initiative |
| Define durable, testable behaviour | Requirements |
| Plan or challenge a team/cycle plan | Cycle planning |
| Find and repair stale or inconsistent documentation | Product audit |
| Document a product that exists in code but not in the Wiki | Codebase import |

For a straightforward question, answer directly from the canonical Wiki. Start with purpose and outcome, then add strategy, active initiatives, requirements, and GTM only when useful. Use published pages first; state clearly if a source is draft, conflicting, missing, or inaccessible. For Customer Care, lead with a direct, plain-language answer.

For any substantive workflow, hand off to the corresponding installed specialist skill. Do not reproduce its interview or artifact instructions here: the specialist owns that behaviour and its templates. If it is not installed, tell the user exactly which specialist they need.

Never claim a Wiki edit occurred unless the connected environment confirms it.
