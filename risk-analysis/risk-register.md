# Risk Register

**Classification: Portfolio scenario.**

| Risk | Category | Likelihood | Impact | Notes |
|---|---|---|---|---|
| Sensitive discussions (HR, legal, compensation, performance) get inadvertently summarized and distributed | Privacy | Medium | High | Findings show employees explicitly don't want more automated recording of these meetings |
| Summary retained longer than the conversation itself would have been, creating a new discoverable record | Data retention | Medium | High | Meetings that were previously ephemeral become a persistent, searchable artifact — a material change in risk profile |
| Inaccurate summary misrepresents what was said or decided | Accuracy | Medium | Medium | Employees already said they'd verify against their own notes for anything consequential — undermining the feature's core value proposition |
| Summary is treated as an authoritative record in a dispute (HR, performance, legal) | Governance | Low | High | Raises questions about who owns and can be compelled to produce the record |
| Employees self-censor in meetings once they know summaries are generated and distributed | Trust / culture | Medium | Medium | A chilling effect on candid discussion is a real cost, even if hard to quantify |
| Governance and legal review required before any organization-wide rollout | Governance | High | Medium | Adds meaningful time and process cost before the feature could ship at all |

## Why Privacy and Retention Are the Risks That Matter Most

These two risks are the ones the [Findings](../user-research/findings.md) most directly confirm as real employee concerns, not hypothetical ones — and they're also the hardest to fully mitigate for a feature whose entire premise is recording and distributing what was said in a meeting.

## Relationship to the Decision

This register is a primary input to the [Decision Memo](../decision-memo/decision.md) — the combination of medium value (see [Opportunity Sizing](../opportunity-sizing/opportunity.md)) and high privacy/governance risk is what tips this from "build carefully" to "don't build."
