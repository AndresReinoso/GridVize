[← Back to LATAM Modules](../README.md) | [← Back to Root](../../../README.md)

# Colombia Power System Intelligence | Sistema Interconectado Nacional (SIN)

Welcome to the Colombia national module for **GridVize**. This directory houses the spatial-temporal analytics, data pipelines, and executive intelligence models for Colombia’s 22+ GW National Interconnected System (SIN).

---

## National System Overview & Key Authorities

* **Target Grid Authorities:** UPME (Unidad de Planeación Minero Energética), XM S.A. E.S.P. (National Dispatch Center - CND), and SUI (Sistema Único de Información).
* **Active System Scale:** 25,100+ MW Net Effective Capacity across hydro, thermal, solar, and wind assets.
* **Core Analytical Focus:** Renewable energy transition (FNCER), regional asset distribution, solar commissioning velocity through 2033, and wholesale market dispatch mechanics.

---

## Operational Pillars & Analytical Chapters

The Colombia module is structured across four core operational pillars:

| Pillar | Chapter Directory | Scope & Focus | Deliverables | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01** | [`/Generation`](./Generation) | Asset mapping, thermal vs. hydro baseload, solar pipeline through 2033. | Interactive Executive Dashboard & Spatial EDA | **Live** |
| **02** | [`/Transmision`](./Transmision) | Regional transmission congestion nodes, tie-lines, and substation capacity. | Network Topology Maps | *In Progress* |
| **03** | [`/Distribucion`](./Distribucion) | Utility operator footprints, energy loss factors, and regional reliability metrics. | Benchmarking BI Cards | *Planned* |
| **04** | [`/Mercado_Energetico`](./Mercado_Energetico) | Spot price volatility ($/kWh), reservoir stress, and dispatch merit order. | Time-Series Quant Models | *Planned* |

---

## Data Pipeline & Domain Integrity

All data processing within this module ingests official public API endpoints from UPME, XM, and SUI using Python (`pandas`, `geopandas`). Technical notebooks retain official regulatory nomenclature (e.g., `capacidad_efectiva_neta_mw`, `tipo_despacho`) to maintain complete data lineage and regulatory accuracy.
