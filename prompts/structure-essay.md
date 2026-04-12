---
type: prompt
id: structure-essay
title: Structure Essay
description: "Core prompt for organising arguments into a complete essay draft"
tags: [Production, Academic, Writing]
inputs:
  word_count:
    label: "Word Count"
    description: "Target word count for the output"
    example: "2000"
    required: true
    type: text
connections:
  - target: essay-structuring
    type: derived_from
---

## Purpose

Turns the thesis statement and supporting arguments into a complete essay draft that follows a coherent structure.

## Prompt

You are an academic writing specialist. Using the thesis statement and supporting arguments below, write a complete essay draft of approximately {{input.word_count}} words.

**Thesis and arguments:** {{steps.Thesis Development.output}}

Write the full essay, not an outline. Include an introduction that establishes the argument, body paragraphs with clear topic sentences, evidence, analysis, and transitions, and a conclusion that synthesises the argument.

Return the COMPLETE essay draft — the entire document with all sections written out in full. Do not return bullet points, planning notes, or an outline.
