# Decision Memo: AI Meeting Summary

**Classification: Portfolio scenario.**

## Decision

**Do not build AI Meeting Summary.**

## Why

| Factor | Assessment |
|---|---|
| User need | Real, but narrower and more partially served than the original proposal assumed — see [Findings](../user-research/findings.md) |
| Incremental value | Medium, concentrated in one segment (decision-making meetings without an existing transcription habit) — see [Opportunity Sizing](../opportunity-sizing/opportunity.md) |
| Cost | High — capture pipeline, summarization, distribution, retention controls, governance review |
| Risk | High — privacy exposure for sensitive meetings, new persistent record of previously ephemeral conversations, potential chilling effect on candor |
| Opportunity cost | Would consume engineering and governance capacity better spent on a higher-frequency, lower-risk initiative |

**Decision: Do not build.**

**Why:** Low-to-medium incremental customer value, once existing alternatives are accounted for, combined with high implementation cost, significant privacy and governance risk, and a real opportunity cost against a better-evidenced alternative.

## Redirect the Investment

Recommend redirecting the same underlying AI capability toward an **enterprise knowledge retrieval experience** — see [Alternatives & Opportunity-Cost Analysis](../alternatives/alternatives-analysis.md) for the full comparison. This addresses a higher-frequency, better-evidenced information-discovery need with materially lower privacy risk, since it operates on documents people have already chosen to make searchable rather than on spontaneous conversation.

## What Would Change This Decision

- Evidence of a specific team or meeting type with a validated, high-frequency need that existing tools genuinely don't meet.
- A materially different risk profile — for example, an opt-in model scoped only to meeting types employees have explicitly said they're comfortable with.
- Governance and legal review producing a retention and consent framework that resolves the privacy concerns identified here, rather than working around them.

This is a **"not now, not like this"** decision, not a permanent rejection of the underlying concept.

## Accountability

This decision, and the reasoning behind it, is owned by the product/program lead who ran this evaluation — not deferred to "the data said no." The data informed the decision; the judgment to weigh medium value against high risk and a real opportunity cost is the actual decision being made and defended here.
