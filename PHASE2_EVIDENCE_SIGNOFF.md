# Phase 2 Evidence and Sign-Off Checklist

**Purpose:** Track evidence needed for the owner to decide whether Phase 2 meets its approved acceptance gate.

**Current state:** All evidence items are **Not assessed**. Approval of the public scope summary is not Phase 2 completion or final acceptance.

## Evidence checklist

For each item, record a sanitized evidence reference or private storage reference. Do not upload credentials, personal information, actual farm records, backups, private URLs, or unredacted logs to this public repository.

| ID | Acceptance area | Evidence to inspect | Status | Reviewer notes / private evidence reference |
| --- | --- | --- | --- | --- |
| P2-01 | Approved scope | Authoritative Phase 2 objectives, exclusions, measurable pass criteria, and stop conditions reconciled with the public summary | Not assessed | |
| P2-02 | Controlled pilot | Dated test matrix covering the approved roles and workflows, expected results, actual results, tester, and environment | Not assessed | |
| P2-03 | Pilot defects | Defect/failure log with severity, disposition, retest result, and rationale for any accepted residual risk | Not assessed | |
| P2-04 | Recovery rehearsal | Dated backup/recovery rehearsal record, procedure followed, restore verification, outcome, and operator | Not assessed | |
| P2-05 | Runbook repeatability | Evidence that a second authorized operator can follow the runbook and obtain the expected outcome without undocumented help | Not assessed | |
| P2-06 | Evidence and audit trail | Redacted test evidence that record changes are attributable and traceable; for timestamp corrections, retain original time, record corrected time, reason, actor, and change time | Not assessed | |
| P2-07 | Risk review | Current risk register, mitigations, stop conditions, unresolved risks, and owner disposition | Not assessed | |
| P2-08 | Independent feedback | GitHub review findings triaged, with blocking findings resolved or explicitly dispositioned and retested where applicable | Not assessed | |
| P2-09 | Owner decision | Final comparison against the authoritative criteria and recorded owner decision | Not assessed | |

## Status definitions

- **Not assessed:** Evidence has not been reviewed.
- **Pass:** Evidence demonstrates the criterion was met.
- **Fail:** Evidence demonstrates the criterion was not met.
- **Blocked:** Evidence is missing, inaccessible, or inconclusive.
- **Accepted risk:** The owner explicitly accepts a documented residual risk; this does not convert a failed control into a pass.

Do not mark an item Pass based only on a dashboard, a verbal report, a checklist entry, or the existence of a document. Record the evidence source and the verification performed.

## Evidence handling

- Keep detailed evidence, raw logs, backups, screenshots containing real records, and access details in the approved private location.
- Publish only a sanitized finding summary or non-sensitive evidence reference.
- Never place credentials, personal information, production data, secret URLs, or exploit details in a public issue or pull request.
- If a potential security weakness is found, report it privately to the owner rather than posting sensitive details publicly.

## Final acceptance record

Complete only after all required evidence has been reviewed and blocking gaps have been resolved or explicitly dispositioned.

- **Decision:** Pending
- **Accepted Phase 2 scope version/date:**
- **Evidence packet reference (private):**
- **Blocking findings remaining:**
- **Accepted residual risks and rationale:**
- **Owner name:**
- **Decision date:**
- **Decision notes:**

An owner may approve or reject Phase 2 completion. Approval of the scope summary or reviewer packet alone is not Phase 2 acceptance. No result here authorizes a production launch, broad rollout, or unapproved deployment.
