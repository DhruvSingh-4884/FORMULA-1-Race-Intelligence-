# Formula 1 Race Intelligence Dashboard

An interactive Formula 1 analytics demonstration built from the project plan and worksheet specifications in this repository.

## Download and run

Download and extract the [complete project bundle](./f1-race-intelligence-complete.zip). From the extracted `f1-race-intelligence` folder, run:

```powershell
python -m http.server 8000
```

Open [http://localhost:8000/dashboard.html](http://localhost:8000/dashboard.html). The dashboard loads its CSV over HTTP, so serve the folder instead of opening the HTML with a `file://` URL.

## Included dashboard

Eight analytical views, four KPI cards, filters for Season, Constructor, Driver, and Tyre Compound, a Top N control, and five story scenes. The bundle also includes the source CSV, data dictionary, calculated-field definitions, worksheet specifications, project plan, performance checklist, validation notes, and a demo walkthrough script.

## Data warning

The included 6,464-row CSV is **synthetic sample data**. It matches the expected schema but does not represent real Formula 1 results. Do not treat the dashboard values as real sporting conclusions. Replace the sample with verified race data before drawing conclusions.

## Tableau status

The project plan includes Tableau workbook creation and Tableau Public publishing. Those Tableau steps are excluded from this deliverable; the bundle contains no fabricated workbook or demo URL.
