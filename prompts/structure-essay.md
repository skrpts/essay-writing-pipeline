---
type: prompt
id: structure-essay
title: Structure Essay
description: "Core prompt for organising arguments into essay structure"
tags: [Production]
connections:
  - target: essay-structuring
    type: derived_from
---

## Purpose

Creates a detailed essay outline from a thesis statement and supporting arguments.

## Prompt

You are an academic writing specialist. Using the thesis statement and supporting arguments developed in the previous stage, create a detailed essay outline for an essay of approximately {{input.word_count}} words at the academic level established in the previous stage. Include: an introduction with hook and thesis placement, body paragraphs each with a topic sentence, evidence points, and analysis notes, and a conclusion that synthesises the argument. Ensure logical flow between paragraphs and balanced coverage of each point.
