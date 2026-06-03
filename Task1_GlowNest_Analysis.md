# Task 1: GlowNest Campaign Viability Analysis
**DT AI Business Analyst Assignment | Ecommerce Fellow**

---

## Brand Snapshot
| Field | Value |
|---|---|
| Product | Premium Face Serum |
| Selling Price (SP) | ₹800 |
| COGS | ₹280 |
| Amazon Referral Fee | 12% of SP = ₹96 |
| Monthly Ad Spend | ₹3,00,000 |
| Units via Ads | 1,500 |
| Organic Units | 2,000 |
| Fixed Costs | ₹1,50,000 |

---

## Q1: Unit Economics (Ad-Attributed Sales)

| Metric | Formula | Value |
|---|---|---|
| Gross Margin per Unit | ₹800 − ₹280 | **₹520** |
| Amazon Referral Fee per Unit | ₹800 × 12% | **₹96** |
| Ad Cost per Unit | ₹3,00,000 ÷ 1,500 | **₹200** |
| Net Margin per Unit (Ad Sales) | ₹520 − ₹96 − ₹200 | **₹224** |
| Net Margin per Unit (Organic) | ₹520 − ₹96 | **₹424** |

**Interpretation:** The product has strong gross margins (65% of SP) but the ad cost per unit (₹200) is consuming 38% of that gross margin. Organic sales are significantly more profitable — ₹424 vs ₹224 per unit. This is the core reason why growing organic share is the most important long-term lever.

---

## Q2: Monthly Profitability

| Item | Calculation | Value |
|---|---|---|
| Revenue from Ad Sales | ₹800 × 1,500 | ₹12,00,000 |
| Revenue from Organic Sales | ₹800 × 2,000 | ₹16,00,000 |
| **Total Monthly Revenue** | | **₹28,00,000** |
| Profit from Ad Units | ₹224 × 1,500 | ₹3,36,000 |
| Profit from Organic Units | ₹424 × 2,000 | ₹8,48,000 |
| Gross Profit (pre-fixed) | ₹3,36,000 + ₹8,48,000 | ₹11,84,000 |
| Fixed Costs | | −₹1,50,000 |
| **Monthly Net Profit** | | **₹10,34,000** |

**Interpretation:** GlowNest is solidly profitable. ₹10.34L monthly net profit on ₹28L revenue = ~37% net margin. Notably, organic sales generate 2.5× more profit than ad-attributed sales despite the same unit volume (₹8.48L vs ₹3.36L). The business is healthy.

---

## Q3: ACOS and TACOS

| Metric | Formula | Value | Health |
|---|---|---|---|
| ACOS | ₹3,00,000 ÷ ₹12,00,000 | **25.0%** | ✅ Healthy |
| TACOS | ₹3,00,000 ÷ ₹28,00,000 | **~10.7%** | ✅ Excellent |
| Break-Even ACOS | (₹520 − ₹96) ÷ ₹800 | **53%** | Ceiling for profitability |

**Is ACOS of 25% healthy?** Yes, in context. The break-even ACOS (the point at which ad spend eats all available margin per ad unit) is 53%. GlowNest is spending only 25% — well within the profitable zone. For a premium skincare brand (₹800 SKU), 25% is competitive.

**Is TACOS of 10.7% healthy?** Very. TACOS below 10-15% is generally considered strong for a brand with a mix of organic and paid. The organic base (2,000 units) is diluting the ad spend's weight on total revenue, which is exactly what healthy brand equity looks like on Amazon.

**What to watch:** ACOS and TACOS will look very different if organic sales drop or if ad spend is increased without proportional unit gains.

---

## Q4: Break-Even Ad Spend

The break-even is the point where monthly net profit = 0.

**Logic:** Total contribution margin (margin per unit × all units) must cover both fixed costs and ad spend.

- Contribution per unit (pre-ad) = ₹800 − ₹280 − ₹96 = **₹424**
- Total contribution (3,500 units) = ₹424 × 3,500 = **₹14,84,000**
- Fixed costs = ₹1,50,000
- **Maximum ad spend = ₹14,84,000 − ₹1,50,000 = ₹13,34,000/month**

**Corresponding break-even ACOS:**
₹13,34,000 ÷ (₹800 × 1,500) = **111%**

Wait — this seems very high. That's because organic units provide margin that subsidises ad losses. If we assume unit volumes are constant (ad units = 1,500 regardless of efficiency), the brand can technically sustain very high ACOS because organic profit offsets it.

**More operationally meaningful break-even (ad units only, ignoring organic subsidy):**
Max ad spend where net margin per ad unit ≥ 0: Ad Cost per Unit ≤ ₹424 → Max ad spend = ₹424 × 1,500 = **₹6,36,000**
Corresponding ACOS = ₹6,36,000 ÷ ₹12,00,000 = **53%**

