# A1 HR Vision Demo: Data Model Review

Air Force A1 / Total Force HR (Iron Compass) "Art of the Possible" demo, presented Dec 1-2, 2026 (dry runs Nov 30).

## Purpose of this repo
A static review page (`index.html`) proposing the data model for the in-scope vignettes. The lead SE approves or requests changes per section and exports the result. The export drives the data model build in the org.

## Scope
- In: V1 Airman portal, V2 PCS Orders Update (marriage), V4 Leave Request, V5 Fitness Assessment.
- Out: V3 Retraining (deprioritized), V6 Reasonable Accommodation (do not do).

## Constraints
- Commercial cloud. Org: A1HR (Public Sector IDO). Domain `a1hr-demo`.
- Airman = Contact + Experience Cloud user. Leave and Fitness are custom objects; Orders Update is a Case record type.
- No credentials in this repo or on the page.

## Workflow
1. Review page published here (private repo, Pages).
2. Lead SE exports decisions JSON.
3. Build the data model from the approved export, then hand off to Experience Cloud and Agentforce workstreams.
