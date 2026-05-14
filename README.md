# Pharmacovigilance-Safety-Analysis-Project
## Project Overview
This project was developed to simulate a real-world pharmacovigilance workflow using FAERS (FDA Adverse Event Reporting System) adverse event data. The project focuses on drug safety monitoring, adverse event analysis, MedDRA coding, causality assessment, signal detection, narrative writing, and aggregate safety reporting.

The objective of this project was to understand the practical workflow followed in pharmacovigilance and drug safety operations while improving analytical and reporting skills using Microsoft Excel.
## Project Objectives
- Analyze adverse event reports from FAERS safety dataset
- Perform MedDRA Preferred Term (PT) and System Organ Class (SOC) coding
- Conduct seriousness and causality assessment
- Identify potential safety signals
- Prepare professional pharmacovigilance narratives
- Develop aggregate safety dashboards and visual reports
## Dataset Information
### Dataset Source:
- FAERS (FDA Adverse Event Reporting System)
### Dataset Included:
- Report IDs
- Adverse reactions
- Suspect drugs
- Drug routes
- Seriousness criteria
- Patient demographics
- Outcomes
- Therapeutic indications

## Pharmacovigilance Workflow Performed
1. Data Cleaning and Preparation
- Organized raw FAERS data
- Removed formatting inconsistencies
- Structured columns for analysis
- Standardized data fields
2. MedDRA Coding
- Performed mapping of adverse events into:
   - Preferred Terms (PT)
   - System Organ Classes (SOC)
```
| Primary Reaction | PT          | SOC                                  |
| ---------------- | ----------- | ------------------------------------ |
| Pneumonia        | Pneumonia   | Infections and infestations          |
| Neutropenia      | Neutropenia | Blood and lymphatic system disorders |
```
3. Seriousness Assessment
- Classified adverse events as:
   - Serious
   - Non-serious
- Based on:
   - Hospitalization
   - Death
   - Life-threatening condition
   - Medically significant event
4. Causality Assessment
- Used a simplified WHO-UMC methodology to classify causality as:
   - Probable
   - Possible
   - Unlikely
- Assessment was based on:
   - Temporal relationship
   - Clinical plausibility
   - Known safety profile
   - Event severity

5. Signal Detection
- Performed basic signal detection analysis by identifying:
  - Repeated infection-related reactions
  - Immune-mediated adverse events
  - Hematologic safety signals
  - Neurological safety events
6. Narrative Writing
- Prepared professional ICSR-style case narratives summarizing:
   - Patient information
   - Suspect drug exposure
   - Adverse events
   - Seriousness
   - Outcome
   - Causality assessment
7. Aggregate Reporting and Dashboard
- Created pivot tables and visual dashboards using Excel.

#### Dashboard Included:
-Dashboard[dashboard.png]
- Top reported adverse reactions
- Serious vs non-serious events
- MedDRA SOC distribution
- Signal category analysis
- Gender and demographic analysis
## Key Findings
- Infection-related adverse events such as pneumonia were frequently reported.
- Immune-mediated and hematologic reactions were identified as important safety observations.
- Serious adverse events were commonly associated with biologic and immunosuppressive therapies.
- Aggregate analysis helped identify recurring safety trends.
### Tools Used
- Microsoft Excel
- FAERS Dataset
- MedDRA-based classification approach
## Skills Demonstrated
- Pharmacovigilance workflow understanding
- MedDRA coding
- Causality assessment
- Signal detection
- Narrative writing
- Aggregate safety reporting
- Dashboard creation and visualization
- Safety data interpretation
## Conclusion
This project successfully simulated a beginner-level pharmacovigilance case processing and safety analysis workflow. It provided practical exposure to adverse event analysis, MedDRA coding, signal detection, and aggregate reporting concepts commonly used in pharmacovigilance and drug safety operations.





  
