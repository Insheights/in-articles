# Insheights Articles

The source of Insheights articles: each article's text, its images and where it was published. The articles here have appeared on [Medium](https://medium.com/@xambrose).

## Series

### [IIVCS](series/iivcs/README.md)

How value flows from strategy to customer, told through the Insheights Integrated Value Creation System (IIVCS). The frameworks themselves are open at [Insheights/in-frameworks](https://github.com/Insheights/in-frameworks). What's planned is in [the series roadmap](series/iivcs/ROADMAP.md).

| Part | Article | Published |
|---|---|---|
| 1 | [Everything between strategy and customer plays in a different key.](series/iivcs/01-strategy-to-customer-different-key/article.md) | 2026-09-09 |
| 2 | [Product Mindset Is How the Whole Company Should Think](series/iivcs/02-product-mindset/article.md) | 2026-09-28 |
| 3 | [Where Value Flow Leaks in Your Operating Model](series/iivcs/03-where-value-flow-leaks/article.md) | 2026-10-06 |
| 4 | [Managing the Flow of Value from Strategy to Customer as One Continuous Stream, Owned End to End](series/iivcs/04-one-continuous-value-stream/article.md) | 2026-10-14 |
| 5 | [Why Most Strategies Can’t Be Executed as Written, and What It Takes to Write One That Can](series/iivcs/05-strategies-that-can-be-executed/article.md) | 2026-10-21 |
| 6 | [From Strategic Intent to Outcomes an Empowered Team Can Own](series/iivcs/06-outcomes-a-team-can-own/article.md) | 2026-10-31 |
| 7 | [Efficiency, Experience, Effectiveness: The Three Tests of Real Value](series/iivcs/07-three-tests-of-real-value/article.md) | 2026-11-04 |

### [Agentic Engineering](series/agentic-engineering/README.md)

No articles yet. What's planned is in [the series roadmap](series/agentic-engineering/ROADMAP.md).

## Standalone

| Article | Published |
|---|---|
| [Your Enterprise AI is paced by processes no one revisits.](standalone/2026-09-05-enterprise-ai-paced-by-processes/article.md) | 2026-09-05 |
| [AI-enabled solutions are products](standalone/2026-09-17-ai-enabled-solutions-are-products/article.md) | 2026-09-17 |

## How this repo is laid out

- `series/<series>/NN-<slug>/`: one folder per article, numbered in reading order. Each series has a `README.md` and a `ROADMAP.md`.
- `standalone/<date>-<slug>/`: articles that belong to no series.
- Each article folder holds `article.md` and its `images/`, and a `linkedin.md` once it has companion LinkedIn posts.
- `templates/article.md`: the starting point for a new article.

Each `article.md` begins with front matter: `title`, `subtitle`, `series`, `part`, `status` (`draft`, `in-review`, `approved` or `published`), `published`, `medium_url` and `canonical`.

Articles already published are kept as they appeared. A correction is reviewed like a new article, then made here and on the published copy together.
