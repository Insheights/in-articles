# Working rules — in-articles

The source of Insheights articles: the IIVCS and Agentic Engineering series, and standalone pieces.

## This repo is public

Everything committed here, on any branch and including this file, is readable by anyone.

- No client or prospect names, no internal strategy, no pricing, no unreleased plans beyond a series roadmap, no local paths or account details.
- No review notes or panel records. Those are kept privately, not here.
- Nothing may imply that Knowledge Pier is a shipping or proven product.

## Direction comes from in-scope

What is written, in what order, and how each article is reviewed before publishing is decided in Insheights' private `in-scope` repo, alongside this checkout at `../in-scope`. Before changing anything beyond a typo or a broken link:

1. Read `../in-scope/CLAUDE.md` and `../in-scope/articles/direction.md`.
2. A new article, or a change to a published one, is reviewed there first. The owner decides before it is published.
3. Make the change on a branch (never `main`) and open a PR. The owner merges.

If `../in-scope` is not present, keep to edits the owner asked for in that session.

## Writing rules

- **Published means as published.** An article with `status: published` matches its published copy. A correction is made here and on the published copy together.
- **IIVCS terms follow `in-frameworks`.** Use each term exactly as in its `glossary.md`, and link to the framework rather than restating it.
- **Front matter is complete.** Every `article.md` carries the fields in `templates/article.md`.
- **Images live beside the article,** in its `images/` folder, referenced by relative path.
