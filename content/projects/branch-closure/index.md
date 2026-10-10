---
title: "Spatial Analysis of Bank Branch Closures"
date: 2026.07.02
summary: "An exploratory, multi-scale spatial analysis of what location characteristics distinguish closed from retained bank branches, using public data only."
tags:
  - Spatial analysis
  - GIS
  - Banking
---

**Context.** Cathay Life Insurance, Loan Appraisal Department (Data Analyst Intern).

**Question.** As branch networks shrink, which neighbourhood characteristics are associated with a branch being closed rather than kept?

**Approach.**
- Built multi-scale buffers (300 m to 2,500 m) around each branch and attached public data on demographics, income, industry structure, housing market and competing financial service density.
- Compared closed and retained branches variable by variable, using normality tests followed by t-tests or Mann-Whitney U tests.
- Designed the workflow as a reusable framework that can be applied to other banks and cities.

**My role.** Designed the spatial pipeline, built the geospatial dataset and ran the statistical comparisons.

*Based on public data only; internal data and results are not shown.*