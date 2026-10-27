[← Back to Colombia Module](../README.md) | [← Back to LATAM Modules](../../README.md) | [← Back to Root](../../../../README.md)

# Colombian Electricity Generation System Analysis (SIN) | Energy Transition & Non-Conventional Renewable Energy (FNCER)

This repository presents a structured exploratory data analysis on the evolution, current installed capacity, and expansion dynamics of the generation fleet across Colombia's National Interconnected System (SIN), covering both operational assets and projects currently under construction.

The analysis utilizes official infrastructure datasets (UPME, XM, and SUI) processed via Python notebooks, ensuring full data traceability and timestamped extraction logs to evaluate the technological and spatial transformations within the national power matrix.

---

## 1. Generation System Analysis in Colombia

The spatial distribution of the SIN reflects a distinct geographic divide: hydroelectric power sustains base-load supply across the Andean inland, whereas solar photovoltaic developments and thermal backup infrastructure form a high-density cluster along the Caribbean Coast. This spatial configuration highlights the onset of a decentralized energy transition expanding beyond the traditional Andean axis.

### Historical Matrix Evolution & Net Effective Capacity

The SIN has surpassed **25,109 MW of Net Effective Capacity**. Historically anchored by hydroelectric power and thermal backup, the fleet now exhibits accelerating technological diversification.

* **Decadal Expansion Trends:** For over five decades, Colombia’s power matrix maintained steady growth dominated almost exclusively by large hydroelectric reservoirs and thermal power plants. However, starting this decade, the rapid entry of non-conventional renewable energy (FNCER) technologies has begun shifting the cumulative expansion profile.
* **Annual Commissioning Velocity:** Between 1900 and 2020, asset additions occurred discretely and spaced out over time. Since 2021, the annual volume of operational plant additions has grown exponentially, setting a historic record in absolute commissioning events during the recent period.
* **Capacity Additions Volatility:** Despite the high volume of recent additions, net annual capacity additions exhibit significant year-over-year variations. The capacity peak reached in 2022 represents the highest single inflection point for large-scale infrastructure additions in the country's recent history.
* **Technology Shift in Recent Triennium:** While previous expansion cycles (1980–2015) relied on alternating cycles between large-reservoir hydro and gas/coal thermal units, project entries over the recent triennium are heavily dominated by solar photovoltaic technology.
* **Fleet Fragmentation & Grid Operations:** There is a clear structural trend toward generation fleet fragmentation. While the 20th century was defined by individual mega-projects delivering hundreds or thousands of megawatts, new developments consist primarily of small and medium-scale solar farms and self-generation facilities (averaging under 20–50 MW). This introduces novel operational challenges for the National Dispatch Center (CND) regarding dispatch control, system inertia, and frequency regulation.
* **Geographic Breakdown of Capacity:** Antioquia, Cundinamarca, and Atlántico concentrate nearly 50% of the country’s Net Effective Capacity. Antioquia retains its historical leadership due
