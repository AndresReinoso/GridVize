<div align="center">

  <img src="https://raw.githubusercontent.com/AndresReinoso/GridVize/main/Assets/GridVize-2.png" alt="GridVize Logo" width="450" />

  ### Visual Data Intelligence for Global Energy Systems

  Executive Overview | Market Deployment | System Architecture | Tech Stack | Author & Services

</div>

---

## Executive Overview

GridVize is an open-source data engine built to turn raw power grid APIs and complex spatial records into clear, decision-ready market intelligence.

Developed under the Logikoo data engineering umbrella, GridVize provides a standardized, market-agnostic framework for analyzing power generation, transmission constraints, and wholesale spot market dynamics across regional grid operators. By decoupling raw data ingestion from the visualization layer, it converts messy, multi-source government records into real-time executive visibility and quantitative market models.

> Interactive Portal: Access the Live GridVize Looker Studio Dashboard  

---

## Market Deployment & Scalability

GridVize decouples raw data extraction from the analytical reporting layer, enforcing a uniform data schema designed to scale across different regional electricity frameworks:

* Active Implementation (Module 01: LATAM - Colombia SIN): Ingests official UPME, XM, and SUI datasets to model 22+ GW of net installed capacity, solar transition velocity through 2033, and wholesale market dispatch mechanics.
* Engine Architecture: Built using standardized data transformation pipelines (UTC time-series normalization, EPSG spatial reprojection to WGS84, and MW/GWh unit standardization) engineered to adapt seamlessly to other regional grid operators (such as ERCOT or ENTSO-E) using the same core processing engine.

---

## System Architecture (Module 01: LATAM - Colombia SIN)

Inside the active LATAM module, the power system is structured across four core operational pillars:

| Module Pillar | Focus & Analytical Scope | Primary Output | Status |
| :--- | :--- | :--- | :--- |
| 01. Generation & Expansion | Installed capacity breakdown, spatial asset distribution, solar commissioning velocity. | Interactive Executive Dashboard & GeoJSON Maps | Live |
| 02. Transmission System | Regional congestion nodes, substation capacity limits, and grid tie-lines. | Spatial Flow Maps | In Progress |
| 03. Distribution & Reliability | Utility operator footprints, energy loss factors, and regional reliability metrics. | Comparative BI Cards | Planned |
| 04. Wholesale Energy Market | Spot price volatility ($/kWh), hydro reservoir stress, and dispatch merit order. | Time-Series Quant Models | Planned |

---

## Tech Stack & Methodologies

* Data Extraction & Pipeline: Python, Pandas, GeoPandas, Requests, NumPy.
* Geospatial Modeling: MAGNA-SIRGAS (EPSG:9377) reprojected to WGS84 (EPSG:4326).
* Data Warehousing & Visualization: Google BigQuery, Looker Studio.
* Domain Specialization: Smart Grids, Time-Series Energy Analytics, Spot Market Dynamics, Power System Operations.

---

## Author & Commercial Services

Need custom automated ETL pipelines, geospatial modeling, or executive Looker Studio dashboards for your organization?

* Brand: Logikoo Data & BI Solutions
* Lead Engineer: Andres Reinoso (Electrical Engineer, MBA)
