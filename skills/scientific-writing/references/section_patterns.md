# Section Patterns for Scientific Manuscripts

Use these outlines when drafting or repairing sections. Keep order consistent between Methods → Results → Discussion.

## Starting with an Outline
When writing from scratch without a provide outline, generate a outline.md.

Begin with a template outline and expand it iteratively. 

### Level 1 Outline (initial ideas)
1. What is the topic of my paper?
2. Why is this topic important?
3. How could I formulate my hypothesis?
4. What are my results (include visuals)?
5. What is my major finding?

### Level 2 Outline (add context and structure)
Group ideas into IMRaD sections before expanding into prose.

## IMRaD Quick Inputs (have these before drafting)
- Research question/hypothesis and primary endpoint(s)
- Design and setting (trial/observational/lab/simulation), preregistration ID if any
- Population/sample (inclusion/exclusion), n per group
- Exposures/interventions/comparators and timing
- Outcomes/measures with units and how measured
- Analysis approach (model/test, covariates, corrections)
- Main results with effect sizes + uncertainty (CI/SD/SE) + p if relevant
- Approvals/data availability (IRB/IACUC/consent), code/data links

## Drafting Sequence
1. Outline visuals/tables and pair each with the matching Methods/Results subsections.
2. Draft order: **Methods → Results → update outline → Introduction → Discussion → Abstract/Title last.**
3. Keep voice consistent (passive acceptable in Methods; active preferred elsewhere). Do not switch voice within the same paragraph.


## Title
- 12–16 words; mention population, exposure, outcome; avoid jargon and abbreviations unless standard.

## Abstract (structured; adapt journal headings)
- Background (1 sentence): why the question matters.
- Objective: what you tested/estimated.
- Methods: design, setting, n, key measures, primary analysis.
- Results: top-line numbers (effect size with CI; p), harms/adverse events if applicable.
- Conclusion: plain-language takeaway and implication; avoid overclaiming causality unless randomized/strongly justified.

## Introduction (context → gap → aim)

Keep brief: 250–600 words for most journals. Be direct—do not use a "suspense" approach; present your contribution and key findings early.

### Three-Move Structure (Swales)

**Move 1: Establish a research territory**
- Show that the general research area is important, central, interesting, or problematic.
- Introduce and review previous research in the area.

**Move 2: Find a niche**
- Indicate a gap in previous research, or extend prior knowledge in some way.

**Move 3: Occupy the niche**
- Outline purposes or state the nature of the present research.
- List research questions or hypotheses.
- Announce principal findings (do not make the reader hunt for them).
- State the value of the present research.
- Optionally indicate the structure of the paper.

### Paragraph-Level Guide
- P1: Context and importance (what is known).
- P2: The gap or limitation in prior work.
- P3: Objective/hypothesis and the specific contribution—include a one-sentence summary of findings and approach.

## Methods

The purpose of this section is to allow others to evaluate and replicate your work. Be meticulous and explicit.

- Design and setting; preregistration/ethical approvals.
- Participants/samples: recruitment, inclusion/exclusion, final n per group/timepoint.
- Variables and measures: definitions, instruments, time points, units.
- Procedures/interventions: how delivered; randomization/blinding if any.
- Analysis: primary/secondary outcomes, models/tests, covariates, missing-data handling, multiple-comparison control, software/versions.
- Reproducibility: data/code availability, protocol links, accession numbers.
- Be explicit: speeds, times, temperatures, sources of materials, equipment settings.
  - ✗ "Bacteria were pelleted by centrifugation."
  - ✓ "Bacteria were pelleted by centrifugation at 3000g for 15 min at 25°C."
- Cite published methods; give full detail if new or modified.
- Passive voice is acceptable and common in Methods, but do not switch between active and passive within the same paragraph.

## Results

The Results section is the heart of your paper. Lead the reader through your story with direct, concise, and clear sentences.

### Structure for Each Subsection
1. Purpose of the experiment/analysis
2. Experimental approach (brief)
3. Data: text and visuals (figures, tables, schematics)
4. Data commentary: meaningful summary highlighting the most important points (do not merely repeat the visuals)

### Guidelines
- Start with cohort/sample flow and key descriptives.
- Present findings in the same order as Methods/aims.
- Report effect sizes with CI and n; include direction and units.
- Reserve interpretation for Discussion; keep prose factual.
- Avoid wordy lead-ins ("In Figure 1, we show…") and overview sentences.
- Do not repeat data already in figures/tables—highlight key points instead.
- Be selective: present only experimental details essential for understanding; excessive data distracts.
- Avoid intensifiers ("clearly shows," "obviously demonstrates")—they reduce objectivity.
- If contradictory findings exist, mention them and offer plausible explanations.

## Discussion

The Discussion places your findings in context and explains their meaning and importance. Structure mirrors the Introduction in reverse: zoom out from your findings to the broader research context.

### Three-Move Structure

**Move 1: The study's major findings**
- State the study's major findings. Common openers: "Our findings demonstrate…," "In this study, we have shown that…," "Our results suggest…"
- Explain the meaning and importance of your findings—do not assume it is obvious to readers.
- Consider and address alternative explanations proactively.

**Move 2: Research context**
- Compare and contrast your findings with published results.
- Explain any discrepancies and unexpected findings.
- State limitations, weaknesses, and assumptions of your study—this adds modesty. Suggest feasible explanations or solutions; do not end on problems that override your findings.

**Move 3: Closing the paper**
- Summarize answers to the research questions.
- State applications, recommendations, and implications.
- End with a single-sentence takeaway without new claims.

### Style
- Use active voice and first-person pronouns to convey confidence.
- Keep language clear, precise, and concise.

## Limitations (if separate section)
- Bullet the major limits with likely direction of bias; mention mitigations if any.

## Data/Code Availability Statements
- Specify repository/DOI/accession and license; note restrictions (privacy/DUA).
