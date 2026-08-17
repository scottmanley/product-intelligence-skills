---
name: product-documentation
description: Create and update structured Scout24 product documentation in Scout Wiki. Use when turning confirmed source material into product overviews, purpose, capabilities, dependencies, vision, strategy, requirements, and initiative documentation.
---

# Product Documentation

Turn confirmed intake material into structured documentation in Scout Wiki. The repository holds skills and templates only; do not create or maintain a parallel product-documentation tree in it.

## Scout Wiki access

Use the installed **@Scout Wiki** plugin/app for every Wiki search, read, draft, and update. If it is not installed or connected, tell the user it is required and ask them to install or connect it before proceeding; accept relevant page links/text only as a fallback. This skill does not install or connect plugins.

## Start

Identify the target product and intended documentation outcome. Search Scout Wiki for the canonical product landing page and relevant child pages before drafting. Read the existing page structure, page details, and related requirements, initiatives, dependencies, or strategy pages that would be affected.

If no canonical product page exists, do not invent a hierarchy: ask the user whether to create the landing page or use the Codebase Import workflow when code is the primary source.

## Core behavior

Use Scout Wiki as the source of truth. Do not invent missing facts or present draft, conflicting, or unsupported material as certain. If sources conflict, state the conflict and ask the user to resolve it before finalizing.

Keep ownership in Wiki page details, not in titles or hierarchy. Write content that survives team and organisation changes, favouring stable purpose, behaviour, dependencies, and strategy over transient delivery chatter.

Create only the page or pages supported by the information architecture. A product landing page is a concise, current overview and navigation hub. Create a child page only when the topic has its own lifecycle, owner, audience, or substantial content. For a new or substantially rewritten product landing page, start with the [product template](references/product.md).

Never remove the template's **At a glance** block. Every product page must name Product Team, Product Manager, Engineering Manager, and Product Status. Use **TBA — accountable owner** when the source does not confirm a value; missing ownership is documentation, not a reason to omit the field.

## Writing standard

Write for scanning. Prefer short, information-dense phrases; cut connective prose, never facts, decisions, caveats, ownership, or source limitations. Lead with the outcome, use one point per bullet, and prefer a compact table when it makes repeated fields easier to compare.

## Documentation workflow

1. Identify the product and desired documentation change.
2. Gather and assess the available source material.
3. Search and read the canonical Scout Wiki pages and relevant context.
4. Resolve material conflicts or missing decisions before writing.
5. Draft the necessary page changes in Scout Wiki.
6. Validate the complete resulting page, including every Markdown link and mandatory ownership/status fields.
7. Hand off the draft with its sources, assumptions, and unresolved questions.

## Documentation areas

Prepare only the documentation areas justified by the source material, which may include:

- overview and purpose
- capabilities or features
- dependencies
- vision and strategy
- initiatives and requirements
- outcomes and learnings

Update current capability, requirements, and GTM pages when an initiative completes. Keep only a concise outcome or learning summary on **Product history & outcomes**, creating that page only when it is needed.

## Source handling

Use interview notes and confirmed stakeholder material as primary sources when provided. Use existing Wiki pages, documents, diagrams, and Linear project links as supporting context. Track sources for important claims when that will help future updates.

## Publishing and handoff

Follow the [Wiki authoring contract](references/wiki-authoring-contract.md). Create substantive changes as Scout Wiki drafts only. A human reviewer must set each page to **full width** in Scout Wiki and publish it.

In the handoff, summarise:

- pages created or updated
- sources used
- assumptions made
- unresolved questions
- the required full-width and publication review
