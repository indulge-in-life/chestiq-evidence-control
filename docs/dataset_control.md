## Observations from Dataset

- Multiple findings per image (multi-label complexity)
- "No Finding" dominates → risk of biased predictions
- Same patient appears across multiple records → risk of leakage
- Demographic attributes available (age, gender)

## Identified Control Risks

1. Model may overfit to dominant class ("No Finding")
2. Evaluation may not reflect real clinical distribution
3. Bias across gender/age not evaluated
4. Lack of patient-level separation

## Required Controls (Future)

- Create dataset_v2 with:
  - balanced sampling
  - patient-level split
- Introduce fairness evaluation (gender/age)
- Track dataset usage per model version

## Assessment Approach

The dataset was not reviewed manually in full. Instead, a combination of:

- Sample inspection of records
- Pattern observation in label distribution
- Review of patient identifiers

was used to identify key risks such as multi-label complexity, repeated patient records, and class imbalance.


# Traceability Links

- Models: model_v1

---

## Dataset Version v2

### Purpose
Improve dataset quality and reduce risks identified in v1

### Changes
- Class imbalance reduced through sampling
- Improved representation of minority classes
- Consideration of patient-level grouping to reduce leakage

### Impact
- Expected improvement in model fairness
- Reduced bias in predictions

### Remaining Risks
- Sampling may reduce diversity
- Bias may still exist without full validation

### Traceability Links
- Models: model_v2
