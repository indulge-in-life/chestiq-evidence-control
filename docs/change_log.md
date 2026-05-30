## Version History

### v1 → v2

#### Changes
- Dataset updated to reduce class imbalance
- Model retrained using improved dataset
- Prompt refined for better output structure

#### Reason for Change
- Address bias in model predictions
- Improve reliability across disease classes

#### Impact
- Improved performance on minority classes
- Reduced bias towards "No Finding"
- Better structured outputs from LLM

#### Supporting Evidence
- eval_v1: rejection due to bias
- eval_v2: approved for controlled use
