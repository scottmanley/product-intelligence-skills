---
name: codebase-import
description: Bootstrap Product Intelligence Wiki documentation for a product that exists in code but has no canonical product page.
---

# Codebase Import

## Scout Wiki access

Use the installed **@Scout Wiki** plugin/app for every Wiki search, read, draft, and update. If it is not installed or connected, tell the user it is required and ask them to install or connect it before proceeding; accept page links/text only as a fallback. This skill does not install or connect plugins.

First confirm that no canonical product Wiki page already exists. Inspect available README files, API contracts, modules, deployment configuration, tests, dependencies, and recent history. Separate structural facts from inferences; do not infer initiatives, metrics, or GTM strategy from code.

Before creating a product draft, confirm its Product Team, Product Manager, Engineering Manager, and Product Status. Treat these as required **At a glance** fields. Ask the PM for any value that cannot be confirmed from an authoritative source; do not derive the operating status from the Wiki draft/published state.

Offer batch drafting or an interactive walkthrough. Before writing, show the proposed product purpose and capability structure and obtain PM confirmation. Create only a product landing page and genuinely independent capability pages, using [the product template](references/product.md) and [the authoring contract](references/wiki-authoring-contract.md).
