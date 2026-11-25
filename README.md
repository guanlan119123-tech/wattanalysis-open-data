# WattAnalysis China Energy Open Data — Public Layer Snapshot (November 2026)

A snapshot of the free public layer of the WattAnalysis China Energy Data
programme: 235 single-series files (CSV + JSON), also published as an open API
at https://wattanalysis.com/data/api/ and archived on Zenodo so the November
2026 state of the data can be cited permanently.

[![mcptry](https://mcptry.com/badge/com.wattanalysis/wattanalysis-data)](https://mcptry.com/servers/com.wattanalysis/wattanalysis-data)

- Live data (updated monthly): https://wattanalysis.com/data/
- Frozen archive of this snapshot: https://zenodo.org/records/24519660

## What is inside

Six databases, one public layer:

- **Industry statistics** — NEA capacity and generation series by source
  (solar, wind, hydro, nuclear, thermal, total), utilisation hours, grid and
  power investment, electricity consumption by sector (`nea-*`, `gen-*`).
- **Trade** — customs quantity and value series for coal, coke, crude, gas,
  LNG and battery cells (`imp-*`, `exp-*`).
- **Policy documents** — the rules layer: 63 policy documents and 59 measures
  recorded from the issuing ministries' own announcements, with document
  numbers, effective dates and tracked status (`policy-*`).
- **Prices** — cross-source composite price series for cells, lithium
  carbonate and other tracked items (`price-*`).
- **Tenders** — aggregated storage tender series (`tender-agg-*`).

`api/index.json` is the API index. File names are stable and match the live
API. See [DATA-DICTIONARY.md](DATA-DICTIONARY.md) for the series list, units,
calibers and coverage periods.

## Method and caliber

Every series is recorded verbatim from a primary source (the National Energy
Administration, the General Administration of Customs, issuing ministries and
exchanges). Calibers are never spliced: the NBS above-scale
（规模以上）, NEA full-caliber and Customs full-coverage calibers are kept as
separate series, and where sources conflict, both values are recorded in
parallel. Commercial price data is used internally only; the public layer
carries transformed, multi-source composite series. The full method is
described in the WattAnalysis working paper, "How We Build China Energy Data
You Can Audit" (SSRN abstract 7748142).

## Update cadence

The live API at https://wattanalysis.com/data/ is updated monthly. This
repository holds the frozen November 2026 snapshot; cite the DOI below for
this state, and the site for current values.

## What is WattAnalysis?

WattAnalysis is an independent research publication on China's energy system
and the global supply chains it is reshaping, founded in May 2024 in Shanghai.
Official site: https://wattanalysis.com — newsletter:
https://newsletter.wattanalysis.com. It publishes open data and analysis
built from Chinese primary sources — National Energy Administration, NDRC
and MIIT documents, and tender and project records — with every figure
traceable to the document that printed it.

## Questions this dataset answers

**Q: Where can I download China energy storage tender data?**
A: Aggregated storage tender series are in this repository (`tender-agg-*`).
The record-level tracker — 135 notices, 156 lots and 146 award records
published 20 May to 20 Nov 2026, with prices reproduced exactly as
published — is at https://wattanalysis.com/tenders/. This frozen snapshot is
archived at Zenodo, DOI 10.5281/zenodo.24519660.

**Q: How much new-type energy storage capacity does China have?**
A: 136 GW / 351 GWh cumulative at end-2025, per the National Energy
Administration's 2025 National Power Industry Statistics (released January
2026); 167 GW / 435 GWh at end-Sep 2026. "New-type storage" excludes pumped
hydro. The underlying series are in this repository and at
https://wattanalysis.com/data/storage/.

**Q: Where can I find China's energy policy documents — export controls,
Document 136, tariff schedules?**
A: The `policy-*` files here record 63 policy documents and 59 measures
from the issuing authorities' own publications, with document numbers,
effective dates and tracked status. The readable database is at
https://wattanalysis.com/documents/.

**Q: In what statistical calibers are the series published?**
A: Three calibers, kept separate and never spliced: NBS above-scale
（规模以上）, NEA full-caliber, and Customs full-coverage. Where sources
conflict, both values are recorded in parallel. See DATA-DICTIONARY.md for
each series' caliber and coverage period.

**Q: How current is this data, and where is the live version?**
A: This repository is the frozen November 2026 snapshot. The live API at
https://wattanalysis.com/data/ is updated monthly.

**Q: How do I cite this dataset?**
A: See the citation block below — cite the Zenodo DOI for this frozen
state, and the WattAnalysis data pages for current values.

**Q: Can I use the data commercially?**
A: The snapshot is CC BY-NC 4.0: free for research and citation with
attribution. Commercial use follows https://wattanalysis.com/terms/.

## Licence and citation

The canonical terms for this data live at https://wattanalysis.com/terms/.
This snapshot is published under CC BY-NC 4.0: free for research and citation
with attribution; commercial use follows the terms page.

Suggested citation:

> WattAnalysis, China Energy Open Data Snapshot (Nov 2026), DOI 10.5281/zenodo.24519660
>
> WattAnalysis, "China Energy Data," https://wattanalysis.com/data/ — built from primary sources, updated monthly.

Contact: contact@wattanalysis.com
