# Construction Project Risk Intelligence Pipeline

A 5-stage pandas data pipeline analysing 1,300 construction project tasks 
across a $64.4M material cost portfolio.

## Pipeline Stages
1. Load & Validate — schema checks and assertions
2. Feature Engineering — 12 new columns, including Complexity Score
3. Risk Analysis — composite risk index, underestimated risk detection
4. Critical Task Flagging — priority scoring and tier assignment
5. Summary Report & Export — PM-ready output

## Key Findings
- 8 tasks flagged P1 (immediate attention)
- 87 tasks underestimated (labelled Low risk, high complexity)
- 5 triple threat tasks identified
- Original 10 columns expanded to 22

## Tools
Python · pandas · matplotlib
