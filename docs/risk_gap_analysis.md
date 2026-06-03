## Identified Gaps (Initial State)

1. No dataset version control
2. No clear linkage between dataset and model
3. No evaluation-based decision process
4. No prompt versioning or control
5. No centralized evidence tracking

## Risks

- Inability to trace model outputs to specific dataset versions
- Potential bias in predictions due to dataset imbalance
- Risk of uncontrolled changes affecting model behavior
- Lack of audit readiness due to missing evidence
- Inconsistent outputs due to untracked prompt changes

## Remediation Actions

- Introduced dataset versioning (v1 and v2)
- Established traceability between dataset, model, and evaluation
- Created structured evaluation reports with decision outcomes
- Implemented prompt version control
- Built evidence index for audit readiness
- Created change log for tracking system evolution

## Current State

- End-to-end traceability established
- All artefacts version-controlled
- Evaluation-driven decision process in place
- Evidence available and structured for audit

## Remaining Gaps

- No detailed fairness metrics implemented
- No automation of traceability (manual documentation)
- No deployment monitoring or post-release tracking
- No clinical validation in real-world settings

## Ethical Risks

- Potential bias across demographic groups not fully evaluated
- Lack of fairness metrics may impact responsible AI compliance
