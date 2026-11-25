# Data Dictionary — WattAnalysis China Energy Open Data (November 2026 snapshot)

Derived from `api/index.json` (generated 2026-11-22). Every entry below is a fact recorded in that index; nothing has been added.

## Monthly statistical series (39)

| File key | Series | Unit | Caliber | Coverage | Observations |
|---|---|---|---|---|---|
| `总盘-08` | Solar generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-solar` | Installed capacity · Solar (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-03 – 2026-09 | 67 |
| `gen-solar` | Generation · Solar (NEA briefings) | TWh | National Energy Administration — full-caliber statistics | 2020-03 – 2026-09 | 26 |
| `exp-cells` | Solar cell exports | m units | General Administration of Customs — full-coverage trade statistics | 2021-08 – 2026-08 | 20 |
| `exp-cells-val` | Solar cell exports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2021-08 – 2026-08 | 20 |
| `总盘-09` | Wind generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-wind` | Installed capacity · Wind (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `gen-wind` | Generation · Wind (NEA briefings) | TWh | National Energy Administration — full-caliber statistics | 2020-03 – 2026-09 | 26 |
| `总盘-10` | Hydro generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-hydro` | Installed capacity · Hydro (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `gen-hydro` | Generation · Hydro (NEA briefings) | TWh | National Energy Administration — full-caliber statistics | 2020-03 – 2026-09 | 23 |
| `总盘-12` | Nuclear generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-nuclear` | Installed capacity · Nuclear (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `总盘-11` | Thermal generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-thermal` | Installed capacity · Thermal (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `nea-hours` | Utilisation hours · All plant (NEA) | hours | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `煤炭-01` | Raw coal output | Mt | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `imp-coal` | Coal & lignite imports | Mt | General Administration of Customs — full-coverage trade statistics | 2020-02 – 2026-09 | 74 |
| `imp-coal-val` | Coal & lignite imports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2022-03 – 2026-07 | 22 |
| `exp-coke` | Coke exports | Mt | General Administration of Customs — full-coverage trade statistics | 2021-08 – 2026-08 | 21 |
| `exp-coke-val` | Coke exports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2021-09 – 2026-08 | 16 |
| `油气-01` | Crude oil output | Mt | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `油气-02` | Crude oil throughput | Mt | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `油气-11` | Natural gas output | bcm | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `imp-crude` | Crude oil imports | Mt | General Administration of Customs — full-coverage trade statistics | 2020-02 – 2026-09 | 74 |
| `imp-crude-val` | Crude oil imports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2022-03 – 2026-07 | 22 |
| `imp-gas` | Natural gas imports | Mt | General Administration of Customs — full-coverage trade statistics | 2020-02 – 2026-09 | 74 |
| `imp-gas-val` | Natural gas imports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2022-03 – 2026-07 | 22 |
| `imp-lng` | LNG imports | Mt | General Administration of Customs — full-coverage trade statistics | 2020-09 – 2026-02 | 59 |
| `imp-lng-val` | LNG imports · Value | USD m | General Administration of Customs — full-coverage trade statistics | 2020-09 – 2025-12 | 41 |
| `nea-inv-grid` | Investment · Grid (NEA) | CNY 100m | National Energy Administration — full-caliber statistics | 2020-02 – 2025-11 | 64 |
| `nea-inv-power` | Investment · Power supply (NEA) | CNY 100m | National Energy Administration — full-caliber statistics | 2020-02 – 2025-11 | 64 |
| `总盘-07` | Total generation | TWh | National Bureau of Statistics — above-designated-size industry | 2020-02 – 2026-09 | 74 |
| `nea-cap-total` | Installed capacity · Total (NEA) | GW | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 73 |
| `nea-use-total` | Electricity use · Total (NEA) | TWh | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 74 |
| `nea-use-pri` | Electricity use · Primary industry (NEA) | TWh | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 74 |
| `nea-use-sec` | Electricity use · Secondary industry (NEA) | TWh | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 74 |
| `nea-use-ter` | Electricity use · Tertiary industry (NEA) | TWh | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 74 |
| `nea-use-res` | Electricity use · Households (NEA) | TWh | National Energy Administration — full-caliber statistics | 2020-02 – 2026-09 | 74 |

Each series is published as `api/<key>.json` and `api/<key>.csv`, and on the live API at `https://wattanalysis.com/data/api/<key>.json` / `.csv`.

## Price series (11)

| Series ID | Title | Family | Source tier | Credibility grade | Points |
|---|---|---|---|---|---|
| WA-PRC-19 | PV full-chain cost curve (model) | PRC-COST | WA-CALC | C | 46 |
| WA-PRC-20 | Storage system cost & LCOE model | PRC-COST | WA-CALC | C | 28 |
| WA-PRC-21 | Green hydrogen LCOH model series | PRC-COST | WA-CALC | C | 19 |
| WA-PRC-28 | Battery-grade lithium carbonate spot price — daily cross-source composite | PRC-MKT | 商业评估（多源变换） | C | 5 |
| WA-PRC-29 | Energy storage cell (280Ah) price — weekly cross-source composite | PRC-MKT | 商业评估（多源变换） | C | 7 |
| WA-PRC-30 | Li-ion battery export unit-value index — world (published-table basis, USD) | PRC-CUS | T1（量额） | B | 24 |
| WA-PRC-31 | Li-ion battery export unit-value index — world (published-table basis, CNY) | PRC-CUS | T1（量额） | B | 26 |
| WA-PRC-32 | Li-ion battery export unit-value index — world (query-channel aggregate, USD) | PRC-CUS | T1（量额） | B | 7 |
| WA-PRC-33 | Li-ion battery export unit-value index — world (query-channel aggregate, CNY) | PRC-CUS | T1（量额） | B | 7 |
| WA-PRC-34 | Tender Candidate Quote Reference Index — EPC scope (TCQ-EPC) | PRC-TND | T1（输入） | B | 1 |
| WA-PRC-35 | Tender Candidate Quote Reference Index — system-supply scope (TCQ-SYS) | PRC-TND | T1（输入） | B | 0 |

Files: `api/price-<series-id-lowercase>.json` / `.csv`.

## Tender aggregate series (4)

| Series ID | Title | Family | Source tier | Credibility grade | Points |
|---|---|---|---|---|---|
| WA-PRC-05 | Storage system tender average price — candidate basis | PRC-TND | T1（输入） | B | 0 |
| WA-PRC-06 | Storage EPC tender average price — candidate basis | PRC-TND | T1（输入） | B | 0 |
| WA-PRC-34 | Tender Candidate Quote Reference Index — EPC scope (TCQ-EPC) | PRC-TND | T1（输入） | B | 1 |
| WA-PRC-35 | Tender Candidate Quote Reference Index — system-supply scope (TCQ-SYS) | PRC-TND | T1（输入） | B | 0 |

Files: `api/tender-agg-<series-id-lowercase>.json` / `.csv`.

## Policy collections

| Collection | Records | Files |
|---|---|---|
| policy-documents | 63 | `api/policy-documents.json`, `api/policy-documents.csv` |
| policy-measures | 59 | `api/policy-measures.json`, `api/policy-measures.csv` |
| policy-status-history | 49 | `api/policy-status-history.json`, `api/policy-status-history.csv` |
| policy-standards | 7 | `api/policy-standards.json`, `api/policy-standards.csv` |

Individual records: 63 policy documents (`api/policy-document-*.json`) and 59 policy measures (`api/policy-measure-*.json`).

## Notes from the index

Wave-3 public layer: price, tender and policy single-series endpoints under the same licence split as the statistical layer — single series are public; bulk datasets remain API-key licensed. Internal assessment layers, single-source point registers and D-grade (withheld) series are never published. UVI endpoints (WA-PRC-30..33) passed the pre-release FX residual check on 2026-11-22 (QC #97; see their release_gate field).
