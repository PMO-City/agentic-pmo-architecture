# Worked example: from mandate to learning

This example is fictional and illustrative. It is intended to show how the nine-step operating loop can work in practice, not to describe a real customer or prescribe one implementation.

## The situation

An organization wants to reduce avoidable release risk. Its leadership issues an internal mandate: for the next release cycle, material readiness concerns must be surfaced before production approval, with a named accountable owner and evidence for each resolved concern.

The mandate is scoped to one product area and one release cycle. It does not authorize an AI system to approve production releases.

## 1. Organizational intent

The mandate identifies:

- the purpose: improve release-readiness judgment;
- the scope: one product area and one release cycle;
- the issuing authority;
- the accountable business owner;
- the effective period;
- the evidence expected; and
- the boundary: production approval remains human.

The statement is more useful than a generic request such as “have the AI check the release,” because it preserves purpose, authority, accountability, and limits.

## 2. Governed Activity

The release owner establishes an Activity called **Release-readiness assessment**.

The Activity records:

- its relationship to the mandate;
- its owner and accountable decision-maker;
- the release scope and completion criteria;
- the authorized participants;
- the method to be applied;
- the sources that may be consulted;
- the Evidence obligations; and
- the conditions requiring human intervention.

The Activity may be associated with a Project, but it remains a distinct unit of governed work.

## 3. Human and AI execution

An AI participant is assigned to prepare a readiness packet. Its assignment permits it to:

- retrieve authorized release records;
- compare the records against the approved readiness method;
- identify missing or conflicting Evidence;
- draft questions for responsible owners; and
- prepare a Decision Landscape for the release owner.

The assignment does not permit the AI to approve production, change the release plan, or represent its recommendation as an accepted decision.

The release owner reviews the scope and starts the Activity. The AI's acting identity, represented organizational participant, assignment, and context are recorded.

## 4. Evidence and operational change

The AI finds that one integration test result is missing and that a deployment dependency has changed since the last review. It cites the source records, timestamps, method version, and uncertainty. It does not call either item resolved.

The responsible engineers investigate. One test is rerun, producing a new result. The dependency owner confirms the change and provides an updated compatibility record. Those actions change the operational situation and produce new Evidence.

## 5. Living Governed State

The responsible domain accepts the new test result and compatibility record. The Living Governed State now represents:

- the updated readiness status;
- the accepted Evidence and its sources;
- the unresolved risk that remains;
- the current owner and accountability;
- the release scope and time; and
- the difference between accepted facts and AI analysis.

The original missing result remains historically visible. It is not overwritten as if it had always existed.

## 6. Workspace Projection and Decision Landscape

The release owner sees a projection containing only the information relevant to the release decision and permitted by access rules. The Decision Landscape summarizes:

- the current readiness state;
- the changed dependency;
- the remaining risk;
- the Evidence supporting each statement;
- options and trade-offs;
- the applicable mandate; and
- the consequences of approving, delaying, or escalating.

Another participant may see a different projection. That does not create a second organizational truth.

## 7. Human judgment and follow-up

The release owner decides that the remaining risk is acceptable only if a rollback rehearsal is completed. The owner creates a governed follow-up Activity and records the decision, rationale, authority, and evidence requirement.

The AI may coordinate the rehearsal and monitor its conditions. It does not silently convert the owner's decision into a broader release policy.

## 8. Validated organizational learning

After the release cycle, the organization reviews the evidence. It finds that the changed dependency was detected early because the readiness method required source-freshness checks. It also finds that the method did not identify one category of environment-specific risk.

The first observation becomes a Learning Candidate. It is assessed against the release context and supporting records. The second becomes a method-gap candidate rather than an immediate rule.

The organization validates a limited learning statement:

> For this product area and release process, source-freshness checks improve early detection of dependency risk when the responsible owner confirms the result.

The statement remains scoped and challengeable. It is not treated as a universal law.

## 9. Digital DNA

The validated learning is retained as Digital DNA with:

- its source Activities and Evidence;
- the applicable method and version;
- its scope and effective conditions;
- uncertainty and known counterexamples;
- the validation decision and owner; and
- a reassessment condition.

The next release-readiness Activity can use the knowledge as a governed input. It remains visible why the knowledge exists and when it should be questioned.

## What the example demonstrates

The value of the loop is not that every step must be automated. The value is that intent, work, execution, Evidence, current state, judgment, and learning remain connected.

It also demonstrates several boundaries:

- AI preparation is not human approval.
- A generated observation is not accepted state.
- A successful release is not automatically a validated learning claim.
- A learning claim is not universal authority.
- A projection is not a different organizational reality.
