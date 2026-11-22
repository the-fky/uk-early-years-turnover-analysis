# UK Early Years Workforce Turnover Analysis

## Business Question
What patterns in England's early years workforce data point to likely drivers of staff leaving?

## Data
DfE Survey of Childcare and Early Years Providers, reporting year 2024 (Explore Education Statistics, GOV.UK). Datasets used: staff turnover, staff joining and leaving, qualification level of staff leaving, proportion of staff by qualification level, and number of paid staff.

## Tools
Power BI Desktop, Power Query

## Process
- Loaded the DfE CSV files and checked the columns and data types.
- Filtered the qualification file to 2024, removed summary rows and grouped qualification levels so they matched the leavers data.
- Fixed setting-type names that differed between files and merged the leavers and workforce tables.
- Built dashboard pages: turnover by setting, qualification level of leavers, and leavers vs workforce.

## Key Findings
1. Turnover is highest in private group-based providers and lowest in maintained nursery schools.
2. Leavers skew towards the least qualified staff. In private group-based settings, Level 1 or below staff are 11% of the workforce but 30% of leavers; Level 6 staff are 11% of the workforce but about 8% of leavers.
3. The same direction appears in school-based settings.

## Recommendations
1. Prioritise retention support in private group-based settings.
2. Support early-career, lower-qualified staff to stay and progress.
3. Collect exit reasons and destinations so the next analysis can explain why.

## Limitations
- Aggregate survey data, one year only (2024), so no individual-level tracking.
- Leavers are staff who left their provider, not necessarily the sector.
- "No UK Early Years qualification" was grouped with "Level 1 or below", and "Level 6 or higher" was matched to "Level 6".
- Workforce percentages are rounded to whole numbers.
- Qualification of leavers is only published for four setting types.
- The data shows patterns, not reasons. Explanations are interpretation.

## Files
`.pbix` (open with free Power BI Desktop), PDF export, screenshots, source CSVs.
