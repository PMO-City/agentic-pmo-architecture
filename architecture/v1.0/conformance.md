# Conformance and evidence

## What conformance means here

Conformance is a scoped claim that a declared implementation preserves the applicable meaning, boundaries, and governance obligations of this public architecture.

This repository does not certify products. PMO City does not grant universal conformance merely because a product can execute a workflow, connect to an API, or display compatible labels.

## A useful claim record

A conformance claim should identify:

| Field | What it answers |
| --- | --- |
| Architecture version | Which public edition is being assessed? |
| Implementation | What system, process, or realization is in scope? |
| Responsibilities | Which concepts and operating responsibilities are claimed? |
| Scenarios | Which Activities, Projects, or decision situations were assessed? |
| Evidence | Which records, tests, observations, approvals, and decisions support the claim? |
| Exclusions | What is explicitly outside the claim? |
| Exceptions | Which gaps are owned, risk-assessed, approved, and time-limited? |
| Decision authority | Who accepted the claim and any exceptions? |
| Validity period | When must the claim be reviewed again? |

## Minimum proof shape

A useful first proof should demonstrate the operating loop in a bounded scenario rather than assert universal coverage. It should show at least:

1. legitimate intent or mandate;
2. a governed Activity with owner, authority, and evidence obligations;
3. human and, where applicable, AI participation;
4. attributable execution and Evidence;
5. reconciliation into accepted current state;
6. a purpose-specific projection or decision context;
7. human judgment or governed follow-up; and
8. a documented learning decision or explicit statement that no learning was validated.

The [worked example](../../examples/mandate-to-learning.md) illustrates this shape. It is an example, not a certification test.

## Evidence should be challengeable

Evidence for a claim may include:

- Activity and Project records;
- authority and assignment records;
- execution logs and external acknowledgements;
- source mappings and reconciliation records;
- approval, rejection, suspension, or correction decisions;
- explanations and uncertainty records;
- tests and failure simulations;
- access and revocation checks; and
- records showing how learning was validated.

Evidence should identify its source, time, scope, version, and limitations. A large volume of logs does not automatically prove governed correctness.

## Common invalid claims

The following are not sufficient by themselves:

- “The system uses AI.”
- “The workflow completed successfully.”
- “The records are stored in an audit log.”
- “The model has access to the right tools.”
- “The product follows the nine-step diagram.”
- “The implementation conforms because an earlier version did.”

Each claim needs a declared scope and evidence connected to the applicable meaning and responsibility boundary.

## Exceptions

An exception should identify the gap, owner, decision authority, risk, compensating controls, expiry, and remediation path. An exception makes a limitation visible; it does not redefine the architecture or quietly turn a non-conforming behavior into a conforming one.

## Version awareness

Claims are version-qualified. A v1.0.1 claim should not silently be presented as a claim against a future public edition. A new public edition may require new evidence, compatibility treatment, or a new decision.

## What this guide does not do

This guide does not define a certification program, legal compliance, regulatory approval, security accreditation, or a universal test suite. Those decisions require separate authority, scope, and evidence.
