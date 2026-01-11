# uidai-operational-stress-analysis
District-level analysis of Aadhaar enrolment and update data to identify operational stress and inclusion risks (UIDAI Data Hackathon).
# District-Level Aadhaar Operational Stress & Inclusion Risk Analysis

## Overview
This project analyzes district-level Aadhaar enrolment and update data provided by UIDAI to identify operational stress patterns and inclusion risks across India.

The analysis was developed as part of the UIDAI Data Hackathon and focuses on scalable, privacy-preserving, and policy-relevant indicators.

## Problem Statement
Despite high Aadhaar coverage, certain districts experience disproportionately high update activity relative to enrolments, leading to operational stress and service inefficiencies. A significant portion of this stress is driven by child (under-18) biometric updates.

## Datasets Used
- Aadhaar Enrolment Dataset
- Aadhaar Biometric Update Dataset
- Aadhaar Demographic Update Dataset

All data is aggregated at district level and contains no personal identifiers.

## Methodology
- Data consolidation from multiple CSV files
- Cleaning and standardization
- District-level aggregation
- Feature engineering and indicator design

### Key Indicators
- Aadhaar System Stress Indicator
- Child Aadhaar Update Risk Zones
- Aadhaar Inclusion Gap Index

## Key Findings
- Majority of districts show low operational stress
- 311 districts fall under medium stress, 67 under high stress
- Over 90% of districts are child-risk dominant
- All medium/high stress districts are also child-risk zones

## Visualizations
Key insights are supported using histograms, violin plots, and state-wise comparisons.

## Conclusion
Operational stress in Aadhaar services is localized and primarily driven by child-centric biometric updates, requiring district-specific and population-focused interventions.

## Recommendations
- District-targeted update drives
- School-linked child Aadhaar update programs
- Regular monitoring using update-to-enrolment ratios
- Data-driven resource allocation

## Author
Abhishek Kumar
