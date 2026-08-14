# Scout Wiki product-documentation contract

Use Scout Wiki as the canonical source for product documentation. The repository holds skills and templates only; do not create or maintain a parallel product-documentation tree in it.

## Read and change safely

1. Search the Wiki before creating a page. Reuse the canonical page; do not create a duplicate because a title is familiar.
2. Fetch a page immediately before any update or append, and pass its current revision and update timestamp to the write operation.
3. Create substantive changes as drafts. A human reviewer must set the page to **full width** in the Wiki and publish it. Mention that manual gate in the handoff.
4. Do not add YAML/front matter or duplicate the Wiki's page details. Use the required **At a glance** block from the applicable template for product, initiative, requirement, or GTM operating information.

## Information architecture

- Product landing pages are concise, current overviews and navigational hubs.
- Create a child page only when the topic has its own lifecycle, owner, audience, or substantial content. Never create blank folder pages.
- An active initiative may be a child page. On completion, first update the current requirements/capability and GTM pages; retain only a concise outcome/learning summary on a **Product history & outcomes** page, creating that page only when needed.

## Link integrity

Before proposing or saving an edit, inspect every Markdown link in the complete resulting page. Replace repository-relative links with a confident canonical Wiki URL. If a target cannot be resolved confidently, use plain text and flag it in the handoff. Re-check links after writing a draft.
