---
name: scientific-writing
description: Structured guidance for drafting and revising scientific manuscripts (IMRaD, abstracts, cover letters, reviewer responses) with checklists for clarity, statistics, and reproducibility. Use when writing or editing academic papers, abstracts, rebuttals, or related scholarly communication.
---

# Scientific Writing

## Overview
A user may ask you to create, edit, or revise the contents of a scientific paper. The contents could be in .md file or .txt file. When writing, understand which part of a paper you are writing using `references/section_patterns.md`. Your writing should stick to the rules for Clarity and Concision in `references/revision_checklists.md`.

  - Draft from notes → use the IMRaD outlines in `references/section_patterns.md`.
  - Revise existing text → use the revision workflow + `references/revision_checklists.md`.
  - Write/condense abstract → follow the abstract pattern in `references/section_patterns.md`.
  - Respond to reviewers → follow `references/reviewer_response.md`.


## Draft From Notes (new text)
1. Start from the outline (question, stakes, visuals); keep Methods/Results in matching order.
2. Write short paragraphs with topic sentence → evidence (numbers/units/n) → single takeaway.
3. Quantitative claims include measure, unit, n per group, effect size, uncertainty, and p if relevant.
4. Add figure/table callouts and draft captions with sample size, test/model, adjustments, and abbreviations.
5. Run the revision checklist.

## Revise Existing Text
1. Identify the goal (clarify, shorten, strengthen claims, adjust tone).
2. Stick to the rules for Clarity and Concision in `references/revision_checklists.md`
3. Macro pass: reorder to align with aims and figures; delete repetition and unnecessary lead-ins.
4. Micro pass: break long sentences; prefer active voice; keep tense consistent (past for Methods/Results).
5. Fill missing details: n per group, units, model/test, uncertainty, multiple-testing handling, software versions.
6. Compare against `references/revision_checklists.md` for a final pass; read aloud or backward to catch flow issues.

## Figures, Tables, and Data
- Captions: what is shown, sample/units, test/model, adjustments/covariates, and definitions of symbols/abbreviations.
- Tables: columns map to variables; include denominators and units; note missingness handling.
- Data/code availability: provide repository/DOI/accession and license; note any access restrictions (privacy/DUA).

## Concision Anchors
- Get to the point; avoid redundant lead-ins (“In Figure 1, we show …”) and filler intensifiers.
- Use first-person active voice when appropriate; avoid nominalizations that bury actions.
- Replace multi-word phrases with shorter equivalents; avoid repeating data already shown in figures/tables.

## Citations and Claims
- Keep placeholders (e.g., “[1]”) if citation details are unknown; do not invent DOIs/PMIDs.
- Attribute external claims; avoid anthropomorphizing models/data.
- Match journal style (APA/Vancouver/etc.) when specified.

## Reviewer Responses
- Use courteous, specific replies that cite exact locations of changes.
- If disagreeing, provide evidence/rationale and, when possible, an alternative check to demonstrate robustness.
- Template and phrasing guidance: see `references/reviewer_response.md`.

## Guidelines for Preferred Drafting Order
here are steps you can tell user how to prepare a draft.
1. Draft Materials/Methods first with enough detail to replicate.
2. Write Results in the same order as Methods/aims; keep interpretation minimal.
3. Update the outline to reflect what you actually did/found.
4. Write the Introduction using context → gap → aim.
5. Draft the Discussion starting with the main finding, then interpretation, strengths/limits, and implications.
6. Finish with Title and Abstract using the provided patterns.

## Resources
- `references/section_patterns.md`: IMRaD outlines, abstract pattern, availability statements.
- `references/revision_checklists.md`: concision/flow, quantitative reporting, reproducibility, style.
- `references/reviewer_response.md`: cover letter and point-by-point response template and guidance.
