# Validation and performance plan

## Current status

The packaged workbook has been assembled locally. Formal load-time and interaction measurements have not been recorded, so this phase remains pending until the checks below are completed in Tableau Public or Tableau Desktop.

## Validation checklist

- [ ] Open `F1_Race_Intelligence_Dashboard.twbx` in Tableau and confirm the packaged data opens without a missing-file prompt.
- [ ] Confirm the dashboard shows driver points, team points, wet/dry races by season, circuit race time, and DNFs by team.
- [ ] Open `Formula 1 Race Intelligence Story` and step through all story points.
- [ ] Check axis titles, legends, filters, labels, and tooltips at the intended display size.
- [ ] Confirm the simulated-data caveat is visible wherever results are presented.

## Performance measurements

Record measurements on the same computer and Tableau version, and note whether the workbook was opened from local storage or GitHub.

| Measurement | Result | Environment / notes |
|---|---|---|
| Time to open workbook | Not measured | Record seconds and Tableau version |
| Time to render dashboard after opening | Not measured | Record seconds and selected filters |
| Filter interaction responsiveness | Not measured | Record the filter and observed delay |
| Story-point navigation responsiveness | Not measured | Record the slowest transition |

Do not mark SkillWallet performance testing complete until results and any corrective actions are recorded here.
