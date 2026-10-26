# Meridian Program Command Center

A working demo of how one program office can run delivery, program and transformation work from a single view. The scenario is a fictional hospital EHR modernization: **Meridian Health Network**, 5 hospitals, 18 months, $14M budget.

**All data is invented.** No real organization, patient or system is represented.

**Live demo:** [https://github.com/anujaprasad17/meridian-command-center/](https://anujaprasad17.github.io/meridian-command-center/)
**Case study:** [case-study.md](case-study.md)
**LinkedIn carousel (PDF):** [LinkedIn-Carousel-Meridian-Command-Center.pdf](LinkedIn-Carousel-Meridian-Command-Center.pdf)

## What it shows

| Tab | What you see |
|---|---|
| Summary | Steering-committee view: overall status, five status tiles, decisions needed, top risks, workstreams |
| Program plan | Planned vs forecast milestones, with float and the chain of milestones that has little slack |
| RAID | Risks, assumptions, issues and dependencies, scored probability × impact, with escalation flags |
| Budget & capacity | Spend vs plan and forecast, plus a team capacity heatmap |
| Delivery | Say/do ratio, defect leakage, sprint chart, release readiness |
| Transformation | Site readiness, benefits tracking, objectives and key results |
| What-if | Slip a milestone or remove people from a team and see dates, cost and benefits move |
| Status report | One-click weekly report built from the data, with PDF download |
| About | The problem, the approach and the rules behind each status colour |

## How it works

- One data set drives every view.
- Forecast dates follow the dependency chain: a milestone cannot finish before its slowest predecessor plus a minimum lag.
- Red, amber and green follow written thresholds, listed on the About tab.
- A risk escalates at a score of 16 or more, or when it is old (over 45 days) and scores 12 or more.
- What-if cost and benefit figures are indicative and use assumed monthly rates.
- The status report is built from fixed text templates. It does not call an AI service.

## Run it

It is a single self-contained HTML file. Open `index.html` in any modern browser. An internet connection is needed for the fonts and the PDF library, which load from public CDNs (Google Fonts and cdnjs).

To publish it yourself, enable **GitHub Pages** (Settings → Pages → deploy from the `main` branch, root folder).

## Files

| File | Purpose |
|---|---|
| `index.html` | The command center |
| `case-study.md` | Walkthrough script and one-page case study |
| `LinkedIn-Carousel-Meridian-Command-Center.pdf` | Dashboard screenshots as an 11-slide carousel |
