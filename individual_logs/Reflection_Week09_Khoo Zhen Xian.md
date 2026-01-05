# Reflection Week 09 - KHOO ZHEN XIAN

### 1. Why is identifying the critical path important for project managers?
Identifying the Critical Path (CP) is important because it reveals the specific sequence of activities that determines the total duration of the project. 

### 2. Which activity posed the highest scheduling risk?
Activity H: Model Training posed the highest scheduling risk.
It is the longest single activity in our WBS. Also, it cannot start until Feature Extraction (Activity G) is 100% complete. If the upstream data quality from the Data Cleaning (Activity E) phase is poor, the training phase will fail, potentially forcing a loop back to earlier stages.

### 3. What trade-offs are involved when crashing a project?
Crashing a project involves cost and quality trade-off. For example, crashing Model Training from 14 days to 10 days, we would likely need to pay for premium cloud GPU resources.

In the other hand, we will face quality trade-off when reducing the number of training epochs or simplifying the model architecture,we may gain time but potentially sacrifice the model's accuracy.