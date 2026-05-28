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
