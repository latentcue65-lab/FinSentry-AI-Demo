# Product Overview

[Back to the client package](../README.md)

## The Business Problem

Banking investigations often span several systems and teams. An analyst needs
the original alert, customer context, transaction evidence, policy constraints
and a clear record of who approved an action. Fragmented information makes that
review difficult to coordinate and explain.

FinSentry AI is designed as an investigation and coordination layer over existing
banking systems. It organizes evidence, produces advisory findings, identifies
missing inputs and coordinates governed human review. It does not replace a
core banking platform or take ownership of a bank's final decisions.

## Suite Scope

These are first-class product domains. Listing a domain describes the suite's
scope, not an assertion that every workflow is shown in this video or ready for
production deployment.

| Domain | Intended role in the operations workspace |
| --- | --- |
| Customer and KYC | Customer context and identity-review evidence |
| AML | Review of financial-crime alerts and supporting evidence |
| Payments | Payment exceptions and investigation coordination |
| Fraud and Disputes | Fraud signals, dispute evidence and case review |
| Credit | Credit-review context and advisory investigation support |
| Compliance | Policy context and review obligations |
| Case Management | Shared cases, evidence, ownership and timelines |
| Governance | Approval boundaries, permissions and decision records |
| Control Tower | Cross-domain operational visibility |

## Reference Workflow

The international-payment-to-AML journey is the deepest reference workflow:

1. An existing banking system supplies an operational alert or payment exception.
2. FinSentry assembles the authorized case context and available source evidence.
3. Bounded agents investigate through permission-controlled tools and services.
4. Findings distinguish source facts, deterministic calculations, AI inferences
   and missing information.
5. Policy constraints determine whether a recommendation can proceed or must
   abstain and require more evidence.
6. Authorized people review a proposed action through maker-checker controls.
7. The case records the human decision and any separately authorized execution
   outcome, rather than treating an AI response as a completed banking action.

In this recording, screening input remains unavailable, the advisory path
abstains and the illustrated checker decision maintains an existing hold. The
case remains under investigation. No funds release is demonstrated.

## Intended Users

- Operations analysts reviewing alerts and exceptions.
- AML, KYC, fraud, credit and compliance specialists contributing evidence.
- Supervisors coordinating cases and reviewing escalations.
- Authorized checkers and governance teams reviewing decisions and audit records.

## Value to Evaluate in a Pilot

A client pilot can measure investigation preparation time, evidence completeness,
handoff quality, reviewer effort and audit traceability against an agreed baseline.
These are evaluation goals, not measured benefits claimed by this package.

See the [Architecture Brief](ARCHITECTURE.md) and
[Demo Guide and Readiness Notes](DEMO_GUIDE.md) for controls and limitations.