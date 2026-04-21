---
name: life-sciences-30d-briefing
description: Generate a practical 30-day international life sciences legal briefing with verifiable links. Use when the user asks for monthly/30-day updates on life sciences M&A, licensing, regulatory compliance, cross-border investment, or dispute developments, and needs output in a client-ready Chinese or bilingual memo format.
---

# Life Sciences 30-Day Briefing

Build a source-backed briefing for lawyers covering five tracks: M&A, Licensing, Regulatory, Cross-border Investment, and Disputes.

## Workflow

1. **Lock reporting window**
   - Compute exact dates as: `today - 30 days` to `today`.
   - Write absolute dates at the top of the report.

2. **Collect only verifiable sources**
   - Prioritize official regulator pages, company investor relations releases, court/agency publications, and top-tier law firm client alerts.
   - For each candidate item, capture: date, actor, event type, legal relevance, source URL.
   - Drop items without a direct URL.

3. **Select 8-12 high-signal developments**
   - Keep balanced coverage across the five tracks.
   - Prefer developments with clear legal/transactional implications.

4. **Draft in “事实-影响-动作” format**
   - For each item, write:
     - 事实（what happened + exact date）
     - 影响（deal/regulatory/dispute consequence）
     - 动作（contractual/structuring/compliance action）

5. **Produce full report sections**
   - A. TL;DR (10 points)
   - B. Five-track deep dive
   - C. Verifiable source links grouped by track
   - D. Next-30-day watchlist

6. **Run quality gate before finalizing**
   - Every factual claim has a link in section C.
   - Dates are within the reporting window (or explicitly marked as context).
   - No placeholder text, no uncited numbers.

## Output Requirements

- Default language: Chinese (unless user asks otherwise).
- Use concise legal writing and practical deal language.
- Keep recommendation lines executable (e.g., specific clause/condition/filing action).
- When uncertainty exists, state it explicitly and avoid over-claiming.

## Use bundled resources

- Use `references/source-priority.md` to choose source reliability tiers.
- Use `references/jurisdiction-playbooks.md` when the user needs jurisdiction-specific clause actions (US/EU/UK/HK/SG).
- Use `assets/report-template.md` as the default output skeleton.
