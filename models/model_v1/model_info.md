## Model Information

### Model Name
Chest X-ray Classifier

### Version
v1

### Purpose
Detect abnormalities in chest X-ray images (e.g., pneumonia, infiltration, mass)

---

## Dataset Used

- Dataset Version: dataset_v1
- Source: NIH Chest X-ray dataset

---

## Key Assumptions

- Dataset is suitable for baseline training
- Labels are accurate enough for initial evaluation

---

## Known Limitations

- Dataset has class imbalance ("No Finding" dominant)
- Multi-label complexity (multiple diseases per image)
- Potential data leakage due to repeated patient IDs

---

## Traceability Links

- Dataset: data/dataset_v1.json
- Dataset Control: docs/dataset_control.md
- Evaluation: evaluations/eval_v1.md 

---

## Status

Draft (Not approved for production use)
