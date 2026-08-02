# General AI Fluency — Impact Project

**Ummema Atif** · FinTech Student, FAST-NUCES ('28) · FlyRank AI Intern
Capstone for the General AI Fluency track (Week 6)

> *I turn vague business questions into models you can actually evaluate.*

---

## Overview

This capstone covers the three deliverables of the AI Fluency Impact Project:

1. **AI stack literacy** — understanding the core building blocks (LLMs, RAG, agents) behind modern AI tools
2. **Personal brand website** — a live, self-built portfolio site
3. **A shipped personal agent** — a working AI agent, live-tested end to end

---

## 1. AI Stack

Covered through Anthropic Academy and applied hands-on during the FlyRank AI internship:

- **LLMs** — how next-token prediction, hallucination, and knowledge cutoffs shape model behavior
- **The 4Ds framework** — Delegation, Description, Discernment, Diligence — for working effectively with AI tools
- **RAG & agents** — how retrieval and tool-use extend a base model into something that can act on real data

---

## 2. Personal Website

**Live at:** [`ak470107.github.io`](https://ak470107.github.io)

A single-page site built with plain HTML/CSS (no frameworks), hosted free on GitHub Pages.

**Sections:**
- **About** — background, education, and current focus
- **Experience** — FlyRank AI internship + society roles
- **Projects** — ML capstone, the shipped agent, and other coursework
- **Skills** — languages, data/BI tools, databases, finance tools
- **Contact** — email, LinkedIn, GitHub

**Design notes:** styled around a "data contract / verification" motif — collapsible sections, dashed ledger-style project rows, and a status tag on each project (`Complete` / `In progress`) — a nod to the data-contract and verification work at the center of the ML capstone.

---

## 3. Personal Agent — Business Question Refiner

A working AI agent built in **n8n**, tied directly to the through-line above.

**What it does:** takes a vague business question and returns:
1. A restated, measurable version of the question
2. 2–3 success metrics (with how they'd be calculated)
3. The specific data needed
4. One key risk or limitation

**Example run** — input: *"Should we invest more in our mobile app?"*
Output included a measurable 12-month growth hypothesis, three metrics (revenue growth %, MAU growth %, incremental ROI), a concrete data list, and an attribution/causality risk — live-tested with the real model, not simulated.

**Status:** live-tested end to end in the n8n editor. The chat interface is private to the n8n workspace; a walkthrough/screenshot of a live run is included on the website in place of a public link, since the underlying webhook only returns a start confirmation rather than the interactive chat.

---

## Repo Structure

```
├── index.html          # personal website (single file, GitHub Pages)
└── README.md            # this file
```

---

## Links

- Website: https://ak470107.github.io
- ML internship repo: https://github.com/ak470107/ML-internship
- LinkedIn: https://www.linkedin.com/in/ummema-atif-2275471a1
