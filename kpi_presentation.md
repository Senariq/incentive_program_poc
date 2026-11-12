# KPI Incentive Program Pitch Presentation

## Purpose

Create a polished, browser-based HTML presentation that explains the incentive-program idea and helps persuade a prospective client to move forward. This file is the working brief: requirements, content, and decisions can be refined as more project details become available.

## Project goal

Pitch a multi-KPI incentive program by showing how decision science turns program data into decisions, actions, and measurable business outcomes. The presentation should answer the client's questions, "What do we do with the insights?" and "What is the mic-drop moment?" It should support a live pitch and remain understandable without undocumented context.

## Intended audience

- Prospective client and business decision-makers.
- Audience roles, industry context, and familiarity with the current program: **to be confirmed**.

## Pitch narrative

Build the presentation around the client's journey from understanding the opportunity to committing to a practical next step. These seven sections are the core narrative; the final slide count and sequence can adapt to the audience.

1. **What We Understand**
   - Reflect the client's objectives, incentive-program context, participant audience, and constraints.
   - Show that the program holder may adopt an incentive sooner than participants, creating an adoption or engagement gap.
   - Frame this gap as a client-specific observation only when supported by approved evidence; otherwise present it as a question to investigate.
2. **What We See**
   - Surface evidence and patterns in current program performance, participant behavior, and relevant KPIs.
   - Use pre/post and cohort analyses to describe what changed, for whom, and when, while distinguishing correlation from causation.
   - Lead with the business implication of the evidence, not a list of analytical methods.
3. **What We Believe Is Possible**
   - Present explicit, testable hypotheses about how a multi-KPI incentive could influence participant behavior and business outcomes.
   - Explain the opportunity and expected mechanism without presenting an untested hypothesis as a guaranteed result.
4. **How Decision Sciences Can Help**
   - Explain how KPI and incentive design, cohort analysis, hypothesis testing, A/B testing, and dashboards can help answer the client's business questions.
   - Position methods as tools in a decision process, not as the pitch's end product.
5. **What the Client Could Learn**
   - Make the learning concrete: which participants respond, which KPI combinations matter, where impact varies, and what intervention is worth testing.
   - Let the presenter explore relevant comparisons or illustrative scenarios interactively, with assumptions visible.
6. **How We Turn Insights Into Outcomes**
   - Show the operating loop: insight -> decision -> targeted action -> measurement -> optimization.
   - For each proposed action, identify the audience or segment, intervention, owner, success measure, and follow-up decision.
   - Connect investment and ROI to transparent assumptions and measured results, not unsupported promises.
7. **Where We Go From Here**
   - Propose a practical next step, such as a discovery session, data assessment, pilot, or experiment.
   - Clarify required data, stakeholders, timing, investment, responsibilities, and the decision needed to proceed.

## Current sales deck and narrative shift

The existing PowerPoint covers useful material: the program-holder/participant adoption gap, pre/post analysis, cohort analysis, hypothesis testing, A/B testing, dashboards, industry- or audience-specific examples, service investment, and ROI.

Keep these capabilities, but weave them into the seven-part client narrative rather than presenting them as a sequence of tools. Each analytical view should answer a client question and lead to a possible decision or action. Industry examples should make the idea relevant to the specific audience. Investment and ROI should support an outcome-focused discussion with clear assumptions.

## Interactive experience and mic-drop moment

- Use interaction to make the story responsive to the client's priorities: reveal evidence progressively, compare cohorts or KPIs, and explore a clearly labeled scenario where useful.
- Preserve a simple presenter-led path through the seven sections; interaction should deepen the discussion, not make the pitch dependent on improvisation or obscure the main point.
- Define the "mic-drop moment" as a concise, evidence-backed reveal that connects a meaningful opportunity or participant segment to a specific action and the outcome that action is intended to change.
- Until client data and analysis support that reveal, treat it as a design goal, not a factual claim. The sample dataset is synthetic and cannot substantiate client impact or ROI.
- Follow the reveal immediately with the practical answer to "What do we do with the insights?": who should act, what they should do, how success will be measured, and what decision follows.

## Presentation requirements

### Content and credibility

- Lead with the client's business outcomes; explain program mechanics in service of those outcomes.
- Use plain language, concise headlines, and one main point per slide.
- Distinguish verified facts from hypotheses, targets, examples, and proposed next steps.
- Do not invent client results, forecasts, testimonials, or program rules. Mark unconfirmed content for review rather than presenting it as fact.
- Define KPIs and eligibility terms where they first appear or provide a compact glossary.
- Pair each insight with its implication, potential action, and a way to measure whether that action worked.
- Keep the call to action explicit and appropriate to the stage of the sales conversation.
- Show investment and ROI only with transparent inputs, assumptions, and caveats; do not imply guaranteed returns.

