> **About this report.** Generated on 24 Sep 2026 by running `Investment_Due_Diligence_Agent.ipynb` unedited on Claude Sonnet 5 + Tavily web search (4.0 min, 5 web searches, about $1.19 of API usage).
> Horizon AI Labs, its pitch and its team are **fictional** (see `sample_data/sample_pitch_deck.txt`). Real companies the search returned are named in the memo only as unrelated look-alikes; real people who share the fictional founders' names have been removed from this public copy. Nothing else was edited.
> This is AI output for teaching: check it before relying on it.

# Horizon AI Labs — Investment Memo

---

## Executive Summary

Horizon AI Labs is pitching itself as an enterprise-grade autonomous supply chain optimization platform targeting mid-market retailers, claiming a 35% reduction in logistics costs and a 40% reduction in delivery times (Pitch: Executive Summary). The company is raising a $5M Series A (Pitch: Fundraising) on the back of $120K ARR from 8 pilot customers (Pitch: Traction) and a founding team with pedigreed résumés at Amazon, Instacart, and Blue Yonder (Pitch: Team).

However, independent verification raises serious concerns on two fronts: (1) **internal arithmetic in the pitch deck does not reconcile** — pricing, customer count, ARR, CAC, and revenue projections are mutually contradictory (see Red Flags below, with full arithmetic); and (2) **no public record of the company, its founders, or its funding round could be located** across five targeted web searches covering the company name, founder backgrounds, funding history, market data, and competitors. This combination of internal inconsistency and total absence of external corroboration is a material red flag that should stop this deal at INVESTIGATE, not proceed to term sheet, until independently resolved.

**Recommendation: INVESTIGATE (do not invest until diligence gaps are closed).**

---

## Company Overview

- **Founded:** August 2023 (Pitch: Company Overview)
- **Headquarters:** San Francisco, CA (Pitch: Company Overview)
- **Team size:** 12 employees (Pitch: Company Overview)
- **Product:** ML platform that ingests real-time data from ERP/WMS systems (Pitch: Our Solution) and integrates with Shopify, SAP, and Oracle (Pitch: Our Solution), claiming 2-week deployment vs. an industry norm of 6+ months (Pitch: Our Solution; Pitch: The Problem)
- **Pricing:** $15K/month per typical mid-market customer (Pitch: Our Solution)
- **Leadership:** CEO Alice Chen, ex-Director of Supply Chain Tech at Amazon; CTO Bob Kumar, ex-Principal ML Engineer at Instacart; VP Sales Carol Martinez, ex-Enterprise AE at Blue Yonder (Pitch: Team)

