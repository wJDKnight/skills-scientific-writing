---
name: writing-coach
description: "Evaluate and improve scientific writing by assessing outlines, drafts, and manuscript sections. Use when: (1) User provides an outline and wants feedback on completeness, (2) User provides a draft of Methods, Results, Introduction, or Discussion for evaluation, (3) User wants revision suggestions for their scientific writing, (4) User requests direct revisions to their manuscript file."
---

# Writing Coach

Help users improve their scientific writing by evaluating outlines and drafts against established standards, providing actionable revision suggestions, and performing direct revisions when requested.

## Workflow

### 1. Identify What User Provided

Determine the type of content:
- **Outline**: A structured list of ideas, questions, or section headings
- **Methods section**: Experimental procedures, materials, design descriptions
- **Results section**: Data presentation, findings, figures/tables references
- **Introduction section**: Background, gap, objectives, hypothesis
- **Discussion section**: Interpretation, context, limitations, implications

### 2. Evaluate Against Criteria

Read the appropriate reference file:
- For outlines → `references/outline_checklist.md`
- For section drafts → `references/section_evaluation.md`
- For conciseness and style → `references/concise_writing_rules.md`

### 3. Provide Feedback

Structure feedback as:
1. **Assessment**: What is present, what is missing, what needs improvement
2. **Specific Issues**: Quote problematic passages with explanations
3. **Revision Suggestions**: Concrete, actionable recommendations

### 4. Revise If Requested

When user explicitly asks for revision:
1. Read the user's file
2. Apply revisions directly using edit tools
3. Explain key changes made

## Evaluation Approach

### For Outlines

Check against Level 1 and Level 2 outline requirements:
- Level 1: Topic, importance, hypothesis, results/visuals, major finding
- Level 2: Proper IMRaD structure with all required elements per section

Report missing elements and suggest how to address gaps.

### For Section Drafts

Evaluate based on section-specific criteria:
- **Methods**: Explicitness, reproducibility, consistency of voice
- **Results**: Clarity, conciseness, objectivity, logical flow
- **Introduction**: Three-move structure (territory → niche → occupy)
- **Discussion**: Three-move structure (findings → context → closing)

Identify common problems:
- Missing details (n, units, effect sizes, CIs)
- Voice inconsistency within paragraphs
- Wordiness and nominalizations
- Unnecessary intensifiers
- Weak lead-in sentences

## Output Format

### Evaluation Report

```
## Evaluation: [Section Type]

### Strengths
- [What is done well]

### Missing Elements
- [Required element]: [Why it matters]

### Issues Found
1. **[Issue type]**: "[Quoted text]"
   - Problem: [Explanation]
   - Suggestion: [How to fix]

### Priority Revisions
1. [Most important fix]
2. [Second priority]
3. [Third priority]
```

### When Revising Files

- Make changes directly to the user's file
- Preserve the overall structure unless restructuring is needed
- Add comments or notes only if user requests them
- After revision, summarize key changes made

## Resources

- `references/outline_checklist.md`: Criteria for evaluating outline completeness
- `references/section_evaluation.md`: Section-specific evaluation criteria and common issues
- `references/concise_writing_rules.md`: 10 rules for concise scientific writing with practical examples

