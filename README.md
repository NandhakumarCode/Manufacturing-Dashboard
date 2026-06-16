This project presents an interactive Power BI dashboard designed to monitor and analyze key manufacturing performance indicators

**Problem Statement**
In many manufacturing environments, data exists across multiple sources but lacks structured visibility. This project addresses that gap by consolidating operational data into a single analytical dashboard that surfaces patterns not easily visible through raw reporting.

**Dashboard Features**

Overall equipment efficiency (OEE) tracking

Shift-wise production and downtime comparison

Machine-level performance analysis (88% to 95% range)

Defect rate distribution by machine and operator

Monthly production trend analysis

Bottleneck identification through downtime concentration

**Key Insights Uncovered**

Overall efficiency was approximately 92%, with downtime contributing a consistent ~2.8% loss

Shift B recorded the highest production but also the highest downtime — indicating possible overloading

Machine performance varied between 88% and 95%; lower-performing machines also showed higher defect rates

Furnace 3 emerged as a critical bottleneck with significantly concentrated defects (~4.7% defect rate)

Operator output was broadly similar, but defect levels varied across operators — suggesting a training gap

Monthly fluctuations in production indicate process inconsistency requiring structured intervention

**Data Model**

Star Schema with Production, Downtime, and Quality tables

DAX measures for dynamic KPI calculation and trend analysis

**Tools Used**

Power BI Desktop — Dashboard development and visualization

DAX — Custom KPI measures and calculated columns

Microsoft Excel — Data preparation and source structuring

