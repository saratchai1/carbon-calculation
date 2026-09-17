# Carbon Calculation

Editable field-based mangrove carbon stock workbook.

## Current field inputs

- Small-tree circumference: **7.0 cm**
- Large-tree circumference: **10.5 cm**
- Planting spacing: **1.5 m × 1.5 m**
- Implied planting density: about **711 trees/rai**
- Default size mix: **50% small / 50% large** (editable)
- Default land area in the workbook: **1 rai** (editable by measured m²)

## Workbook

`mangrove_carbon_stock_calculator.xlsx`

Sheets:

- **Dashboard** — summary KPIs and size-mix sensitivity
- **Inputs** — yellow editable cells for area, spacing, survival, size mix, wood density, carbon fraction, POM/species confirmation, manual stock override, and ex-ante reference
- **Calculation** — transparent tree-level AGB/BGB/carbon formulas and per-rai aggregation
- **Sources** — links to the project Carbon Credit LLM Wiki

## Important interpretation

This workbook currently reports a **SCREENING_ESTIMATE**, not verified or certified credits. The measured circumferences imply diameters of about **2.23 cm** and **3.34 cm**, both below the 4.5 cm DBH threshold documented for the Standard T-VER Group 2 tree workflow. Species, approved wood density, correct measurement point (including Rhizophora POM where applicable), and equation applicability must be confirmed before using the result as a project-grade monitoring value.

The workbook also shows the registered **9.4 tCO2e/rai/year** ex-ante increment as a separate reference; this is not the same quantity as the current measured carbon stock.

## Canonical methodology context

See the project wiki: https://github.com/saratchai1/carbon-credit-wiki-llm
