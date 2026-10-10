# Phase 2 Review Checklist (Scope Summary)

**Purpose:** Give independent reviewers a concrete, bounded set of Phase 2 readiness questions.

**Source note:** This is a high-level summary of the Phase 2 gate discussed in the project notes. It is not copied from the private application repository and is not the authoritative scope or implementation. The owner should reconcile it against the approved Phase 2 scope before inviting reviewers.

## Phase 2 objective

Evaluate readiness for a controlled field pilot and recovery rehearsal. Phase 2 is not a public production launch, broad rollout, external integration, or authorization to access live systems.

## Readiness areas

For each item, reviewers should state whether the expectation is clear and testable, identify any missing evidence, and recommend a specific improvement.

| Area | Review question |
| --- | --- |
| Repeatable pilot | Are pilot workflows and expected outcomes defined so another tester can repeat them consistently? |
| Recovery drill | Are backup, restore/recovery, and verification steps documented with clear success criteria and ownership? |
| Role review | Are the user roles, allowed actions, and role-specific test responsibilities explicit? |
| Reproducible runbook | Can an operator follow the runbook without undocumented knowledge or ambiguous steps? |
| Evidence and auditability | Is evidence captured in a way that supports review, traceability, and correction history, including who changed a timestamp, when, and why? |
| Risk review | Are known risks, unresolved failures, mitigations, and stop conditions recorded and understandable? |
| Owner acceptance | Is there an explicit final owner decision against the acceptance criteria before declaring Phase 2 complete? |

## Reviewer response

For each readiness area, use one of these outcomes:

- **Clear:** understandable and testable as written.
- **Needs clarification:** intent is apparent, but a tester could reasonably interpret it more than one way.
- **Gap:** an expected control, step, evidence item, or acceptance criterion appears absent.
- **Not assessed:** the published packet does not contain enough information.

Include a short rationale and a proposed remedy for every **Needs clarification** or **Gap** result. Separate direct observations from assumptions.

## Exclusions and safety

- Do not test production or attempt to access any live system.
- Do not ask for or handle credentials, personal information, or farm records.
- Do not treat this review as a penetration test, security certification, launch approval, or permission to change production.
- Keep findings limited to the public review packet. Report suspected security issues privately to the owner rather than publishing sensitive details.

## Completion decision

Review feedback informs the owner's decision; it does not itself complete Phase 2. Completion remains subject to reconciliation with the authoritative approved scope, closure or explicit acceptance of blocking findings, required pilot and recovery evidence, and the owner's recorded approval.
