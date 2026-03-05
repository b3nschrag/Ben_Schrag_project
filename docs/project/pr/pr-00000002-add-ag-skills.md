---
title: "Add agricultural data analysis skills from borealBytes/ag-skills"
status: draft
author: benschrag
date: 2026-03-05
 reviewers: []
---

## Summary

- Adds 12 agricultural data analysis skills from borealBytes/ag-skills repository
- Skills include field boundaries, soil data, weather data, satellite imagery, cropland data layers, and EDA tools
- Includes example data for testing each skill

## Changes

### Files Added

- `.opencode/skills/` - 47 files totaling 14,063 lines
  - 12 skill directories with SKILL.md files
  - Python modules for data download and processing
  - Example datasets for testing

### Skills Added

| Category      | Skills                                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Data Download | field-boundaries, ssurgo-soil, nasa-power-weather, cdl-cropland, sentinel2-imagery, landsat-imagery, interactive-web-map |
| Analysis      | eda-explore, eda-visualize, eda-correlate, eda-time-series, eda-compare                                                  |

## Verification

- All 12 skill directories contain SKILL.md files
- Root SKILL.md and README.md present
- Commit pushed to `Schrag_project_branch`

## Status

- [x] Download skills from borealBytes/ag-skills
- [x] Commit to local branch
- [x] Push to remote
- [ ] Create GitHub PR

## GitHub PR URL

https://github.com/b3nschrag/Ben_Schrag_project/compare/main...Schrag_project_branch
