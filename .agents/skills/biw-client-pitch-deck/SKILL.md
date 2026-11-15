---
name: biw-client-pitch-deck
description: If no client dataset is provided, request it; then help BI WORLDWIDE sales and analysts turn it into a reviewable, interactive HTML pitch for a potential client. Use for dataset analysis, evidence-backed incentive opportunities, client-safe storytelling, and creating or updating the pitch deck.
---

# BI WORLDWIDE Interactive Client Pitch

Use this skill to turn a prospective client's dataset into a persuasive, evidence-led interactive HTML pitch that BI WORLDWIDE sales can review and present. The deck should show how a client's incentive program data can inform better decisions—not pretend that a synthetic example is a client result. Work in the existing project and preserve the self-contained HTML approach.

## Start with the dataset

- If the user has not provided or identified a client dataset, ask them to upload or point to it before making data-based claims. Do not silently substitute the synthetic reference data for client data.
- If a dataset is already attached, pasted, or present in the workspace, inspect it and proceed. Ask only for missing information that materially changes the story; mark other unknowns for sales review.
- Accept source files similar to those in `references/`, including CSV data and a data dictionary. Keep analysis local; do not send client data to external services.
- `references/sample_location_performance_data.csv` is synthetic demonstration data, not a prospect's data. `references/POC Dictionary-Table 1.csv` describes its generic columns. The repository-root `references/Internal Mapping-Table 1.csv` is confidential source-to-generic engineering mapping; use it only when needed and never expose its source-specific field names or contents in the pitch.
- Keep row-level or identifying data out of the client-facing deck unless explicitly approved and necessary. Prefer aggregate views, safe cohort labels, and approved terminology.

## Analyze before writing the pitch

1. **Establish context:** Identify the prospect and industry, program/platform, participant population, period, business question, intended decision, and sales audience. Use supplied discovery answers, and frame unconfirmed items as review questions.
2. **Profile the dataset:** Check its grain, row count, date coverage, duplicate keys, missingness, field meanings, category consistency, and plausible ranges. Identify which outcomes, incentives/rewards, participant segments, costs, and comparison variables are present or absent.
3. **Validate measures:** Use the client's approved data dictionary and program definitions. Confirm KPI formula, period, denominator, eligibility, threshold, and baseline. The generic reference dictionary is not a substitute for client-approved rules. Do not invent missing calculations or thresholds.
4. **Find the strongest supported story:** Analyze the available KPIs, participant tiers, engagement, trend, and reward exposure only where the data supports them. Quantify a clear opportunity with the comparison, denominator, period, and limitations visible.
5. **Connect evidence to an action:** For each opportunity, identify the participant group, proposed program/reward action, accountable program owner, executive sponsor as applicable, success metric, cost inputs, guardrails, and decision that follows.
6. **Create the interactive HTML pitch:** Update `index.html` using the existing single-file approach. Make the pitch presenter-led, easy to review, and useful to sales; include only client-safe evidence and clearly flag all assumptions and review items.

## Client and program context

BI WORLDWIDE serves large clients in multiple industries. Context provided for this work includes automotive incentive programs; life-sciences sales and employee recognition; financial-services sales; and health-care marketing. Participants may be employees, sales teams, or customers. Program types include employee recognition, sales incentives, customer gamification (including Bunchball Nitro), learning delivery (LDS), and self-selected goal programs (GoalQuest). Select only the sector and program confirmed for the prospect. Do not imply that named companies are clients, users, or approved references.

Potential business outcomes include incremental revenue, sales volume, employee or customer retention, and engagement. Treat revenue as the primary outcome when appropriate; explain how the other KPIs support it or serve as leading indicators or guardrails. Do not combine unlike KPIs into one score without client-approved weights.

Possible reward levers include monetary incentives, points and redemption, sweepstakes, public recognition, appreciation, and special winner experiences. Data about past motivation can inspire hypotheses, but only prospect-specific evidence can support a prospect-specific claim.

## Pitch narrative

Adapt the existing seven-section deck to the available data and sales opportunity:

1. **What We Understand:** Prospect context, participant audience, program goals, and constraints.
2. **What the Data Shows:** KPI baselines and performance patterns with clear definitions, denominators, and reporting period.
3. **What Could Be Possible:** A concise, quantified opportunity and testable explanation; distinguish finding from hypothesis.
4. **How BI WORLDWIDE Can Help:** Connect program design, incentive platform, participant insights, and measurement to the client's decision.
5. **What the Client Could Learn:** Who responds, which segments move, what maintains upper-tier performance, and where further evidence is needed.
6. **How Insights Become Outcomes:** A proposed action, owner, incremental success measure, cost/guardrail, and follow-up decision.
7. **Where to Go From Here:** Practical next step, information required, stakeholders, and decision needed to scope a pilot or deeper analysis.

Lead with the business implication, not a list of analytical methods. Make the strongest evidence-backed opportunity the “mic-drop” moment: a specific segment, observed opportunity, proposed action, and measurable outcome. If the dataset cannot establish the finding, present it as a hypothesis to validate—not as a result.

## Evidence, experimentation, and fairness

- Distinguish client-provided facts, observed results, derived metrics, hypotheses, recommendations, assumptions, and open review questions in wording and visuals.
- Never invent client outcomes, participant behavior, rules, thresholds, ROI, forecasts, testimonials, or data coverage. Attribute each finding to a source, period, definition, and comparison.
- Synthetic data can demonstrate the interaction or analytical method only. Prominently label it synthetic; it cannot establish a prospect's performance, adoption, causal impact, or ROI.
- Pre/post and cohort comparisons can show association, not prove that the incentive caused a change. State selection, confounding, and coverage limits.
- Use incremental outcomes when a credible baseline and comparison exist. Calculate ROI only with approved incremental value, reward and delivery costs, and transparent assumptions.
- Recommend experiments only with client approval. Address fairness concerns directly: preserve transparent eligibility and core program rules; consider optional reward or communication variants or phased rollouts only when approved. If randomized experiments are unacceptable, offer an observational comparison and describe its weaker causal evidence. Do not promise causal proof from a non-experimental design.
- Keep all client data and confidential mappings private. Do not add client branding, imply client endorsement, or use named client examples without authorization.

## HTML and review requirements

- Keep the presentation self-contained and browser-ready. Preserve visible navigation, keyboard controls, responsive layout, readable charts, and print/PDF support where present.
- Match the supplied BI WORLDWIDE homepage palette: white/light surfaces, deep navy text, vivid orange primary accents, and purple secondary accents. Use the homepage image as a color reference only; do not copy its logo or imagery unless approved.
- Make data period, metric definition, denominator, cohort/filter, and source clear wherever a chart or finding appears.
- Make exploratory controls deepen the story without hiding the headline or requiring improvisation.
- Label the output as a reviewable sales draft. Call out items for BIW/sales/client confirmation, including KPI definitions, client-safe terminology, reward rules, experiment feasibility, investment assumptions, and approval owners.
- Do not describe the current static synthetic demo as an automatic dataset importer. Replace or recompute sample values from the provided dataset when preparing a prospect-specific pitch.

## Working process

1. Request the dataset if it is missing; otherwise inspect the supplied data and relevant project files.
2. Trace how the existing HTML renders content before editing; make a focused update that supports the client story.
3. Verify calculations against the source data and dictionary. Check client-safe terminology, data boundaries, fairness, and whether each claim is supported.
4. Run an appropriate focused HTML/script check. If browser review is unavailable, state that limitation and report the checks performed.
5. Summarize the resulting pitch, evidence-backed opportunity, assumptions/open review questions, and validation status.
