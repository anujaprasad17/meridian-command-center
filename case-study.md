# Meridian Program Command Center: walkthrough script and case study

Both pieces describe a fictional program. Say so in the first sentence of any recording or post.

---

## Part 1. Three-minute walkthrough script

Spoken pace is about 150 words a minute, so this runs close to three minutes. Stage directions are in brackets.

**0:00 to 0:20. The problem** [Summary tab on screen]

"This is a demo I built to show how I run a large healthcare transformation. The scenario is fictional: a five-hospital network replacing its electronic health record over 18 months, with a $14 million budget. The usual problem is that dates, money, risks and clinical readiness sit in different files, so the committee finds out late. Here, one data set drives every view."

**0:20 to 1:00. The steering view** [Point to the status tiles]

"This is the page a committee reads in 60 seconds. Overall status is amber. Wave 1 go-live is forecast for January 26, 2027 and the program finishes August 31, 2027. Budget forecast is about $15 million, around 7% over. Clinician readiness averages 64%, against an 80% target. Each colour follows a written rule, listed on the About tab, so nobody has to argue about what amber means."

[Point to the decisions box] "Below that are the three decisions I need from the committee: release contingency, fund four contract trainers, and escalate a vendor. A status page should end in decisions, not just numbers."

**1:00 to 1:40. Plan and risk** [Program plan tab, then RAID tab]

"The forecast dates come from the dependency chain. Data migration is three weeks late, but Wave 1 still holds, with only one day of float. The Wave 2 readiness gate has three, so the next slip lands on a go-live. That is where I would spend my attention."

[RAID tab] "Every item has a probability and impact score, an owner and an age. Anything scoring 16 or more, or old and still serious, gets an escalate flag. The pharmacy interface vendor is the top one."

**1:40 to 2:15. Money, people and delivery** [Budget & capacity tab, then Delivery]

"Spend has run about 8% over plan each month since April. The heatmap shows why: training is over 120% of capacity from December to March. Cloud Platform sits near 70%, so I can propose loaning two engineers to data migration instead of asking for new budget."

[Delivery tab] "Say/do is 88%, short of a 90% target, so I would coach on commitment sizing before pushing for more speed."

**2:15 to 2:45. What-if** [What-if tab, drag sliders]

"Before a meeting I can test options. If I slip the migration milestone by four more weeks, Wave 1 moves, Wave 2 moves with it, and the page shows the added cost and the benefits pushed out. If I take two people off training, it shows the delay that causes. This turns a debate into numbers."

**2:45 to 3:00. Close** [Status report tab, click Generate, then Download PDF]

"One click turns all of this into the weekly report, including any scenario I have set, and a second click saves it as a PDF I can send to the committee. The pattern is the same on any program: one source of truth, written rules for status, and every view ending in a decision."

---

## Part 2. One-page case study

### Meridian Health Network: EHR modernization command center
*A fictional program built as a portfolio demo.*

**Role shown:** program management, with delivery and transformation views.

**Context.** A five-hospital network is replacing its legacy electronic health record in three go-live waves over 18 months. Budget is $14 million. The program is in month 8 and amber: data migration is three weeks late, a pharmacy interface vendor is behind, training capacity is short, and the forecast sits about 7% over budget.

**Problem.** Each workstream reported in its own format. The steering committee could not see how a slip in one place affected a go-live date, a budget line or clinical readiness, so decisions arrived late and arguments were about whose numbers were right.

**Approach.**
1. *One data set.* Milestones, risks, spend, capacity, sprints and site readiness all feed from the same source.
2. *Forecasts from dependencies.* A milestone cannot finish before its slowest predecessor plus minimum lag. Float, and the chain with little of it, are visible.
3. *Written status rules.* Red, amber and green follow thresholds for schedule, budget, risk, benefits and readiness.
4. *Escalation by rule.* A risk score of 16 or more, or an old item scoring 12 or more, is flagged.
5. *Scenarios before meetings.* A what-if planner shows date, cost and benefit effects of a delay or a staffing change.
6. *Decisions on page one.* The summary ends in the choices the committee must make.

**What the program office would track.**

| Area | Measures |
|---|---|
| Schedule | Forecast vs baseline for each go-live, float on the critical chain |
| Cost | Spend vs plan, forecast at completion, contingency drawn |
| Risk | Open items scoring 15+, escalations, average age |
| Delivery | Say/do ratio, defect leakage, release readiness |
| Transformation | Site readiness, super-user coverage, benefits vs plan |

**Decisions the page supports.**
- Release about $0.75M of the $0.8M contingency to cover a $1.0M overrun, and offset the rest by deferring low-value scope.
- Fund four contract trainers to protect the Wave 1 date.
- Escalate the vendor under the contract's SLA clause.
- Decide whether to hold the January date or protect clinician readiness at the flagship.

**What I would do differently in a real program.** Replace the seeded data with live feeds from the work-tracking and finance systems, and agree thresholds with the sponsor in week one.

**Limits.** All data is invented. Cost and benefit figures in the what-if tool use assumed monthly rates and are indicative only.
