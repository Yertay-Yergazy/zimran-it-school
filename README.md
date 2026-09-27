# Zimran IT School — Test Submissions

Two independent business/data analyses submitted for the Zimran IT School test.

Prepared by **Yertay Yergazy** — [LinkedIn](https://www.linkedin.com/in/yertay-yergazy/) · ertaiergazy04@gmail.com

## Contents

- [`task-1-presentation.pdf`](task-1-presentation.pdf) — Task 1: Spotify growth & retention teardown (11-slide deck, widescreen 16:9)
- [`task-2-analysis.xlsx`](task-2-analysis.xlsx) — Task 2: partner ROI analysis (completed tables + written answers)

---

## Task 1 — Spotify: Growth & Retention Teardown

An independent business analysis of Spotify: how the company acquires, converts, and retains customers, and what's worth learning from it.

**What's inside the deck:**

1. **Prepared By** — author & contact
2. **Business Model** — who pays, why, and how it's priced
3. **Key Metrics** — growth (MAU, subscribers, revenue, ARPU) and efficiency (conversion, margins, cash flow), each with YoY change
4. **Margin** — where the revenue actually goes, and why the margin structure looks the way it does
5. **Acquisition** — channels used, marketing spend trend, and why Spotify doesn't lean on paid acquisition
6. **Funnel** — the top mechanics converting free users to Premium
7. **Retention** — a breakdown of Spotify Wrapped as a retention mechanic
8. **What We'd Learn** — four takeaways applicable beyond Spotify
9. **Sources & Methodology** — every figure traces to a primary filing or an official Spotify statement; anything without one is explicitly labeled as an estimate

**Sources:** SEC 20-F / 6-K filings (Spotify and Netflix, as a comparable), Spotify's Q2 2026 shareholder deck and earnings calls, Spotify Newsroom (Wrapped 2025, Investor Day 2026), and industry coverage (Music Business Worldwide, Digital Music News, eMarketer) for figures Spotify doesn't disclose directly — labeled accordingly throughout the deck.

**Design:** styled after [zimran.io](https://zimran.io/)'s visual identity (dark/violet palette, Space Grotesk + DM Sans typography).

---

## Task 2 — Partner ROI Analysis ("zimran.test")

Reverse-engineered from a 14,966-row raw click-level dataset (click_id, profile_id, partner_id, country, age, gender, OS) — not estimated from the summary numbers alone.

**What's inside the workbook (3 sheets):**

1. **Task 2 - Tables** — Table 1 (zimran.test's ROI per partner: clicks → registrations → leads → 6-month income → ROI → keep/drop decision) and Table 2 (each partner's own media-buying economics: impressions, CPM/CPC, budget, profit, ROI)
2. **Methodology** — exact definitions used (e.g. how "leads" were computed from raw rows), and the assumptions that aren't fully specified by the task (flagged explicitly, with a sensitivity check on the borderline partner)
3. **Answers** — written answers to all six Task 2 questions, each backed by the computed numbers

**Headline result:** Partner #1 mobile is clearly profitable (ROI +107%) and should be kept; Partner #1 desktop is a clear drop (ROI −18%); Partner #2 is a genuine borderline case whose keep/drop conclusion flips depending on a modeling assumption the task doesn't pin down — flagged rather than forced into a false-confidence answer.
