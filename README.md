# How Tech Trend Bytes is written

The editorial system behind [techtrendbytes.com](https://techtrendbytes.com), a phone and tech
blog written for readers in India.

This repository holds the **writing rules**, not the site. It is published as a reference for
anyone running a small blog with an AI assistant and wondering how to keep the output sounding
like a person rather than a content mill.

## What is in here

| File | What it is |
|---|---|
| [`playbook/house-style.md`](playbook/house-style.md) | The voice guide. Paragraph length, banned phrases, sourcing rules, and the India-first conventions |
| [`playbook/templates/`](playbook/templates) | Four article structures: news post, comparison, buying guide, deal guide |
| [`publish-checklist.md`](publish-checklist.md) | The two-minute check before anything goes live |

## The rules that matter most

**Two independent sources for any number.** Prices, dates and specs get linked to the sentence
they support. Leaks are labelled as leaks. YouTube is never a source, and neither is a site that
only repeats another site.

**Have an opinion.** Every piece says who should buy, who should wait and who should skip. A
balanced shrug helps nobody and travels nowhere.

**Short paragraphs.** One to three sentences, around seventeen words. Never more than sixty.

**Never bluff.** If something is not confirmed, the article says so and says who reported it.

**A banned-phrase list**, because the fastest way to sound like a machine is to write
"in today's fast-paced world" or "delve into".

## How it runs

Drafts are produced on a schedule by Claude following these rules, then saved as WordPress
**drafts**. Nothing publishes automatically. A human reads every piece, checks the prices against
the sources, adds the image, and presses publish.

The automation itself — the scheduled task definitions, the WordPress scripts, the SEO audit
tooling — lives in a private repository, because it is wired to a specific site and carries
credentials and analytics.

## Licence

Shared as a reference. The writing guidelines are Chinmay Namase's own; please adapt the ideas
rather than republishing the text as your own.
