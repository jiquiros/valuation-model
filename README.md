# Valuation Model — Caesars Entertainment, Inc. (NASDAQ: CZR)

**Project:** Full intrinsic valuation during active M&A process  
**Unique angle:** Fertitta Entertainment announced a $17.6B all-cash acquisition of CZR on May 28, 2026 — this model was built during the **live go-shop period** (expires ~July 11, 2026) to answer: *is $31.00/share fair value, or is there room for a competing bid?*

---

## What this is

A full sell-side valuation model using three independent methods — DCF, trading comparables, and precedent transactions — applied to Caesars Entertainment during an active take-private process. All data sourced exclusively from public filings (SEC EDGAR, 8-K press releases, deal announcements).

> **Why CZR right now:** The go-shop window is open. The board retained PJT Partners to solicit superior proposals. This model provides the analytical foundation to evaluate whether $31.00 represents full value or leaves upside on the table.

---

## Files in this repository

| File | Description |
|------|-------------|
| `CZR_Valuation_Model.xlsx` | Full 6-tab valuation model |
| `README.md` | This file |

---

## Excel model — 6 tabs

| Tab | Content |
|-----|---------|
| **Assumptions** | All inputs in blue: revenue growth, EBITDA margins, WACC, TGR, deal parameters. Single source of truth for the entire model. |
| **DCF Valuation** | 5-year unlevered FCF projection → terminal value (Gordon Growth) → EV bridge → implied share price. Includes 5×5 WACC × TGR sensitivity table with color scale vs. $31 offer. |
| **Trading Comps** | Four gaming peers (MGM, Wynn, Boyd, Penn) with FY2025 actuals. Implied CZR valuation at median, mean, low, and high peer multiples. |
| **Precedent Transactions** | Nine gaming M&A deals (2018–2026). Separates operating company deals from real estate transactions. Implied CZR value at 8x–10x operator precedent range. |
| **Football Field** | Summary of all three methods in a single table. Low/base/high range per method vs. the Fertitta $31.00 offer. Analytical conclusion included. |
| **Deal Assessment** | Board-style analysis: deal parameters, valuation range summary, five key questions for the go-shop process, and a final recommendation. |

---

## CZR financial snapshot (FY2025 actuals)

| Metric | Value | Source |
|--------|-------|--------|
| Revenue | $11.5B | CZR 8-K, Feb 17 2026 |
| Same-store Adj. EBITDA | $3.624B | CZR 8-K, Feb 17 2026 |
| Caesars Digital EBITDA | $236M (+102% YoY) | CZR 8-K, Feb 17 2026 |
| EBITDA margin | ~31.5% | Calculated |
| Net debt | $11.0B | CZR 8-K, Feb 17 2026 |
| Diluted shares | ~185M | Est. post-buybacks |

---

## Deal snapshot — Fertitta acquisition

| Parameter | Value | Source |
|-----------|-------|--------|
| Offer price | $31.00/share (all-cash) | Definitive agreement, May 28 2026 |
| Implied equity value | $5.74B | Press release |
| Implied enterprise value | $17.6B | Press release |
| Implied EV / EBITDA | 8.91x | InsideArbitrage |
| Premium to unaffected price | 49% | vs. Feb 25 2026 close |
| Go-shop expiry | ~July 11, 2026 | Definitive agreement |
| Advisors | PJT Partners (CZR) · MS + GS (Fertitta) | Press release |

---

## Key findings

**DCF (base case — WACC 8.5%, TGR 2.5%):**
Implied share price ~$28–35 depending on assumptions. The Fertitta offer sits near the middle of the range — fair, but below the bull case if Digital EBITDA continues compounding at 50%+ annually.

**Trading comps (peer multiples 6.2x–7.3x EBITDA):**
Implied share price ~$22–29. The $31 offer is *above* the comp range — Fertitta is paying a control premium that the public market does not assign to CZR standalone. This is expected in take-private transactions.

**Precedent transactions (operator deals 8x–10x EBITDA):**
Implied share price ~$25–36. The 8.9x deal multiple sits within this range and is consistent with historical gaming operator M&A. Not an outlier.

**Conclusion:**
$31.00 represents fair value relative to operator precedents. However, the DCF bull case and Macquarie's post-announcement target of $34 suggest a competing strategic bidder could justify a modestly higher price — particularly given Digital EBITDA growing 102% YoY, which pure trading comp analysis understates.

---

## Modeling assumptions & limitations

- WACC (8.5%) is estimated using a simplified CAPM approach; a formal WACC would require a regression beta and more precise capital structure inputs
- Revenue projections (4–5% growth) are the author's estimates based on management commentary, backlog, and Digital ramp; not official guidance
- Net debt ($11.0B) uses FY2025 year-end figures; actual closing net debt will differ
- Tax rate (22%) reflects CZR's effective rate with NOL utilization; could change post-acquisition depending on Fertitta's structure
- Shares outstanding (~185M) is an estimate post-buyback program; exact diluted count requires proxy filing

---

## Skills demonstrated

- Full DCF modeling (unlevered FCF, terminal value, EV bridge, share price)
- WACC × TGR sensitivity analysis with conditional formatting
- Trading comparable analysis (peer selection, multiple application, implied valuation)
- Precedent transaction analysis (deal sourcing, operator vs. RE deal segmentation)
- Football field valuation summary
- Live deal analysis during active M&A process (go-shop context)
- Sell-side board advisory framing

---

## Data sources

- Caesars Entertainment 8-K, Full Year 2025 Results (Feb 17, 2026) — SEC EDGAR
- Fertitta-Caesars definitive agreement press release (May 28, 2026) — BusinessWire
- MGM Resorts 8-K, Full Year 2025 (Feb 5, 2026) — SEC EDGAR
- Wynn Resorts 8-K, Full Year 2025 (Feb 4, 2026) — SEC EDGAR
- Boyd Gaming 8-K, Full Year 2025 (Feb 5, 2026) — SEC EDGAR
- PENN Entertainment 8-K, Full Year 2025 (Feb 26, 2026) — SEC EDGAR
- InsideArbitrage — deal metrics and EV/EBITDA calculation
- StockAnalysis.com — peer EV/EBITDA cross-reference

---

## Other projects in this portfolio

| Project | Description |
|---------|-------------|
| [M&A Model — CloudCore / DataStream](github.com/jiquiros/ma-financial-model) | EPS accretion/dilution model; SaaS acquisition; fictional case calibrated to real benchmarks |
| [LBO Model — Haynes International](https://github.com/jiquiros/LBO-Model-Haynes-International-Inc.-NASDAQ-HAYN-) | Full LBO using real HAYN public data; compared vs. actual Acerinox acquisition at $970M |
| IPO Analysis | *Coming soon* |

---

*Connect on [LinkedIn](www.linkedin.com/in/jose-isaac-quiros-b348a7217) for questions or feedback.*

*This model is for educational and portfolio purposes only. Not investment advice. All data is from publicly available sources.*
