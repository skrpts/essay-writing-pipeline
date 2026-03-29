---
type: prompt
id: essay-draft
title: Essay Draft
description: "Task prompt for generating a first draft from an essay outline"
tags: [Production, Academic, Writing]
connections:
  - target: essay-structuring
    type: derived_from
---

## Purpose

Generates a complete first draft following the established essay structure and thesis.

## Prompt

Write a first draft for the essay outline below. Use academic tone appropriate for the level established in the earlier stages.

**Essay outline:** {{steps.structure-essay.output}}

Follow the structure provided, developing each paragraph with clear topic sentences, supporting evidence, and analytical commentary. Maintain consistent argument throughout and ensure smooth transitions between paragraphs. Target the word count specified in the essay outline.
