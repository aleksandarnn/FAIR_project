# FAIR_project

Data derived from U.S. EPA Air Quality System (AQS) “AirData” Daily Summary (accessed 2025-09-15).
Original source is a U.S. Government Work (public domain).
This repository’s cleaned dataset, RDF conversion, and metadata are dedicated to the public domain under CC0 1.0.
EPA does not endorse any analysis or conclusions presented here.

- **Data**: `data/daily_42602_2022_sample1000.csv` (sample 1k rows used for demo/testing).
- **Metadata**: DCAT at `metadata/dataset.ttl`; optional catalog at `metadata/catal og.ttl`.
- **Shapes**: SHACL constraints at `shapes/dcat-shapes.ttl`.
- **Diagram**: `docs/metadata-diagram.drawio` (+ PNG export).

## Distributions
- Sample CSV (this repo): `data/daily_42602_2022_sample1000.csv`
- RDF (Turtle): `data/daily_42602_2022.ttl` 
- Full CSV: see EPA AirData page (linked above) — included as a DCAT distribution via `accessURL`.


## Source & License
- **Original data**: U.S. EPA AQS “AirData”, U.S. Government Work (public domain).
- **This repo (cleaned CSV, RDF, SHACL/metadata, docs)**: **CC0 1.0 Public Domain Dedication** — see [LICENSE](./LICENSE).

Please cite as: “U.S. EPA, Air Quality System (AQS), AirData Daily Summary (NO₂, 2022), accessed 01-10-2025; cleaned and republished by <Aleksandar Nikolov & Emils Johansens/ University of Twente>.”
