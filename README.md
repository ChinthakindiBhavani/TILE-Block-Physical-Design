# TILE Block – Physical Design Implementation (28nm)

Physical design implementation of a TILE block at 28nm technology node, covering the complete RTL-to-GDSII backend flow using **Synopsys ICC2**.

## Project Overview

- **Technology Node:** 28nm
- **Design Size:** 300K+ standard cells
- **Tool:** Synopsys IC Compiler II (ICC2)
- **Flow:** Floorplanning → Placement → CTS → Routing → Timing Closure

## Key Responsibilities & Achievements

- Performed floorplanning and power planning for the TILE block, defining core area, macro placement, and power grid structure
- Executed placement and optimization to meet timing, congestion, and utilization targets
- Carried out Clock Tree Synthesis (CTS) with useful skew and CCD techniques to balance clock latency
- Performed detailed routing and resolved post-route DRC violations (shorts/opens)
- Closed setup and hold timing violations through ECO flow — buffer/delay cell insertion and spare cell utilization
- Debugged filler cell insertion errors and completed physical verification checks

## Tools & Techniques

- **EDA Tool:** Synopsys ICC2 (Fusion Compiler flow)
- **STA:** report_timing path analysis, setup/hold closure
- **ECO Flow:** Post-route timing fixes via buffer insertion
- **Physical Verification:** DRC/LVS clean-up

## Notes

This repository documents the physical design flow and methodology followed for the TILE block project. Scripts and reports will be added as the project is organized.
