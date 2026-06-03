# Chestiq Evidence Control

# Audit-Ready AI Traceability & Evidence Control System

## Overview

This project demonstrates a structured approach to ensuring traceability, evidence control, and audit readiness in an AI-based chest X-ray analysis system.

## Problem

AI systems often face challenges such as:

- Lack of traceability across datasets, models, and evaluations
- Poor visibility of changes and their impact
- Missing or unstructured evidence for decisions
- Difficulty in demonstrating regulatory compliance

## Solution

This project introduces a traceability and evidence control framework that:

- Versions datasets, models, and prompts
- Establishes traceable links between all artefacts
- Uses evaluation reports to support decision-making
- Captures changes and their impact through a change log
- Maintains an evidence index for audit readiness

## Traceability Flow

Dataset → Model → Evaluation → Prompt → Decision

## Key Features

- Dataset versioning (dataset_v1 → dataset_v2)
- Model traceability linked to dataset versions
- Evaluation-driven decision process (reject/approve)
- Prompt versioning for LLM traceability
- Change log for controlled evolution
- Evidence index for audit readiness
- Risk and gap analysis for continuous improvement

## Outcome

- Initial system (v1) identified critical risks and was rejected
- Improvements were introduced in dataset_v2 and model_v2
- Updated system (v2) was approved for controlled use
- End-to-end traceability and evidence control established

## Why This Matters

In regulated AI environments, it is not sufficient to build models. It is essential to:

- Prove how models were built
- Trace outputs back to datasets
- Justify changes and decisions
- Provide structured evidence for audit

This project demonstrates how these requirements can be addressed systematically.

## Author

Pravin Kumar Kathirmani
