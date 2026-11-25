# Working rules — in-articles

The source of Insheights articles: the IIVCS and Agentic Engineering series, and standalone pieces.

## This repo is public

Everything committed here, on any branch and including this file, is readable by anyone.

- No client or prospect names, no internal strategy, no pricing, no unreleased plans (a series lists only what is published), no local paths or account details.
- No review notes or panel records. Those are kept privately, not here.
- Nothing may imply that Knowledge Pier is a shipping or proven product.
- Only published articles. A draft is written and reviewed in `../in-scope`, and comes here only on the PR that publishes it, whole, with its images and LinkedIn post. **Merging that PR is its publication** (018): this repo is the source, and Medium and LinkedIn are filled from the merged copy afterwards.

## Direction comes from in-scope

What is written, in what order, and how each article is reviewed before publishing is decided in Insheights' private `in-scope` repo, alongside this checkout at `../in-scope`. Before changing anything beyond a typo or a broken link:

1. Read `../in-scope/CLAUDE.md` and `../in-scope/articles/direction.md`.
2. A new article, or a change to a published one, is reviewed there first. The owner decides before it is published.
3. Make the change on a branch (never `main`) and open a PR. The owner merges.

If `../in-scope` is not present, keep to edits the owner asked for in that session.

## Repo rules

- **Published means as published.** An article with `status: published` matches its published copy. A correction is reviewed in `in-scope` like a new article, and the owner decides; it is then made here and on the published copy together.
- **Front matter is complete.** Every `article.md` carries the fields in `templates/article.md`.
- **Images live beside the article,** in its `images/` folder, referenced by relative path.

## Writing rules

How the articles are written (terms, structure, templates, voice) is kept privately in `in-scope`, where articles are drafted and reviewed: `../in-scope/rules/article-writing.md`. Read it before writing or editing article text. Without `../in-scope`, keep to edits the owner asked for, as above.
