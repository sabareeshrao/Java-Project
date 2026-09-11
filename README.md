# Java Project

This repository is the canonical source of truth for the Java interview-training project built from the user's curated interview-question workbook and established GIS / aerial-topographic work context.

## Purpose

- Build the knowledge base question by question.
- Keep answers consistent with the same multi-year Java/GIS project history.
- Reuse previously established architecture, incidents, tools, and terminology instead of inventing unrelated stories for every question.
- Store a compact 30–60 second study answer for each question.
- Store a render-ready Developer Simulation Engine script with a target of no more than 10 meaningful steps per question.
- Preserve Git history as an audit trail while treating the current files on `main` as the canonical truth.

## Canonical question identity

Questions keep the immutable `Family ID` from the curated workbook. The first build is `QF-001-002`.

## Repository layout

```text
experience/       Established work-history context
questions/        Compact interview study records
simulations/      Render-ready training scripts
```

## Build rule

For every new question:

```text
Workbook question
      ↓
Read current repository truth
      ↓
Reuse established experience/project facts
      ↓
Add only the smallest new context needed
      ↓
Create compact interview answer
      ↓
Create <=10-step simulator script
      ↓
Commit to main
```
