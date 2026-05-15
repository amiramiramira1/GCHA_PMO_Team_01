# Wideband Delphi Estimation Results
## GCHA AI Model Training Consensus

**Date:** 15/3/2026  
**Facilitator:** Enas (London PM)  
**Participants:** 3 team members (Berlin, Cairo, Bangalore, London PM)  
---

## Task Description
Train the GCHA AI predictive model using cleaned historical patient data from 85 hospitals to achieve ≥90% accuracy. Includes data preprocessing, transfer learning setup, training iterations, validation, and documentation.

---

## Round 1: Initial Estimates
| Team Member | Role | Estimate | Rationale |
|-------------|------|---------|-----------|
| Habiba      | Berlin AI Specialist | 60h  | Transfer learning reduces time; assumes clean data |
| Amira        | Cairo Data Lead      | 200h | Data messy; multiple iterations likely |
| Enas    | London PM           | 80h  | Modern AI tools; clean data assumed |

**Range:** 60h - 200h → **Spread factor:** 3.33×
---

## Discussion Highlights
- Hospital data quality is a major risk  
- Transfer learning valid, saves time  
- 3 iterations realistic  
- 90% medical accuracy stricter than commercial  

**Key Insight:** Cairo must pre-clean data before Berlin starts; 3 training iterations needed

---

## Round 2: Revised Estimates
| Team Member | Round 1 | Round 2 | Reason for Change |
|-------------|---------|---------|-----------------|
| Habiba      | 60h     | 100h    | Accounted for 3 iterations + validation buffer |
| Amira        | 200h    | 140h    | Risk reduced with confirmed clean data |
| Enas      | 80h     | 120h    | Adjusted for strict accuracy target |

**Final Range:** 100h - 140h  
**Final Consensus:** 120h

---

## Key Assumptions
- Cairo delivers ≥90% clean data with quality report  
- Transfer learning from MediPredict (80% reuse) available  
- GPU infrastructure ready  
- Maximum 3 training iterations  
- Team experienced in AI (5+ years)

---

## Lessons Learned
- Wide initial spread uncovers hidden assumptions  
- Discussion revealed critical dependencies  
- Transfer learning reduces time but iterations needed  
- Medical accuracy requirements stricter than commercial  
- Consensus > median; conservative buffer useful  

---

## Risks & Mitigation
- Data quality <90% → +30h, check early report  
- Transfer learning unavailable → +180h, fallback to open-source  
- >3 iterations required → +20h/iteration, review after 3 runs  
- GPU unavailable → schedule delays, use cloud if needed

---

**Final Estimate:** 120 hours
