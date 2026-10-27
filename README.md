# Formula 1 Race Intelligence Dashboard

A Tableau project built for the SkillWallet (SmartBridge) Data Analytics with Tableau programme. It explores race outcomes, championship points, wet and dry conditions, circuit race times, and team reliability from the supplied Formula 1 project dataset.

> **Data note:** The supplied dataset is simulated. Findings describe this dataset and should not be presented as real Formula 1 history.

## Project files

- `F1 Racing Project Dataset.xlsx` — source workbook supplied with the project.
- `F1_Race_Intelligence_Dashboard.twbx` — packaged Tableau Public workbook. Open it in Tableau Public or Tableau Desktop.
- `f1_clean.csv` — prepared CSV supplied with the project files.
- `PROJECT_SEQUENCE.md` — project workflow aligned to the SkillWallet phases, with completion notes.
- `DATA_NOTES.md` — caveats and current data-preparation limits.
- `PERFORMANCE_AND_VALIDATION.md` — validation checklist and performance-measurement template.
- `WEB_INTEGRATION.md` — publication and embedding steps; no published URL is claimed yet.
- `DEMO_SCRIPT.md` — short project presentation outline and evidence checklist.

## Dashboard

The `Race Intelligence Dashboard` brings together:

- Driver championship points
- Team championship points
- Race counts by season, split by wet and dry conditions
- Average total race time by circuit
- DNFs by team

The workbook also retains the source worksheets for driver performance and season race counts. The `Formula 1 Race Intelligence Story` presents an overview followed by team points, wet/dry mix, reliability, and circuit pace.

## Open the workbook

1. Download `F1_Race_Intelligence_Dashboard.twbx` and `F1 Racing Project Dataset.xlsx` from this repository.
2. Open the `.twbx` file in Tableau Public or Tableau Desktop.
3. If Tableau prompts for the source file, reconnect it to `F1 Racing Project Dataset.xlsx`.

The workbook is saved as a local packaged file and has not been published to Tableau Public. Add a Tableau Public link here after publishing is approved and completed.

## Data and interpretation notes

The source workbook contains race results, championship standings, lap intelligence, qualifying results, and circuit metadata. The Tableau dashboard uses the available standings and race-result views; the project sequence notes which analysis and delivery steps still need completion.

Known dataset caveats recorded in the project brief:

- The data is simulated and should not be interpreted as actual historical F1 results.
- Carlos Sainz appears under two teams in the supplied records; use a team-aware driver label when comparing him.
- Bahrain is overrepresented in the race records and can dominate host-location summaries.
- Many qualifying rows use placeholder driver and team names.
- The 2026 season is partial.

## SkillWallet workflow

Follow the eight project phases in order: data collection and extraction, data preparation, data visualization, dashboard, story, performance testing, web integration, and project demonstration and documentation. See [`PROJECT_SEQUENCE.md`](PROJECT_SEQUENCE.md) for deliverables and status. The performance measurements, live web integration, and demo evidence are explicitly marked pending until completed.

## Credits

Prepared for the SkillWallet (SmartBridge) Data Analytics with Tableau programme.
