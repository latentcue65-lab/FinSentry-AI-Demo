# Demo Guide and Readiness Notes

[Back to the client package](../README.md)

## Watch the Selected Demo

[Download the narrated 4:20 MP4](https://github.com/latentcue65-lab/FinSentry-AI-Demo/releases/download/client-demo-20261008/FinSentry-AI-Demo-4m20.mp4).

The video uses the existing stationary 1080p edition with English narration and
embedded captions. Its source is a recorded synthetic sandbox demonstration,
not a live production or client-data session.

| Timestamp | Topic |
| --- | --- |
| 0:00 | Why agent completion is not banking clearance |
| 0:23 | Connected banking operations |
| 0:49 | Recorded payment and evidence |
| 1:15 | Missing screening input |
| 1:40 | Policy abstention |
| 2:04 | Maker request and self-approval restriction |
| 2:30 | Checker review and maintaining an existing hold |
| 2:56 | Bounded agents and architecture explanation |
| 3:26 | Audit trail and unresolved case |
| 3:53 | Scope disclosure and review question |

## How to Interpret the Recording

Recorded interface states illustrate an existing sandbox investigation. Captions,
static evidence outlines and explanatory diagrams guide the viewer; they are not
newly executed clicks or additional banking transactions.

The illustrated checker outcome maintains an existing hold. It does not release
a payment. Screening input is unavailable, the advisory path abstains and the
case remains under investigation.

Architecture explanations describe implementation concepts. They do not prove
that every adapter, provider, recovery scenario or infrastructure component was
executed during this recording.

## Verification and Limitations

The source media package records successful 260-second decoding, 1080p output,
audio checks, retained chapter timing and native Microsoft Edge playback. These
are media checks, not production acceptance or a complete security assessment.

The existing engineering notes do not establish a fully green repository-wide
verification gate. They record a default-environment media dependency issue and
an earlier API import-timeout failure. Do not use this client package as a claim
that all application tests, banking integrations or production controls passed.

No production banking adoption, regulatory certification, measured savings,
validated risk score or autonomous banking action is claimed.

## Before a Client Pilot

Agree and verify the following with the institution's technical, operations,
security and compliance owners:

1. Pilot boundaries, authorized data sources and permitted operational actions.
2. Data classification, privacy, retention, residency and model-provider terms.
3. Identity integration, role permissions and independent maker-checker review.
4. Bank-specific API contracts, service authority and end-to-end reconciliation.
5. Policy ownership, evidence requirements and abstention or escalation behavior.
6. Evaluation criteria, including correctness, missing-data handling and adversarial
   or unauthorized requests.
7. Availability, recovery, audit retention, incident response and operational support.
8. Current passing verification evidence for the exact pilot build and environment.

This is a review checklist, not an assertion that these approvals or controls
have already been accepted by a bank.

## Package Boundaries

Only finished demonstration media and client-facing explanatory documents are
published here. Application source code, secrets, raw recordings, internal logs,
database exports and deployment configuration are excluded.