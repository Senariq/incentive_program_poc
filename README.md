# Multi-KPI Incentive Program Pitch

An interactive, browser-based presentation concept for pitching a multi-KPI incentive program. The story is designed to move from understanding the client's context to turning evidence into decisions and measurable outcomes.

## View the presentation

Open [`index.html`](./index.html) directly in a modern browser. It is self-contained and does not require a build step or external assets.

- Use the section navigation, **Previous / Next**, or the left and right arrow keys to move through the presentation.
- Use **Present** or press **F** to enter full-screen mode.
- Explore the synthetic KPI summary by selecting a sample region; the learning lenses and insight-to-outcome steps are also interactive.
- Use the browser's print dialog to print or save a PDF.

The deck includes a cover followed by seven sections: What We Understand, What We See, What We Believe Is Possible, How Decision Sciences Can Help, What the Client Could Learn, How We Turn Insights Into Outcomes, and Where We Go From Here.

## Project files

| File | Purpose |
| --- | --- |
| [`index.html`](./index.html) | Self-contained interactive pitch presentation. |
| [`kpi_presentation.md`](./kpi_presentation.md) | Living requirements brief, narrative plan, assumptions, and open questions. |
| [`sample_location_performance_data.csv`](./sample_location_performance_data.csv) | 1,000 synthetic location snapshots used for the presentation's illustrative KPI summary. |
| [`Generic_POC_Performance_Data_Dictionary/POC Dictionary-Table 1.csv`](./Generic_POC_Performance_Data_Dictionary/POC%20Dictionary-Table%201.csv) | Client-facing definitions for the sample data columns. |
| [`Generic_POC_Performance_Data_Dictionary/Internal Mapping-Table 1.csv`](./Generic_POC_Performance_Data_Dictionary/Internal%20Mapping-Table%201.csv) | Internal-only source-to-generic field mapping; do not share externally. |

## Sample data and interpretation

The sample CSV contains fictional locations for the October 2026 reporting month. The presentation summarizes KPI pass rates across the sample's eight fictional sales regions. Some rule thresholds are not specified in the data dictionary, so the sample uses provisional assumptions documented in [`kpi_presentation.md`](./kpi_presentation.md).

The sample is for development and demonstration only. It is not client data and cannot establish client performance, participant adoption, causal impact, or ROI. Validate KPI definitions, thresholds, and all external claims before using them in a client presentation.
