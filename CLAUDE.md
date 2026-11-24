# Working rules — in-articles

The source of Insheights articles: the IIVCS and Agentic Engineering series, and standalone pieces.

## This repo is public

Everything committed here, on any branch and including this file, is readable by anyone.

- No client or prospect names, no internal strategy, no pricing, no unreleased plans (a series lists only what is published), no local paths or account details.
- No review notes or panel records. Those are kept privately, not here.
- Nothing may imply that Knowledge Pier is a shipping or proven product.
- Only published articles. A draft is written and reviewed in `../in-scope` and arrives here when it is published, with its images and LinkedIn post, on no branch before then.

## Direction comes from in-scope

What is written, in what order, and how each article is reviewed before publishing is decided in Insheights' private `in-scope` repo, alongside this checkout at `../in-scope`. Before changing anything beyond a typo or a broken link:

1. Read `../in-scope/CLAUDE.md` and `../in-scope/articles/direction.md`.
2. A new article, or a change to a published one, is reviewed there first. The owner decides before it is published.
3. Make the change on a branch (never `main`) and open a PR. The owner merges.

If `../in-scope` is not present, keep to edits the owner asked for in that session.

## Writing rules

- **Published means as published.** An article with `status: published` matches its published copy. A correction is reviewed in `in-scope` like a new article, and the owner decides; it is then made here and on the published copy together.
- **IIVCS terms follow `in-frameworks`.** Use each term exactly as in its `glossary.md`, and link to the framework rather than restating it.
- **The `in-frameworks` writing rules apply here too.** Spell out every acronym at its first use on each page, the README and each series index included: "Insheights Integrated Value Creation System (IIVCS)", "Organization Strategy Model (OSM)". One fact, one home: link to a definition, a template or an earlier article rather than restating it.
- **Name the framework element the article teaches.** One sentence, wherever it fits best, with a deep link to it in `in-frameworks` (the guide step, the model, the glossary entry). Link only to what exists there: the templates and the Stocklight examples live in the articles, not in the framework repo.
- **Number templates across the series.** "Template N: <what it is>." A new article continues from the last whole number used.
- **Summarise, don't re-quote.** When an article builds on an earlier one, give a short "story so far" and link back, rather than restating earlier statements in full.
- **Say what IIVCS does, not what other frameworks fail to do.** Credit general practice as general practice, and name a source when one exists.
- **End a new series article's `## What comes next`** with the link to `in-frameworks` and the Quick Self-Assessment line, as in `templates/article.md`. A closing question to the reader may follow them.
- **Front matter is complete.** Every `article.md` carries the fields in `templates/article.md`.
- **Images live beside the article,** in its `images/` folder, referenced by relative path.