**Recommendation to GlowNest:** Think in two zones. The operational danger zone is ACOS above 53% (losing money on every ad-attributed unit). The business-level danger zone is when total ad spend exceeds ₹13.34L (unlikely at this scale). Current ₹3L spend has enormous headroom.

---

## Q5: Scenario — ACOS Worsens to 40%, Ad Units Drop to 1,200

At 40% ACOS with 1,200 ad units, implied ad spend = 0.40 × ₹800 × 1,200 = **₹3,84,000**

| Metric | Base | Worsened |
|---|---|---|
| Ad Spend | ₹3,00,000 | ₹3,84,000 |
| Ad Units | 1,500 | 1,200 |
| Ad Cost per Unit | ₹200 | ₹320 |
| Net Margin per Ad Unit | ₹224 | ₹104 |
| Profit from Ad Units | ₹3,36,000 | ₹1,24,800 |
| Profit from Organic | ₹8,48,000 | ₹8,48,000 |
| Gross Profit | ₹11,84,000 | ₹9,72,800 |
| Fixed Costs | −₹1,50,000 | −₹1,50,000 |
| **Monthly Net Profit** | **₹10,34,000** | **₹8,22,800** |

**The business remains profitable** (₹8.23L profit), but profit has fallen 20.4%. The organic base is the buffer.

**What I'd recommend:**
1. **Don't panic, but act:** A 40% ACOS with falling units is an early warning signal, not a crisis — organic cushion is working.
2. **Audit spend immediately:** Identify which campaigns/keywords drove the ACOS spike. Often 20% of keywords drive 80% of wasteful spend.
3. **Check listing quality:** Is click-through-rate falling? That's a listing problem, not an ad problem.
4. **Protect organic rank:** Paradoxically, cutting ad spend too aggressively can hurt organic ranking on Amazon. Don't cut below the organic-support threshold.
5. **Fix the conversion rate:** If the listing converts at 8% vs a competitor at 12%, no amount of ACOS optimisation fixes that.

---

## Q6: Scenario — Double Ad Spend to ₹6,00,000 | Units Increase to 2,500

| Metric | Base | Scaled |
|---|---|---|
| Ad Spend | ₹3,00,000 | ₹6,00,000 |
| Ad Units | 1,500 | 2,500 |
| Ad Revenue | ₹12,00,000 | ₹20,00,000 |
| Total Revenue | ₹28,00,000 | ₹36,00,000 |
| ACOS | 25% | 30% |
| TACOS | 10.7% | 16.7% |
| Ad Cost per Unit | ₹200 | ₹240 |
| Net Margin per Ad Unit | ₹224 | ₹184 |
| Profit from Ad Units | ₹3,36,000 | ₹4,60,000 |
| Profit from Organic | ₹8,48,000 | ₹8,48,000 |
| Gross Profit | ₹11,84,000 | ₹13,08,000 |
| Fixed Costs | −₹1,50,000 | −₹1,50,000 |
| **Monthly Net Profit** | **₹10,34,000** | **₹11,58,000** |
| **Incremental Profit** | — | **+₹1,24,000** |
| **Incremental Ad Spend** | — | **+₹3,00,000** |

**Return on incremental spend: ₹1,24,000 extra profit on ₹3,00,000 extra spend = 41% ROI.** Not spectacular, but not bad.

**Should GlowNest do it?**

**Yes, with conditions:**
- TACOS rises from 10.7% to 16.7% — technically crosses the 15% yellow-flag threshold. This is acceptable if organic share grows alongside.
- The real question is the brand's growth objective. If the goal is **topline/market share**, scale up — ₹8L more revenue per month accelerates category rank and builds organic equity for future months (the flywheel).
- If the goal is **margin maximisation**, stay at current spend. The incremental ROI is modest.
- **Key risk:** Diminishing returns are real. Only 67% unit increase from 100% spend increase. If the next ₹3L brings only 500 units (not 1,000), the math breaks.

**My recommendation:** Test a step-up to ₹4.5L first. Measure incremental ROAS on the additional ₹1.5L carefully before committing to full doubling.

---

## Summary Scorecard

| Metric | Value | Status |
|---|---|---|
| Monthly Net Profit | ₹10,34,000 | ✅ Healthy |
| ACOS | 25% | ✅ Well within break-even (53%) |
| TACOS | 10.7% | ✅ Excellent |
| Organic contribution | ₹8,48,000 of ₹11,84,000 gross profit | ✅ Strong base |
| Break-even ad spend | ₹13,34,000 | ✅ Large headroom |

**GlowNest is a well-run Amazon business. The organic base is strong and provides a meaningful buffer against ad volatility. The primary growth lever is growing organic share, not increasing ad spend.**
