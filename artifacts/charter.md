# Project Charter

Proposed Lurentra pilot · Draft for discussion

> PORTFOLIO WORKED EXAMPLE — Prepared September 2026. Based on Lurentra product context. Proposed plans, roles, ratings and simulated status are illustrative, not approved or historical project records.

Purpose: demonstrate how a business can turn a spreadsheet of sales and collections data into understandable metrics, with transparent validation and reliable outputs.

## Context and authority

Known context: Lurentra is a B2B sales and collections analytics product. Betül’s documented responsibilities include scope, priorities, acceptance criteria and release readiness. This charter proposes a future pilot; sponsor approval, reviewer availability, budget and dates remain unconfirmed.

## Pilot scope

- In scope: one agreed input template; upload and column mapping; validation feedback; agreed sales and overdue-collections metrics; a management summary and CSV/PDF outputs.
- Out of scope for this example: live ERP integrations, automated collection actions, multi-company rollout, custom model training and paid production onboarding.
- Change control: record the request, business reason, delivery impact and acceptance changes. The project lead decides whether to replace existing scope or defer the request.

## Proposed acceptance criteria

| ID | Acceptance criterion | Evidence |
| --- | --- | --- |
| AC-01 | A valid agreed sample file completes the upload-to-report flow. | Recorded walkthrough with synthetic data. |
| AC-02 | Missing required fields and invalid values produce actionable validation feedback. | Negative-case checklist. |
| AC-03 | Agreed metrics reconcile to an independently checked reference dataset. | SQL/Excel reconciliation with zero unexplained differences. |
| AC-04 | Outputs contain the agreed metrics and match the validated calculation results. | Export comparison checklist. |
| AC-05 | No unresolved critical blocker remains in the agreed pilot flow. | Defect review and recorded go/no-go decision. |

## Proposed milestone sequence

| Gate | Deliverable | Exit condition |
| --- | --- | --- |
| M1 · Define | Scope and reference dataset | Project lead records scope; reviewer confirms metric definitions. |
| M2 · Validate | Working pilot flow and test evidence | AC-01 to AC-04 verified; issues logged. |
| M3 · Review | Demo, feedback and release decision | AC-05 met; reviewer feedback and decision recorded. |

## Ownership and constraints

The founder holds project-lead, engineering and QA responsibilities in this example; these are separate responsibilities, not a claim of separate staff. A business reviewer is a proposed pilot participant, not a confirmed customer. Reviewer availability and independent business validation are dependencies. No budget or delivery date is committed.

## Approval status

Draft / not approved. The project lead would record the approver, decision date, scope version and any conditions before committing the pilot baseline.

