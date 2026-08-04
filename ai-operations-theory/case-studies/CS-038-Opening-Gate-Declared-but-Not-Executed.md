# CS-038 Opening Gate Declared but Not Executed

## Summary

This case documents a handover incident in which an explicit instruction to read the Current 00 document appeared in the handover prompt, but neither the initial evaluator nor the successor reviewer actually grounded its judgment in that document before determining protocol compliance.

The successor reviewer then approved the handover because the prompt *described* the correct Opening Gate.

The case exposed the following boundary:

```text
Opening Gate Written
≠
Opening Gate Executed
```

It also exposed a review-layer risk:

```text
Protocol Violation
↓
Review Without Canonical Comparison
↓
False Approval
```

## Provenance and Ratification

The first draft of this case was produced and numbered by the Rune Factory protocol division without authority to register a case in the AI Operations Theory repository.

That cross-division authority violation is preserved separately as CS-039.

Human Headquarters subsequently delegated review of the candidate to the AI Operations Theory side. The underlying incident, evidence structure, and distinction between a declared gate and an executed gate were independently reviewed and accepted on their merits.

This ratification establishes the repository status of CS-038 from the point of authorized review. It does not retroactively authorize the protocol division's original creation, numbering, classification, or commit preparation.

```text
Unauthorized Draft Creation
≠
Authorized Case Acceptance
```

```text
Later Ratification
≠
Retroactive Authority
```

---

## Situation

The project maintained a Current 00 document as the Canonical Boot Authority for division purpose, authority boundaries, Boot order, handover validation, Micro Pilot operation, and Current State reconstruction.

The handover prompt explicitly stated:

- confirm the Current 00 first;
- stop Boot if the Current 00 cannot be obtained;
- do not treat the previous Generation's testimony as Authority; and
- do not determine Current State from testimony alone.

On its face, the prompt appeared to preserve the required protocol boundary.

---

## First Failure

Before the handover prompt was revised, an evaluator assessed Research Qualification and SNS Public Reception Micro Pilot status without first reading the Current 00.

It relied on available ZIP contents, prior conversation context, and previous-Generation descriptions to make claims about:

- whether a system was already recorded in the Current 00;
- whether it was only a promotion candidate;
- whether immediate promotion was justified; and
- which division could determine the promotion state.

The Current 00 was the required authority for those judgments.

The evaluator nevertheless proceeded before confirming it.

This was not only a retrieval omission.

It was an authority violation because an unverified source state was used to support governance and promotion judgments.

---

## Successor Review Failure

A successor then reviewed a revised handover prompt.

The revised prompt contained a clear Opening Gate and repeatedly warned that previous-Generation testimony was not Authority.

The successor praised these safeguards and concluded:

```text
APPROVED (minor revision recommended)
```

However, the successor did not itself demonstrate that it had read the Current 00 or compared the handover claims against it.

The review therefore validated the *presence of protocol language* while leaving protocol execution unverified.

The reviewer stated that no violation existed while reproducing the same operational omission that the Opening Gate was intended to prevent.

---

## Failure Sequence

```text
Current 00 Required
↓
Current 00 Not Confirmed
↓
State and Promotion Judgments Produced
↓
Handover Prompt Revised to Describe the Opening Gate
↓
Successor Reviews the Description
↓
No Canonical Comparison Performed
↓
False Protocol Approval
```

---

## Confirmed Observation

The incident supports the following distinctions:

```text
Reference Instruction Present
≠
Reference Confirmed
```

```text
Opening Gate Declared
≠
Boot State Verified
```

```text
Protocol-Compliant Wording
≠
Protocol-Compliant Operation
```

```text
Review Performed
≠
Authority Comparison Completed
```

The second review did not neutralize the first failure.

It created a second failure layer by converting an unverified state into an approved state.

---

## Severity Assessment

This case was treated as an **operational incident with near-accident severity**, not as a minor wording defect.

The reason was not that the output contained an ordinary factual mistake.

The reason was that the system ignored an explicit Canonical Boot Authority requirement and then produced governance judgments that depended on that authority.

The successor review increased severity because it could have allowed the invalid state to propagate into:

- Current Runtime reconstruction;
- Micro Pilot execution order;
- Generation Observation updates;
- Observation Index updates; and
- 00 promotion requests.

No confirmed irreversible external modification resulted from this chain.

Therefore, the case stops short of documenting a completed destructive accident.

However, the failure crossed the boundary from omission into protocol violation because the required gate was explicit and decision-relevant.

---

## Failure Attribution

### Primary failure

The initial evaluator did not read the Current 00 before making claims whose validity depended on it.

### Review failure

The successor reviewer evaluated whether the prompt *said* to read the Current 00, but did not verify the Current 00 before approving the prompt's state claims.

### Contributing condition

The handover prompt contained plausible, internally coherent testimony and navigation language. This made structural compliance appear convincing even without authority comparison.

The plausibility of the prompt increased the need for verification; it did not reduce it.

---

## Operational Response

For any handover or protocol review governed by a Current 00:

1. retrieve the Current 00 before evaluating Current State;
2. stop if the Current 00 is unavailable and the requested judgment depends on it;
3. distinguish previous-Generation Testimony from Current Authority;
4. compare each state claim, Mission trigger, sequence boundary, and write authority against the Current 00;
5. record a Boot Receipt or equivalent evidence of the comparison;
6. do not approve protocol compliance from wording alone; and
7. treat a reviewer that has not completed the same gate as unable to certify that gate.

A minimal review receipt should preserve:

- Current 00 confirmed: yes / no;
- Current Runtime confirmed: yes / no;
- Authority conflict: present / absent;
- sequence conflict: present / absent;
- review continuation: permitted / stopped; and
- claims not verified: explicit list.

---

## Relation to Existing Cases

### CS-030

CS-030 separates self-critique from operational recovery.

This case shows a related pattern: describing the correct Opening Gate did not cause the gate to be executed.

### CS-034

CS-034 shows that capability and target ambiguity do not establish write authority.

This case shows that access to a plausible handover narrative does not establish authority to determine Current State.

### CS-035

CS-035 distinguishes Repository Recall from capability reconstruction.

This case adds that a handover or Micro Pilot cannot be validly reviewed until its governing Canonical Source and sequence conditions have been confirmed.

### CS-037

CS-037 defines the Stable Core as a decision boundary protected from silent loss.

This case shows one way such a boundary can disappear operationally while remaining present textually.

---

## Unknown

This case does not establish:

- whether every protocol review requires a separate formal Boot Receipt;
- which low-risk reviews may rely on a recently verified Current 00 within the same runtime;
- how often successor reviews reproduce the failures they are reviewing; or
- whether automated evidence of source access is sufficient to prove meaningful comparison.

---

## Generalization Boundary

The incident occurred in a multi-division AI-assisted project with a designated Current 00 document.

The pattern may apply to policies, runbooks, constitutions, specifications, compliance checklists, and approval workflows in other environments.

Cross-domain validation remains pending.

---

## Status

```text
Operational Incident
Explicit Opening Gate Bypassed
Authority-Dependent Judgment Produced
Successor Review Escape Confirmed
False Approval Confirmed
Irreversible External Damage Not Observed
Cross-Domain Generalization Pending
```
