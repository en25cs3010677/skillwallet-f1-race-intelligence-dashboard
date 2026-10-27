# SkillWallet project sequence

This checklist follows the project phases shown in SkillWallet for **FORMULA 1 Race Intelligence Dashboard Analysis Report (2010–2026)**. The dataset is simulated, so all findings apply to the supplied data only.

| Step | SkillWallet phase | Deliverable in this repository | Status |
|---|---|---|---|
| 1 | Data Collection & Extraction from Database | `F1 Racing Project Dataset.xlsx` | Source dataset included |
| 2 | Data Preparation | `f1_clean.csv` and Tableau data model | Prepared CSV included; a reproducible preparation script and full data dictionary are not included yet |
| 3 | Data Visualization | Driver and team points, wet/dry race counts, circuit race times, and DNFs by team | Included in workbook |
| 4 | Dashboard | `Race Intelligence Dashboard` | Included in workbook |
| 5 | Story | `Formula 1 Race Intelligence Story` | Included in workbook |
| 6 | Performance Testing | `PERFORMANCE_AND_VALIDATION.md` | Test plan included; measurements not yet recorded |
| 7 | Web Integration | `WEB_INTEGRATION.md` | Pending a published Tableau Public URL and confirmed integration target |
| 8 | Project Demonstration & Documentation | `DEMO_SCRIPT.md`, `README.md`, and this checklist | Documentation and demo script included; recording and screenshots remain pending |

## Suggested presentation order

1. Introduce the decision-support goal and simulated-data caveat.
2. Show driver and team championship points.
3. Compare wet and dry race counts by season.
4. Explore circuit race-time differences.
5. Review DNFs by team as a reliability view.
6. Demonstrate the packaged dashboard and Tableau story.
7. Record performance results in `PERFORMANCE_AND_VALIDATION.md`, then complete web integration and demonstration assets.

## Data caveats

- Carlos Sainz appears under two teams; distinguish records with a team-aware driver label.
- Bahrain is overrepresented in the race records.
- Many qualifying records use placeholder driver and team names.
- 2026 is a partial season.
- The dataset appears simulated; do not present dashboard findings as real F1 history.
