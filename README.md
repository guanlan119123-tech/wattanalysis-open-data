# WattAnalysis China Energy Open Data — Public Layer Snapshot (November 2026)

A snapshot of the free public layer of the WattAnalysis China Energy Data
programme: 235 single-series files (CSV + JSON), also published as an open API
at https://wattanalysis.com/data/api/ and archived on Zenodo so the November
2026 state of the data can be cited permanently.

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

## Licence and citation

The canonical terms for this data live at https://wattanalysis.com/terms/.
This snapshot is published under CC BY-NC 4.0: free for research and citation
with attribution; commercial use follows the terms page.

Suggested citation:

> WattAnalysis, China Energy Open Data Snapshot (Nov 2026), DOI 10.5281/zenodo.24519660

Contact: contact@wattanalysis.com
