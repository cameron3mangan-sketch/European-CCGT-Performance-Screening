# European-CCGT-Performance-Screening
CCGT Performance Model (HA-Class Ambient Sensitivity)
Overview

This project is a first-order model exploring how ambient conditions influence combined cycle performance, using an HA-class gas turbine reference aligned with modern GE Vernova technology.

The model applies ISO 2314 baselining to isolate the impact of:

Temperature
Altitude
Humidity

It is designed to reflect the type of performance thinking used in high-efficiency plants such as Bouchain, where small changes in gas turbine behaviour drive meaningful plant-level outcomes.

Engineering Approach
Gas Turbine (HA-Class Reference)
Power scaled with inlet air density (mass flow driven)
Temperature penalty applied to reflect increased compressor work
ISO efficiency used as a baseline reference

This captures the core sensitivity of advanced gas turbines to ambient conditions.

Combined Cycle Representation
Exhaust energy linked to steam cycle via HRSG recovery factor
Steam turbine output modelled as a proportional gain

This reflects a key real-world behaviour:

The gas turbine sets the ceiling, the steam cycle amplifies it

Atmospheric Modelling
ISA-based pressure variation with altitude
Moist air density (including humidity effects)

Humidity is included to capture second-order effects often neglected in simple models, but relevant in real operating environments.

Plant Comparison

The model evaluates a consistent HA-class configuration across representative European sites, including:

UK (Peterhead, Keadby 2)
France (Bouchain reference case)
Spain (renewable-influenced dispatch environments)
High-altitude scenario (density-driven performance gain)

All sites use identical hardware assumptions to isolate environmental impact.

Outputs
Gas turbine power (MW)
Combined cycle power (MW)
Efficiency sensitivity (temperature-driven)
Annual energy (MWh/year)
CO₂ emissions (t/year)

Results are ranked and visualised to highlight performance variation across sites.

Key Insight

Cooler, denser air increases compressor mass flow, improving gas turbine output.
This increases available exhaust energy, strengthening steam cycle contribution.

Outcome:
Ambient conditions create a compounding effect across the combined cycle, consistent with real HA-class plant behaviour.

Assumptions & Scope

This is a first-order engineering model intended to demonstrate understanding, not replicate OEM tools.

No compressor maps or firing temperature control
No part-load or dispatch optimisation
Simplified HRSG and steam cycle
Fixed performance sensitivities
Why This Matters

The model reflects a practical understanding of how HA-class gas turbines behave within a combined cycle system, and how site conditions influence real-world performance.

It focuses on clarity over complexity to show the link between:
environment → gas turbine → combined cycle output
