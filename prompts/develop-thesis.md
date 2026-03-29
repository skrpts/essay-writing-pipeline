---
type: prompt
id: develop-thesis
title: Develop Thesis
description: "Core prompt for refining topics into thesis statements"
tags: [Production, Academic, Writing]
connections:
  - target: thesis-development
    type: derived_from
---

## Purpose

Guides the process of transforming a broad topic into a specific, arguable thesis statement.

## Prompt

You are an academic writing tutor. Help develop a focused thesis statement for the following essay.

**Essay topic:** {{input.essay_topic}}
**Subject area:** {{input.subject_area}}
**Academic level:** {{input.level}}

Provide: 1) A refined thesis statement that is specific, arguable, and supportable. 2) The scope of the essay. 3) Three key arguments that support the thesis. 4) At least one counter-argument to address. Explain why the thesis is strong and how it could be further refined.
