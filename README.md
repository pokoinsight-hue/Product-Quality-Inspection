# Optimizing Quality Inspection Through Sampling Analysis
  ACME Manufacturing- Minor Defects Monitoring

## Description
ACME Manufacturing produces electronic components used in industrial robotics, where consistent product quality is critical. Minor defects do not affect functionality but serve as an early indicator of process instability.

The company currently inspects one component every 15 minutes, which managers believe increases cost and reduces production efficiency. This project analyzes historical inspection data to evaluate whether reduced sampling strategies can maintain effective defect monitoring while lowering inspection effort.

## Break Down
Process Stability
Overall defect levels remained stable across the production period, with no sustained upward trends. This confirmed the process was suitable for evaluating alternative sampling strategies.

Daily Risk Assessment
Analysis of average defects by production day showed no consistent daily risk pattern. Variations were isolated rather than systematic.

Sampling Strategy Comparison
A 30-minute sampling strategy closely tracked the full 15-minute inspection trend and detected defect spikes effectively. A 60-minute strategy introduced higher volatility and greater deviation, increasing quality risk.

Before building the Power BI report, the dataset was reviewed and prepared to ensure it could support time-based analysis. Defect values were validated and standardized, and a sequential inspection number was created to act as a time index since no timestamps were provided. Production day values were normalized for consistent grouping, and reduced sampling scenarios were simulated by filtering inspection sequences to reflect less frequent inspections. The cleaned and structured data model was then used for rolling trend calculations and comparative reporting.

### Quality Overview

<img width="1919" height="977" alt="image" src="https://github.com/user-attachments/assets/d79a2c97-1ced-4ce4-b02b-e84c7f3628c4" />
High-level view of minor defect trends with KPI indicators and rolling averages to assess overall process stability.

### Daily Stability

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/d514b41f-9998-462e-8b28-a423655708de" />


Analysis of defect behavior by production day to identify potential calendar-based risk patterns.

### Sampling Strategy Comparison

<img width="1918" height="975" alt="image" src="https://github.com/user-attachments/assets/fffc6b43-50f8-427b-9eb1-d79a6e3c8b93" />

Comparison of full, 30-minute, and 60-minute inspection strategies using rolling averages to support inspection frequency decisions.

## Recommendation

Based on the analysis, a 30-minute inspection interval is recommended. This strategy maintains effective monitoring of minor defects while reducing inspection volume by approximately 50%. Hourly sampling is not recommended due to increased volatility and quality risk.




