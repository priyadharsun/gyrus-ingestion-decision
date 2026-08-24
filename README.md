# Gyrus Ingestion Decision

A decision record evaluating five routes for getting Duck Creek data into a Snowflake
warehouse for the Gyrus broker platform.

**Live page:** https://priyadharsun.github.io/gyrus-ingestion-decision/

## What this covers

| Section | Contents |
|---|---|
| 01–04 | The decision, a Snowflake primer for engineers new to it, and the foundation work that is identical under every route |
| 05–09 | The five routes, each as a numbered walkthrough: Clarity data share, scheduled extracts, API ingestion, managed connector, direct database CDC |
| 10–13 | Cross-cutting concerns: deletes, the dimensional model, cost, security and PII |
| 14–18 | A weighted selection framework, the recommendation, vendor questions, a 90-day plan and risks |

## Structure

```
index.html   the complete page — self-contained, no build step, no dependencies
.nojekyll    tells GitHub Pages to serve the file as-is
```

The page is a single HTML file. Fonts load from Google Fonts; everything else is inline.
It respects the visitor's light/dark preference.

## Editing

Edit `index.html` directly and push. GitHub Pages redeploys automatically, usually within
a minute.

## Status

Open — awaiting answers to the vendor questions in section 16. The status block at the top
of the page should be updated once a route is chosen.
