# WA Broadacre Farm Debt Serviceability Analysis
## Credit Assessment - Mallet Ridge Pastoral Co. | $1.5M Machinery Facility | May 2026

> **Disclaimer:** Mallet Ridge Pastoral Co. is a fictional entity created for
illustrative purposes. All financial inputs are derived from publicly available
ABARES benchmark data. This analysis does not constitute financial or
investment advice.

---

## Research Question

Under current market conditions, can a representative Western Australian broadacre
cropping operation service a $1.5 million term loan facility for machinery
replacement - and under what revenue and input cost conditions does debt
serviceability break down?

---

## Project Purpose

This project models the debt serviceability of a representative WA broadacre
cropping operation against a proposed $1.5M term loan using ABARES farm survey
benchmark data. It is structured as a preliminary credit assessment for an
agribusiness lending institution, demonstrating:

- Cost structure and margin analysis using publicly available government benchmark data
- Debt Service Coverage Ratio (DSCR) calculation under base case and stress scenarios
- Sensitivity analysis across combined revenue and input cost movements
- Written credit memorandum for a defined commercial audience

---

## Key Findings

- **Base case DSCR: 3.06x** (cash income basis) - serviceable at current conditions
- **Conservative DSCR: 0.91x** (farm business profit basis) - already below the
  1.25x minimum threshold before any stress is applied
- **A 30% revenue decline** - consistent with the 35% fall observed in 2023–24
  and supported by ABARES March 2026 forecasts - renders farm cash income
  negative and debt unserviceable.
- **Recommendation: Conditional approval** with protective covenants including 
  forward grain sales requirements and annual DSCR testing

---

## The Farm - Mallet Ridge Pastoral Co.

A fictional representative WA broadacre cropping operation located in the 
**Shire of Merredin, Central Wheatbelt** (314mm average annual rainfall).

| Parameter | Detail |
|---|---|
| Total area | 5,200 ha freehold |
| Cropping area | 4,200 ha - wheat, barley, canola, lupins |
| Livestock | 600 ha - 3,200 Merino ewes |
| Grain marketing | CBH Merredin receival / Kwinana terminal |
| Land value estimate | AUD $4,800/ha arable (Rabobank 2026, adjusted for rainfall zone) |
| Ownership | Multigenerational family - 46 years in operation |
| Facility purpose | John Deere X9 1100 harvester + Case IH Early Riser 2160 planter |

---

## The Facility

| Item | Amount |
|---|---|
| John Deere X9 1100 combine harvester + 50ft header | $1,200,000 |
| Case IH Early Riser 2160 precision planter + air cart | $500,000 |
| Gross capital outlay | $1,700,000 |
| Less: trade-in credit (2014 combine + existing seeder) | ($200,000) |
| **Net facility required** | **$1,500,000** |

---

## Stress Scenarios

| Scenario | Variable | Change | DSCR | Verdict |
|---|---|---|---|---|
| Base case | - | - | 3.06x | Conditional approval |
| Scenario 1 - Revenue decline | Total receipts | −30% | Negative | Decline |
| Scenario 2 - Fertiliser spike | Fertiliser cost | +40% | 2.08x | Conditional approval |
| Scenario 3 - Combined shock | Revenue −20%, Fertiliser +30% | Combined | Negative | Decline |

---

## Data Sources

| Source | Data Used | Date |
|---|---|---|
| ABARES Farm Data Portal | Farm financials - WA Cropping 2017-18 to 2023-24 | Accessed May 2026 |
| ABARES Agricultural Commodities Report | Wheat GVP outlook, revenue forecasts 2026-27 | March 2026 |
| ABARES Weekly Update No.19/2026 | APW wheat $403/t, canola $808/t, AUD/USD 0.71, WA seasonal conditions | 21 May 2026 |
| ABARES Financial Performance Report | National cropping farm benchmarks | July 2025 |
| RBA Table F7 | New small business lending rate: 7.01% p.a. | March 2026 |
| RaboResearch Farmland Outlook 2026 | WA arable land AUD $6,330/ha state median - adjusted to AUD $4,800/ha for Merredin zone | April 2026 |
| Rabobank Agribusiness Outlook May 2026 | Fertiliser market - Strait of Hormuz impact, urea escalation | May 2026 |
| Bureau of Meteorology | Merredin average annual rainfall 314mm | Historical |

---

## Repository Structure

```
wa-farm-credit-analysis/
├── /data
│   └── data_sources_and_assumptions.md  
├── /memo
│   └── WA_Farm_Debt_Serviceability_Analysis.xlsx
├── /memo
│    └── WA_Credit_Memo.pdf
└── README.md
```

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Financial model - cost build, DSCR calculation, scenario analysis, sensitivity table |
| Microsoft Word → PDF | Credit memorandum |
| GitHub | Version control and portfolio publishing |

---

## Methodology Note

This model uses ABARES benchmark averages for WA cropping farms as a proxy
for Mallet Ridge's financial profile. Individual farm results will vary. A lender
applying this framework to a specific borrower would supplement these benchmarks
with actual farm financial statements. The conservative DSCR using farm business
profit (0.91x at base case) highlights that benchmark-level analysis may overstate
true debt serviceability - a limitation explicitly acknowledged in the credit
memorandum.

---

## Author

**Shin Tran** | University of Western Australia (2026)  | Perth, Western Australia
