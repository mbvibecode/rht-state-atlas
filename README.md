# Initial Investments in Rural Health Transformation

[**Open the live 50-state atlas →**](https://mbvibecode.github.io/rht-state-atlas/)

An interactive, source-transparent review of how every state proposed using the Rural Health Transformation Program and what states reported as initially obligated through July 31, 2026.

## Explore the atlas

[![Preview of the Initial Investments in Rural Health Transformation website](atlas-preview.jpg)](https://mbvibecode.github.io/rht-state-atlas/)

The State Map is intentionally proposal-focused. Teal capsules identify proposed program areas, orange capsules identify proposed technology areas, and gray means the selected area was not named in the abbreviated state abstract.

## View the leadership infographic

[![Preview of the Initial Investments in Rural Health Transformation infographic](infographic-preview.jpg)](RHT_50_State_Leadership_Report.pdf)

[**Open the full-resolution one-page infographic →**](RHT_50_State_Leadership_Report.pdf)

## What we did

This project turns two lengthy CMS reports into a consistent 50-state evidence package. We:

1. Reviewed the December 2025 state-provided project abstracts for all 50 states.
2. Coded 12 recurring program and technology focus areas, plus eight specific technology groups.
3. Built an interactive state atlas with an equal-area map, state summaries, comparison charts, matrices, and downloadable evidence.
4. Parsed and reconciled 679 reported obligation records totaling **$4.001 billion** through July 31, 2026.
5. Compared proposal themes with explicit obligation categories, initiatives, and line items while keeping the two evidence sources separate.
6. Created a reviewable Excel inventory, CSV data, presentation heat maps, and a one-page leadership infographic.

## Project at a glance

| Measure | Result |
|---|---:|
| States reviewed | 50 |
| Proposal focus areas | 12 |
| Named technology groups | 8 |
| Reported obligation records reviewed | 679 |
| Reported obligations through July 31, 2026 | $4.001B |
| States reporting positive obligations | 48 of 50 |
| Share of the $9.995B award total reported as obligated | 40.0% |

## How to read the proposal–obligation comparison

The source-reconciliation work uses four simple labels:

- **P+O:** the area is named in the proposal abstract and supported by explicit obligation evidence.
- **P:** the area is proposed but not explicitly named in the July 31 obligations snapshot.
- **O:** explicit obligation evidence is present, but the area is not named in the abbreviated abstract.
- **—:** the area was not explicitly located in either supplied report.

A **P-only** result is not a contradiction and does not mean the activity was cancelled. The obligations report captures an early phase of the program. An obligation is also not the same as an expenditure, delivered service, implementation milestone, or outcome.

Broad categories such as `IT Advances` and `Consumer Tech Solutions` are not used to infer AI, cybersecurity, telehealth, EHR, or another technology subtype unless the initiative or line-item language supports that interpretation.

## Main public files

- [Interactive website](index.html)
- [One-page leadership infographic](RHT_50_State_Leadership_Report.pdf)
- [Presentation and heat-map package](RHT_Heat_Map_MB.pdf)
- [Excel evidence inventory](RHT_50_State_Inventory.xlsx)
- [50-state proposal coding and financial context](RHT_50_State_Data.csv)

## Public source reports

- [CMS state-provided project abstracts, December 2025](rht-program-state-provided-abstracts.pdf)
- [CMS reported obligated funds through July 31, 2026](RHTP-Obligated-Funds-10082026.pdf)

## Method in brief

Proposal classifications are analyst-curated from the state abstract compilation. General needs or possible recipients alone do not qualify as a proposed activity. Obligation evidence requires a positive-dollar official category or explicit initiative or line-item description. Zero-dollar initiatives are excluded.

Care-area and technology linkage uses a stricter rule: the care area and named technology must appear in the same positive-dollar line-item/category segment, or a care-specific initiative title must govern the technology line item. State-level, page-level, or broad-initiative co-occurrence alone does not qualify.

The project is descriptive and is not an official CMS rating, funding determination, or assessment of state performance.

## Static-site deployment

The published entry point is `index.html`. The site is self-contained and does not require external scripts, fonts, maps, or analytics. To redeploy, rebuild and review the source package, synchronize the public website files, test locally, and commit and push the updated package to the `main` branch used by GitHub Pages.