**Independent verification status:** No public company profile, press coverage, Crunchbase-type record, or founder LinkedIn history matching these details could be located. Searches for "Horizon AI Labs" surfaced only unrelated companies: a demand-forecasting platform at horizonsolutions.ai (https://www.horizonsolutions.ai), a supply-chain planning company called "Horizon"/Vyora (source: a personal LinkedIn post; name and link removed from this public copy), "New Horizon" (https://www.newhorizon.ai), and an internal Unilever lab called "AI Horizon3 Lab" (https://www.unilever.com/news/news-search/2023/new-ai-lab-to-boost-innovation-technology-and-collaboration) — none of which match the claimed company.

---

## Investment Thesis (As Pitched)

The company's thesis, per its own materials, is: mid-market retailers lose $40B annually to supply chain inefficiencies (Pitch: The Problem); incumbent solutions are expensive ($100K+/year), slow to implement (6+ months), and often fail to deliver ROI (Pitch: The Problem); Horizon AI Labs offers a faster, cheaper, ML-driven alternative that captures an underserved mid-market segment within a $25B TAM / $6B SAM (Pitch: Market Opportunity), evidenced by early traction (8 pilots, $120K ARR, NPS of 72) (Pitch: Traction) and a credible, operator-heavy founding team (Pitch: Team) — positioning the company to scale rapidly with proven unit economics (Pitch: Closing Remarks).

This is a coherent narrative on paper. The problem is that almost none of its load-bearing numbers survive cross-checking against either the deck's own internal math or external market data (see below).

---

## Strengths (As Pitched — Unverified Externally)

1. **Differentiated speed-to-value positioning:** 2-week deployment vs. 6-month industry norm is a compelling wedge if true (Pitch: Our Solution vs. Pitch: The Problem).
2. **Founding team pedigree:** Amazon, Instacart, and Blue Yonder backgrounds would be strong signals of domain expertise (Pitch: Team) — *see Red Flags, these are unverified*.
3. **Multi-vertical diversification:** Grocery, fashion, and e-commerce customer base reduces single-sector concentration risk, if accurate (Pitch: Risk Mitigation).
4. **Budget discipline on paper:** The $5M use-of-funds breakdown ($2.5M S&M + $1.5M Engineering + $500K Ops + $500K Buffer) sums correctly to the $5M ask (Pitch: Fundraising) — this is the one major internal check that passes.
5. **Real market exists:** Independent research confirms a genuine, large, and growing supply chain software market ($19.3B–$35.2B depending on source/year — https://market.us/report/supply-chain-management-software-market; https://www.marketsandmarkets.com/Market-Reports/supply-chain-management-market-190997554.html), and a validated crowded field of AI-native and incumbent competitors (https://www.htfmarketinsights.com/report/4397339-ai-in-supply-chain-and-logistics-market), so the category itself is not fictional even if the company's specific claims are unverified.

---

## Red Flags

### 1. ARR / Pricing / Customer Count are mutually contradictory — **High Confidence**
- Pitch states price = $15K/month/customer (Pitch: Our Solution) → **$15K × 12 = $180K/year/customer**.
- Pitch states 8 pilot customers (Pitch: Traction).
- Expected ARR: **8 × $180K = $1,440,000**.
- Pitch states actual ARR = **$120K** (Pitch: Traction; Pitch: Financial Projections).
- **Gap: $1.44M expected vs. $120K stated — a ~12x discrepancy.**
- Reverse check: $120K ÷ 8 = $15K/customer/**year**, i.e., $1,250/month — 12x below the stated $15K/**month** price.
- **Conclusion:** Either the price, the customer count, or the ARR is fabricated or wildly mis-stated. All three cannot be simultaneously true.

### 2. LOI value implies a different price point than stated — **High Confidence**
- Pitch states 2 LOIs worth a combined $180K ARR (Pitch: Traction) → **$180K ÷ 2 = $90K/customer/year = $7.5K/month**.
- Pitch states standard price is $15K/month (Pitch: Our Solution).
- **Gap: LOI-implied price is exactly 50% of the stated list price**, with no explanation (e.g., discount, different tier) disclosed.

### 3. Stated CAC target is inconsistent with the company's own spending plan — **High Confidence**
- Pitch: $2.5M Sales & Marketing budget to land 50 new customers (Pitch: Fundraising) → **implied CAC = $2.5M ÷ 50 = $50,000/customer**.
- Pitch: target CAC = $8,000 (Pitch: Market Opportunity).
- **Gap: implied CAC is 6.25x the claimed target CAC** ($50K vs. $8K).

### 4. LTV:CAC ratio is implausibly high and methodologically suspect — **Medium Confidence**
- Pitch: LTV = $180K, CAC = $8K (Pitch: Market Opportunity) → **LTV:CAC = 22.5:1**.
- Healthy SaaS benchmarks are typically 3:1–5:1; ratios above ~20:1 usually indicate an underestimated CAC or an overstated/mis-modeled LTV rather than "exceptional" economics.
- Additionally, $180K LTV exactly equals one year of contract value at the stated $15K/month price ($15K × 12 = $180K), implying the "lifetime" value assumes only a single year of retention — inconsistent with a genuine multi-year LTV calculation.

### 5. Customer acquisition plan implies revenue far above the stated 2025 projection — **High Confidence**
- Pitch: land 50 new customers with the S&M budget (Pitch: Fundraising) at $15K/month = $180K/year each → **50 × $180K = $9,000,000** in potential incremental ARR.
- Pitch: 2025 projected ARR = $2.5M (Pitch: Financial Projections).
- **Gap: implied capacity is 3.6x the actual 2025 target**, even before accounting for existing $120K base — the sales plan and the revenue projection do not describe the same business.

### 6. TAM claim is below independent market data for the same year — **Medium Confidence**
- Pitch: TAM = $25B (2024) (Pitch: Market Opportunity).
- MarketsandMarkets: SCM software market = $35.21B in 2024 (https://www.marketsandmarkets.com/Market-Reports/supply-chain-management-market-190997554.html).
- Maximize Market Research: $31.19B in 2023, trending toward $58.13B by 2030 (https://www.maximizemarketresearch.com/market-report/global-supply-chain-management-software-market/94230).
- Market.us: $19.3B in 2023 (https://market.us/report/supply-chain-management-software-market).
- **Gap:** The deck's $25B figure sits below the two higher independent estimates (~20–30% understatement vs. MarketsandMarkets/Maximize) and above the lowest (Market.us), suggesting either cherry-picked or unsourced methodology rather than a rigorous TAM build.

### 7. No public corroboration of the company's existence, founders, or funding round — **High Confidence (absence of evidence)**
- Zero matches for "Horizon AI Labs" as a San Francisco supply-chain optimization startup founded August 2023 across company, founder, and funding searches.
- "Alice Chen" and "Bob Kumar" searches return only unrelated people who share these common names (names and profile links removed from this public copy), none connected to Amazon supply chain tech, Instacart ML, or this company.
- Funding search surfaces only unrelated, confirmed-different companies: a BFSI-focused "Horizon AI" with a $3.5M seed (https://startupintros.com/orgs/horizon-ai; https://theventurecodex.com/companies/horizon-ai) and "Horizon3.ai," a cybersecurity unicorn with an entirely distinct funding history through a $250M Series E at $2B valuation (https://techcrunch.com/2026/08/03/horizon3-hits-2-billion-valuation-with-250m-series-e-as-ai-threats-escalate; https://www.wsj.com/pro/cybersecurity/cyber-startup-horizon3-ai-raises-250-million-e1ca54b6).
- **Conclusion:** For a company claiming enterprise pilots, LOIs, and a $5M raise, a complete absence of digital footprint (no press, no LinkedIn presence for named executives, no funding database entry) is atypical and warrants direct verification before proceeding.

### 8. Efficacy claim (35% cost reduction) exceeds observed competitive benchmark — **Medium Confidence**
- Pitch: 35% reduction in logistics costs (Pitch: Executive Summary; Pitch: Our Solution).
- Comparable competitor Alice Labs claims 15–30% cost reduction with 30–90 day ROI (https://alicelabs.ai/en/industries/supply-chain-logistics-manufacturing).
- **Gap:** Horizon's claimed 35% sits above the top of the observed competitive range, with no underlying methodology or case study disclosed to substantiate the delta.

### 9. Growth-rate deceleration is steep and unexplained — **Medium Confidence**
- $120K (2024) → $2.5M (2025) implies **~20.8x** growth; $2.5M (2025) → $8M (2026) implies **~3.2x** growth (Pitch: Financial Projections).
- These multiples are not directly stated in the deck (they are derived), and the sharp deceleration from 20x to 3.2x is unexplained — particularly given Red Flag #5, which shows the underlying 2025 sales-capacity assumption is itself internally inconsistent with the $2.5M figure.

---

## Unverified Claims (Cannot Confirm or Deny)

The following claims have no supporting or contradicting external evidence and rely entirely on the pitch itself:

- Founding date, HQ, and headcount (Pitch: Company Overview) — no filings or company page located.
- "$40B annual loss to supply chain inefficiencies" (Pitch: The Problem) — no matching figure in any market report reviewed.
- Incumbent solution cost ($100K+/year) and implementation timelines (6+ months) (Pitch: The Problem) — directionally plausible (Netherlands AI market report cites ~€500K average AI integration cost for SMEs: https://www.researchandmarkets.com/reports/6210330/netherlands-ai-in-supply-chain-optimization-market) but not a direct confirmation.
- Technical claims: real-time ERP/WMS ingestion, 2-week deployment, integrations with Shopify/SAP/Oracle (Pitch: Our Solution) — no case studies, customer reviews, or partner directory listings found.
- NPS of 72 vs. "industry average of 40" (Pitch: Traction) — self-reported metric with no independent source for either figure.
- $6B mid-market SAM segmentation (Pitch: Market Opportunity) — no independent report segments the market this way (100–500 employee mid-market retail band could not be isolated in any source reviewed).
- "Blue-chip advisor, founder of a $2B logistics startup" (Pitch: Risk Mitigation) — no name given, cannot be verified.
- "Proven integration partnerships with SAP and Oracle" (Pitch: Risk Mitigation) vs. "Integrates with" SAP and Oracle (Pitch: Our Solution) — ambiguous as to whether these are formal partnerships or simple technical integrations; no partner-program listing found for either vendor.
- All named team backgrounds (Amazon, Instacart, Blue Yonder) (Pitch: Team) — no LinkedIn or press corroboration found under these names.

---

## Recommendation: **INVESTIGATE**

This is not a PASS on the merits of the market opportunity — the supply chain software category is real, large, and growing (https://www.marketsandmarkets.com/Market-Reports/supply-chain-management-market-190997554.html), and the wedge (faster, cheaper deployment for underserved mid-market retailers) is a reasonable thesis. But the deal as currently packaged cannot be evaluated on its numbers, because those numbers contradict each other (Red Flags #1–5), and the company has **zero independent verification** of its existence, team, or traction (Red Flag #7). This combination — internal financial inconsistency plus total absence of external corroboration — is disqualifying until resolved. It is not yet a confirmed fraud pattern, but it is indistinguishable from one at this stage of diligence.

### Next Diligence Steps (Required Before Any Term Sheet)

1. **Direct founder interview + document verification:** Request cap table, incorporation documents (Delaware/CA entity registration), and bank statements showing actual ARR and cash position. Reconcile against Red Flags #1, #2, #3, #5.
2. **Reference calls with named pilot customers:** Independently contact at least 5 of the 8 claimed pilot customers to confirm contract value, actual monthly price paid, and satisfaction (validate or refute Red Flags #1–2 and the NPS claim).
3. **Founder background verification:** Request LinkedIn profiles, verify Amazon/Instacart/Blue Yonder employment directly with those companies' alumni networks or via background-check vendor (resolve Red Flag #7).
4. **Funding/legal check:** Run a formal PitchBook/Crunchbase/Delaware Secretary of State search (paid databases go beyond what public web search covers) to confirm entity existence and any prior funding history not captured in open web search.
5. **Unit economics reconciliation:** Request the underlying CAC/LTV model and customer contracts to reconcile the $8K CAC / $180K LTV claims against the $50K implied CAC from the S&M budget (Red Flags #3–4).
6. **TAM/SAM source request:** Ask for the specific market research methodology and sources behind the $25B TAM / $6B SAM figures, and compare against MarketsandMarkets, Maximize Market Research, and Market.us figures cited above.
7. **Advisor verification:** Obtain the name of the "$2B logistics startup founder" advisor and confirm the relationship directly.
8. **Technical diligence:** Request a live product demo and confirmation of actual SAP/Oracle integration status (partnership agreement vs. technical connector) (Red Flag re: Risk Mitigation vs. Our Solution ambiguity).

**Do not proceed to investment committee vote or term sheet until items 1–4 are resolved.** If independent verification (items 1–4) fails to surface a real, matching company and team, this should move immediately to PASS.