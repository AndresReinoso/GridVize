<div align="center">

  <img src="https://raw.githubusercontent.com/AndresReinoso/GridVize/main/Assets/GridVize-2.png" alt="GridVize Logo" width="450" />

  ### Visual Data Intelligence for Global Energy Systems

  Executive Overview | Market Modules | System Architecture | Tech Stack | Author & Services

</div>

---

## Executive Overview

GridVize is an open-source data engine built to turn raw power grid APIs and complex spatial records into clear, decision-ready market intelligence.

Developed under the Logikoo data engineering umbrella, GridVize provides a standardized, market-agnostic framework for analyzing power generation, transmission constraints, and wholesale spot market dynamics across regional grid operators. By decoupling raw data ingestion from the visualization layer, it converts messy, multi-source government records into real-time executive visibility and quantitative market models.

> **Interactive Portal:** [Access the Live GridVize Looker Studio Dashboard](https://datastudio.google.com/reporting/3fb79ecb-bc6c-4257-b36e-5ea239e293e8/page/p_5xthvz1o8d)

---

## Market Modules & Regional Scope

GridVize standardizes heterogeneous energy datasets into modular regional implementations:

| Market Module | Region / System | Primary Grid Authorities | Capabilities & Status |
| :--- | :--- | :--- | :--- |
| [`Module 01: LATAM - Colombia`](./Market_Modules/LATAM/Colombia) | National Interconnected System (SIN) | UPME / XM / SUI | Live: Asset mapping (22+ GW capacity), solar expansion velocity (2020–2033), dispatch merit order. |

---

## System Architecture (Module 01: LATAM - Colombia SIN)

Inside each regional module, the grid is modeled across four core operational pillars:

| Module Pillar | Focus & Analytical Scope | Primary Output | Status |
| :--- | :--- | :--- | :--- |
| **01** | [`/Generation`](./Market_Modules/LATAM/Colombia/Generation) | Asset mapping, thermal vs. hydro baseload, solar pipeline through 2033. | **Live** |
| **02** | [`/Transmision`](./Market_Modules/LATAM/Colombia/Transmision) | Regional transmission congestion nodes, tie-lines, and substation capacity. | *In Progress* |
| **03** | [`/Distribucion`](./Market_Modules/LATAM/Colombia/Distribucion) | Utility operator footprints, energy loss factors, and regional reliability metrics. | *Planned* |
| **04** | [`/Mercado Energetico`](./Market_Modules/LATAM/Colombia/Mercado_Energetico) | Spot price volatility ($/kWh), reservoir stress, and dispatch merit order. | *Planned* |
---

## Tech Stack & Methodologies

* Data Extraction & Pipeline: Python, Pandas, GeoPandas, Requests, NumPy.
* Geospatial Modeling: MAGNA-SIRGAS (EPSG:9377) reprojected to WGS84 (EPSG:4326).
* Data Warehousing & Visualization: Looker Studio.

---

## Author & Commercial Services

Need custom automated ETL pipelines, geospatial modeling, or executive Looker Studio dashboards for your organization?

* Brand: Logikoo Data & BI Solutions
* Lead Engineer: Andres Reinoso (Electrical Engineer, MBA)
