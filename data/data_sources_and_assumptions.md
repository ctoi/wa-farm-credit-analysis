# Data Sources and Assumptions
## WA Broadacre Farm Debt Serviceability Analysis - Mallet Ridge Pastoral Co.

All data used in this analysis is publicly available. Every input is recorded 
below with its source, URL where applicable, date accessed, and how it was used 
in the model. Inputs are tiered by data quality.

**Tier 1** - Primary government source. Directly cited, current, unambiguous.  
**Tier 2** - Credible industry or trade source. Cited with caveats on specificity.  
**Tier 3** - Informed estimate. Grounded in observable market logic. Explicitly labelled.  
**Tier 4** - Illustrative assumption. No external basis claimed.

---

## Primary Model Data

### 1. ABARES Farm Data Portal - WA Cropping Benchmark
- **Tier:** 1
- **Publisher:** Australian Bureau of Agricultural and Resource Economics 
  and Sciences (ABARES), Department of Agriculture, Fisheries and Forestry
- **URL:** https://www.agriculture.gov.au/abares/research-topics/surveys/farm-survey-data
- **Date accessed:** 20 April 2026
- **Reference period:** Financial years ending June 2018 to June 2024
- **Data used:**
  - Total cash receipts per farm
  - Total cash costs per farm
  - Farm cash income per farm
  - Farm business profit per farm
  - Fertiliser cost per farm
  - Fuel oil and grease per farm
  - Interest paid per farm
  - Total area cropped (ha)
  - Wheat area sown (ha)
  - Canola area sown (ha)
- **Filters applied:** Industry = Cropping, Region = Western Australia
- **Note:** Financial variables expressed in real 2024-25 dollars. 
  Data for 2024 and later years are ABARES forecasts, not survey actuals. 
  This analysis uses 2023-24 (year ending June 2024) as the base year - 
  the most recent actual survey data available.

---

### 2. ABARES Financial Performance of Broadacre Farms 2022-23 to 2024-25
- **Tier:** 1
- **Authors:** Vernon Topp, Jay Ryder, Joshua Smith
- **Publisher:** ABARES, July 2025
- **DOI:** https://doi.org/10.25814/eezs-zw23
- **Data used:**
  - National cropping farm cash income 2023-24: $456,200 per farm
  - Farm business profit decline context 2023-24
  - WA regional performance commentary - below average rainfall impact
- **Citation:** Topp V, Ryder J and Smith J 2025, *Financial performance of 
  broadacre farms, 2022-23 to 2024-25*, ABARES, Canberra, July 2025

---

### 3. ABARES Agricultural Commodities Report - March Quarter 2026
- **Tier:** 1
- **Publisher:** ABARES, March 2026
- **DOI:** https://doi.org/10.25814/98pm-3f48
- **Data used:**
  - Gross value of agricultural production 2025-26: $101.4 billion (forecast)
  - GVP forecast decline 2026-27: -6% to $95.0 billion
  - Wheat GVP forecast 2026-27: down 13% to $9.5 billion
  - Revenue outlook commentary - global oversupply constraining grain prices
- **Citation:** ABARES 2026, *Agricultural Commodities Report: March Quarter 
  2026*, ABARES, Canberra, March 2026

---

### 4. ABARES Weekly Australian Climate, Water and Agricultural Update No. 19/2026
- **Tier:** 1
- **Publisher:** ABARES, 21 May 2026
- **DOI:** https://doi.org/10.25814/5f3e04e7d2503
- **Data used:**
  - APW wheat price: $403/t FOB Port Adelaide (week ending 20 May 2026)
  - Canola price: $808/t FOB Kwinana WA (week ending 20 May 2026)
  - AUD/USD exchange rate: 0.71 (20 May 2026)
  - WA seasonal conditions: dry, soil moisture declining in cropping regions
  - Global wheat production conditions: broadly favourable, 
    upward revision to USDA estimates
