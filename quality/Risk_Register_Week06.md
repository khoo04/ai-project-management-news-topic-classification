# Risk Register (Week 06)

| Risk ID | Description                                   | Category    | Likelihood (L) | Impact (I) | Score (L×I) | Response                      |
|---------|-----------------------------------------------|-------------|----------------|------------|--------------|-------------------------------|
| R1      | Dataset too small or imbalanced               | Technical   | 3              | 4          | 12           | Mitigate (augmentation)       |
| R2      | Sensor data inconsistency                     | Technical   | 4              | 3          | 12           | Prevent (data validation)     |
| R3      | Training takes too long due to weak hardware  | Resource    | 3              | 4          | 12           | Mitigate (optimize model)     |
| R4      | Team member unavailable for one week          | Schedule    | 2              | 3          | 6            | Transfer/Share workload       |
| R5      | Cloud compute costs exceed budget             | Cost        | 4              | 4          | 16           | Reduce usage, set limits      |
| R6      | Miscommunication in team                      | Stakeholder | 3              | 2          | 6            | Improve communication plan    |
| R7      | Delay in UI development                       | Schedule    | 3              | 3          | 9            | Add buffer time               |
| R8      | Code merge conflicts on GitHub                | Technical   | 2              | 3          | 6            | Follow Git branching strategy |


## Top Priority Risks (Mitigation Plans)

1. **R5 – Cloud compute costs exceed budget**
   - **Mitigation:** Set cloud usage limits, use local GPU when possible, enable usage alerts.
   - **Owner:** David
   - **Deadline:** 20 Oct

2. **R1 – Dataset too small or imbalanced**
   - **Mitigation:** Add public weather datasets, apply data augmentation, balance classes.
   - **Owner:** Alice
   - **Deadline:** 18 Oct

3. **R2 – Sensor data inconsistency**
   - **Mitigation:** Apply data cleaning rules, automatic validation scripts, remove outliers.
   - **Owner:** Farah
   - **Deadline:** 19 Oct
