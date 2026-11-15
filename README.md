# BI WORLDWIDE Interactive Client Pitch

An interactive HTML pitch workflow for BI WORLDWIDE sales and analysts. Use a prospective client's dataset to build a reviewable, evidence-led pitch that connects program performance and participant behavior to decisions and measurable outcomes. The included sample remains synthetic and is not a prospect's data.

The presentation uses the supplied BI WORLDWIDE homepage palette: light surfaces, deep navy, bright orange, and purple accents.

## View the presentation

Open [`index.html`](./index.html) directly in a modern browser to review the self-contained interactive example. It does not require a build step or external assets. The sample values in it are not automatically populated from a client dataset; replace or recompute them from the dataset provided for a prospect-specific pitch.

- Use the section navigation, **Previous / Next**, or the left and right arrow keys to move through the presentation.
- Use **Present** or press **F** to enter full-screen mode.
- Explore the synthetic KPI summary by selecting a sample region; the learning lenses and insight-to-outcome steps are also interactive.
- Use the browser's print dialog to print or save a PDF.

The example includes a cover followed by seven sections: What We Understand, What We See, What We Believe Is Possible, How Decision Sciences Can Help, What the Client Could Learn, How We Turn Insights Into Outcomes, and Where We Go From Here.

## Create a prospect-specific pitch

Use the [`BIW client pitch skill`](./.agents/skills/biw-client-pitch-deck/SKILL.md) with the prospect's dataset. Provide the dataset (for example, a CSV) and its data dictionary when available; if no dataset is provided, the skill asks for one before making data-based claims. Add relevant prospect context or discovery answers if known.

The workflow profiles and analyzes the supplied data, then updates the interactive HTML pitch with supported findings, assumptions, and review questions. The current sample is only a demonstration; it is not automatically replaced or analyzed as prospect data.

The skill follows the open Agent Skills specification and is stored under `.agents/skills/` for VS Code's default discovery. Its instructions are portable across compatible agents; another agent may require the skill directory under its own supported location, such as `.claude/skills/`.

## Project files

| File | Purpose |
| --- | --- |
| [`index.html`](./index.html) | Self-contained interactive pitch template and synthetic example. |
| [`.agents/skills/biw-client-pitch-deck/SKILL.md`](./.agents/skills/biw-client-pitch-deck/SKILL.md) | Portable Agent Skill for analyzing a provided prospect dataset and creating a reviewable interactive HTML pitch. |
| [`.agents/skills/biw-client-pitch-deck/references/sample_location_performance_data.csv`](./.agents/skills/biw-client-pitch-deck/references/sample_location_performance_data.csv) | 1,000 synthetic location snapshots used for the presentation's illustrative KPI summary. |
| [`.agents/skills/biw-client-pitch-deck/references/POC Dictionary-Table 1.csv`](./.agents/skills/biw-client-pitch-deck/references/POC%20Dictionary-Table%201.csv) | Client-facing definitions for the sample data columns. |
| [`references/Internal Mapping-Table 1.csv`](./references/Internal%20Mapping-Table%201.csv) | Internal-only source-to-generic field mapping; do not share externally. |

## Sample data and interpretation

The skill's sample CSV contains fictional locations for the October 2026 reporting month. The presentation summarizes KPI pass rates across the sample's eight fictional sales regions. Some rule thresholds are not specified in the data dictionary, so the sample uses provisional assumptions in the presentation.

The sample is a synthetic location-level sales example for development and demonstration only. It is not participant data or representative of every industry or program, and it cannot establish prospect performance, participant adoption, causal impact, or ROI. Validate KPI definitions, thresholds, fairness guardrails, and all external claims before sharing a prospect-specific pitch.
