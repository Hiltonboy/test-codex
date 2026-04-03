---
name: life-sciences-case-analyzer
description: Produce publication-ready Chinese analyses of recent (last 30 days) US and EU court decisions relevant to life sciences transactions. Use when the user asks for pharma/biotech/medtech or digital-health case selection, deal-focused reasoning, clause-level drafting takeaways, monthly Top 5/Top 10 digests, or templates covering control, CRE, earn-out, IP ownership/licensing, antitrust, data compliance, and regulatory risk.
---

Execute the following workflow.

## 1) Scope and jurisdiction filter (mandatory)

Select only court decisions that satisfy all conditions below:
- Jurisdictions:
  - United States: federal and state courts (including Delaware and other transaction-heavy courts)
  - European Union courts only: Court of Justice (CJEU) and General Court (GC)
- Industry: life sciences in a broad sense (pharma, biotech, medtech, healthcare services, digital health, clinical/health data)
- Transaction relevance: decision must materially involve one or more of:
  - control allocation
  - commercially reasonable efforts (CRE) or equivalent efforts covenant
  - earn-out/contingent value mechanics
  - IP ownership or licensing structure
  - antitrust/competition constraints affecting deals
  - regulatory risk allocation

If relevant decisions in the last 30 days are limited, explicitly state the date window and provide the highest-confidence subset rather than padding with weak cases.

## 2) Research rules

- Verify each case date and court level before writing.
- Prefer primary sources (court opinions, official press releases, court dockets) over commentary.
- Provide absolute dates (e.g., 2026-03-19) to avoid ambiguity around “this month/last month.”
- Preserve neutral tone: no advocacy, no emotional wording.

## 3) Required output style

Write in Chinese, professional but readable for BD/investment audiences.
- Avoid textbook phrasing and AI-sounding boilerplate.
- Keep section structure clear but do not over-fragment into too many short paragraphs.
- Use “transaction language” instead of pure litigation fact narration.

## 4) Per-case mandatory structure

For each selected case, include all sections below in order:

1. 【案件背景（交易视角）】
   - Explain deal relationship (license / acquisition / JV / post-closing governance)
2. 【争议是如何产生的】
   - Show where the deal or performance process created the dispute
3. 【法院是如何判断的（核心 reasoning）】
   - Distill the decisive logic and clause-interpretation path
4. 【这个判决真正重要的点】
   - Provide a neutral but clear viewpoint (e.g., “该判决实际上传递了一个信号…”) 
5. 【对交易结构的影响】
   - Analyze implications for control, license-vs-equity boundary, IP control, CRE, earn-out triggers
6. 【条款层面的启示（重点）】
   - Must include:
     - 风险点（what goes wrong）
     - drafting方向（how to fix）
     - Optional near-clause structure examples (not full contract language required)

## 5) Long-form article wrapper (default)

When asked for a publishable article, use this shell:
- 标题：必须体现“交易含义”
- 开头 Hook：一句话说明该案与交易/BD的关系
- 正文：按“每案六段结构”输出
- 结尾：总结法院趋势与对未来交易设计的影响

## 6) Monthly digest mode

When asked for “Top 5/Top 10” monthly digest:
- Suggested title: `过去一个月最值得关注的X个生命科学判例（交易律师视角）`
- Opening must include:
  - one-line market trend
  - one-line case-pattern observation (e.g., control disputes rising)
- Each case can be shorter (3–5 compact paragraphs), but must still include at least:
  - deal background
  - key dispute
  - one-line drafting signal
- Closing must answer:
  - “法院在往哪个方向走”
  - “对未来交易的潜在影响”

## 7) Quality checklist before finalizing

Confirm all boxes:
- [ ] All cases are within the stated date window and eligible courts
- [ ] Each case is genuinely life-sciences + transaction relevant
- [ ] Each case has clause-level drafting takeaways
- [ ] Writing is publishable with minimal user edits (target 5–10%)
- [ ] Sources are linked
