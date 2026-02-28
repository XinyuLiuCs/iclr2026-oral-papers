# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository (https://github.com/XinyuLiuCs/iclr2026-oral-papers) contains the complete list of ICLR 2026 Oral papers (223 papers) with abstracts, authors, affiliations, and Chinese translations.

**License**: MIT License (Copyright 2025 XinyuLiuCs)

## Repository Structure

Flat structure with all files in the root directory:

- `paper-list.md` — Quick reference table: paper number, title, OpenReview link
- `paper-details.md` — Full English details: title, authors, affiliations, abstract, TL;DR, keywords, primary area, OpenReview link
- `paper-details-translated.md` — Bilingual version (English + Chinese): translated titles, TL;DRs, and abstracts
- `README.md` — Repository description and SEO content

## Data Source

All paper data is sourced from the [OpenReview API](https://api2.openreview.net/notes?content.venue=ICLR+2026+Oral). Author affiliations are retrieved from OpenReview author profiles via the profiles API.

## Document Format

### paper-list.md

Markdown table with columns: #, Title, OpenReview link.

### paper-details.md

Each paper section:

```
## {num}. {Title}

**OpenReview**: {url}
**Authors**: {author1 (institution1), author2 (institution2), ...}
**Institutions**: {deduplicated institution list}
**Primary Area**: {area}
**Keywords**: {keywords}
**TL;DR**: {one-line summary}
**Abstract**: {full abstract}

---
```

### paper-details-translated.md

Each paper section (English first, Chinese below):

```
## {num}. {English title}

**{Chinese title}**

**OpenReview**: {url}
**Authors**: {authors with affiliations, original}
**Institutions**: {institutions, original}
**Primary Area**: {area}
**Keywords**: {keywords}

**TL;DR**: {English TL;DR}
**TL;DR翻译**: {Chinese TL;DR}

**Abstract**:
{English abstract}

**摘要翻译**:
{Chinese abstract}

---
```

## Translation Standards

Two-step process (output only the final result):
1. **Literal Translation** — Translate sentence-by-sentence faithfully
2. **Idiomatic Refinement** — Polish for natural, professional Chinese

### Rules

- Target: Simplified Chinese (简体中文), professional/technical tone
- Do not add explanations or commentary not in the original
- Do not translate: product names, model names, dataset names, benchmark names, method/system names and acronyms (e.g., DPO, RAG, GNN, Mamba, RLHF, ImageNet)
- Preserve technical terminology consistency across all translations
- Preserve all hyperlinks and references

## Git Workflow

- **User identity**: `XinyuLiuCs <xinyu.liu.cs@gmail.com>`
- **Remote**: `git@github.com:XinyuLiuCs/iclr2026-oral-papers.git` (SSH)
- **Commit messages**: Descriptive, in English

## Updating Data

To refresh or extend the paper list:

1. Query the OpenReview API: `https://api2.openreview.net/notes?content.venue=ICLR+2026+Oral&limit=100&offset={n}`
2. Fetch author profiles in batches: `https://api2.openreview.net/profiles?ids={comma-separated-ids}`
3. Update `paper-list.md`, `paper-details.md`, and `paper-details-translated.md`
4. Update the paper count badge in `README.md` if total changes
