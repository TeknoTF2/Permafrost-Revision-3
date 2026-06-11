# Permafrost — Editorial & Analysis Website

A complete editorial, beta-read, craft, and market analysis of the **Permafrost** manuscripts
(Book One & Book Two, Revision 3), produced from a full read of both books.

## Viewing the site

Open `site/index.html` in any browser, or serve it locally:

```bash
cd site
python3 -m http.server 8000
# then visit http://localhost:8000
```

> The Data page uses Chart.js from a CDN, so charts need an internet connection.
> All figures are also stated in the page text.

## Contents

| Page | What's in it |
|---|---|
| `site/index.html` | Executive summary, overall verdict, ten-second diagnosis, top-3 revision notes |
| `site/analysis.html` | Structural analysis of both books, 8 major themes, world/setting review, macro craft notes |
| `site/characters.html` | Clickable hub → full character pages in `site/characters/` (the five leads, Yoo, Billy, Barbatos, Dantalion/Everos, Elizabeth, Orthek, plus the full supporting cast) |
| `site/chapters-book1.html` | All 30 chapters: strengths, improvements, emotional read, 1–10 rating |
| `site/chapters-book2.html` | All 40 chapters, same treatment |
| `site/beta-read.html` | Reader-experience report: highs, dips, confusions, arguments, questions |
| `site/data.html` | Hard data with charts: chapter lengths, dialogue density, prose tics, crutch words, adverbs, filter words, character page-time |
| `site/market.html` | Comps, audience, hooks, blurb draft, path analysis, commercial risks |

## Methodology

- Both manuscripts were read in full; chapter notes are preserved in `.analysis/`.
- All statistics on the Data page were computed directly from the manuscript text
  (chapter segmentation by heading; dialogue measured via curly double quotes;
  interior monologue via curly single quotes).
- Quoted lines in the analysis are verbatim from the Revision 3 text.
