# Risk Register (Week 06)

| Risk ID | Description                                         | Category    | Likelihood (L) | Impact (I) | Score (L×I) | Response                         |
|---------|-----------------------------------------------------|-------------|----------------|------------|--------------|----------------------------------|
| R1      | Dataset labels may be incorrect or inconsistent     | Technical   | 3              | 4          | 12           | Mitigate (relabel, manual check) |
| R2      | Class imbalance causes poor model accuracy          | Technical   | 4              | 4          | 16           | Mitigate (balancing techniques)  |
| R3      | Training takes too long due to large dataset        | Resource    | 3              | 4          | 12           | Optimize preprocessing            |
| R4      | Team member unavailable for a week                  | Schedule    | 2              | 3          | 6            | Redistribute tasks                |
| R5      | High compute cost using cloud GPU/CPU               | Cost        | 4              | 3          | 12           | Reduce, usage monitoring          |
| R6      | Miscommunication during feature development         | Stakeholder | 3              | 2          | 6            | Improve meeting frequency         |
| R7      | UI development delays                                | Schedule    | 3              | 3          | 9            | Add buffer time                   |
| R8      | Merge conflicts on GitHub                           | Technical   | 2              | 3          | 6            | Follow Git workflow               |



## Top Priority Risks (Mitigation Plans)

1. **R2 – Class imbalance causes poor model accuracy**
   - **Mitigation:** Apply oversampling, undersampling, or synthetic data (SMOTE). Ensure each topic category has adequate representation.
   - **Owner:** Khoo
   - **Deadline:** 18 Nov 25

2. **R1 – Dataset labels may be incorrect or inconsistent**
   - **Mitigation:** Perform manual review of samples, remove suspicious entries, apply rule-based validation to detect mislabeled items.
   - **Owner:** Aqem
   - **Deadline:** 1 Nov 25

3. **R3 – Training takes too long due to large dataset**
   - **Mitigation:** Use optimized preprocessing, reduce vocabulary size, use TF-IDF or distilled models to speed up training.
   - **Owner:** Fariz
   - **Deadline:** 15 Nov 25
