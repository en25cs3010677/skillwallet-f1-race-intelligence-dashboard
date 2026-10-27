# Data notes

## Files

- `data/source/F1 Racing Project Dataset.xlsx` is the supplied source workbook.
- `data/processed/f1_clean.csv` is the prepared CSV available with the project files.
- `F1_Race_Intelligence_Dashboard.twbx` is the packaged Tableau workbook used for the dashboard and story.

## Interpretation and limitations

- The supplied data appears simulated. Dashboard findings describe this dataset only and are not claims about actual Formula 1 history.
- Carlos Sainz appears under two teams in the supplied records; use a team-aware driver label when comparing records.
- Bahrain is overrepresented in the race records and can dominate host-location summaries.
- Many qualifying rows use placeholder driver and team names.
- The 2026 season is partial.
- The processed CSV is included for reuse. A reproducible cleaning script and a full field-by-field data dictionary are not included in this project package yet.

## Tableau views

The packaged workbook includes driver championship points, team championship points, wet/dry race counts by season, average race time by circuit, and DNFs by team, plus a story that presents the main views in sequence.
