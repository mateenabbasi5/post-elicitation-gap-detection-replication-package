# Replication Package: Evidence-Grounded AI-Assisted Detection of Post-Elicitation Requirements Gaps Across Asynchronous Software Artifacts

This repository contains the replication package for the study on AI-assisted, evidence-grounded detection of post-elicitation requirements gaps across asynchronous software engineering artifacts.

## Repository purpose

The package is intended to make the study transparent and reproducible. It contains:

- five scenario bundles (S1-S5),
- clean and seeded versions of each scenario,
- frozen prompts used for AI-assisted analysis,
- raw AI outputs,
- gold-standard annotations,
- prediction logs,
- normalization and scoring files,
- false-negative records,
- scenario-level metrics,
- and aggregate results used in the paper.

## Study overview

The study evaluates whether AI-assisted analysis can detect post-elicitation requirements gaps across asynchronous artifacts such as:

- meeting transcript excerpts,
- requirements specifications,
- user stories or backlog items,
- acceptance criteria,
- decision logs.

The evaluation uses a structured taxonomy of six gap types:

- G1 Missing Requirements
- G2 Hidden Assumptions
- G3 Inconsistencies
- G4 Decision Voids
- G5 Traceability Gaps
- G6 Stakeholder Silence

## Scenario overview

The replication package contains five scenarios:

- **S1**: Clinic appointment booking
- **S2**: E-commerce returns
- **S3**: University course registration
- **S4**: Travel reimbursement system
- **S5**: Warehouse inventory system

Each scenario includes:
- a clean bundle,
- a seeded bundle,
- a gold standard with eight seeded gaps,
- AI predictions,
- normalized scoring,
- and scenario-level metrics.

## Package structure

```text
scenarios/
  S1/
  S2/
  S3/
  S4/
  S5/

prompts/
aggregate_results/
paper_assets/
