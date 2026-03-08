---
type: workflow
id: essay-writing-pipeline
title: Essay Writing Pipeline
description: "From topic to polished essay: thesis, outline, draft, and revision"
tags: [Production]
connections:
  - target: thesis-development
    type: uses
  - target: essay-structuring
    type: uses
  - target: develop-thesis
    type: uses
  - target: structure-essay
    type: uses
  - target: essay-draft
    type: uses
---

## Overview

This workflow guides the complete essay writing process from initial topic through to a polished draft, ensuring a strong thesis and coherent structure throughout.

## Pipeline Stages

### Stage 1: Thesis Development

Invoke the **thesis-development** skill to refine a vague topic into a focused, arguable thesis statement with clear scope.

### Stage 2: Essay Structuring

Invoke the **essay-structuring** skill to organise supporting arguments into a coherent essay structure with logical flow.

### Stage 3: First Draft

Invoke the **essay-draft** prompt to generate a first draft following the established structure and thesis.

### Stage 4: Revision

Review the draft against the thesis and structure, checking for argument coherence, evidence quality, and academic tone.

## Output

A structured essay containing:

- Focused thesis statement
- Logical argument structure
- First draft with academic tone
- Revision notes and improvement suggestions