- **Citation:** ABARES 2026, *Weekly Australian Climate, Water and Agricultural 
  Update No. 19/2026*, ABARES, Canberra, 21 May 2026

---

## Lending Rate Data

### 5. Reserve Bank of Australia - Statistical Table F7 Business Lending Rates
- **Tier:** 1
- **Publisher:** Reserve Bank of Australia
- **URL:** https://www.rba.gov.au/statistics/interest-rates/
- **Publication date:** 13 May 2026
- **Data used:**
  - Series FLRBFNSBT: New loans funded in the month, Small business, Total
  - March 2026 value: **7.01% per annum**
- **Use in model:** Base case interest rate for $1.5M facility pricing
- **Note:** Agricultural lending rates may differ from the small business 
  indicator rate. This rate is used as a publicly verifiable proxy. 
  Actual farm lending rates are commercially negotiated and not publicly published.

---

## Land Valuation Data

### 6. RaboResearch - Australian Farmland Price Outlook 2026
- **Tier:** 2
- **Author:** Paul Joules, Commodities Analyst, RaboResearch Australia 
  and New Zealand
- **Publisher:** Rabobank
- **Publication date:** April 2026
- **Based on information as at:** 28 April 2026
- **Data used:**
  - WA arable (cropping) land state median 2025: **$6,330/ha** (+4% YOY)
  - WA grazing land state median 2025: **$18,600/ha** (+7% YOY)
  - WA sub-regional breakdown by rainfall band 
  - Five-year cumulative WA land value growth: ~140%
  - 2026 base case land price forecast: +2% YOY
  - Downside scenario: -2% YOY if soil moisture fails and input costs remain high
  - Fertiliser market: ~30% of global urea supply through Strait of Hormuz
  - Fertiliser prices expected elevated for at least six months
  - RBA forecast: two 25bp rate hikes in May and August 2026
- **Analytical adjustment:** The $6,330/ha state median was adjusted downward 
  to **$4,800/ha** for Mallet Ridge's Merredin location. Merredin sits in the 
  300-400mm annual rainfall band - the lowest rainfall zone in the WA dataset - 
  which the report's sub-regional chart shows trades at a material 
  discount to the state median. The $4,800/ha figure is consistent with 
  independent market commentary showing Central Wheatbelt land at $5,000-$8,000/ha 
  and Eastern Wheatbelt at $1,125-$1,600/ha (Grain Central, May 2023), 
  with Merredin at 314mm sitting between these two zones.
- **Citation:** Joules P 2026, *Australian Farmland Price Outlook 2026*, 
  RaboResearch Food and Agribusiness, Rabobank Australia, April 2026

---

## Current Market Context

### 7. Rabobank Agribusiness Monthly - May 2026
- **Tier:** 2
- **Publisher:** Rabobank
- **Data used:**
  - Iran conflict and Strait of Hormuz - impact on global fertiliser supply
  - Middle East urea spot prices: +8% month-on-month April 2026
  - Morocco DAP phosphate prices: +20% month-on-month April 2026
  - Strait of Hormuz traffic: below 10% of pre-war levels
  - Australia urea supply agreement with Indonesia: 250,000 tonnes secured
  - RBA cash rate: current 4.35%, forecast 4.60% after August 2026 hike
  - AUD/USD: ~0.71, forecast 0.72 over next 12 months
  - Australian CPI March 2026: 4.6% YOY
- **Use in model:** Justification for Scenario 2 fertiliser cost shock 
  and current market context in credit memo

---

## Location and Climate Data

### 8. Bureau of Meteorology - Merredin Climate Station
- **Tier:** 1
- **Publisher:** Australian Bureau of Meteorology
- **URL:** https://www.bom.gov.au/climate/averages/tables/cw_010093.shtml
- **Data used:** Merredin average annual rainfall: 314mm

---

## Machinery Pricing

