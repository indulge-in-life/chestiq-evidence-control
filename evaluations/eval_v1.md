## Evaluation Report

### Model
model_v1

### Dataset
dataset_v1

---

## Evaluation Summary

This evaluation assesses the baseline performance of model_v1 trained on dataset_v1.

---

## Key Observations

- Model shows reasonable performance on dominant class ("No Finding")
- Performance on minority disease classes is limited
- Multi-label predictions increase complexity in evaluation

---

## Risks Identified

1. Bias towards dominant class ("No Finding")
   - Model may under-detect rare diseases

2. Data leakage risk
   - Repeated patient IDs may influence results

3. Limited clinical reliability
   - No fairness or subgroup evaluation performed

---

## Decision

❌ Not approved for production use

---

## Reason for Decision

- Dataset-related risks not addressed
- Bias and fairness not evaluated
- Model performance not reliable for clinical use

---

## Traceability Links

- Model: models/model_v1/model_info.md
- Dataset: data/dataset_v1.json
- Dataset Control: docs/dataset_control.md

---

## Next Actions

- Create improved dataset version (dataset_v2)
- Address class imbalance
- Introduce fairness evaluation