### Data and sharing

- Use only approved, client-safe data and terminology in externally shared materials.
- The client-facing reference is `Generic_POC_Performance_Data_Dictionary/POC Dictionary-Table 1.csv`.
- `Generic_POC_Performance_Data_Dictionary/Internal Mapping-Table 1.csv` is internal-only. It contains source-specific field names and must not be copied into the presentation or any external deliverable.
- Validate the meaning, calculation, reporting period, and approval status of any KPI before using it.
- Whether the final presentation will use real client data, anonymized data, sample data, or no data is **to be confirmed**.

### HTML format and usability

- Deliver the presentation as a self-contained HTML experience unless a later requirement calls for another packaging approach.
- Make it suitable for presenting in a modern desktop browser and readable on smaller screens.
- Provide clear slide progression and visible navigation; support keyboard navigation where practical.
- Support a guided presentation path and optional interactive drill-downs or comparisons, with a clear way to return to the main story.
- Keep typography, contrast, spacing, and charts readable when projected.
- Avoid unnecessary animation; any transitions should be subtle and should not obstruct presenting or reading.
- Decide later whether offline operation, print/PDF output, presenter notes, or a particular browser/device must be supported.

### Visual direction

- Aim for a polished, confident, business-focused look that supports the pitch rather than competing with it.
- Branding, colors, logo usage, imagery, and any client-specific visual guidelines are **to be confirmed**.
- Prefer simple diagrams and purposeful charts to dense tables or decorative graphics.
- Do not use client branding or imply client endorsement without approval.

## Working assumptions

- This is a sales presentation for a prospective business client, not an internal technical specification.
- The first deliverable is a reusable HTML presentation foundation; final content and design will be developed iteratively.
- No client-specific facts, approved brand assets, or final program terms have been provided yet.
- The available generic POC dictionary may inform KPI terminology, but it does not by itself establish the client's approved program rules or expected results.

## Sample data

- `sample_location_performance_data.csv` contains 1,000 synthetic location snapshots for the October 2026 reporting month. It follows the column names and order in the client-facing POC data dictionary.
- `index.html` uses an aggregate summary of the sample to demonstrate KPI pass rates and regional comparisons; it does not expose the sample as client evidence.
- The records and names are fictional; this file is for development and demonstration only, not client reporting or evidence of actual program performance.
- The dictionary references several thresholds without specifying values. The sample uses provisional assumptions for rule flags: 100% primary target attainment, a 100 relative-sales index, effectiveness scores of 80 and 115 for the two primary-sales pathways, a 0.20 secondary-to-primary ratio or 30 credited units, 80% priority-product activation, scores of 90 for installed-base and ancillary productivity, 90% case resolution, and facility level 3. These values are illustrative and must be confirmed before being treated as program rules.
- For the customer-loyalty flag, the sample treats meeting either the district or region benchmark as sufficient, as described in the dictionary. Benchmark-selection logic remains to be agreed.

## Open questions

Fill these in as details become available:

- Who is the prospective client, who participates in the program, and who can approve or act on recommendations?
- Which business outcomes and KPIs matter most, and how should competing KPI priorities be balanced?
- What evidence supports the adoption gap between program holders and participants for this client?
- Which participant behaviors, segments, or program decisions should the analysis help explain?
- What client-approved data, baseline, comparison groups, and experiment options are available?
- What is the strongest evidence-backed opportunity that could serve as the mic-drop moment?
- What action could follow each insight, who would own it, and how would success be measured?
- What industry-specific examples, investment details, and ROI assumptions are approved?
- What next-step decision should the pitch secure, and what pilot scope, timing, and stakeholders are realistic?
- What branding, visual references, browser, accessibility, confidentiality, and review requirements apply?

## Proposed work sequence

1. **Understand the client:** Confirm audience, business objectives, existing program, participant journey, constraints, and desired next decision.
2. **Map questions to evidence:** Identify approved data and analyses needed to describe the current state, evaluate hypotheses, and determine what the client could learn.
3. **Design the outcome story:** Agree on the seven-part narrative, the evidence-backed mic-drop moment, recommended actions, success measures, and any ROI assumptions.
4. **Build the interactive HTML experience:** Implement the guided narrative, visual system, navigation, and purposeful comparisons or drill-downs.
5. **Populate and refine:** Add client-approved content, relevant industry examples, data visualizations, investment details, and next-step proposal.
6. **Review and validate:** Check analytical accuracy, claims, data-sharing safety, usability, and readiness to present.

## Decisions and status

- **Current status:** The client narrative and requirements are defined at a high level; client-specific evidence, design, and implementation details remain open.
- **Next input needed:** Client/audience context, priority business outcomes, available approved data, and the decision or commitment the pitch should secure.
- **Decision log:** Add dated decisions here as scope is agreed.