### 9. John Deere X9 1100 Combine Harvester - Dealer Indicative Pricing
- **Tier:** 3
- **Data used:** New 2025-26 model with 50ft draper header and precision 
  guidance: indicative AUD $1,200,000
- **Source type:** Industry knowledge and dealer indicative pricing. 
  Not from a single citable URL.
- **Label in model:** Indicative dealer pricing - 2025-26 model year

### 10. Case IH Early Riser 2160 Precision Planter - Dealer Indicative Pricing
- **Tier:** 3
- **Data used:** Flagship broadacre configuration with high-capacity 
  air cart: indicative AUD $500,000
- **Source type:** Industry knowledge and dealer indicative pricing
- **Label in model:** Indicative dealer pricing - current model year

---

## Supporting Market References

### 11. Grain Central - WA Land Market Commentary
- **Tier:** 2
- **Article:** "Hot WA market shows switch to year-round transactions"
- **Date:** May 2023
- **URL:** https://www.graincentral.com/property/hot-wa-market-shows-switch-to-year-round-transactions/
- **Data used:** Central Wheatbelt (350-450mm) $5,000-$8,000/ha; 
  Eastern Wheatbelt (300-340mm) $1,125-$1,600/ha - used to triangulate 
  Merredin zone land value estimate

### 12. DPIRD WA - Wheat Western Australia
- **Tier:** 1
- **Publisher:** Department of Primary Industries and Regional Development, WA
- **URL:** https://www.dpird.wa.gov.au/businesses/plant-and-crop-farming/grains/wheat/
- **Date accessed:** 26 May 2026
- **Data used:** WA wheat production on 4,000 mostly family-run farms, 
  1,000-15,000 hectares; WA generates ~40% of Australia's total wheat 
  production, >95% exported

### 13. Shire of Merredin
- **Tier:** 1
- **URL:** https://www.merredin.wa.gov.au/community/about-merredin/about-merredin.aspx
- **Data used:** Average annual rainfall 314mm confirmed

---

## Key Assumptions - Explicitly Stated

| Assumption | Value | Basis | Tier |
|---|---|---|---|
| Loan term | 7 years | Standard machinery finance term in Australian agribusiness lending | 4 |
| Amortisation method | Straight-line | Conservative - Year 1 debt service is the highest point | 4 |
| Minimum acceptable DSCR | 1.25x | Standard agribusiness lending covenant threshold | 4 |
| Trade-in credit | $200,000 | 2014 John Deere combine + existing seeding bar - dealer estimate | 3 |
| Profit-to-income ratio | 29.7% | Derived from ABARES 2023-24 WA Cropping data: $290,580 ÷ $978,440 | 1 |
| Other costs (residual) | $1,932,640 | Total costs minus fertiliser, fuel, interest - held constant in scenarios | 1 |
| Merredin land value | $4,800/ha arable | RaboResearch 2026 state median adjusted for 300-400mm rainfall zone | 2 |

---

## Scenario Justification

| Scenario | Magnitude | Historical anchor | Current anchor |
|---|---|---|---|
| Revenue decline −30% | Conservative | Receipts fell 35% from 2022-23 to 2023-24 (ABARES) | ABARES March 2026 forecasts wheat GVP down 13% in 2026-27; WA dry conditions documented May 2026 |
| Fertiliser +40% | Conservative | Fertiliser rose 84% from 2020-21 to 2021-22 (ABARES) | Rabobank May 2026 documents ongoing price escalation from Strait of Hormuz disruption |
| Combined −20% revenue, +30% fertiliser | Moderate | Simultaneous pressure observed historically | Consistent with ABARES 2026-27 outlook - lower prices and higher costs occurring together |

---

*This document was prepared as part of an independent portfolio project 
demonstrating commercial analytical skills. All data sources are publicly 
available. Mallet Ridge Pastoral Co. is a fictional entity.*

*Prepared: May 2026*
