# PM Portfolio Progress — 16 November 2026

## Current milestone: CareNest case-study revision

**Status:** Revised on a review branch; not merged or published.

- Portfolio repository: `zenifeni-star/zainab-enifeni-portfolio`
- Review branch: `review/carenest-case-study-v1-1-2026-11-16`
- Case-study file: `carenest.html`
- Commit: `e75f6ed3a80750d19e32f0345cc3b21ff01d8a07`
- Main branch remains unchanged at the previous CareNest HTML blob.

## Work completed

- Added a clear PM-programme-simulation context and a documented contribution section.
- Corrected the RICE interpretation: Expert Q&A is 1.2; Immunization Reminder is 1.25. RICE is described as post-research feature prioritization, not validation of the pivot.
- Added all six candidate scores and the Reach-unit ambiguity note.
- Added the research sample boundary: six mothers, infant ages 2–9 months, four first-time mothers and two who were not; omitted locations because the interview summary and Full PRD conflict.
- Separated PRD requirements, RICE recommendations, reported prototype delivery and validation still needed.
- Added the documented four-step feeding-guidance journey from the Lovable brief.
- Added the original PRD month-one targets with denominator/label cautions and a clearly labeled proposed Weekly Guided Care Actions metric.
- Added limitations and a separate section for the later Hybrid Care Guide AppDeploy iteration, with its live demo link.
- Preserved the existing visual system and the next-case-study navigation to Kindred.

## Evidence reviewed

- User Interview Findings Summary
- RICE Prioritisation document
- Full PRD and Week 6 PRD
- Sprint Planning Notes
- Lovable prototype brief
- Prior CareNest research, scope, measurement and final-audit artifacts
- Current GitHub `carenest.html` and `index.html`
- AppDeploy CareNest app metadata, v7 deployment status, source test plan and source files

## QA and boundaries

- Static content checks passed for the corrected RICE statement, contribution section, sample limitations, disputed-location note, scope discrepancy, proposed metric, original targets and separate later iteration.
- HTML section and div counts are balanced.
- The original `main` branch was verified unchanged after the review-branch commit.
- No site deployment or publication was performed.
- The later AppDeploy iteration is deployed, but its stored test file lists scenarios rather than pass/fail results. Deployment logs include a failed guide request and a logo resource-load error; do not claim clean end-to-end QA, clinical validation or user outcomes.

## Portfolio position

- **Nestuge and Clinsights:** previously reported published; not re-audited in this run.
- **CareNest:** case-study page revised on a review branch; not yet merged/published or counted as polished. A separate later Hybrid Care Guide demo is live.
- **Kindred / TTC Community:** next case study after CareNest review.
- **Gatherly and Rentwise:** existing case-study pages and live MVP links; not audited against the full polished-case-study criteria in this run.

Do not count page listings as polished case studies. The quality bar remains: narrative, contribution, evidence, decisions, limitations and presentation must all be reviewable.

## Next milestone

Review the CareNest v1.1 branch and, after approval, merge/publish it and verify the live page. Then update the existing Kindred/TTC Community case study using the already documented invitation-only pilot, circles/shared feed, pseudonymous participation, moderation, appeals and medical-safety boundaries. Do not start another project or write another PRD while these existing case studies remain unfinished.


## Final QA pass — 23 November 2026

**Branch state:** `review/carenest-case-study-v1-1-2026-11-16` remains unmerged. A fresh GitHub comparison showed the review branch ahead of `main`; `main` still contains the older CareNest page. No merge, deploy or publication was performed.

### QA findings and action taken

- Rechecked the current review-branch CareNest HTML and progress record rather than relying on the prior summary.
- Confirmed the case page contains the contribution boundary, six-person sample limitations, omitted conflicting interview locations, corrected RICE values (Expert Q&A 1.2; Immunization Reminder 1.25), the PRD/RICE scope discrepancy, Reach-unit ambiguity, original month-one targets, proposed WGCA definition, validation limits and separate later Hybrid Care Guide iteration.
- Confirmed the page has a document title, English language declaration, viewport metadata, responsive layout rules, reduced-motion handling, no placeholder copy, and a working in-page narrative structure.
- Found that the homepage card still described CareNest as an “Independent MVP” for “first-time mothers” and made the separate Hybrid Care Guide look like the same original project. Updated the card on this review branch only to describe the PM-programme simulation, the six-interview pivot and documented prototype work. The demo link is now explicitly labeled as a separate later iteration.
- The case-study HTML currently contains no original programme prototype screenshots. A CareNest-branded image is present in the Library, but no original onboarding/feeding/check-in screen captures were found in the reviewed sources. Do not substitute screenshots from the later Hybrid Care Guide. Add original prototype screens only if recoverable; otherwise the flow description remains the available visual evidence.
- The live Netlify page could not be fetched through the available web inspection route during this run. Since the review branch remains unmerged, the v1.1 case-study page is not considered live or verified.

### Approval-ready checklist

1. Review the revised CareNest page on the branch.
2. Confirm the homepage card accurately describes the programme simulation and separate later demo.
3. If available, supply or recover 2–3 screenshots from the original programme prototype; do not use later Hybrid Care Guide screens as substitutes.
4. Approve merging the review branch. No merge or deployment should occur before explicit approval.
5. After approval and publication, verify the live CareNest page, internal navigation and separate demo link, then audit the rendered page once more.

### Portfolio position after this QA pass

- **Nestuge and Clinsights:** previously reported published; still not re-audited against the current full quality bar.
- **CareNest:** copy and homepage summary revised on the review branch; awaiting explicit approval, merge/publication and live verification. Not yet counted as polished.
- **Kindred / TTC Community:** remains next, but work must wait until CareNest is approved, published and verified.
- **Gatherly and Rentwise:** existing pages and live MVP links; not yet audited against the full quality bar.

No new project or PRD was started. The next milestone remains approval and publication of the existing CareNest revision, not another duplicate document.
