# Delta-Airlines-Financial-Analysis-2019-2023


## Project background

The COVID-19 pandemic caused the most severe disruption in commercial aviation history. Between 2019 and 2020, Delta Air Lines saw revenue fall from $47 billion to $17 billion — a 64% collapse in a single year. This project goes beyond the headline numbers to identify the operational and financial drivers behind both the crash and the subsequent recovery.

Rather than simply tracking revenue over time, this analysis examines the *why*: how fuel costs, load factor, aircraft utilization, workforce size, and revenue mix each contributed to Delta's financial trajectory from 2019 through 2023.

---

## Data Sources

All data sourced from official public filings and government databases:

| Source | Data Retrieved | Link |
|---|---|---|
| SEC EDGAR — Delta 10-K Filings | Annual revenue, costs, operating stats (2019–2023) | [EDGAR](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000027904&type=10-K) |
| SEC EDGAR — Delta 10-Q Filings | Quarterly revenue breakdown, cost line items (Q1–Q3 each year) | [EDGAR](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000027904&type=10-Q) |
| Bullfincher.io | Cross-reference for quarterly revenue (UAL, DAL, AAL, LUV) | [Bullfincher](https://bullfincher.io) |

> **Note:** Q4 figures for each year are derived values — calculated as the full-year annual total (from 10-K) minus the sum of Q1+Q2+Q3 (from 10-Q filings). All derived figures are flagged in the `data_source` column of each dataset.

---

## Dashboard

![Dashboard Overview](Dashboard/dashboard_overview.png)

The dashboard is structured across five analytical sheets:

1. **Industry Comparison** — Revenue and net income across Delta, United, American and Southwest 2019–2023
2. **Cost Per Mile vs. Revenue** — Delta CASM and CASM-ex vs. TRASM, showing when the airline was flying above or below its cost floor
3. **Load Factor Analysis** — Seat utilization over time and its relationship to profitability
4. **Aircraft in Service vs. Operating Costs** — Fleet utilization as a driver of fixed cost absorption
5. **Passengers Carried vs. Cargo Revenue** — How cargo partially offset passenger revenue collapse during COVID

---

## Key Findings

- **Q2 2020 was the floor:** Delta carried only 5.6 million passengers, down from 54 million in Q2 2019 — a 90% collapse in a single quarter
- **Costs don't fall as fast as revenue:** Salaries, depreciation and landing fees remained largely fixed even as revenue evaporated, pushing CASM to 59¢ in Q2 2020 vs. 14.5¢ in Q2 2019
- **Cargo was a quiet cushion:** Cargo revenue held at $98–$142M through the worst COVID quarters while passenger revenue fell 83%, as belly freight demand surged with grounded dedicated freighters
- **Premium recovered faster than main cabin:** By Q3 2022, premium ticket revenue had exceeded 2019 levels while main cabin was still catching up — a structural shift in Delta's revenue mix
- **The fuel shock of 2022 nearly erased the recovery:** Despite revenue returning to 2019 levels by Q2 2022, net income was only $1.3B for the full year as fuel hit $3.74/gallon — up from $2.02 in 2019
- **Load factor as the leading indicator:** Load factor recovery consistently preceded revenue recovery by 1–2 quarters, making it the best early signal of financial improvement

---

## Executive Summary

Between 2019 and 2020, Delta Air Lines saw its total operating revenue fall from $47 billion to $17.1 billion — a 64% collapse driven by the near-total shutdown of commercial air travel during the COVID-19 pandemic. In Q2 2020 alone, passengers carried dropped from 54 million to 5.6 million, and the airline posted an operating loss of $4.8 billion in a single quarter.
This analysis goes beyond the revenue headline to examine the operational and financial drivers behind both the collapse and the four-year recovery that followed. Using raw quarterly data sourced directly from Delta's SEC 10-K and 10-Q filings, this project investigates five core relationships: how Delta's costs compared to competitors during the downturn, how cost-per-mile tracked against revenue-per-mile as capacity was cut and restored, how load factor behaved as a leading indicator of financial recovery, how fleet utilization drove fixed cost absorption, and how cargo revenue partially cushioned the collapse in passenger demand.
Delta Air Lines was selected as the primary subject of this analysis because it consistently files the most detailed operational statistics of any major U.S. carrier, enabling a granularity of analysis not easily replicated with American, United or Southwest data. Industry-level context is provided through a comparative dataset covering all four major U.S. legacy and low-cost carriers across the same period.
Key findings include: operating costs proved largely fixed even as revenue evaporated, pushing cost-per-available-seat-mile to 59 cents in Q2 2020 versus 14.5 cents pre-pandemic; load factor recovery consistently preceded revenue recovery by one to two quarters, making it the strongest early signal of financial improvement; cargo revenue held relatively stable through the worst COVID quarters as belly freight demand surged; and despite revenue returning to 2019 levels by mid-2022, full profitability was delayed by a fuel cost spike to $3.74 per gallon following the Russia-Ukraine war — the single biggest external shock to the recovery timeline.






